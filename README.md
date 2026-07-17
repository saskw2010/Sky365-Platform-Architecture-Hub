# SKY365 Platform Architecture Hub

The official evidence-first architectural knowledge base for SKY365 as a **Metadata-Driven Application Platform (MDAP)**.

## Open the Architecture Hub

**[Launch the published Architecture Hub](https://saskw2010.github.io/Sky365-Platform-Architecture-Hub/)**

The site includes:

- Repository and Controller lineage.
- Code On Time Controller architecture and conversion fidelity.
- Controller-to-screen runtime lifecycle.
- Engine catalog and maturity matrix.
- Existing, partial, planned, and unestablished Engine contracts.
- Metadata property reference.
- AI and semantic readiness assessment.
- Architecture Decision Records and living-knowledge governance.

## Validated architecture position

SKY365 is treated as an MDAP, not as an ERP application. Controllers are the central metadata model for screens, CRUD, lookups, validation, and tool discovery. Workflow, dashboard, report, security, AI, and semantic capabilities are linked domains with documented deviations and maturity levels.

## Evidence statuses

| Status | Meaning |
|---|---|
| Verified | Executable source and an identifiable runtime path were found. |
| Partial | Useful executable components exist, but the complete Engine boundary is not proven. |
| Prototype | A demonstrable experiment exists without production lifecycle evidence. |
| Documented only | Architecture, research, or roadmap exists without verified runtime implementation. |
| Not established | No complete implementation boundary was found in the inspected source scope. |

## Start here

- [Architecture Hub](index.html)
- [Mission completion audit](mission-completion-audit.html)
- [Engine catalog](engine-catalog.html)
- [Engine maturity matrix](engine-maturity-matrix.html)
- [Controller and screen registry](controller-screen-registry.html)
- [Code On Time Controller architecture](codeontime-controller.html)
- [Metadata property reference](metadata-property-reference.html)
- [ADR index](adr/index.html)

## Local preview

From the repository root:

```powershell
python -m http.server 8765 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8765/`.

## Scope and safety

This repository contains architectural documentation only. It does not contain production source code or copied credentials. Claims are tied to pinned repository revisions and must be refreshed when implementation evidence changes.

