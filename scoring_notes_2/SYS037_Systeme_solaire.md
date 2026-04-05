# Scoring Notes — SYS037 Système solaire

## Identification

- **System ID :** SYS037
- **System name :** Système solaire
- **Domain :** physical
- **Subdomain :** mécanique céleste / dynamique gravitationnelle
- **Scale :** macro
- **Date scored :** 2026-04-04
- **Scorer :** CL
- **Confidence globale :** high

## Sources

1. Murray & Dermott, *Solar System Dynamics*, Cambridge University Press, 1999
2. Laskar, *Large-Scale Chaos in the Solar System*, Astronomy & Astrophysics 287, 1994
3. Goldreich, *Tides and the Earth–Moon System*, Scientific American 226, 1972

---

## A1 — Profondeur hiérarchique

| Sous-critère                                  | Score | Justification                                                                                                                                                                                                                                                                                                                                                                                                            |
| --------------------------------------------- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| H1 : ≥ 2 niveaux causaux distincts            | 1     | Niveau 1 : interaction Soleil–planètes (problème de Kepler). Niveau 2 : sous-systèmes planète–satellites (ex. Jupiter–lunes galiléennes). Deux niveaux causaux nets, avec des échelles de temps et de force très différentes.                                                                                                                                                                                            |
| H2 : ≥ 3 niveaux causaux distincts            | 1     | Niveau 3 : dynamique interne des corps (différenciation, marées internes, volcanisme de marée sur Io). Les marées sont un couplage gravitationnel orbital → déformation interne, un troisième niveau causal distinct (Goldreich 1972).                                                                                                                                                                                   |
| H3 : ≥ 4 niveaux causaux distincts            | 0.5   | On peut distinguer un 4e niveau : les résonances séculaires à l'échelle du système entier (précession des périhélies, chaos séculaire décrit par Laskar 1994), qui émergent de l'accumulation des perturbations mutuelles sur des millions d'années. Niveau légitime mais sa séparabilité par rapport aux niveaux 1-2 est discutable — c'est un effet statistique cumulatif plus qu'un niveau structurellement distinct. |
| H4 : Niveaux fonctionnellement différenciés   | 1     | Les niveaux remplissent des fonctions dynamiques différentes : le niveau central (Soleil) fixe la géométrie globale, les sous-systèmes satellitaires ont leur propre dynamique quasi-indépendante, les résonances séculaires gouvernent la stabilité à long terme. Murray & Dermott distinguent explicitement ces régimes.                                                                                               |
| H5 : Causalité bidirectionnelle entre niveaux | 0.5   | La causalité descendante (Soleil → orbites planétaires → orbites satellitaires) est dominante. La causalité ascendante existe mais est faible : les marées satellite → planète dissipent de l'énergie et modifient lentement l'orbite (recul de la Lune, Goldreich 1972), les perturbations planétaires mutuelles modifient le champ central effectif. C'est réel mais très asymétrique.                                 |

**Score A1 = 0.80 / 1.00**

**Hésitations / ambiguïtés :**
Le 4e niveau (chaos séculaire) pose question : est-ce un niveau hiérarchique propre ou un comportement émergent des niveaux 1-2 ? On accorde 0.5 par prudence. La bidirectionnalité existe physiquement mais la dissymétrie Soleil → reste est écrasante ; 0.5 reflète le caractère très asymétrique.

---

## A2 — Capacité de propagation (formulation V2.1.1 : invariance d'échelle)

