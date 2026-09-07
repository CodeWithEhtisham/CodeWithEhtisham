## Ehtisham Ahmed

I build **AI agents and MCP servers**, and the production Python they run on.

Most of my work is backend systems for LLM applications — tool-calling agents, Model Context Protocol servers, and the async infrastructure underneath them: FastAPI, SQLAlchemy 2.x async, Celery, Redis, Postgres. I also ship TypeScript front-ends, including one deployed to the Cloudflare Workers edge runtime.

Based in Quetta, Pakistan. Open to contract work on agent and MCP integrations.

### Selected work

**[netdiag-mcp](https://github.com/CodeWithEhtisham/netdiag-mcp)** · Python, MCP SDK 2.x
An MCP server giving agents read-only DNS, TLS, HTTP and RDAP diagnostics for any host. Keyless — no API keys to run it. Includes an SSRF guard that refuses non-public targets and re-validates every redirect hop, because these tools take a hostname from a language model and then make a request to it. 65 tests, with the security-critical ones deliberately offline.

**Production LLM agent** · Python — client work, private
A tool-calling agent for a retail platform, built and maintained solo: FastAPI, async SQLAlchemy, Celery workers, Redis, Postgres, Docker. Also an MCP server exposing the same domain to LLM clients.

**[whatismytools.com](https://whatismytools.com)** · TypeScript, Next.js 16, Cloudflare Workers
18 browser-based network and device diagnostics in 4 languages, deployed to the edge via OpenNext. Everything runs client-side — the interesting constraint is that edge runtimes have no Node APIs, so DNS, geolocation and throughput measurement all had to be rebuilt on web primitives.

### Stack

**Backend** — Python · FastAPI · SQLAlchemy 2.x (async) · Pydantic v2 · Celery · Redis · PostgreSQL · Alembic · Docker
**AI/agents** — Model Context Protocol · tool calling · LLM application architecture
**Frontend** — TypeScript · React 19 · Next.js 16 · Tailwind
**Infra** — Cloudflare Workers · Linux · GitHub Actions

### Experience

**Full Stack Developer**, National Centre of Robotics and Automation — 2023–present
**Software Engineer**, Government Innovation Lab (UNDP) — 2020–2022

BS Computer Science, BUITEMS (2016–2020) · Winner, Google Android Developers Challenge (2021)

### Contact

[LinkedIn](https://www.linkedin.com/in/ehtishamahmed) · [Stack Overflow](https://stackoverflow.com/users/13269204/ehtisham) · [Twitter](https://twitter.com/EhtishamPyCoder)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=CodeWithEhtisham&theme=dark&hide_border=false&include_all_commits=true&count_private=true)
