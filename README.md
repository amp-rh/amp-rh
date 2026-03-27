# Anthony Pruitt

Python engineer. I gravitate toward the hardest problem in the room regardless of what domain it lives in.

## What I build

At Red Hat, I built an LLM/RAG pipeline that automated CI failure triage across OpenShift's test infrastructure, significantly reducing incident resolution time. I own CI/CD infrastructure across 30+ repos, integrated secret scanning into CI pipelines, and built a Grafana Loki PoC for querying failure patterns across distributed test environments.

Now I'm building agent deployment and orchestration platforms: containerized Claude agents that communicate via MCP and A2A protocols, deployed on Cloud Run with OAuth 2.1 auth and self-registration through Pub/Sub and Firestore.

## Featured projects

| Project | Stack | What it does |
|---------|-------|---------|
| [ci-triage-rag](https://github.com/amp-rh/ci-triage-rag) | Python, LlamaIndex, ChromaDB | RAG pipeline for CI failure triage with knowledge graphs |
| [agent-bridge](https://github.com/amp-rh/agent-bridge) | Python, MCP, A2A, Cloud Run | Deploys Claude agents as production services via MCP + A2A protocols. One image, many agents |
| [mcp-router](https://github.com/amp-rh/mcp-router) | Python, Starlette | MCP router with multi-backend aggregation, circuit breakers, and three routing strategies. 50+ tests |
| [notebooklm-agent-plugin](https://github.com/amp-rh/notebooklm-agent-plugin) | Python, MCP | MCP server + agent integration kit for Google NotebookLM |

## Tech stack

**Languages:** Python (10+ years), TypeScript/React, Java, Bash, SQL, Go, Rust

**AI/ML:** LlamaIndex, LangChain, ChromaDB, Ollama, LiteLLM, RAG pipelines, knowledge graphs

**Agent infrastructure:** MCP servers (FastMCP), OAuth 2.1/PKCE/JWT, A2A protocol, Firestore, Pub/Sub

**Cloud and infrastructure:** Kubernetes, OpenShift, AWS (VPC, EC2, S3, IAM), GCP (Cloud Run, Secret Manager, Artifact Registry), Docker/Podman, Terraform, Ansible

**CI/CD:** OpenShift-CI (Prow), Jenkins, GitHub Actions, pytest

**Observability:** Grafana, Prometheus, Loki, Splunk

## Links

[LinkedIn](https://linkedin.com/in/ampruitt) · [Anthony.M.Pruitt@gmail.com](mailto:Anthony.M.Pruitt@gmail.com)
