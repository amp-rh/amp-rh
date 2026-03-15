# Anthony Pruitt

Building AI infrastructure that ships — from RAG pipelines in production at Red Hat to agent deployment platforms on GCP.

## What I do

I design and build the systems that put LLMs to work on real problems. At Red Hat, I built a RAG pipeline that automated CI failure triage across OpenShift's test infrastructure, cutting mean time to resolution by 40%. Now I'm building agent deployment and orchestration platforms — containerized Claude agents that communicate via MCP and A2A protocols, deployed on Cloud Run with OAuth 2.1 and self-registration.

Previously: Software Quality Engineer → AI/ML Platform Engineer at Red Hat, where I went from writing test automation to owning the LLM-powered systems that replaced manual triage workflows.

## Featured projects

| Project | What it does |
|---------|-------------|
| [interop_llm_tools](https://github.com/amp-rh/interop_llm_tools) | RAG pipeline for CI failure triage — LlamaIndex + ChromaDB + knowledge graphs. **Reduced MTTR 40%** at Red Hat. |
| [agent-bridge](https://github.com/amp-rh/agent-bridge) | Container image that deploys Claude agents as services via MCP + A2A protocols. One image, many agents. |
| [mcp](https://github.com/amp-rh/mcp) | Production MCP router with multi-backend aggregation, circuit breakers, and three routing strategies. 50+ tests. |
| [notebooklm-agent-plugin](https://github.com/amp-rh/notebooklm-agent-plugin) | MCP server + agent integration kit for Google NotebookLM with Cursor and Claude Code support. |

## Tech stack

**AI/ML:** LlamaIndex · LangChain · ChromaDB · Ollama · LiteLLM · RAG · Knowledge Graphs

**Infrastructure:** Docker/Podman · Google Cloud Run · Firestore · OAuth 2.1 · MCP · A2A

**Languages & Tools:** Python · FastMCP · Starlette · pytest · uv · ruff

## Links

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ampruitt-blue?style=flat&logo=linkedin)](https://linkedin.com/in/ampruitt)
