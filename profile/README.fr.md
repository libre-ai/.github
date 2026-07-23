[English](README.md) · **Français**

# Libre AI

Libre AI est un laboratoire logiciel open-source et souverain qui reconstruit sa gamme de produits pour l'ère de l'IA.

**Tout le travail en cours se déroule dans le dépôt de base canonique : [`libre-ai/libre-ai`](https://github.com/libre-ai/libre-ai)** — contrats, spécifications, architecture et fondations partagées.

La topologie cible est multi-dépôts ([ADR-0008](https://github.com/libre-ai/libre-ai/blob/main/docs/adr/0008-multi-repo-target-topology-and-brand.md)) : chaque dépôt produit est une unité indépendante et interopérable qui rouvre sous un nom conforme à son architecture et consomme la base comme dépendance versionnée. Jusqu'à son activation par décision du propriétaire, un dépôt reste réservé avec une note d'état — et son README décrit déjà ce qu'il est, ce qui existe déjà, et où vit le travail. Les dépôts d'outillage historiques sont retirés après capture vérifiée ; le registre de gel est [`ecosystem/LEGACY-MANIFEST.yaml`](https://github.com/libre-ai/libre-ai/blob/main/ecosystem/LEGACY-MANIFEST.yaml).

Huit produits sont en cours de reconstruction à partir de spécifications verrouillées : **Radar, Notebook, AI Practices, Sessions, Boussole Politique, Spec Studio, Model Policy et Carrière**. Aucun n'est encore publié ; les fondations viennent d'abord, et la page de chaque produit renvoie vers le code qui existe déjà. Une neuvième surface, **Missions**, est la couche humaine au-dessus de l'orchestration d'agents (Polaris, couche-2).

L'étoile polaire du portefeuille est **la méthode elle-même** ([ADR-0009](https://github.com/libre-ai/libre-ai/blob/main/docs/adr/0009-constellation-portfolio-and-method.md)) : la gestion agentique gouvernable de cette constellation — plans bornés, refus, preuves, portes de contrôle. Son traceur public est cette forge même, auto-documentée. L'inventaire lisible par machine de cette organisation est [`ecosystem/repositories.v1.yaml`](https://github.com/libre-ai/libre-ai/blob/main/ecosystem/repositories.v1.yaml) ; cette page en est une projection.

Commencer ici :

- [Vision](https://github.com/libre-ai/libre-ai/blob/main/vision.md) — pourquoi une reconstruction greenfield, horizon 10 ans
- [Objectifs et état](https://github.com/libre-ai/libre-ai/blob/main/STATUS.md) — transformation par phases (G0–G5), actuellement G2
- [Architecture cible](https://github.com/libre-ai/libre-ai/blob/main/docs/architecture/TARGET.md)
- [Registre des invariants](https://github.com/libre-ai/libre-ai/blob/main/docs/decisions/INVARIANTS.md)