| Sous-critère                                                  | Score | Justification                                                                                                                                                                                                                                                                                                                                            |
| ------------------------------------------------------------- | ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| P1 : Perturbation locale affecte ≥ 1 autre module fonctionnel | 1     | Toute perturbation orbitale d'une planète affecte ses voisines par couplage gravitationnel. Les résonances moyennes (ex. Jupiter–Saturne en quasi-résonance 5:2) montrent une propagation inter-module directe (Murray & Dermott ch. 8).                                                                                                                 |
| P2 : Propagation traverse ≥ 1 niveau hiérarchique             | 1     | Les perturbations planétaires se propagent vers le sous-système satellitaire (ex. perturbations solaires sur les satellites de Jupiter, résonance de Laplace Io–Europe–Ganymède couplée au champ solaire). Inversement, la dissipation de marée dans un satellite modifie l'orbite planétaire sur le long terme.                                         |
| P3 : Propagation modifie l'état global observable             | 0.5   | Le chaos séculaire de Laskar montre que de petites perturbations modifient à terme l'architecture orbitale globale (excentricités de Mercure, inclinaisons), mais seulement sur des échelles de temps > 10⁷ ans. Sur des échelles observables humaines, l'état global paraît fixe. On accorde 0.5 car la modification est réelle mais extrêmement lente. |
| P4 : Isolement difficile sans modification structurelle       | 1     | La gravité est à longue portée et non écrantable. Il est impossible d'isoler gravitationnellement une planète des autres sans la retirer physiquement du système. C'est une propriété fondamentale du couplage 1/r².                                                                                                                                     |
| P5 : Couplage fonctionnel non trivial                         | 1     | Les résonances orbitales (Laplace, résonances séculaires, résonances de Kozai-Lidov) sont des couplages non linéaires où de petites perturbations produisent des effets structurants majeurs — création de lacunes dans les anneaux, capture en résonance, chaos déterministe (Laskar 1994, Murray & Dermott ch. 8-10).                                  |

**Score A2 = 0.90 / 1.00**

**Hésitations / ambiguïtés :**
P3 est le point délicat : le chaos est réel et démontré numériquement par Laskar, mais sa manifestation observable exige des durées géologiques. La question est de savoir si « observable » signifie « en principe » ou « en pratique ». On choisit un compromis à 0.5.

---

## A3 — Intégration

| Sous-critère                             | Score | Justification                                                                                                                                                                                                                                                                                                                                                     |
| ---------------------------------------- | ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| I1 : Mécanisme explicite de coordination | 0.5   | Le champ gravitationnel central du Soleil impose une coordination géométrique globale (orbites quasi-coplanaires, quasi-circulaires). Cependant, ce n'est pas un mécanisme de coordination actif mais un effet de la formation dans un disque proto-planétaire + domination de la masse centrale. On accorde 0.5 : coordination réelle mais passive/structurelle. |
| I2 : Réduction de variance observable    | 1     | Le système montre une variance orbitale très réduite : faibles excentricités, faibles inclinaisons mutuelles, espacement régulier (loi de Titius-Bode approximative). Les résonances contribuent à structurer la distribution des orbites. La coplanarité elle-même est une réduction de variance par rapport à un système isotrope.                              |
| I3 : Synchronisation multi-niveaux       | 1     | Les résonances orbitales synchronisent des objets à différents niveaux : résonance de Laplace (3 satellites de Jupiter), résonances spin-orbite (Mercure 3:2, Lune 1:1), verrouillage de marée (Goldreich 1972). Ces synchronisations couplent orbite, rotation et déformation interne.                                                                           |
| I4 : Boucles de rétroaction globales     | 0.5   | Les interactions séculaires créent des boucles faibles : la précession d'une planète influence les fréquences propres du système, qui à leur tour contraignent les précessions possibles. Mais ces boucles sont très lentes et ne constituent pas un mécanisme de rétroaction au sens fort (pas de correction ciblée). 0.5.                                       |
| I5 : Maintien d'un état global cohérent  | 0.5   | Le système est métastable sur ~ 5 Ga (Laskar 1994), ce qui est remarquable. Cependant, cet état cohérent est le résultat de conditions initiales + lois de conservation (énergie, moment angulaire), pas d'un mécanisme actif de maintien. Le système ne « répare » pas sa cohérence ; il est simplement dans un bassin dynamique stable. 0.5.                    |

**Score A3 = 0.70 / 1.00**

