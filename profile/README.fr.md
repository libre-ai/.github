[English](README.md) · **Français**

# Libre AI

**Des logiciels souverains et explicables — construits en public, par des agents IA sous gouvernance humaine.**

Libre AI est un laboratoire logiciel open-source indépendant. Nous reconstruisons une gamme complète de produits pour l'ère de l'IA, en repartant d'une base propre, avec une conviction simple : les outils qui comptent doivent appartenir à ceux qui s'en servent. Code ouvert, données sous votre contrôle, décisions traçables, réversibilité — non pas des promesses marketing, mais des règles écrites, publiques et vérifiables.

## Une fabrique inhabituelle

La plupart des éditeurs montrent leurs produits et cachent leur fabrique. Ici, la fabrique est le premier produit.

L'ensemble du portefeuille est développé par des agents IA opérant sous une méthode gouvernée : des plans bornés avant d'agir, des preuves exigées à chaque étape, des portes de contrôle où un humain tranche, des refus documentés quand une limite est atteinte. Rien ne se joue en coulisses — chaque pull request, chaque décision d'architecture, chaque porte franchie est visible dans cette forge, qui se documente elle-même.

Cette méthode s'appelle **Polaris**. Elle pilote la construction de tout le reste — et elle deviendra un produit à part entière, pour les équipes qui veulent opérer leurs propres flottes d'agents avec le même niveau d'exigence.

## Ce que nous construisons

Huit produits open-source, avec une règle commune : la spécification est publiée et verrouillée avant le code.

| Produit                                                                  | En une phrase                                                                                                         |
| ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| [**Radar**](https://github.com/libre-ai/feed-radar)                      | Un lecteur de flux qui explique pourquoi chaque article vous est proposé — curation portable, zéro algorithme opaque. |
| [**Notebook**](https://github.com/libre-ai/notebook)                     | Vos connaissances, locales d'abord et privées ; vous décidez exactement de ce qu'une IA peut en voir.                 |
| [**Sessions**](https://github.com/libre-ai/sessions)                     | Apprentissage collectif et facilitation ancrés dans les sources, pas dans des slides.                                 |
| [**AI Practices**](https://github.com/libre-ai/ai-practices)             | Se former à des pratiques IA professionnelles, sur des contenus sourcés et vérifiables.                               |
| [**Boussole Politique**](https://github.com/libre-ai/boussole-politique) | Comparer ses positions aux votes publics réellement exprimés — en privé, sources à l'appui.                           |
| [**Spec Studio**](https://github.com/libre-ai/spec-studio)               | Décisions produit, spécifications et passations bornées, prêtes à être confiées à des agents.                         |
| **Model Policy**                                                         | Choisir un modèle d'IA selon une politique explicable, pas par habitude.                                              |
| [**Carrière**](https://github.com/libre-ai/carriere)                     | Un assistant de recherche d'emploi souverain et explicable, pensé pour les cadres.                                    |

S'y ajoute [**Missions**](https://github.com/libre-ai/missions) : la surface humaine du pilotage d'agents — proposer, relire, autoriser, valider. C'est par elle que Polaris rencontrera ses utilisateurs.

## Où nous en sommes — sans enjolivement

**Aucun produit n'est encore publié.** Plutôt que d'empiler sur l'existant, nous avons gelé nos dépôts historiques et repartons de zéro : architecture cohérente, noms définitifs, exigences en place dès la première ligne. Les fondations — contrats, architecture, briques partagées — se construisent dans le dépôt central, [`libre-ai/libre-ai`](https://github.com/libre-ai/libre-ai), où se trouve tout le travail en cours. Chaque produit dispose déjà de son dépôt réservé, dont le README dit ce qu'il est, ce qui existe déjà et où vit le travail — de même que le futur site public, [Website](https://github.com/libre-ai/website).

Une règle gouverne notre communication : rien n'est mis en vitrine qui ne soit vérifiable. Les portes franchies et les preuves sont publiées au fil de l'eau ; l'inventaire complet de l'organisation, [`ecosystem/repositories.v1.yaml`](https://github.com/libre-ai/libre-ai/blob/main/ecosystem/repositories.v1.yaml), est la source machine-lisible dont cette page est la lecture humaine.

## Nos engagements

- **Souveraineté** — open-source de bout en bout, aucun enfermement propriétaire, réversibilité garantie.
- **Vie privée** — local-first partout où c'est possible ; zéro profilage, zéro donnée personnelle dans les logs.
- **Explicabilité** — chaque sélection, chaque verdict, chaque refus peut être tracé jusqu'à sa justification.
- **Preuve avant promesse** — une capacité n'est revendiquée que lorsqu'elle est démontrable publiquement.

## Pour aller plus loin

- [Vision](https://github.com/libre-ai/libre-ai/blob/main/vision.md) — pourquoi une reconstruction complète, à horizon 5–10 ans
- [Objectifs et état](https://github.com/libre-ai/libre-ai/blob/main/STATUS.md) — la transformation par phases (G0–G5) ; G2 achevée, vague 1 en cours
- [Architecture cible](https://github.com/libre-ai/libre-ai/blob/main/docs/architecture/TARGET.md)
- [Registre des invariants](https://github.com/libre-ai/libre-ai/blob/main/docs/decisions/INVARIANTS.md) — ce qui est doctrine, rien d'autre
- Les décisions fondatrices : [un dépôt par produit, une marque (ADR-0008)](https://github.com/libre-ai/libre-ai/blob/main/docs/adr/0008-multi-repo-target-topology-and-brand.md) · [le portefeuille et la méthode (ADR-0009)](https://github.com/libre-ai/libre-ai/blob/main/docs/adr/0009-constellation-portfolio-and-method.md)
