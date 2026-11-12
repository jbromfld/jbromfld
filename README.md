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

A local research platform with agents for RSS briefings, detailed paper and article summaries, and optional knowledge queries across indexed research. A shared dashboard supports source management, review, ratings, and search. Temporal workflows handle scheduled batches and checkpointed processing; the knowledge assistant uses Lassy to retrieve evidence for answers with citations.

**Built with:** Python, FastAPI, Temporal, Ollama, PostgreSQL, and OpenTelemetry.

**Engineering focus:** durable workflows, local inference, source provenance, and integration between research and retrieval services.

### [lassy](https://github.com/jbromfld/lassy) - Local document indexing and retrieval

A shared retrieval service that indexes application-supplied document text and returns ranked evidence with citations and provenance. It combines local embeddings, PostgreSQL/pgvector vector and keyword search, publication recency, and optional cross-encoder reranking. Native MCP over stdio and an optional HTTP API expose the same document service; calling applications handle source collection and answer generation.

**Built with:** Python, PostgreSQL, pgvector, Sentence Transformers, MCP, and FastAPI.

**Engineering focus:** offline model loading, idempotent document updates, consistent indexing across clients, and reusable retrieval interfaces.

### [babar](https://github.com/jbromfld/babar) - Persistent local application memory

An application-memory service that stores sourced notes and recalls relevant context across conversations and restarts. Applications connect through MCP over stdio with a fixed namespace and control when memory changes are authorized. Local embeddings and text matching support retrieval, while explicit revisions, provenance, consolidation, and forgetting keep stored memory inspectable and manageable. Abacus uses it for optional advisor memory.

**Built with:** Python, PostgreSQL, pgvector, Sentence Transformers, and MCP.

**Engineering focus:** revision-checked writes, idempotency, atomic persistence, and application-controlled memory lifecycles.

### [abacus](https://github.com/jbromfld/abacus) - Local budgeting and planning

A personal budget application for recurring income and bills, statement imports, spending trends, savings goals, and cash projections. Reviewable imports and remembered payee classifications support everyday bookkeeping. Optional Ollama features add PDF extraction and a budget advisor, with Babar providing approved memory across conversations. The managed deployment uses Argo CD and packages the advisor's memory service with the application.

**Built with:** React, TypeScript, Python, FastAPI, PostgreSQL, Ollama, and Argo CD.

**Engineering focus:** traceable imports, consistent financial projections, database migrations, and controlled integration of local AI features.

### [gcp-rag-proto](https://github.com/jbromfld/gcp-rag-proto) - Cloud-deployable knowledge search prototype

A retrieval-augmented generation (RAG) prototype with documentation ingestion, Elasticsearch vector and keyword search, answer feedback, and an operational metrics dashboard. A FastAPI service and Streamlit interface support local development, with Terraform and Cloud Build configuration for Google Cloud deployment. Model integrations support local inference, Vertex AI, and Azure OpenAI.

**Built with:** Python, FastAPI, Streamlit, Elasticsearch, Docker, and Terraform.

**Engineering focus:** configurable retrieval, model-provider integration, source management, and infrastructure as code.

### [radiofed](https://github.com/jbromfld/radiofed) - Music-data pipelines

A batch-oriented Python pipeline for ingesting MIDI files, enriching records with Million Song Dataset metadata and genre labels, and extracting timing, pitch, chord, and key features. It prepares structured datasets for music analysis and machine-learning experiments.

**Built with:** Python, SQL, MIDI datasets, and Million Song Dataset metadata.

**Engineering focus:** repeatable ingestion, metadata enrichment, and feature preparation for research.

## Tools and interests

- **Delivery and infrastructure:** GitHub Actions, Jenkins, Azure DevOps, Docker, Kubernetes, Helm, Terraform, Ansible, AWS, and Azure.
- **Programming and data:** Python, Bash, Groovy, Java, PowerShell, SQL, and PostgreSQL.
- **Applied AI projects:** local inference, RAG, MCP integrations, agent memory, and workflow orchestration.
- **Security and operations:** automated testing, SAST/DAST, vulnerability management, SBOMs, and observability.

For my full work history, education, and training, see my [resume](professional/README.md).
