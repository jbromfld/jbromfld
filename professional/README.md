# James Bromfield

**Senior DevOps Engineer**  
Ann Arbor, Michigan · [Email](mailto:jbromfld@gmail.com) · [GitHub](https://github.com/jbromfld) · [Portfolio](../README.md)

## Professional summary

Software and DevOps engineer with 5+ years of experience designing and implementing CI/CD systems, developer tooling, and cloud-native delivery automation. Hands-on experience with Python, GitHub Actions, Jenkins, Kubernetes, Docker, Terraform, automated testing, and security and quality gates. Experienced in gathering requirements across engineering teams, producing technical designs and architecture documentation, and building reusable automation that standardizes software delivery at enterprise scale. Public projects apply that engineering focus to local research agents, knowledge retrieval, and AI-assisted developer workflows.

## Professional experience

### Cognizant Technology Solutions - Ann Arbor, MI

**Senior DevOps Engineer | August 2024 - Present**

- Gathered and reconciled requirements across release engineering, development squads, technology risk, and platform engineering to design CI/CD solutions balancing developer usability, security, deployment reliability, and operational requirements.
- Designed and developed an object-oriented Python CI/CD initialization framework that generates configuration maps for downstream GitHub Actions reusable workflows.
- Developed 75+ reusable Python-based GitHub Actions and pipeline assets to standardize CI/CD capabilities across application teams.
- Migrated 100+ Adobe Experience Manager (AEM) repositories and 300+ microservices from Jenkins to GitHub Actions, encompassing CI, security, deployment, and manifest-driven pipelines.
- Designed and implemented a stateful CI/CD architecture for AEM using PostgreSQL to track release state and automatically advance deployments based on security and quality gates, replacing manual environment-promotion decisions with policy-driven automation.
- Redesigned an internal VS Code security-remediation plugin as a thin client backed by a service layer, centralizing AppSec/Jira and SonarQube remediation processing, AI orchestration, and prompt management.
- Used CI/CD metrics to identify PR build inefficiencies, then designed and implemented a protected-branch PR process that reduced build times by more than 25%.
- Produced architecture diagrams, technical design documents, implementation guidance, and usage documentation for reusable CI/CD tooling and pipeline architectures.

**Associate DevOps Engineer | April 2022 - August 2024**

- Migrated CI/CD workflows from Jenkins to GitHub Actions across Java, Node, and AEM pipelines, implementing automated testing, security scanning, and rollback capabilities.
- Architected manifest-driven AEM deployments, integrating smoke and regression testing, security pipelines, and environment validations.
- Built automated workflows for SiteSpect campaigns, enabling feature routing and weighted traffic distribution.
- Enhanced environment stability testing pipelines with improved reporting and visibility for development teams.

### Revature - Ann Arbor, MI

**Associate DevOps Engineer | May 2021 - April 2022**

- Consolidated CI/CD pipelines for Maven, npm, AEM, and WebSphere into Jenkins, introducing gated release workflows with Jira automation and automated exception handling.
- Supported containerized deployments and infrastructure provisioning using Docker and Terraform.

### Paragon Development Systems - Madison, WI

**Help Desk Analyst | March 2019 - April 2021**

- Provided network, user administration, and application support for clients in education, healthcare, financial services, and energy sectors.

## Skills

| Area | Technologies and practices |
| --- | --- |
| Security and compliance | Secure coding, vulnerability management, SAST/DAST, security automation, SBOM |
| Cloud and infrastructure | AWS, Azure, Kubernetes, Docker, Helm, Terraform, Ansible, PostgreSQL |
| CI/CD and automation | GitHub Actions, Jenkins, Azure DevOps, Maven, npm, Yarn, automated testing, reusable workflows |
| Programming and scripting | Python, Bash, Groovy, Java, PowerShell |
| Developer tooling and observability | Artifactory, Jira, Confluence, Splunk, Dynatrace |
| Applied AI project technologies | FastAPI, Temporal, Ollama, pgvector, Elasticsearch, RAG, MCP integrations |

## Education

**Pennsylvania State University** - College of Information Sciences and Technology  
B.S. Information Sciences and Technology | May 2021

## Certifications and professional education

- **[Applied AI and Data Science Program](https://credentials.professional.mit.edu/20b0515a-f7c0-4f78-aa66-9d336404a347#acc.ETgVPMJ0)** - MIT Professional Education | June 2026

## Public projects

Selected personal projects demonstrate applied AI, retrieval, and workflow engineering alongside my professional CI/CD work:

- **[lalaland](https://github.com/jbromfld/lalaland) — Local research agents:** RSS briefings and detailed paper summaries using FastAPI, Temporal, Ollama, and PostgreSQL. Research processing includes evidence notes with source references, checkpointed chunks, scheduled batches, and a review dashboard.
- **[lassy](https://github.com/jbromfld/lassy) and [lassy-extension](https://github.com/jbromfld/lassy/tree/main/extension) — Knowledge retrieval in the IDE:** Documentation ingestion and hybrid vector/keyword search using FastAPI and PostgreSQL/pgvector. The VS Code extension adds an `@knowledge` chat participant with direct API and MCP modes, cited context, and client-side answer generation.
- **[gcp-rag-proto](https://github.com/jbromfld/gcp-rag-proto) — Cloud-deployable knowledge search:** FastAPI and Streamlit application with Elasticsearch hybrid search, source management, answer feedback, and metrics. Includes Terraform for Google Cloud deployment and integrations for local models, Vertex AI, and Azure OpenAI.
- **[radiofed](https://github.com/jbromfld/radiofed) — Music-data experimentation:** Python pipeline for MIDI ingestion, Million Song Dataset metadata enrichment, and musical feature preparation for analysis and ML experiments.

See my [portfolio](../README.md#featured-projects) for project details and engineering focus.
