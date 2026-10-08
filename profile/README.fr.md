<!-- SPDX-FileCopyrightText: 2026 Libre AI contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->

<!-- libre-ai:brand-intro:begin -->
# Libre AI

> Les plateformes propriétaires vous louent le produit.

## Possédez la fabrique.

Libre AI réunit les logiciels, la méthode et les preuves pour construire des outils d'IA que vous pouvez vérifier, modifier et déployer où vous le décidez.

**Ouverts, souverains et explicables.** Conçus dans une fabrique ouverte où la preuve fait partie du produit.

[Prenez les clés.](https://libre-ai.fr/#produits) · [Voir les preuves.](https://libre-ai.fr/#preuves)
<!-- libre-ai:brand-intro:end -->

Des projets pour travailler et apprendre avec l’IA, en gardant la main sur les sources et les décisions.

**Aujourd’hui :** chaque dépôt ci-dessous porte son implémentation et ses propres contrôles. Aucun ne propose encore d’application installable. Ce qui est réellement prouvé pour un projet donné est consigné dans sa fiche d’état — rien ici n’affirme plus que ces fiches.

## Les produits envisagés

Choisissez le besoin qui vous intéresse :

- [Suivre le travail confié à l’IA](https://github.com/libre-ai/ai-work-supervision)
- [Comprendre quels usages des modèles sont permis](https://github.com/libre-ai/ai-model-policy)
- [Apprendre en pratiquant avec l’IA](https://github.com/libre-ai/ai-practice-workbench)
- [Préparer et animer un atelier d’apprentissage](https://github.com/libre-ai/learning-session-facilitation)
- [Retrouver ses notes et leurs sources](https://github.com/libre-ai/personal-knowledge-notebook)
- [Repérer les informations utiles dans sa veille](https://github.com/libre-ai/information-feed-filter)
- [Préparer un itinéraire à partir de sources consultables](https://github.com/libre-ai/travel-itinerary-planner)
- [Signaler un incident et vérifier sa correction](https://github.com/libre-ai/signalement)

## Pour les développeurs

Ces composants sont prévus pour construire et relier les produits :

- [Construire les interfaces des applications](https://github.com/libre-ai/application-development-toolkit)
- [Définir les données échangées entre outils](https://github.com/libre-ai/schemas-and-contracts)
- [Synchroniser des données partagées](https://github.com/libre-ai/collaborative-data-sync)
- [Évaluer si une exécution peut continuer ou reprendre](https://github.com/libre-ai/execution-continuity-evaluator)
- [Limiter les accès des programmes exécutés](https://github.com/libre-ai/execution-sandbox)
- [Vérifier les permissions d’une action](https://github.com/libre-ai/capability-authorization)
- [Appliquer les règles de conservation et de suppression](https://github.com/libre-ai/organization-data-lifecycle)
- [Examiner les règles d’accès aux bases de données](https://github.com/libre-ai/database-policy-inspector)
- [Vérifier qu’un fichier correspond à ce qui est attendu](https://github.com/libre-ai/artifact-verification)
- [Consigner les contrôles qu’un agent a réellement exécutés](https://github.com/libre-ai/pi-evidence)

## État des projets

<!-- libre-ai:project-status:begin -->
<!-- Section générée depuis les fiches project.v1.yaml de la constellation
     (projection fleet-status) et l'index de migration du hub — ne pas éditer à la main. -->

### Produits (couche 1)

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [ai-model-policy](https://github.com/libre-ai/ai-model-policy) | ai-model-policy: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [ai-practice-workbench](https://github.com/libre-ai/ai-practice-workbench) | ai-practice-workbench: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [carriere](https://github.com/libre-ai/carriere) | Assistant de recherche d'emploi pour cadres — souverain, explicable (8e produit, ratifié 2026-07-23). | Avancement non calculable — périmètre à clarifier | idea | 2026-10-08 |
| [information-feed-filter](https://github.com/libre-ai/information-feed-filter) | information-feed-filter: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [learning-session-facilitation](https://github.com/libre-ai/learning-session-facilitation) | learning-session-facilitation: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [personal-knowledge-notebook](https://github.com/libre-ai/personal-knowledge-notebook) | personal-knowledge-notebook: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [signalement](https://github.com/libre-ai/signalement) | Signalement web relu, reproduction exécutable et vérification déterministe, avec projections portables vers plusieurs systèmes de travail. | 18,8 % du périmètre actuellement déclaré | specified | 2026-10-06 |
| [travel-itinerary-planner](https://github.com/libre-ai/travel-itinerary-planner) | travel-itinerary-planner: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-08 |
### Orchestration (couche 2)

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [ai-work-supervision](https://github.com/libre-ai/ai-work-supervision) | ai-work-supervision: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [orchestrator](https://github.com/libre-ai/execution-continuity-evaluator) | Cœur Rust sans effet pour le contrôle et les décisions authorized-execution, avec preuves de rejeu déterministe et outillage de revue. | 100 % du périmètre actuellement déclaré | usable | 2026-09-10 |
| [harness](https://github.com/libre-ai/execution-sandbox) | Bibliothèque candidate de confinement attesté : cœur Rust et module hôte présents, dépendances explicitement bornées, qualification Linux et admission du garde encore ouvertes. | 0 % du périmètre actuellement déclaré | specified | 2026-09-12 |
### Briques structurantes (couche 3)

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [artifact-verification](https://github.com/libre-ai/artifact-verification) | artifact-verification: recovered sources with documentary integration under review. | Avancement non calculable — périmètre à clarifier | idea | 2026-10-07 |
| [authz-biscuit](https://github.com/libre-ai/capability-authorization) | Autorisation interne Biscuit Ed25519, refus par défaut : émission, atténuation, vérification, révocation et rotation à deux clés. | 50 % du périmètre actuellement déclaré | usable | 2026-07-30 |
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
| [project-governance](https://github.com/libre-ai/project-governance) | Autorité de doctrine : décisions, invariants, index d'écosystème, schéma de fiches, outillage de flotte. | 33,3 % du périmètre actuellement déclaré | usable | 2026-09-09 |
| [contracts](https://github.com/libre-ai/schemas-and-contracts) | Autorité canonique des contrats : catalogue, vecteurs, politiques de compatibilité. | 50 % du périmètre actuellement déclaré | usable | 2026-07-30 |
### Moyeu

| Projet | Résumé | Avancement | Maturité | Vérifié le |
| --- | --- | --- | --- | --- |
| [libre-ai](https://github.com/libre-ai/libre-ai) | L'archive du hub — histoire intégrale, index de migration et registre d'oubli (jalon γ complet, ADR-0020). | 100 % du périmètre actuellement déclaré | usable | 2026-07-30 |

### Moyeu archivé

Le hub historique [libre-ai/libre-ai](https://github.com/libre-ai/libre-ai) est archivé : 83/88 chemins tracés à l'index de migration ont quitté le hub (double présence tant que la preuve verte n'est pas faite à destination — jamais d'absence).

<!-- libre-ai:project-status:end -->

## Le projet

[Site prévu](https://github.com/libre-ai/project-website) · [Règles du projet](https://github.com/libre-ai/project-governance) · [Contribuer](https://github.com/libre-ai/.github/blob/main/CONTRIBUTING.md) · [Signaler une faille en privé](https://github.com/libre-ai/.github/blob/main/SECURITY.md)

[English](README.md)
