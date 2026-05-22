# Awesome AI Agent Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of frameworks, tools, courses, and patterns for building production-grade AI agents in 2026.

Maintained by [NEXUS Algo Academy](https://nexus-bot.pro/courses/) — we teach AI Agent Engineering professionally. [Free Prompt 101 mini-course](https://nexus-bot.pro/prompt-101/) · [Full AI Agents course ($199)](https://nexus-bot.pro/ai-agents/).

## Contents

- [Frameworks](#frameworks)
- [Model Context Protocol (MCP)](#mcp)
- [Vector Databases](#vector-databases)
- [Observability](#observability)
- [Deployment](#deployment)
- [Memory Systems](#memory-systems)
- [Tools & Functions](#tools-functions)
- [Courses & Learning](#courses-learning)
- [Production Case Studies](#production-case-studies)
- [Best Practices](#best-practices)
- [Related Lists](#related-lists)

## Frameworks

- [Claude Agent SDK](https://docs.anthropic.com/en/api/agent-sdk) — Anthropic's official SDK. Industry standard 2026.
- [OpenAI Agents](https://platform.openai.com/docs/assistants) — Native multi-step agent framework with tools.
- [LangChain](https://www.langchain.com/) — Mature, sprawling, often over-engineered. Pick carefully.
- [LlamaIndex](https://www.llamaindex.ai/) — Data-first approach, strong for RAG patterns.
- [Antigravity 2.0](https://google.dev/antigravity) — Google's agent platform launched at I/O 2026.
- [CrewAI](https://www.crewai.com/) — Multi-agent role-based framework.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's conversational multi-agent framework.

## MCP (Model Context Protocol)

The cross-vendor standard for connecting agents to tools (Anthropic 2024 → adopted by Google I/O 2026).

- [MCP Specification](https://spec.modelcontextprotocol.io/) — Official spec.
- [@modelcontextprotocol/sdk](https://github.com/modelcontextprotocol/typescript-sdk) — TypeScript SDK.
- [mcp-python](https://github.com/modelcontextprotocol/python-sdk) — Python SDK.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) — Community list of MCP servers.

## Vector Databases

- [Pinecone](https://www.pinecone.io/) — Managed, fast, opinionated.
- [Weaviate](https://weaviate.io/) — Open-source with full-text + vector hybrid.
- [Qdrant](https://qdrant.tech/) — Rust-based, self-host friendly.
- [pgvector](https://github.com/pgvector/pgvector) — Postgres extension. Good enough for most cases.
- [Chroma](https://www.trychroma.com/) — Lightweight, embedded.

## Observability

- [Langfuse](https://langfuse.com/) — Open-source LLM observability.
- [Helicone](https://www.helicone.ai/) — Drop-in OpenAI/Anthropic proxy with logging.
- [LangSmith](https://www.langchain.com/langsmith) — LangChain's observability platform.
- [Arize Phoenix](https://phoenix.arize.com/) — Open-source ML observability.

## Deployment

- [Modal](https://modal.com/) — Serverless Python, agent-friendly.
- [Cloudflare Workers](https://workers.cloudflare.com/) — Edge-deployed agents.
- [Hetzner Cloud](https://www.hetzner.com/cloud) — Cheap VPS for production agents ($5/mo).
- [Fly.io](https://fly.io/) — Container deployment, multi-region.
- [Railway](https://railway.app/) — Simple deploys for Python/Node agents.

## Memory Systems

- [Mem0](https://mem0.ai/) — User-memory layer for agents.
- [Zep](https://www.getzep.com/) — Conversational memory store.
- [LangChain Memory](https://python.langchain.com/docs/modules/memory/) — Various memory backends.

## Tools & Functions

- [Anthropic Tool Use](https://docs.anthropic.com/en/docs/agents-and-tools/tool-use/overview) — Native Claude tool calling.
- [Composio](https://composio.dev/) — Pre-built tools for 250+ apps.
- [Toolhouse](https://toolhouse.ai/) — Tool registry for LLMs.

## Courses & Learning

- [Prompt 101 (free, 30 min)](https://nexus-bot.pro/prompt-101/) — Prompting fundamentals.
- [AI Agents Course ($199, founder pricing)](https://nexus-bot.pro/ai-agents/) — Production agent engineering with 3 capstones.
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) — Andrew Ng's free agent courses.
- [Anthropic's Agent Engineering Training (free YouTube)](https://www.youtube.com/@AnthropicAI) — Official tutorials.

## Production Case Studies

- [How we built 7 AI agents that save 200 hours/year](https://nexus-bot.pro/articles/ai-agent-engineer-roadmap-2026) — NEXUS Algo case study.
- [Cursor's agent architecture](https://www.cursor.com/blog/composer) — How Cursor builds Composer.
- [Replit Agent post-mortem](https://blog.replit.com/agent-v2) — Lessons from shipping Replit Agent.

## Best Practices

- [Anthropic: Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) — Foundational paper.
- [OpenAI: Building Reliable Agents](https://platform.openai.com/docs/guides/agents) — Practical guide.
- [Prompt 101: 5 Patterns (free)](https://nexus-bot.pro/prompt-101/) — Patterns every agent engineer needs.

## Related Lists

- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers)
- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- [Awesome RAG](https://github.com/lucifertrj/Awesome-RAG)

---

## Contributing

PRs welcome. Quality bar: only resources that are actively maintained and that you'd recommend to a colleague.

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
