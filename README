# docsgraph
 
**A local-first enterprise document intelligence platform combining secure contract management, synchronized web and desktop access, evidence-grounded search, contract analysis, workflows, and knowledge-graph visualization.**
 
</div>
---
 
## What we're building
 
docsgraph turns a pile of contracts and documents into a navigable knowledge graph — local-first, so your data stays on your machine by default, but synchronized across web and desktop when you need it. Search is evidence-grounded: answers point back to the exact passage they came from, not just a plausible-sounding summary. Contracts are analyzed automatically, and relationships between documents, parties, and clauses are visualized as an explorable graph, similar in spirit to tools like Obsidian — but built specifically for document and contract intelligence rather than general note-taking.
 
## Repositories
 
| Repo | Description |
|---|---|
| [`docsgraph`](https://github.com/docsgraph/docsgraph) | Main product monorepo — synchronized web and desktop clients, shared UI, the local-first document model, knowledge-graph visualization, search interfaces, contract-analysis features, and the synchronization client. |
| [`docsgraph-server`](https://github.com/docsgraph/docsgraph-server) | Self-hostable backend for organizations — synchronization, document processing, OCR, indexing, permissions, collaboration, workflows, audit logs, retention policies, and external integrations. |
| [`docsgraph-eval`](https://github.com/docsgraph/docsgraph-eval) | Independent benchmark and testing suite for OCR, extraction, retrieval, evidence attribution, graph generation, permissions, synchronization, and offline consistency. |
 
## How it fits together
 
```text
Client layer                 Backend layer                Quality layer
─────────────                ──────────────                ─────────────
docsgraph            ──────▶  docsgraph-server      ◀────  docsgraph-eval
(web + desktop UI,             (self-hostable sync,          (benchmarks OCR,
 local-first model,            OCR, indexing,                 retrieval, graph
 graph view, search,           permissions, workflows,        quality, and sync
 contract analysis)            audit logs)                    consistency)
```
 
- **`docsgraph`** is what a user opens — a local-first client (web and desktop) where documents live, get analyzed, and get explored through search and the knowledge graph. It works offline and syncs when connected.
- **`docsgraph-server`** is the self-hostable backend organizations run to enable sync, collaboration, permissions, and heavier processing (OCR, indexing) across a team, without giving up control of where data lives.
- **`docsgraph-eval`** keeps the other two honest — it's a standalone benchmark suite that measures whether extraction, search, and graph generation are actually accurate, and whether sync stays consistent when clients go offline and reconnect.
## Getting started
 
- New to the project? Start with the main [`docsgraph`](https://github.com/docsgraph/docsgraph) repo to understand the local-first document model and graph view.
- Running docsgraph for a team or organization? See [`docsgraph-server`](https://github.com/docsgraph/docsgraph-server) for self-hosting, sync, and permissions setup.
- Working on extraction, search, or graph quality? [`docsgraph-eval`](https://github.com/docsgraph/docsgraph-eval) has the benchmarks and test suites used to validate changes.
## Contributing
 
We welcome contributions across all repositories — document processors, search improvements, graph-visualization features, connectors to external systems, and documentation. See each repository's `CONTRIBUTING.md` for specifics, or the shared guidelines in this organization's [`.github`](https://github.com/docsgraph/.github) repo.
