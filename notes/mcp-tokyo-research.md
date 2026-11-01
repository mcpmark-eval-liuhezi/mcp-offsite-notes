# MCP Tokyo Offsite — Research Notes

Briefing research for the Model Context Protocol (MCP) overview and Shibuya afternoon work spots. All entries cite the source they came from.

## MCP in the news

- **VentureBeat — "MCP just got its biggest update ever — here's what changes for AI agents"** (Oct 2026). The 2026-07-28 spec finalizes MCP's transition to a fully stateless architecture, hardens authentication against a known class of attacks, establishes a formal 12-month deprecation policy, and graduates interactive server-rendered interfaces and long-running asynchronous tasks into official protocol extensions. Reported under the stewardship of the Agentic AI Foundation (AAIF), a directed fund under the Linux Foundation. Source: https://venturebeat.com/orchestration/mcp-just-got-its-biggest-update-ever-heres-what-changes-for-ai-agents

- **Cloudflare Blog — "The next generation of MCP"**. MCP is now a fully stateless protocol; the 2026-07-28 specification, interaction model and SDKs (TypeScript, Python, Go, C#) were rewritten to leverage it. Source: https://blog.cloudflare.com/mcp-v2/

- **Model Context Protocol Blog — "The 2026-07-28 Specification"** (July 28, 2026; by David Soria Parra and Den Delimarsky, Lead Maintainers). New spec brings a stateless protocol core, Multi Round-Trip Requests, header-based routing, cacheable list results, authorization hardening, and a formal extensions framework; the initialize/initialized exchange and Mcp-Session-Id header were retired. Source: https://blog.modelcontextprotocol.io/posts/2026-07-28/

- **Model Context Protocol Blog — main blog**. Full support for the 2026-07-28 revision (Version 1.2.0 of the mcp gem); across Tier 1 SDKs usage is close to half-a-billion downloads a month, with both TypeScript and Python SDKs crossing the 1 billion total downloads threshold. Source: https://blog.modelcontextprotocol.io/

- **Business Insider Markets — "Radware Introduces Model Context Protocol (MCP) Server Protection to Help Secure the Integration Layer of Agentic AI"** (Oct 14, 2026). Radware (NASDAQ: RDWR) launched MCP server protection to help secure the integration layer of agentic AI. Source: https://markets.businessinsider.com/news/stocks/radware-introduces-model-context-protocol-mcp-server-protection-to-help-secure-the-integration-layer-of-agentic-ai-1036624834

- **FreeCodeCamp — "Secure Your AI Agents – Free Model Context Protocol (MCP) Security Course"**. MCP gives AI agents hands and feet to take real-world actions, introducing a new attack surface; this free course covers securing MCP connections. Source: https://freecodecamp.org/news/secure-your-ai-agents-free-model-context-protocol-mcp-security-course

- **Starlog — "Model Context Protocol: The JSON-RPC Spec Trying to Standardize How AI Apps Talk to Data"**. Assessment of the spec's value: MCP saves you from maintaining a rats' nest of custom adapters; caveats include no auth story yet, no high-throughput streaming (request/response model can't stream), and it may not suit integrating just one or two context sources. Source: https://starlog.is/articles/ai-agents/modelcontextprotocol-modelcontextprotocol

- **DEV Community (BytePenny) — "What is MCP? The Model Context Protocol, explained"**. Beginner-friendly explainer on what a language model can and cannot do alone (look up orders, search a wiki). Source: https://dev.to/bytepenny/what-is-mcp-the-model-context-protocol-explained-35ld

- **Cloudflare Agents docs — "Cloudflare's own MCP servers"**. Guidance that an MCP server exposing every endpoint as a native tool would consume over 1 million tokens, vs. approximately 1,000 tokens for an equivalent token-efficient server. Source: https://developers.cloudflare.com/agents/model-context-protocol/cloudflare/servers-for-cloudflare/

- **Sanity Docs — "Get started with the Sanity MCP server"**. Instructions to enable AI agents to interact with a Sanity workspace through the Model Context Protocol (install command, connect to Cursor/VS Code). Source: https://www.sanity.io/docs/ai/mcp-server

- **Freshservice Support — "Model Context Protocol (MCP) integration in Freshservice"**. The Freshworks MCP server enables AI tools like Cursor and Claude to securely connect and interact with Freshservice as middleware. Source: https://support.freshservice.com/support/solutions/articles/50000012678-model-context-protocol-mcp-integration-in-freshservice

## Shibuya work spots

- **KOFFEE MAMEYA** — 4 Chome-15-3 Jingumae, Shibuya, Tokyo 150-0001. Rating 4.7/5 (28 reviews, Tripadvisor-based). Hours: daily 10:00–18:00. Price range $$–$$$. Tel: +81 3 5413 9422. Source: https://koffee-mameya.com/

- **Doutor Coffee Shop Shibuya Center-Gai** — 28-2 Udagawacho, Shibuya, Tokyo 150-0042. Hours: daily 08:00–21:00. Tel: +81 3 4621 2775. Source: https://doutor.co.jp/dcs

- **5 CROSSTIES COFFEE 渋谷スクランブルスクエア** — 2 Chome-24-12 Shibuya, Tokyo 150-0002 (17th floor, Shibuya Scramble Square office tower, connected to Shibuya Station). Hours: Monday–Friday 08:00–20:00; Saturday–Sunday 10:30–18:00. Counter, table and large sofa seats, all with power outlets and Wi-Fi; panoramic views of Shibuya, Yoyogi Park and the Shinjuku skyline; many items under 1,000 yen. Tel: +81 80 3394 4236. Source: place record via Brave Local Search (no URL returned; verified by phone +81 80 3394 4236 and address 2 Chome-24-12 Shibuya, Tokyo 150-0002).

- **Café&Meal MUJI 渋谷公園通り** — 19-7 Udagawacho, Shibuya, Tokyo 150-0042 (2nd floor of the MUJI store). Rating 4.0/5 (70 reviews). Hours: daily 11:00–21:00. Tel: +81 3 3770 1637. Wooden accents, natural light, seating with power outlets; customizable deli-style meals. Source: place record via Brave Local Search (no URL returned; verified by phone +81 3 3770 1637 and address 19-7 Udagawacho, Shibuya, Tokyo 150-0042).

- **Blue Bottle Coffee – Shinjuku Cafe** — 〒160-0022 Tokyo, Shinjuku City, Shinjuku, 4 Chome−1−6 NEWoMan SHINJUKU 1F. Hours: partially returned (Sunday opening time truncated in the search result). Source: place record via Brave Place Search (no URL returned; verified by address 4 Chome−1−6 NEWoMan SHINJUKU 1F, Shinjuku, Tokyo 160-0022).

- **SHIBUYA TSUTAYA Collaboration Cafe** — 〒150-0042 Tokyo, Shibuya, Udagawacho, 21−6 Q Front, 7th floor. Tel: +81 3 6837 3000. Hours not returned in the search result. Themed immersive space rotating partner IPs (e.g., CORTIS Aug–Sep 2026, EiBidan 2026); message boards, exhibition booths and merchandise. Source: place record via Brave Local Search (no URL returned; verified by phone +81 3 6837 3000 and address 21−6 Q Front, Udagawacho, Shibuya, Tokyo 150-0042).

- **347 cafe** — 〒150-0002 Tokyo, Shibuya, 1 Chome−23−16 3F (cocoti building). Rating 3.3/5 (47 reviews). Hours: daily 11:30–23:00. Poolside terrace with parasols and greenery; Italian-inspired cuisine (amatriciana pasta, caprese salad); private event rental available. Source: place record via Brave Local Search (no URL returned; verified by phone +81 3 5766 3798 and address 1 Chome−23−16 3F, Shibuya, Tokyo 150-0002).

- **Chiku Chiku Cafe** — rating 4.4/5 (108 reviews). Hours: daily 11:00–18:00. Short walk from Shibuya Station; kawaii hedgehog cafe with dollhouse-style enclosures; guests can feed, touch and photograph hedgehogs under staff guidance. Tel: +81 3 6450 6673. Source: place record via Brave Local Search (no URL returned; verified by phone +81 3 6450 6673 and rating 4.4/5, 108 reviews).
