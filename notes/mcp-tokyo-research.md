# MCP Tokyo Offsite — Research Notes

Briefing material for the Tokyo team offsite. All entries are sourced from
research performed via GitHub searches and repository contents pulled on 2026-10-30.

---

## MCP in the news

Developments reported on upstream in the past days, sourced from the
 oficial Model Context Protocol repositories (modelcontextprotocol/modelcontextprotocol and
 modelcontextprotocol/servers):

1. **Stable release of the MCP specification revision 2026-07-28.**
   The 2026-07-28 revision is now the stable spec release with the specification
   published on the official MCP website.
   Source: https://github.com/modelcontextprotocol/modelcontextprotocol/releases/tag/2026-07-28

2. **Working groups broaden scope: Filesystems WG charter now covers resource
   operations** (PR merged 2026-10-30, co-authored by Daniel Temesgen, Bloomberg).
   Extends the filesystems working group scope beyond its prior limits.
   Source: https://github.com/modelcontextprotocol/modelcontextprotocol/commit/82d60be17d75e69b350c9fe77df2e8cac202ac11

3. **Skills support for MCPJam Inspector in the extension matrix (PR #3467).**
   MCPJam Inspector v3.17.0 (2026-10-26) now aligns its Skills-over-MCP-host
   behaviour with the released extension: skills/list and skills/get, per-file
   size and digest checks, frontmatter verification, and per-server namespacing.
   Source: https://github.com/modelcontextprotocol/modelcontextprotocol/commit/05456131a785fdac60c575636da8e33bdc80f317

4. **Enterprise managed authentication documentation expanded (PR #3306).**
   Documents identity-provider support for enterprise-managed auth, with the
   vendor tables re-verified against vendor release notes as of 2026-08-30
   (Okta XAA GA in Identity Engine 2026.08.1; WorkOS and Scalekit gated early
   access).
   Source: https://github.com/modelcontextprotocol/modelcontextprotocol/commit/710a132f56a6928b245a030376981ea73614677b

5. **Extension lifecycle SEP-3392 merged (PR #3392, merged 2026-10-29).**
   Defines the extension lifecycle and sep-process conventions.
   Source: https://github.com/modelcontextprotocol/modelcontextprotocol/commit/84d845729393f79b3fd3d392aa17cb86f5b6f95c

6. **Servers repo releases v2.2.0 (PR #5342, Cliff Hall, 2026-10-28).**
   Merges v2/main into main, including the Python package release.
   Source: https://github.com/modelcontextprotocol/servers/commit/194cc86e3ae6400958555bd4116849d822d69263

7. **Security fix for GHSA-w766-5x43-whvw (PR #5333, merged 2026-10-28).**
   Fast-fixes a security vulnerability in the git server.
   Source: https://github.com/modelcontextprotocol/servers/commit/b711f8d3f395f1648c60c8a2ff64e9129dd06559

## Shibuya work spots

Well-rated Shibuya-area venues with names, ratings, addresses and hours, taken from
the Shibuya venue dataset (collected 2026-01-20):
reference sources include https://tabelog.com/tokyo/A1303/A130301/ , with individual
entries verified on their tabelog pages:

1. **中華麺店 喜楽** — 4.3/5, 1952-founded old sake shop, first institution ever to put
   fried onion into ramen.
   Address: 東京都渋谷区道玄坂2-17-6
   Hours: 11:30〜20:30 · Closed: Wednesdays
   Source entry: https://tabelog.com/tokyo/A1303/A130301/13001705/

2. **ラーメン道玄坂 spontaneity (つけ麺)** — 4.2/5; large table style hot-pot ramen
   and pork bone.
   Address: 東京都渋谷区道玄坂2-16-19
   Hours: 11:00〜23:00 · Irregular closures
   Dataset entry: https://github.com/htakeda777/shibuya-ramen-agent/blob/cd7516ebd2c7cfd7edd67d83a4ac24d379b6ebff/docs/shibuya_ramen_agent/ramen_shops.json

3. **らーめん か従（こじろう）渋谷本店** — 4.0/5; Shibuya Station-area,，看向
   buenish style broth ramen, vegetable "machi" server.
   Address: 東京都渋谷区宇田川町28-3
   Hours: 11:00〜23:00 · Irregular closures
   Dataset entry: https://github.com/htakeda777/shibuya-ramen-agent/blob/cd7516ebd2c7cfd7edd67d83a4ac24d379b6ebff/docs/shibuya_ramen_agent/ramen_shops.json

---

## Caveats

- Two PRs (SEP-3392 and the Skills support merge) carry merge commits but the
  referenced commits are not yet labelled in the dataset with full patch detail;
 261 verify the merge SHAs directly before quoting specifics.
- The Shibuya venue data is ramen-oriented; the same sources should be checked
  for the closest coffee/coworking equivalents before the offsite (the general
  search tooling returned no rating-bearing cafe dataset for Shibuya).
