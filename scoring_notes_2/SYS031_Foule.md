# Scoring Notes — SYS031 Foule (crowd dynamics)

## Identification

- **System ID :** SYS031
- **System name :** Foule (crowd dynamics)
- **Domain :** social
- **Subdomain :** physique sociale / dynamique collective
- **Scale :** meso
- **Date scored :** 2026-04-04
- **Scorer :** CL
- **Confidence globale :** medium

## Sources

1. Helbing, Farkas & Vicsek, *Simulating Dynamical Features of Escape Panic*, Nature 407 (2000)
2. Helbing & Johansson, *Pedestrian, Crowd, and Evacuation Dynamics*, arXiv:1309.1609 (2013)
3. Moussaïd, Helbing & Theraulaz, *How Simple Rules Determine Pedestrian Behavior and Crowd Disasters*, PNAS 108 (2011)

---

## A1 — Profondeur hiérarchique

| Sous-critère | Score | Justification |
|---|---|---|
| H1 : ≥ 2 niveaux causaux distincts | 1 | Niveau individu (force sociale, locomotion) et niveau collectif (flux macroscopique, onde de densité). Helbing 2000 modélise explicitement ces deux couches. |
| H2 : ≥ 3 niveaux causaux distincts | 0.5 | On peut distinguer : (i) perception/décision individuelle, (ii) interactions locales de voisinage (cluster ~5-10 personnes), (iii) pattern macroscopique (lane formation, turbulence). Le niveau intermédiaire est réel mais sa frontière avec les deux autres est floue. |
| H3 : ≥ 4 niveaux causaux distincts | 0 | Pas de quatrième niveau identifiable endogènement. L'infrastructure (murs, sorties) est un contexte externe, pas un niveau causal propre à la foule. |
| H4 : Niveaux fonctionnellement différenciés | 0.5 | Le niveau individu est locomoteur/décisionnel, le niveau macro est hydrodynamique. Mais les « fonctions » sont homologues : tous les agents font la même chose, la différenciation fonctionnelle est faible comparée à un organisme. |
| H5 : Causalité bidirectionnelle entre niveaux | 1 | Clairement bidirectionnel : les individus génèrent le flux collectif, et le flux collectif (densité locale, pression) contraint en retour le mouvement individuel. Helbing 2000 : la pression de foule force les individus contre les murs, modifiant leur comportement. |

**Score A1 = 0.60 / 1.00**

**Hésitations / ambiguïtés :**
Le statut du niveau « cluster / voisinage » est le point délicat. Dans le modèle de Moussaïd 2011, les règles simples d'interaction locale produisent des structures méso (files, bandes), mais celles-ci sont émergentes et transitoires plutôt que structurellement stables. H2 à 0.5 reflète cette ambiguïté.

---

## A2 — Capacité de propagation (formulation V2.1.1 : invariance d'échelle)

| Sous-critère | Score | Justification |
|---|---|---|
| P1 : Perturbation locale affecte ≥ 1 autre module fonctionnel | 1 | Un individu qui tombe ou ralentit perturbe immédiatement son voisinage ; la perturbation se propage via contact et réajustement de trajectoire (Helbing 2000 : « faster-is-slower effect »). |
| P2 : Propagation traverse ≥ 1 niveau hiérarchique | 1 | Une chute locale produit une onde de densité macroscopique ; inversement, un engorgement macro contraint les trajectoires individuelles. Propagation clairement trans-niveaux. |
| P3 : Propagation modifie l'état global observable | 1 | En régime dense, une perturbation locale peut déclencher un phénomène de « crowd turbulence » affectant l'ensemble de la foule (Helbing 2013). Les transitions vers le blocage (clogging) sont globales. |
| P4 : Isolement difficile sans modification structurelle | 1 | On ne peut pas isoler un sous-groupe dans une foule dense sans barrière physique. L'absence de frontière structurelle rend le couplage inévitable. Helbing 2013 souligne l'impossibilité d'isoler des zones sans réaménagement spatial. |
| P5 : Couplage fonctionnel non trivial | 0.5 | Le couplage est fort mais relativement simple : forces de contact, imitation directionnelle, ajustement de vitesse. Ce sont des mécanismes de couplage physique/comportemental directs, pas des boucles fonctionnelles complexes multi-variables. |

**Score A2 = 0.90 / 1.00**

