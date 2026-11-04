# Finance Lab Portfolio

Independent portfolio capability: holdings, investment transactions and portfolio calculations. Detailed product/precision contracts and implementation are deferred beyond Budget R1.

Planning documentation only. This repository is not an R1 runtime dependency; do not add placeholder application code.

The canonical [architecture](https://github.com/finance-lab-project/app/blob/main/docs/architecture.md) and [release plan](https://github.com/finance-lab-project/app/blob/main/docs/roadmap.md) live in `app`. Track this module's work in [its issues](https://github.com/finance-lab-project/portfolio/issues) and its private project board.

Java without Spring. Business modules own their domain, application API, Vaadin adapters, persistence mappings and reviewed SQL migrations. The ORM is a library; business rules and aggregate revisions remain with the business module. Root assembly pins immutable module versions.

No runnable implementation or completed checks are claimed by this initial repository setup. Separate learning issues are not part of this backlog. Use synthetic examples only; no real financial data, employer material, secrets or local paths.
