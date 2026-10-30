# MCP Tokyo Offsite — Research Briefing

Team research summary for the upcoming Tokyo team offsite. Prepared from tool-returned
search results only; where a tool returned zero usable results for a topic, that is stated
explicitly rather than filled in from memory.

Source reporting channels used: Brave Search (web / news / local-place / image /
LLM-context endpoints) and GitHub repository/issue search as a supplementary channel.

---

## MCP in the news

### Context about the search outcome

- Brave Search exhausted its monthly usage quota on all endpoints (web, news, local place,
  image, and LLM-context), returning HTTP 402 for every query. No headline-level news
  coverage of the Model Context Protocol was therefore retrievable.
  - Source: Brave Search API usage-limit response (multiple queries, all blocked with
    402 Payment Required).

### MCP — verified facts returned by GitHub search

Each item below cites the exact source returned by GitHub repository search
(scoped to `org:modelcontextprotocol`, `in:name,description`, sorted by stars).

- **Specification & documentation repository** — "Specification and documentation for
  the Model Context Protocol", 9,566 stars.
  - Source: https://github.com/modelcontextprotocol/modelcontextprotocol
- **Official MCP Servers repository** — "Model Context Protocol Servers" (reference
  servers), 91,687 stars, 11,887 forks.
  - Source: https://github.com/modelcontextprotocol/servers
- **Python SDK** — "The official Python SDK for Model Context Protocol servers and
  clients", 24,710 stars. Repo description states it is maintained in collaboration
  with Google for the Go SDK.
  - Source: https://github.com/modelcontextprotocol/python-sdk
- **TypeScript SDK** — official TS SDK for MCP servers and clients, 13,685 stars.
  - Source: https://github.com/modelcontextprotocol/typescript-sdk
- **.NET (C#) SDK** — official C# SDK for MCP servers and clients, 4,605 stars;
  repo description notes collaboration with Microsoft.
  - Source: https://github.com/modelcontextprotocol/csharp-sdk
- **Java SDK** — official Java SDK for MCP servers and clients, 3,755 stars;
  repo description notes collaboration with Spring AI.
  - Source: https://github.com/modelcontextprotocol/java-sdk
- **Go SDK** — official Go SDK for MCP servers and clients, 5,290 stars;
  repo description notes collaboration with Google.
  - Source: https://github.com/modelcontextprotocol/go-sdk
- **Rust SDK** — official Rust SDK for the Model Context Protocol, 4,069 stars.
  - Source: https://github.com/modelcontextprotocol/rust-sdk
- **Inspector tool** — "Deterministic testing tools for MCP servers", 11,194 stars;
  useful for validating MCP integration against the protocol trees from the
  specification.
  - Source: https://github.com/modelcontextprotocol/inspector
- **Community-sourced registry** — "A community driven registry service for Model
  Context Protocol (MCP) servers", 7,423 stars.
  - Source: https://github.com/modelcontextprotocol/registry

### Tooling release detail returned by GitHub issue search

- A GitHub-generated "Go Fan" module report (`modelcontextprotocol/go-sdk`) documents
  release **v1.8.0, released 2026-09-14** as a hardening/fix release (no new protocol
  revision) with fixes and caps spelled out for the team:
  - JSON decoding now rejects nesting deeper than 1000 levels before parsing
  - New `MaxEventSize` on SSE/lib changes and `MaxLineLength` on stdio to bound buffered
    input
  - OAuth dynamic-client-registration responses capped at 1 MB
  - fixes for session-leak, deadlock, and teardown-hang in `ServerSession`/`Client.Connect`
  - two `MCPGODEBUG` escape hatches (`plaintextstatefulrejection`,
    `blockingcancelnotify`) slated for removal in v1.9.0 — the report tracks these
  - notes that `Stateless = true` opts into the `2026-07-28` revision but drops session
    affinity; `Stateless = false` still allows negotiating down to `2025-11-25`
  - Source: https://github.com/github/gh-aw/issues/73148

## Shibuya work spots

### Search outcome

- Brave Search local/place endpoints were depleted by the same monthly-quota limit, so
  no Shibuya venue listings (coffee shops or co-working spots) with addresses, ratings,
  or hours were retrievable. No venue entry is asserted from memory below.
  - All four exhausted sources: Brave web, news, local-place, and image searches.
- A supplementary GitHub repository search for a Shibuya cafe/coworking directory returned
  no usable results (refuted in favor of explicit absence rather than invented data).
  - Sources: https://github.com/search?q=Shibuya+coffee+shop+coworking (name/description
    search) and https://github.com/search?q=Shibuya+coffee+shop+coworking (code search),
    both returning no Shibuya venue listing with ratings/addresses/hours.

### Placeholder structure for the team to complete

- **Venue 1** — Name, rating, address, hours: **unverified — no source retrieved.**
  - Source: none retrieved; flagged for manual follow-up before the offsite.
- **Venue 2** — Name, rating, address, hours: **unverified — no source retrieved.**
  - Source: none retrieved; flagged for manual follow-up before the offsite.

## Recommended next steps before circulating

1. Re-run the news search when the Brave Search quota resets, or add reputable news
   outlets as sources once coverage is available.
2. Manually verify Shibuya work spots against a local Yelp/Tabelog/Goo map listing to
   fill in names, addresses, and afternoon hours (current constraint blocked automated
   retrieval at research time).
3. Add contact info / pricing notes for a group of ~6, since automated research did not
   return that data.