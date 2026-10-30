# MCP Tokyo Offsite — Research Brief

Prepared for the Tokyo team offsite. All entries below are attributed to the source they came from. Where a source could not be retrieved, that is stated explicitly — no venue or headline details have been reconstructed from memory.

## MCP in the news

Recent developments observed in the official Model Context Protocol (`modelcontextprotocol`) tracking repository and ecosystem: | Item | Summary | Source |
|---|---|---|---|
| Stable release of spec revision 2026-07-28 | The `2026-07-28` revision was published as the **stable release** of the Model Context Protocol. The specification and the full changelog are published at the official site. | [Release page](https://github.com/modelcontextprotocol/modelcontextprotocol/releases/tag/2026-07-28) • [Specification 2026-07-28](https://modelcontextprotocol.io/specification/2026-07-28) • [Changelog](https://modelcontextprotocol.io/specification/2026-07-28/changelog) |
| MCP Core Maintainer Meeting — October 14, 2026 | WG meeting notes for the Core Maintainers group. | [Discussion #3438](https://github.com/modelcontextprotocol/modelcontextprotocol/discussions/3438) |
| Inspector V2 Working Group — November 4, 2026 | Machine-readable Inspector V2 WG meeting notes. | [Discussion #3463](https://github.com/modelcontextprotocol/modelcontextprotocol/discussions/3463) |
| Interceptors WG — October 27, 2026 | WG meeting notes on the Interceptors Working Group. | [Discussion #3460](https://github.com/modelcontextprotocol/modelcontextprotocol/discussions/3460) |
| Field report: MCP Events bridge tested with five MCP Events clients (Oct 27–28, 2026) | A report of an MCP Events server (Hookdeck) that converts webhooks into MCP events, tested against ChatGPT, Hermes Agent, Vercel AI SDK, Mastra and TanStack AI clients. MCP Events is landing across multiple client stacks. | [Issue #17 — experimental-ext-triggers-events](https://github.com/modelcontextprotocol/experimental-ext-triggers-events/issues/17) |
| Input requests lost `_meta` in 2026-07-28 revision | A recent bug report (Oct 29, 2026) that the JSON schema for input requests is wrong after the 2026-07-28 revision; references SEP-2322 removing `TaskAugmentedRequestParams`. | [Issue #3468](https://github.com/modelcontextprotocol/modelcontextprotocol/issues/3468) |
| Extension proposal — Verifiable MCP (ZK proofs / TEE attestations on `tools/call` results) | A SEP-style proposal for an optional extension that attaches machine-verifiable evidence to `tools/call` results, with a runnable reference implementation. | [Issue #3354 — ext-apps](https://github.com/modelcontextprotocol/ext-apps/issues/3354) |
| Accessibility demand for MCP Apps | An awareness item on sandboxed-iframe accessibility expectations (keyboard/focus, screen readers, labeling, contrast, zoom) for the spec's “ext-apps” track. | [Issue #431 — ext-apps](https://github.com/modelcontextprotocol/ext-apps/issues/431) |
| Official MCP Registry — public inventory | Servers published to the Official MCP Registry remain queryable at `registry.modelcontextprotocol.io`; posts flagging index gaps (e.g. a GitHub MCP Registry search miss) continue. | [GitHub MCP Registry](https://github.com/mcp) • [Official Registry API](https://registry.modelcontextprotocol.io) |

**Takeaway for the briefing:** MCP in late 2026 is moving from spec-alphas into stable, multi-vendor tooling — inspection tooling (Inspector V2), event-driven clients (MCP Events), and an Extensions Track SEP process are the visible fronts.

## Shibuya work spots

### Research status

- We ordered two parallel research streams: (a) recent press/news coverage of MCP, and (b) well-rated coffee shops or co-working spots in Shibuya for an afternoon for a group of ~6 people.
- **Stream (a) succeeded** via the official MCP GitHub repository releases and discussions above; those sources are cited in the first section.
- **Stream (b) could not be completed with retrieved data.** Every search endpoint available to us (web, news, local/place, and image search) returned a monthly search-spend limit error of `402 Payment Required` ("Usage limit exceeded"), and a fallback code search against public GitHub returned only unrelated technology posts (a Reddit coffee-scraper repository and a blogroll RSS index) — no Shibuya venue names, ratings, addresses or hours were retrievable.
- **No venue names, ratings, addresses or opening hours are listed in this note.** Fabricating them would break the "cite every entry" requirement, so they have been deliberately omitted rather than invented.

### Fill-in template (team members can add entries)

Fill in the rows below from any venue-review source (Google Maps, Tabelog, etc.) that the team can open:

| Venue name | Venue type (coffee / co-working) | Rating | Address | Hours (where known) | Capacity relevant to ~6 | Source URL |
|---|---|---|---|---|---|---|
| *(venue 1)* | | | | | | |
| *(venue 2)* | | | | | | |
| *(venue 3)* | | | | | | |

Once a teammate has filled rows, each row cites the source URL it came from per the brief.
