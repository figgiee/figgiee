# Brandon Figarella

Product engineer. I own a consumer surface end to end: I make the product and architecture calls, direct Claude, Cursor, and Gemini against them, and own the verification of what ships.

Most of what I build lives in private commercial repos, so this profile shows a slice of it. The fastest way to see the work is the live links below. For the private code, read access or a walkthrough is available on request.

### Live, open it now
- [wavhaven.io](https://wavhaven.io): a music marketplace I designed in Figma and shipped to production end to end on React 19 and the Cloudflare edge.
- [storybook.wavhaven.io](https://storybook.wavhaven.io): its design system, 88 stories across 27 components, with an accessibility panel on every story.
- [brandonfigarella.dev](https://brandonfigarella.dev): portfolio and case studies.

### Public code
- [chimera](https://github.com/figgiee/chimera): a local-first AI stack for LM Studio. A Docker RAG pipeline (pgvector, SearXNG, TEI embeddings) wired to 8 MCP tool servers. The public slice of the agent tooling I build and run daily.

### Private and commercial (read access on request)
- **Bastion**: an endpoint detection and response platform I co-founded at Halden Technologies. Rust detection agent, a gRPC control plane over SurrealDB, and a Flutter operator console.
- **OmniDex**: a desktop Unreal-asset manager (Electron, React 19, Rust via napi-rs) with sub-millisecond FTS5 search, used daily by the team building our UE5 game.

### How I work
I make the architecture and design calls and can defend each one. Agents implement against that direction, gated by build-time lint and architecture checks and a typed error taxonomy, so a failure surfaces as a specific, recoverable state. I can write the code by hand, which is the only reason I trust what the agent hands back.

**Stack:** TypeScript, React 19, Rust, Python, C++ · Cloudflare Workers (D1, R2, KV, Durable Objects, Queues, Vectorize), Hono, Postgres, SQLite FTS5 · Figma to production, design systems, WCAG AA · Claude Code, Cursor, MCP servers

brandonfigarella@gmail.com · [linkedin.com/in/brandon-figarella](https://linkedin.com/in/brandon-figarella)
