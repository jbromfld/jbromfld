# James Bromfield

**Senior DevOps Engineer | CI/CD automation, developer tooling, and applied AI**

I design software delivery systems that are easier to operate, safer to automate, and more useful to the teams that depend on them. My work blends infrastructure, developer experience, and applied AI into practical systems that help engineers move faster without losing reliability.

Based in Ann Arbor, Michigan.

[Resume](professional/README.md) · [GitHub projects](https://github.com/jbromfld?tab=repositories) · [Email](mailto:jbromfld@gmail.com)

## Experience at a glance

- **5+ years in software and DevOps engineering**, spanning GitHub Actions, Jenkins, Python, Kubernetes, Docker, and Terraform.
- **75+ reusable Python-based GitHub Actions and pipeline assets** developed to standardize delivery across application teams.
- **100+ AEM repositories and 300+ microservices migrated** from Jenkins to GitHub Actions.
- **More than 25% reduction in PR build times** through a redesigned protected-branch process and a cleaner delivery model.

## What I build

I focus on systems that improve how software gets from code to production: reliable CI/CD, scalable automation, developer workflows, and AI-assisted operational tooling.

## Featured projects

### [lalaland](https://github.com/jbromfld/lalaland) - Local research agents

Two local agents turn RSS feeds into short daily briefings and research papers or articles into detailed engineering summaries. A shared dashboard supports review, ratings, and search. The research workflow uses evidence notes with page or section references, checkpointing, and scheduled batches.

**Built with:** Python, FastAPI, Temporal, Ollama, PostgreSQL, and OpenTelemetry.

**Engineering focus:** durable workflows, local inference, resumable processing, and visibility into long-running work.

### [lassy](https://github.com/jbromfld/lassy) - Knowledge ingestion and retrieval

A retrieval-augmented generation (RAG) service that scrapes documentation, chunks and embeds it in PostgreSQL/pgvector, and combines vector and keyword search. It supports Copilot-backed answers and a retrieval-only mode that returns ranked source chunks with citations for client-side generation.

**Built with:** Python, FastAPI, PostgreSQL, pgvector, and Docker.

**Engineering focus:** configurable retrieval profiles, source citations, feedback, and integration with developer tools.

The companion [lassy-extension](https://github.com/jbromfld/lassy-extension) adds an `@knowledge` participant to VS Code Chat. It retrieves context through the service or an MCP endpoint, supplies citation labels to the selected chat model, and falls back to showing retrieved context if generation fails.

### [cogenial-disco](https://github.com/jbromfld/cogenial-disco) - CI/CD remediation memory prototype

A prototype for retrieving past pipeline fixes and consolidating validated solutions into a searchable memory store. The design separates remediation from validation and commits memory only after a human-reviewed PR merges and CI passes. Agent entrypoints are not yet built; the repository documents the architecture, memory model, and planned remediation workflow.

**Built around:** Python, PostgreSQL, pgvector, LangChain/LangGraph, and local embeddings.

**Engineering focus:** reusable operational knowledge, human review, and validation before retaining a proposed fix.

### [gcp-rag-proto](https://github.com/jbromfld/gcp-rag-proto) - Cloud-deployable knowledge search prototype

A retrieval-augmented generation (RAG) application combining vector and keyword search with source ingestion, answer feedback, and an operational metrics dashboard. It includes a local development setup and Terraform configuration for deployment to Google Cloud, with support for local models, Vertex AI, and Azure OpenAI.

**Built with:** Python, FastAPI, Streamlit, Elasticsearch, Docker, and Terraform.

**Engineering focus:** configurable retrieval, model-provider integration, and infrastructure as code.

## More public projects

These repositories extend the portfolio into IDE integration and music-data experimentation.

| Project | What it does |
| --- | --- |
| [lassy-extension](https://github.com/jbromfld/lassy-extension) | VS Code knowledge-search participant with direct RAG and MCP connection modes, source display, and client-side answer generation. |
| [radiofed](https://github.com/jbromfld/radiofed) | Music data and ML experimentation repository focused on MIDI ingestion, metadata enrichment, and feature preparation for research workflows. |

## Tools and interests

- **Delivery and infrastructure:** GitHub Actions, Jenkins, Azure DevOps, Docker, Kubernetes, Helm, Terraform, Ansible, AWS, and Azure.
- **Programming and data:** Python, Bash, Groovy, Java, PowerShell, SQL, and PostgreSQL.
- **Applied AI projects:** local inference, RAG, MCP integrations, agent memory, and workflow orchestration.
- **Security and operations:** automated testing, SAST/DAST, vulnerability management, SBOMs, and observability.

For my full work history, education, and training, see my [resume](professional/README.md).
