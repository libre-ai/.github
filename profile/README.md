<!-- SPDX-FileCopyrightText: 2026 Libre AI contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->

<!-- libre-ai:brand-intro:begin -->
# Libre AI

> Proprietary platforms rent you the product.

## Own the factory.

Libre AI brings together the software, method, and evidence to build AI tools you can inspect, modify, and deploy where you choose.

**Open, sovereign, and explainable.** Built in an open factory where evidence is part of the product.

[Take the keys.](https://libre-ai.fr/#produits) · [See the evidence.](https://libre-ai.fr/#preuves)
<!-- libre-ai:brand-intro:end -->

Projects for working and learning with AI, while keeping control over sources and decisions.

**Today:** each repository below carries its implementation and its own checks. None of them is a released application you can install yet. What is actually proven for a given project is recorded in that repository's own state card — nothing here claims more than those cards do.

## Planned products

Choose the need that interests you:

- [Track work assigned to AI](https://github.com/libre-ai/ai-work-supervision)
- [Understand which model uses are permitted](https://github.com/libre-ai/ai-model-policy)
- [Prepare and facilitate a learning session](https://github.com/libre-ai/learning-session-facilitation)
- [Find your notes and their sources](https://github.com/libre-ai/personal-knowledge-workspace)
- [Plan an itinerary using sources you can inspect](https://github.com/libre-ai/travel-itinerary-planner)
- [Report an incident and verify its fix](https://github.com/libre-ai/signalement)

## For developers

These components are planned to build and connect the products:

- [Build application interfaces](https://github.com/libre-ai/application-development-toolkit)
- [Define data exchanged between tools](https://github.com/libre-ai/schemas-and-contracts)
- [Synchronize shared data](https://github.com/libre-ai/collaborative-data-sync)
- [Assess whether work can continue or resume](https://github.com/libre-ai/execution-continuity-evaluator)
- [Limit access for programs being run](https://github.com/libre-ai/execution-sandbox)
- [Check permissions for an action](https://github.com/libre-ai/capability-authorization)
- [Apply data retention and deletion rules](https://github.com/libre-ai/organization-data-lifecycle)
- [Inspect database access rules](https://github.com/libre-ai/database-policy-inspector)
- [Check that a file matches what is expected](https://github.com/libre-ai/artifact-verification)
- [Record which checks an agent actually ran](https://github.com/libre-ai/pi-evidence)

## Project status

<!-- libre-ai:project-status:begin -->
<!-- Section générée depuis les fiches project.v1.yaml de la constellation
     (projection fleet-status) et l'index de migration du hub — ne pas éditer à la main. -->

### Produits (couche 1)

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [ai-model-policy](https://github.com/libre-ai/ai-model-policy) | ai-model-policy: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [ai-practice-workbench](https://github.com/libre-ai/ai-practice-workbench) | archived; its scope moved to libre-ai/personal-knowledge-workspace | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [carriere](https://github.com/libre-ai/carriere) | Assistant de recherche d'emploi pour cadres — souverain, explicable (8e produit, ratifié 2026-07-23). | Avancement non calculable — périmètre à clarifier | idea | 2026-10-08 |
| [information-feed-filter](https://github.com/libre-ai/information-feed-filter) | archived; its scope moved to libre-ai/personal-knowledge-workspace | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [learning-session-facilitation](https://github.com/libre-ai/learning-session-facilitation) | learning-session-facilitation: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [personal-knowledge-workspace](https://github.com/libre-ai/personal-knowledge-workspace) | personal-knowledge-workspace: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [signalement](https://github.com/libre-ai/signalement) | Signalement web relu, reproduction exécutable et vérification déterministe, avec projections portables vers plusieurs systèmes de travail. | 18,8 % du périmètre actuellement déclaré | specified | 2026-10-07 |
| [travel-itinerary-planner](https://github.com/libre-ai/travel-itinerary-planner) | travel-itinerary-planner: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-08 |
### Orchestration (couche 2)

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [ai-work-supervision](https://github.com/libre-ai/ai-work-supervision) | ai-work-supervision: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [execution-continuity-evaluator](https://github.com/libre-ai/execution-continuity-evaluator) | Cœur Rust sans effet pour le contrôle et les décisions authorized-execution, avec preuves de rejeu déterministe et outillage de revue. | 100 % du périmètre actuellement déclaré | usable | 2026-09-10 |
| [execution-sandbox](https://github.com/libre-ai/execution-sandbox) | Bibliothèque candidate de confinement attesté : cœur Rust et module hôte présents, dépendances explicitement bornées, qualification Linux et admission du garde encore ouvertes. | 0 % du périmètre actuellement déclaré | specified | 2026-09-12 |
### Briques structurantes (couche 3)

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [artifact-verification](https://github.com/libre-ai/artifact-verification) | artifact-verification: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [capability-authorization](https://github.com/libre-ai/capability-authorization) | Autorisation interne Biscuit Ed25519, refus par défaut : émission, atténuation, vérification, révocation et rotation à deux clés. | 50 % du périmètre actuellement déclaré | usable | 2026-07-30 |
### Atelier (couche 4)

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [collaborative-data-sync](https://github.com/libre-ai/collaborative-data-sync) | collaborative-data-sync: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-08 |
| [organization-data-lifecycle](https://github.com/libre-ai/organization-data-lifecycle) | organization-data-lifecycle: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
### Transverse

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [database-policy-inspector](https://github.com/libre-ai/database-policy-inspector) | database-policy-inspector: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [pi-evidence](https://github.com/libre-ai/pi-evidence) | Pi package and CLI for declared-check evidence and replay. | 50 % du périmètre actuellement déclaré | usable | 2026-10-06 |
| [project-governance](https://github.com/libre-ai/project-governance) | Autorité de doctrine : décisions, invariants, index d'écosystème, schéma de fiches, outillage de flotte. | 33,3 % du périmètre actuellement déclaré | usable | 2026-10-08 |
| [schemas-and-contracts](https://github.com/libre-ai/schemas-and-contracts) | Autorité canonique des contrats : catalogue, vecteurs, politiques de compatibilité. | 50 % du périmètre actuellement déclaré | usable | 2026-07-30 |
### Moyeu

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [libre-ai](https://github.com/libre-ai/libre-ai) | L'archive du hub — histoire intégrale, index de migration et registre d'oubli (jalon γ complet, ADR-0020). | 100 % du périmètre actuellement déclaré | usable | 2026-07-30 |

### Moyeu archivé

Le hub historique [libre-ai/libre-ai](https://github.com/libre-ai/libre-ai) est archivé : 83/88 chemins tracés à l'index de migration ont quitté le hub (double présence tant que la preuve verte n'est pas faite à destination — jamais d'absence).

<!-- libre-ai:project-status:end -->

## The project

[Planned website](https://github.com/libre-ai/project-website) · [Project rules](https://github.com/libre-ai/project-governance) · [Contribute](https://github.com/libre-ai/.github/blob/main/CONTRIBUTING.md) · [Report a vulnerability privately](https://github.com/libre-ai/.github/blob/main/SECURITY.md)

[Français](README.fr.md)
