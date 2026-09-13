# Azure Knowledge Base

Personal learning, research, and reference repository for Microsoft Azure cloud services,
architecture patterns, and system design — organized as a documentation source for MSP Portal.

**GitHub:** https://github.com/MSP-learn/azure-knowledge

## What this is

A structured collection of everything I'm learning about Azure:

- **Step-by-step guides** — learn Azure services from zero through production-ready patterns
- **Visual diagrams** — architecture sketches, data flows, deployment topologies
- **System design glossary** — Azure-native and cloud-agnostic terms connected to Azure services
- **Service deep-dives** — compute, networking, storage, databases, AI/ML, security, DevOps
- **Architecture patterns** — Well-Architected Framework, landing zones, migration, hybrid cloud

## Repository layout

| Path | Purpose |
| --- | --- |
| `.docs-source.yml` | Source metadata for MSP Portal sync |
| `docs/` | Published learning content (flat markdown) |
| `docs/README.md` | Learning landing page |
| `guides/` | Contributor notes and learning-path guidance |
| `.agents/skills/` | Agent skills for generating diagrams, architecture reviews, etc. |
| `scripts/` | Utility scripts for content review |

## How to use this

1. Browse `docs/` by topic — each service or concept has its own page
2. Follow `guides/` for curated learning paths (Azure Fundamentals → Solutions Architect)
3. Run `node scripts/review-content.mjs` to check markdown quality
4. The content is structured for MSP Portal: `docs/` gets synced, `guides/` stays local

## Learning approach

Each topic follows this structure when applicable:

- **What it is** — plain-language definition
- **How it works** — architecture, components, data flow
- **When to use it** — decision criteria, trade-offs, anti-patterns
- **Step-by-step** — hands-on walkthrough
- **Diagram** — visual representation
- **Related terms** — cross-references to the system design glossary