**Hésitations / ambiguïtés :**
P5 est le point de débat. Le couplage est puissant (non-linéaire, produisant des transitions de phase) mais repose sur peu de variables couplées (position, vitesse, direction). Le caractère « non trivial » vient de la non-linéarité plutôt que de la complexité fonctionnelle.

---

## A3 — Intégration

| Sous-critère | Score | Justification |
|---|---|---|
| I1 : Mécanisme explicite de coordination | 0.5 | Pas de coordinateur central. La coordination émerge de règles locales (évitement, alignement, imitation ; Moussaïd 2011). Le mécanisme existe mais est implicite/distribué, non explicite. |
| I2 : Réduction de variance observable | 1 | Formation spontanée de files (lanes) en flux bidirectionnel : la variance directionnelle diminue drastiquement par rapport au mouvement aléatoire. Moussaïd 2011 et Helbing 2013 documentent cette auto-organisation réductrice de variance. |
| I3 : Synchronisation multi-niveaux | 0.5 | En régime de lane formation ou de stop-and-go waves, il y a synchronisation partielle entre comportement individuel et pattern collectif. Mais cette synchronisation est fragile, transitoire, et se brise en haute densité (passage à la turbulence). |
| I4 : Boucles de rétroaction globales | 0.5 | La densité globale affecte la vitesse de chaque individu (diagramme fondamental densité-vitesse). Mais la « rétroaction » est plus une contrainte physique qu'un mécanisme informationnel de régulation. Pas de signal global intégré, juste une agrégation de contraintes locales. |
| I5 : Maintien d'un état global cohérent | 0 | La foule ne maintient pas un état global de façon robuste. Les régimes (fluide, bloqué, turbulent) sont des conséquences de conditions aux limites, pas d'un maintien actif. En panique, la cohérence se fragmente (Helbing 2000). |

**Score A3 = 0.50 / 1.00**

**Hésitations / ambiguïtés :**
I1 est le point central : le débat porte sur le statut des « social forces » comme mécanisme de coordination. Elles coordonnent de facto mais ne sont pas un mécanisme dédié à la coordination — elles sont des réponses individuelles qui ont un effet coordinateur émergent. I4 est aussi ambigu : le diagramme fondamental montre un couplage global, mais est-ce une « boucle de rétroaction » ou simplement une contrainte physique ?

---

## A4 — Normativité

| Sous-critère | Score | Justification |
|---|---|---|
| N1 : Attracteur dynamique existant | 1 | Les régimes de flux (laminar flow, lane formation) sont des attracteurs bien documentés. Le diagramme fondamental densité-vitesse définit des états stationnaires vers lesquels le système converge. |
| N2 : Correction active d'écart | 0.5 | Chaque individu corrige sa trajectoire (évitement, ajustement de vitesse). Mais il n'y a pas de correction d'écart au niveau collectif : la foule ne « cherche » pas à revenir à un état — les individus le font pour eux-mêmes. Le résultat collectif est un sous-produit. |
| N3 : Hiérarchie de priorités régulatoires | 0.5 | Au niveau individuel : éviter le contact > atteindre la destination > maintenir la vitesse préférée (Helbing 2000 modélise ces priorités). Mais cette hiérarchie est celle de l'agent, pas de la foule comme système. |
| N4 : Mécanisme interne de stabilisation | 0.5 | La friction et les forces de répulsion sociale stabilisent les flux laminaires. Mais au-delà d'un seuil de densité, ces mécanismes échouent et le système devient instable (transition vers la turbulence). Stabilisation réelle mais à domaine de validité limité. |
| N5 : Résistance aux perturbations prolongées | 0 | La foule ne résiste pas aux perturbations prolongées. Un blocage de sortie durable mène au désastre, pas à l'adaptation. Helbing 2000 montre que la foule en panique amplifie les perturbations plutôt que de les absorber (arching, clogging). |

**Score A4 = 0.50 / 1.00**

**Hésitations / ambiguïtés :**
La question fondamentale est : la normativité de la foule est-elle endogène ou simplement la somme des normativités individuelles ? Les attracteurs existent au niveau collectif (lane formation), mais la « correction » et la « régulation » sont portées par les agents individuels. N2 et N3 à 0.5 reflètent cette tension.