**Hésitations / ambiguïtés :**
La tension centrale : le système solaire est remarquablement ordonné, mais cet ordre provient largement de la formation et de la conservation, pas de mécanismes intégratifs actifs. I1 et I5 reçoivent 0.5 pour cette raison. I3 est fort grâce aux verrouillages de marée et résonances, qui sont de véritables synchronisations maintenues dynamiquement.

---

## A4 — Normativité

| Sous-critère                                 | Score | Justification                                                                                                                                                                                                                                                                                                                                                                                                                                |
| -------------------------------------------- | ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| N1 : Attracteur dynamique existant           | 1     | Les orbites oscillent autour de configurations quasi-keplériennes. Les résonances stables sont des attracteurs au sens dynamique (tores KAM). Le système occupe un bassin d'attraction dans l'espace des phases, identifié par les études numériques de Laskar.                                                                                                                                                                              |
| N2 : Correction active d'écart               | 0.5   | Les résonances de mouvement moyen corrigent les écarts : un satellite en résonance 1:1 (Troyen) subit une force de rappel vers le point de libration. Le verrouillage de marée corrige activement les écarts de synchronisation spin-orbite (Goldreich 1972). Cependant, pour le système planétaire global, il n'y a pas de correction active des écarts orbitaux — la stabilité vient de la quasi-intégrabilité, pas de la correction. 0.5. |
| N3 : Hiérarchie de priorités régulatoires    | 0.5   | Il existe une hiérarchie naturelle des échelles de temps : le mouvement képlérien domine (période orbitale), les perturbations séculaires agissent sur des temps > 10⁴ fois plus longs, le chaos séculaire sur > 10⁶ orbites. Cette séparation d'échelles fonctionne comme une hiérarchie de priorités, mais elle est purement mécanique, sans « choix » ou modulation. 0.5.                                                                 |
| N4 : Mécanisme interne de stabilisation      | 1     | Les tores KAM fournissent une stabilisation structurelle : tant que les perturbations sont suffisamment petites, le mouvement reste quasi-périodique et confiné (théorème KAM, appliqué explicitement dans Murray & Dermott). La dissipation de marée amortit les oscillations de libration.                                                                                                                                                 |
| N5 : Résistance aux perturbations prolongées | 1     | Le système a survécu ~ 4.5 Ga avec une architecture essentiellement inchangée malgré le Late Heavy Bombardment, la perte de masse solaire, les passages stellaires proches. Laskar montre que même le chaos séculaire ne déstabilise le système que sur des horizons > 5 Ga. Résistance remarquable.                                                                                                                                         |

**Score A4 = 0.80 / 1.00**

**Hésitations / ambiguïtés :**
N2 : la correction active est claire pour les résonances locales (libration, marées) mais absente au niveau global. N3 : la hiérarchie d'échelles de temps est réelle mais purement émergente de la mécanique, sans allocation intentionnelle.

**Distinction normativité endogène / imposée :**
Entièrement endogène. La normativité du système solaire découle des lois de la gravitation et des conditions initiales. Aucun agent extérieur n'impose de normes. Les attracteurs, les stabilisations KAM, la dissipation de marée sont des propriétés intrinsèques de la dynamique gravitationnelle. C'est un cas paradigmatique de normativité physique émergente.

---

## A5 — Capacité de révision (formulation V2.1.1 : plasticité endogène)

