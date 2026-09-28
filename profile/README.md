[![github_banner](https://github.com/user-attachments/assets/ea7bfb9e-93b4-409b-89eb-ea7e05b2d998)](https://www.pgedge.com/)

# pgEdge

**Build on cloud. Deploy anywhere.** pgEdge is 100% open-source, enterprise-grade Postgres, under the PostgreSQL License. pgEdge Starfleet takes it from first prototype to production: start building on pgEdge-hosted cloud in under two minutes, then deploy the identical Postgres platform to your own cloud, on-premises, or air-gapped infrastructure, with no replatforming.

We're a team of PostgreSQL contributors, committers, and longtime community members who came here because distributed Postgres is genuinely interesting. Our CTO [Dave Page](https://github.com/dpage) is a PostgreSQL core team member and the creator of pgAdmin - he'll tell you distributed databases were the subject of his master's dissertation, and he's not joking. In September 2025 we re-licensed our core extensions - Spock, Snowflake, and lolor - from a proprietary license to the PostgreSQL License, because open source isn't a strategy for us. It's just how we think Postgres should work.

Everything here is 100% open-source. No catch.

**[Start with pgEdge Starfleet →](https://www.pgedge.com/products/starfleet)** - get a Postgres database running in under two minutes, 14-day free trial, no credit card required. Deploy anywhere from there: our cloud, your cloud, or on-premises.

---

## Products

### [pgEdge Starfleet](https://www.pgedge.com/products/starfleet)
The enterprise Postgres cloud platform: build fast on pgEdge-hosted cloud (14-day free trial, no credit card), then take the same Postgres platform to your own cloud (AWS, Azure, GCP) or fully on-premises, even air-gapped, without replatforming. Built-in MCP server, RAG server, and PostgREST API server for agentic AI development, plus copy-on-write database branching, implemented without replacing the Postgres storage layer. Secure by default: not open to the internet, with IP allowlisting, and true read-only MCP connections via pgEdge SafeSession.
[Start free](https://www.pgedge.com/products/starfleet) · [Docs](https://docs.pgedge.com)

### [pgEdge Enterprise Postgres](https://www.pgedge.com/products/what-is-pgedge-enterprise-postgres)
The self-hosted deployment path for pgEdge Starfleet, and a complete Postgres distribution (v16–18) on its own: bundles Spock, lolor, Snowflake Sequences, pgVector, pgCat, pgBackRest, PostGIS, and 20+ extensions. Deploy on VMs, bare metal, Kubernetes, Docker, or fully on-premises, including air-gapped. Same-day patches for every PostgreSQL release - enhancements, bug fixes, and security updates without delay.
[Download](https://www.pgedge.com/download/enterprise-postgres) · [GitHub](https://github.com/pgEdge)

### [pgEdge Agentic AI Toolkit](https://www.pgedge.com/products/agentic-ai-postgres)
Open-source tools for building AI agents on Postgres: [pgedge-postgres-mcp](https://github.com/pgEdge/pgedge-postgres-mcp) (MCP Server, pre-release), [pgedge-rag-server](https://github.com/pgEdge/pgedge-rag-server) (RAG Server), a PostgREST API server for browser-client database access, [pgedge-vectorizer](https://github.com/pgEdge/pgedge-vectorizer) (async text chunking and embedding generation via background workers), and [pgedge-docloader](https://github.com/pgEdge/pgedge-docloader) (Document Loader). Integrated into pgEdge Starfleet. Ellie, the AI assistant on [pgedge.com](https://www.pgedge.com) and [docs.pgedge.com](https://docs.pgedge.com), runs on this stack.
[Get started](https://www.pgedge.com/products/agentic-ai-postgres) · [GitHub](https://github.com/pgEdge)

### [pgEdge AI DBA Workbench](https://www.pgedge.com/products/ai-dba-workbench)
Free, open-source, agentless Postgres monitoring and AI-assisted diagnosis for any Postgres 14+ - including Amazon RDS, Supabase, Cloud SQL for PostgreSQL, Azure Flexible Server, and community Postgres. Ships with Ellie (an optional AI assistant), 21 MCP tools, persistent memory, and 3-tier anomaly detection.
[Download](https://www.pgedge.com/download/ai-dba-workbench) · [GitHub](https://github.com/pgEdge/ai-dba-workbench)

---

## Core Extensions

These are the building blocks of pgEdge Enterprise Postgres and pgEdge Starfleet. All three were re-licensed to the PostgreSQL License in September 2025 - feel free to use them, fork them, and contribute.

| Repo | What it does |
|---|---|
| [spock](https://github.com/pgEdge/spock) | Multi-master logical replication for Postgres 15–18 - write anywhere, read anywhere. The engine behind pgEdge Enterprise Postgres. |
| [snowflake](https://github.com/pgEdge/snowflake) | Globally unique int8 IDs for distributed writes - a drop-in replacement for `bigserial`. |
| [lolor](https://github.com/pgEdge/lolor) | Large Object Logical Replication for Postgres 16+. |

No compatibility layer. Just Postgres.

Building from source means patching your own PostgreSQL tree first - Spock ships the version-specific patches for exactly that. Most teams skip the patching step and run these extensions on pgEdge Enterprise Postgres instead: the same precompiled, tested, and validated binaries that back every pgEdge Starfleet deployment, hosted or self-managed.

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
| [terraform-provider-pgedge](https://github.com/pgEdge/terraform-provider-pgedge) | Terraform provider for pgEdge's managed cloud. |
| [pulumi-pgedge](https://github.com/pgEdge/pulumi-pgedge) | Pulumi provider for pgEdge's managed cloud. |

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
- [Bluesky](https://bsky.app/profile/pgedge.bsky.social)
