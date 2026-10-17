# James Bromfield

**Senior DevOps Engineer | CI/CD automation, developer tooling, and applied AI**

I build tools that make software delivery more reliable and easier to operate. My professional work spans reusable CI/CD frameworks, cloud infrastructure, security automation, and developer experience. My public projects explore how AI agents, retrieval, and local models can help engineers find information and work through operational problems.

Based in Ann Arbor, Michigan.

[Resume](professional/README.md) · [GitHub projects](https://github.com/jbromfld?tab=repositories) · [Email](mailto:jbromfld@gmail.com)

## Experience at a glance

- **5+ years in software and DevOps engineering**, with experience across GitHub Actions, Jenkins, Python, Kubernetes, Docker, and Terraform.
- **75+ reusable Python-based GitHub Actions and pipeline assets** developed to standardize delivery across application teams.
- **100+ AEM repositories and 300+ microservices migrated** from Jenkins to GitHub Actions.
- **More than 25% reduction in PR build times** through a redesigned protected-branch PR process.

## Featured projects

### [lalaland](https://github.com/jbromfld/lalaland) - Local research agents

Two local agents turn RSS feeds into short daily briefings and research papers or articles into detailed engineering summaries. A shared dashboard supports review, ratings, and search. The research workflow uses evidence notes with page or section references, checkpointed processing, and scheduled batches.

**Built with:** Python, FastAPI, Temporal, Ollama, PostgreSQL, and OpenTelemetry.

**Engineering focus:** durable workflows, local inference, resumable processing, and visibility into long-running work.

### [cogenial-disco](https://github.com/jbromfld/cogenial-disco) - CI/CD remediation memory prototype

A prototype for retrieving past pipeline fixes and consolidating validated solutions into a searchable memory store. The design separates remediation from validation and commits memory only after a human-reviewed PR merges and CI passes. The public README describes agent entrypoints and the local simulation harness as planned work.

**Built around:** Python, PostgreSQL, pgvector, LangChain/LangGraph, and local embeddings.

**Engineering focus:** reusable operational knowledge, human review, and validation before retaining a proposed fix.

### [gcp-rag-proto](https://github.com/jbromfld/gcp-rag-proto) - Cloud-deployable knowledge search prototype

A retrieval-augmented generation (RAG) application combining vector and keyword search with source ingestion, answer feedback, and a metrics dashboard. Includes a local development setup and Terraform configuration for deployment to Google Cloud, with support for local models, Vertex AI, and Azure OpenAI.

**Built with:** Python, FastAPI, Streamlit, Elasticsearch, Docker, and Terraform.

**Engineering focus:** configurable retrieval, model-provider integration, and infrastructure as code.

## More public projects

These repositories explore complementary parts of an AI-assisted developer workflow, from knowledge retrieval and CI/CD queries to prompt discovery inside the editor.

| Project | What it does |
| --- | --- |
| [rag-service](https://github.com/jbromfld/rag-service) | Ingests documentation, chunks and embeds it in PostgreSQL/pgvector, and returns hybrid vector and keyword search results with citations. Supports retrieval-only responses so an MCP client can generate the answer. |
| [kbsearch-mcp-server](https://github.com/jbromfld/kbsearch-mcp-server) | Exposes knowledge-base search, CI/CD database queries, and feedback through the Model Context Protocol (MCP) for compatible coding assistants. Connects the retrieval and natural-language-to-SQL services to the editor. |
| [nl2sql-service](https://github.com/jbromfld/nl2sql-service) | Supports natural-language questions about deployments and tests through a prepare/execute workflow. Extracts query parameters, provides schema context, and caches SQL patterns for reuse with changing values. |
| [prompt-service](https://github.com/jbromfld/prompt-service) | FastAPI and PostgreSQL service for prompt discovery, full-text search, category autocomplete, usage tracking, and ratings. Blends text relevance with popularity; semantic search is documented as future work. |
| [prompt-extension](https://github.com/jbromfld/prompt-extension) | VS Code extension for discovering reusable prompts and inserting them into GitHub Copilot. Uses `prompt-service` for search, categories, usage, and feedback. |
| [radiofed](https://github.com/jbromfld/radiofed) | ML testing repository. Its current public README contains only a brief project label. |

## Tools and interests

- **Delivery and infrastructure:** GitHub Actions, Jenkins, Azure DevOps, Docker, Kubernetes, Helm, Terraform, Ansible, AWS, and Azure.
- **Programming and data:** Python, Bash, Groovy, Java, PowerShell, and PostgreSQL.
- **Applied AI projects:** local inference, RAG, MCP integrations, agent memory, and workflow orchestration.
- **Security and operations:** automated testing, SAST/DAST, vulnerability management, SBOMs, and observability.

For my full work history, education, and training, see my [resume](professional/README.md).