**Distinction normativité endogène / imposée :**
La normativité est essentiellement ascendante (bottom-up) : elle émerge de la normativité individuelle (chaque piéton a un objectif, évite les collisions). La foule en tant que système ne possède pas de norme propre. En contexte d'évacuation, une normativité externe (sorties, barrières, consignes) s'ajoute mais n'est pas endogène à la foule.

---

## A5 — Capacité de révision (formulation V2.1.1 : plasticité endogène)

| Sous-critère | Score | Justification |
|---|---|---|
| R1 : Ajustement paramétrique local | 1 | Les individus ajustent en permanence vitesse, direction, distance interpersonnelle. Moussaïd 2011 : les piétons modifient leurs paramètres comportementaux en fonction de la densité locale. |
| R2 : Modification durable de configuration interne | 0.5 | La foule peut passer d'un régime fluide à un régime de files (lane formation) de façon relativement stable. Mais cette « configuration » est réversible dès que les conditions changent — sa durabilité est conditionnelle aux conditions aux limites. |
| R3 : Reconfiguration de réseau ou de structure | 0.5 | Les transitions de phase (fluide → bloqué → turbulent) constituent des reconfigurations structurelles du réseau d'interactions. Mais elles sont subies (déclenchées par la densité) plutôt qu'activement initiées par le système. |
| R4 : Modification des mécanismes de régulation | 0 | La foule ne modifie pas ses propres mécanismes de régulation. Les « social forces » et règles d'évitement restent les mêmes ; seuls leurs paramètres varient. Pas de méta-régulation. |
| R5 : Capacité à produire de nouvelles règles | 0 | Aucune capacité de la foule à engendrer de nouvelles règles comportementales. Les agents suivent des heuristiques fixes (Moussaïd 2011 : « simple rules »). |

**Score A5 = 0.40 / 1.00**

**Hésitations / ambiguïtés :**
R2 et R3 sont les points ambigus. La lane formation est-elle une « modification durable de configuration » ou simplement un état d'équilibre conditionnel ? Les transitions de phase sont-elles des « reconfigurations » au sens fort ? On accorde 0.5 car les changements sont réels et structurels mais pas endogènement pilotés.

---

## Synthèse

| Axe | Score |
|-----|-------|
| A1 | 0.60 |
| A2 | 0.90 |
| A3 | 0.50 |
| A4 | 0.50 |
| A5 | 0.40 |

### Gradients (calculés)

| Gradient | Valeur |
|----------|--------|
| Δ₂₃ = A2 − A3 | +0.40 |
| Δ₄₅ = A4 − A5 | +0.10 |
| Δ₁₂ = A1 − A2 | −0.30 |
| Δ₃₅ = A3 − A5 | +0.10 |
| Δ₄₃ = A4 − A3 | 0.00 |

### Classification (rempli APRÈS scoring)

- **Régime primaire :** Réactif-propagatif — propagation très forte (A2 = 0.90) avec intégration et normativité modérées, capacité de révision limitée.
- **Régime secondaire :** Auto-organisé faible — émergence de patterns (lanes, ondes) sans contrôle centralisé ni plasticité structurelle.
- **Marge :** Δ₂₃ = +0.40 est le gradient dominant : la foule propage massivement mais intègre faiblement. Profil typique d'un système à couplage fort mais à gouvernance faible.
- **Surprise par rapport au jugement intuitif :** Non. On s'attend intuitivement à ce qu'une foule soit un système à propagation forte et contrôle faible. Le scoring confirme le profil « amplificateur non régulé ». La relative faiblesse de A5 (0.40) souligne l'absence de plasticité endogène, ce qui est cohérent avec la littérature sur les désastres de foule : le système ne sait pas s'adapter.

---

## Notes libres

La foule est un cas d'école de système émergent sans agent central. Son profil — propagation élevée, intégration et normativité moyennes, plasticité basse — explique sa vulnérabilité aux catastrophes : les perturbations se propagent efficacement mais le système n'a ni les mécanismes d'intégration pour les absorber, ni la plasticité pour reconfigurer sa réponse.

Le gradient Δ₂₃ = +0.40 est le signal le plus important : c'est l'écart entre la capacité à transmettre des perturbations et la capacité à les intégrer de façon cohérente. C'est exactement ce qui rend les foules denses dangereuses.

Question ouverte : une foule avec communication verbale ou guidage externe (haut-parleurs, signalétique dynamique) verrait-elle son A3 et A4 augmenter significativement ? Cela correspondrait à un système augmenté plutôt qu'au système « nu » évalué ici.
