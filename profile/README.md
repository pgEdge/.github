[![github_banner](https://github.com/user-attachments/assets/a1095d63-da3c-4f09-9f93-fea11822a42f)](https://www.pgedge.com/get-started/platform)

# pgEdge

**Write anywhere. Read anywhere.** pgEdge is 100% open-source, enterprise-grade Postgres, under the PostgreSQL License, for Agentic AI app development and applications that need reliable multi-region high availability while still running 100% community Postgres.

We're a team of PostgreSQL contributors, committers, and longtime community members who came here because distributed Postgres is genuinely interesting. Our CTO [Dave Page](https://github.com/dpage) is a PostgreSQL core team member and the creator of pgAdmin - he'll tell you distributed databases were the subject of his master's dissertation, and he's not joking. In September 2025 we re-licensed our core extensions - Spock, Snowflake, and lolor - from a proprietary license to the PostgreSQL License, because open source isn't a strategy for us. It's just how we think Postgres should work.

Everything here is 100% open-source. No catch.

**[Get started →](https://www.pgedge.com/get-started)** - instant access to all pgEdge products across VM, bare metal, Kubernetes, Docker, and fully managed cloud. Pick your deployment, get your code.

---

## Products

### [pgEdge Enterprise Postgres](https://www.pgedge.com/products/what-is-pgedge-enterprise-postgres)
A complete Postgres distribution (v16–18) bundling Spock, lolor, Snowflake Sequences, pgVector, pgCat, pgBackRest, PostGIS, and 20+ extensions, deployable on VMs, bare metal, Kubernetes, Docker, or on-premises. Same-day patches for every PostgreSQL release - enhancements, bug fixes, and security updates without delay.
[Download](https://www.pgedge.com/download/enterprise-postgres) · [GitHub](https://github.com/pgEdge)

### [pgEdge Cloud](https://www.pgedge.com/products/pgedge-cloud)
Fully managed enterprise-ready Postgres DBaaS, built on Spock for active-active multi-region replication.
[Learn more](https://www.pgedge.com/products/pgedge-cloud) · [Free trial](https://app.pgedge.com) · [Terraform](https://github.com/pgEdge/terraform-provider-pgedge) · [Pulumi](https://github.com/pgEdge/pulumi-pgedge)

### [pgEdge Agentic AI Toolkit](https://www.pgedge.com/products/agentic-ai-postgres)
Free, open-source tools for building AI agents on Postgres: [pgedge-postgres-mcp](https://github.com/pgEdge/pgedge-postgres-mcp) (MCP Server, pre-release), [pgedge-rag-server](https://github.com/pgEdge/pgedge-rag-server) (RAG Server), [pgedge-vectorizer](https://github.com/pgEdge/pgedge-vectorizer) (Postgres extension for async text chunking and embedding generation via background workers), and [pgedge-docloader](https://github.com/pgEdge/pgedge-docloader) (Document Loader). Available in pgEdge Cloud. Ellie, the AI assistant on [pgedge.com](https://www.pgedge.com) and [docs.pgedge.com](https://docs.pgedge.com), runs on this stack.
[Get started](https://www.pgedge.com/products/agentic-ai-postgres) · [GitHub](https://github.com/pgEdge)

### [pgEdge AI DBA Workbench](https://www.pgedge.com/products/ai-dba-workbench)
Free, open-source, agentless Postgres monitoring and AI-assisted diagnosis for any Postgres 14+ - including Amazon RDS, Supabase, Cloud SQL for PostgreSQL, Azure Flexible Server, and community Postgres. Ships with Ellie (an optional AI assistant), 21 MCP tools, persistent memory, and 3-tier anomaly detection.
[Download](https://www.pgedge.com/download/ai-dba-workbench) · [GitHub](https://github.com/pgEdge/ai-dba-workbench)

---

## Core Extensions

These are the building blocks of pgEdge Enterprise Postgres. All three were re-licensed to the PostgreSQL License in September 2025 - feel free to use them, fork them, and contribute.

| Repo | What it does |
|---|---|
| [spock](https://github.com/pgEdge/spock) | Multi-master logical replication for Postgres 15–18. The engine behind pgEdge Enterprise Postgres. |
| [snowflake](https://github.com/pgEdge/snowflake) | Globally unique int8 IDs for distributed writes - a drop-in replacement for `bigserial`. |
| [lolor](https://github.com/pgEdge/lolor) | Large Object Logical Replication for Postgres 16+. |

No compatibility layer. Just Postgres.

---

## Developer Tools

| Repo | What it does |
|---|---|
| [pgedge-anonymizer](https://github.com/pgEdge/pgedge-anonymizer) | PII anonymization for Postgres with 100+ patterns covering 19 countries. |
| [pgedge-loadgen](https://github.com/pgEdge/pgedge-loadgen) | Realistic Postgres workload generator across 7 app types, including pgvector workloads. |

---

## Infrastructure & Deployment

| Repo | What it does |
|---|---|
| [control-plane](https://github.com/pgEdge/control-plane) | Declarative Postgres cluster management API, written in Go. |
| [pgedge-helm](https://github.com/pgEdge/pgedge-helm) | Helm chart for deploying pgEdge clusters on Kubernetes. |
| [postgres-images](https://github.com/pgEdge/postgres-images) | Container images built from pgEdge Enterprise packages. |
| [pgedge-ansible](https://github.com/pgEdge/pgedge-ansible) | Ansible collection for building and managing distributed pgEdge clusters. |
| [terraform-provider-pgedge](https://github.com/pgEdge/terraform-provider-pgedge) | Terraform provider for pgEdge Cloud. |
| [pulumi-pgedge](https://github.com/pgEdge/pulumi-pgedge) | Pulumi provider for pgEdge Cloud. |

---

## Support

The people who answer support tickets at pgEdge are the same people who wrote PostgreSQL books, contributed patches upstream, and speak at Postgres conferences, including PGConf.dev. 24x7x365 coverage for pgEdge Enterprise Postgres, with diagnostics, recovery assistance, bug fixes for core Postgres and approved extensions, and access to the pgEdge knowledge base.

For teams that want more, the Forward Deployed Engineer service adds a dedicated point of contact, performance tuning, architecture reviews, and quarterly check-ins.

[Postgres support services](https://www.pgedge.com/support)

---

## Resources

- [Get started](https://www.pgedge.com/get-started) - VM, bare metal, Kubernetes, Docker, fully managed cloud
- [Docs](https://docs.pgedge.com)
- [Blog](https://www.pgedge.com/blog)
- [Webinars](https://www.pgedge.com/webinars)
- [YouTube](https://www.youtube.com/@pgEdge)
- [Demos](https://www.pgedge.com/demo-video)
- [FAQ](https://www.pgedge.com/resources/faq)
- [pgScorecard](https://pgscorecard.com) - a framework for comparing how closely Postgres distributions track community Postgres. (pgEdge scores 100%.)

---

## Community

- [Discord](https://discord.com/invite/pgedge/login)
- [LinkedIn](https://www.linkedin.com/company/pgedge/)
- [Mastodon](https://mastodon.social/@pgEdgeDistributedPostgres)
- [X](https://twitter.com/pgEdgeInc)