| Sous-critère                                       | Score | Justification                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------------------------------- | ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| R1 : Ajustement paramétrique local                 | 1     | Les éléments orbitaux (excentricité, inclinaison, longitude du nœud) varient continuellement sous l'effet des perturbations mutuelles. La dissipation de marée ajuste les paramètres orbitaux et rotationnels (recul de la Lune à ~ 3.8 cm/an, Goldreich 1972). Ajustement permanent et mesurable.                                                                                      |
| R2 : Modification durable de configuration interne | 0.5   | La migration planétaire précoce (modèle de Nice) a modifié durablement l'architecture. La capture en résonance (ex. Neptune–Pluton 3:2) est un changement de configuration durable. Cependant, dans le système actuel mature, de telles reconfigurations sont extrêmement rares. 0.5 reflète la capacité historique vs. la rigidité actuelle.                                           |
| R3 : Reconfiguration de réseau ou de structure     | 0.5   | Le Late Heavy Bombardment et la migration planétaire ont reconfiguré la structure du système (déplacement des géantes, dispersion de la ceinture de Kuiper). Mais le système actuel est essentiellement figé structurellement. La prochaine reconfiguration possible (déstabilisation de Mercure, Laskar 1994) est dans > 1 Ga. Capacité théorique présente, exercice actuel quasi-nul. |
| R4 : Modification des mécanismes de régulation     | 0     | Les « mécanismes de régulation » (gravité, lois de Kepler, tores KAM) sont des propriétés de la physique fondamentale. Le système ne peut pas modifier ses propres lois de régulation. La dissipation de marée peut modifier les paramètres mais pas la nature du mécanisme de marée lui-même.                                                                                          |
| R5 : Capacité à produire de nouvelles règles       | 0     | Le système solaire ne produit pas de nouvelles règles dynamiques. Les lois gravitationnelles sont fixes. Même le chaos déterministe de Laskar opère strictement dans le cadre des équations de Newton/Einstein existantes. Aucune nouveauté régulatoire.                                                                                                                                |

**Score A5 = 0.40 / 1.00**

**Hésitations / ambiguïtés :**
R2-R3 : la question est celle de la temporalité. Le système a montré historiquement (formation, migration) une plasticité considérable, mais le système mature actuel est extrêmement rigide. On score l'état actuel en pondérant la capacité résiduelle. R4-R5 : scores nets à 0 — un système purement physique ne modifie pas ses propres lois.

---

## Synthèse

| Axe | Score |
| --- | ----- |
| A1  | 0.80  |
| A2  | 0.90  |
| A3  | 0.70  |
| A4  | 0.80  |
| A5  | 0.40  |

### Gradients (calculés)

| Gradient      | Valeur |
| ------------- | ------ |
| Δ₂₃ = A2 − A3 | +0.20  |
| Δ₄₅ = A4 − A5 | +0.40  |
| Δ₁₂ = A1 − A2 | −0.10  |
| Δ₃₅ = A3 − A5 | +0.30  |
| Δ₄₃ = A4 − A3 | +0.10  |

### Classification (rempli APRÈS scoring)

- **Régime primaire :** Système dissipatif-conservatif à forte inertie structurelle — couplage fort (A2 = 0.90) et normativité élevée (A4 = 0.80) mais plasticité très limitée (A5 = 0.40).
- **Régime secondaire :** Système hiérarchique bien différencié (A1 = 0.80) avec intégration passive-structurelle (A3 = 0.70).
- **Marge :** Le gradient Δ₄₅ = +0.40 est le plus marqué : le système « tient » fortement ses normes mais ne peut pas les réviser. Profil typique d'un système physique mature verrouillé dans un bassin d'attraction.
- **Surprise par rapport au jugement intuitif :** Non. Le système solaire est intuitivement un système très stable, bien couplé, mais rigide. Le scoring confirme ce profil. La relative faiblesse de A3 (0.70 vs. 0.80-0.90 attendu intuitivement) reflète la distinction correcte entre « ordre apparent » et « intégration active ». Le score A5 bas est attendu pour un système purement physique sans capacité d'innovation.

---

## Notes libres

Le système solaire est un cas-test intéressant pour la grille car il force à distinguer rigoureusement entre stabilité passive (conséquence de la conservation de l'énergie et du moment angulaire) et régulation active (correction d'écarts, rétroaction ciblée). Le scoring montre que le système excelle en couplage et normativité physique mais manque fondamentalement de plasticité — il ne peut que « subir » ses propres lois. Le chaos de Laskar est crucial pour ne pas surévaluer la stabilité : le système est métastable, pas absolument stable. La séparation entre la phase de formation (haute plasticité) et la phase mature (quasi-nulle) est un défi pour le scoring ; on choisit de scorer l'état actuel tout en notant la capacité historique.
