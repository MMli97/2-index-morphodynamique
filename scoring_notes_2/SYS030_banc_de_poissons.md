# Scoring Notes — SYS030 Banc de poissons (fish school)

## Identification

- **System ID :** SYS030
- **System name :** Banc de poissons (fish school)
- **Domain :** biological
- **Subdomain :** comportement collectif animal
- **Scale :** meso
- **Date scored :** 2026-04-04
- **Scorer :** CL
- **Confidence globale :** high

## Sources

1. Couzin & Krause, *Self-Organization and Collective Behavior in Vertebrates*, Adv. Stud. Behav. 32 (2003)
2. Katz, Tunstrøm, Ioannou, Huepe & Couzin, *Inferring the Structure and Dynamics of Interactions in Schooling Fish*, PNAS 108 (2011)
3. Gautrais et al., *From Behavioural Analyses to Models of Collective Motion in Fish Schools*, Interface Focus 2 (2012)

---

## A1 — Profondeur hiérarchique

| Sous-critère | Score | Justification |
|---|---|---|
| H1 : ≥ 2 niveaux causaux distincts | 1 | Deux niveaux nets : (1) le poisson individuel avec ses règles locomotrices locales (vitesse, orientation) et (2) le banc comme entité collective dotée de propriétés émergentes (forme, polarisation, direction globale). Couzin & Krause 2003 distinguent explicitement ces deux échelles. |
| H2 : ≥ 3 niveaux causaux distincts | 0.5 | On peut identifier un niveau intermédiaire — le voisinage local (« interaction zone ») au sein duquel chaque poisson calcule ses réponses (zone de répulsion, zone d'alignement, zone d'attraction chez Couzin 2003). Ce voisinage n'est cependant pas un module structurel stable mais un horizon d'interaction glissant. Statut intermédiaire. |
| H3 : ≥ 4 niveaux causaux distincts | 0 | Pas de quatrième niveau identifiable. Il n'y a pas de « méta-banc » ni de sous-systèmes organiques différenciés au sein du banc. |
| H4 : Niveaux fonctionnellement différenciés | 0.5 | Le niveau individuel et le niveau collectif remplissent des fonctions distinctes (locomotion locale vs navigation/protection globale). Toutefois, le banc ne possède pas de sous-structures spécialisées permanentes (pas de leaders fixes, pas d'organes différenciés). L'asymétrie fonctionnelle reste émergente et transitoire. |
| H5 : Causalité bidirectionnelle entre niveaux | 1 | Clairement démontrée : les règles individuelles engendrent la dynamique collective (bottom-up), et la configuration globale du banc contraint en retour le comportement de chaque individu (top-down) — un poisson en position frontale subit un environnement social différent d'un poisson central. Katz et al. 2011 montrent que la structure d'interaction est bidirectionnelle. |

**Score A1 = 0.60 / 1.00**

**Hésitations / ambiguïtés :** Le statut du « voisinage local » comme véritable troisième niveau est discutable. C'est un horizon d'interaction plutôt qu'une entité structurelle discrète. H4 est délicat : la différenciation fonctionnelle existe (positions front/arrière, individus qui initient des tournants) mais elle est transitoire et non assignée de façon fixe.

---

## A2 — Capacité de propagation (formulation V2.1.1 : invariance d'échelle)

| Sous-critère | Score | Justification |
|---|---|---|
| P1 : Perturbation locale affecte ≥ 1 autre module fonctionnel | 1 | Un seul poisson qui change brusquement de direction (fuite d'un prédateur) provoque un ajustement en cascade chez ses voisins puis au-delà. Démontré quantitativement par Katz et al. 2011. |
| P2 : Propagation traverse ≥ 1 niveau hiérarchique | 1 | Une perturbation individuelle modifie la forme et la polarisation du banc entier (passage individu → collectif). La propagation traverse donc le niveau local vers le niveau global. |
| P3 : Propagation modifie l'état global observable | 1 | Les transitions collectives (swarm ↔ polarisé ↔ tore) peuvent être déclenchées par des perturbations locales. Couzin 2003 montre que de légers changements paramétriques individuels induisent des transitions de phase globales. |
| P4 : Isolement difficile sans modification structurelle | 0.5 | Le couplage est fort mais purement spatial : un poisson éloigné du banc (hors portée sensorielle) cesse d'être couplé. L'isolement est donc physiquement possible par simple distance, mais au sein du banc dense il est effectivement impossible sans extraire l'individu. Score intermédiaire. |
| P5 : Couplage fonctionnel non trivial | 1 | Le couplage est non-linéaire : l'interaction dépend de la distance, de l'angle relatif, et de la zone d'interaction (répulsion/alignement/attraction). Katz et al. 2011 montrent une dépendance anisotrope complexe du couplage vitesse-direction. |

**Score A2 = 0.90 / 1.00**

**Hésitations / ambiguïtés :** P4 est le point délicat. Le couplage est médié par la proximité physique et sensorielle ; il ne s'agit pas d'un couplage « câblé » indissociable. Mais dans les conditions écologiques normales (banc dense), il est effectivement très difficile d'isoler un sous-ensemble sans fragmenter la structure.

---

## A3 — Intégration

| Sous-critère | Score | Justification |
|---|---|---|
| I1 : Mécanisme explicite de coordination | 1 | Trois mécanismes explicites et bien caractérisés : (1) répulsion à courte portée, (2) alignement à moyenne portée, (3) attraction à longue portée. Gautrais et al. 2012 et Couzin 2003 formalisent ces règles comme mécanismes de coordination. |
| I2 : Réduction de variance observable | 1 | Le banc réduit massivement la variance inter-individuelle d'orientation et de vitesse par rapport à des poissons non-schooling. La polarisation du banc (ordre paramétrique proche de 1) en est la mesure directe. |
| I3 : Synchronisation multi-niveaux | 0.5 | Il y a synchronisation entre le niveau individuel et le niveau collectif (chaque poisson ajuste sa direction à la direction moyenne locale et globale). Mais avec seulement ~2 niveaux nets, la « multi-niveaux » reste limitée. Pas de synchronisation entre sous-systèmes spécialisés. |
| I4 : Boucles de rétroaction globales | 0.5 | Les boucles de rétroaction existent mais sont émergentes et locales dans leur mécanisme (chaque poisson ne « voit » que son voisinage). L'effet global est une conséquence statistique de la sommation des interactions locales, non un signal de rétroaction global dédié. Pas de mécanisme de feedback centralisé. |
| I5 : Maintien d'un état global cohérent | 1 | Le banc maintient une cohésion spatiale et une polarisation persistantes sur de longues durées, malgré le renouvellement constant des positions relatives. La cohérence globale (forme, densité, direction) est robuste. |

**Score A3 = 0.80 / 1.00**

**Hésitations / ambiguïtés :** I4 est le point central : le banc n'a pas de « signal global » mais l'intégration locale itérée produit un effet fonctionnellement équivalent à une rétroaction globale. La question est de savoir si l'on évalue le mécanisme (local → 0.5) ou le résultat fonctionnel (global → 1). Score conservateur retenu.

---

## A4 — Normativité

| Sous-critère | Score | Justification |
|---|---|---|
| N1 : Attracteur dynamique existant | 1 | Le banc présente des attracteurs nets : état polarisé (déplacement parallèle), état toroïdal (milling), état de swarm. Couzin 2003 les modélise comme des bassins d'attraction dans l'espace des paramètres. |
| N2 : Correction active d'écart | 1 | Chaque poisson corrige activement son écart par rapport à ses voisins (en direction, distance, vitesse). Un individu qui dévie est « rappelé » par les forces d'attraction et d'alignement. C'est le cœur même du modèle de Couzin. |
| N3 : Hiérarchie de priorités régulatoires | 1 | Hiérarchie explicite : la répulsion (anti-collision) prime sur l'alignement, qui prime sur l'attraction. Cette hiérarchie est fonctionnelle et démontrée dans les trois sources. |
| N4 : Mécanisme interne de stabilisation | 0.5 | La stabilisation est distribuée et robuste, mais il n'y a pas de mécanisme « interne » au sens d'un organe régulateur centralisé. La stabilisation émerge de la redondance massive des interactions locales. Efficace mais pas architecturalement dédié. |
| N5 : Résistance aux perturbations prolongées | 0.5 | Le banc résiste bien aux perturbations brèves (prédateur ponctuel) et se reforme rapidement. Face à une perturbation prolongée (prédateur persistant, courant fort), le banc peut se fragmenter ou changer d'état (transition de phase). La résistance est réelle mais limitée dans sa durée et son intensité. |

**Score A4 = 0.80 / 1.00**

**Hésitations / ambiguïtés :** N4 et N5 posent la question de la robustesse d'un système sans contrôleur central. La stabilisation est efficace par redondance mais fragile face aux perturbations extrêmes ou prolongées — le banc ne « persiste » pas comme un organisme mais se reforme.

**Distinction normativité endogène / imposée :** Principalement endogène. Les règles d'interaction sont inscrites dans le comportement individuel de chaque poisson (prédispositions sensorimotrices innées). La normativité n'est pas imposée par un agent extérieur. Toutefois, la pression de prédation constitue une contrainte sélective externe qui façonne indirectement les paramètres des règles.

---

## A5 — Capacité de révision (formulation V2.1.1 : plasticité endogène)

| Sous-critère | Score | Justification |
|---|---|---|
| R1 : Ajustement paramétrique local | 1 | Les poissons ajustent en temps réel leurs paramètres locaux (distance inter-individuelle, vitesse, réactivité) en fonction du contexte (densité locale, présence de prédateur). Katz et al. 2011 montrent une modulation contextuelle des forces d'interaction. |
| R2 : Modification durable de configuration interne | 0.5 | Les transitions entre états collectifs (polarisé → tore → swarm) constituent des reconfigurations durables tant que le contexte le justifie. Mais elles sont réversibles et ne laissent pas de « trace » structurelle permanente dans le banc. Le banc n'apprend pas au sens strict. |
| R3 : Reconfiguration de réseau ou de structure | 0.5 | La topologie du réseau d'interactions change (qui est voisin de qui) lors de mouvements, fusions, fissions du banc. Mais ces reconfigurations sont passives (résultant du mouvement) plutôt qu'activement dirigées vers un objectif. |
| R4 : Modification des mécanismes de régulation | 0 | Les règles de base (répulsion / alignement / attraction) ne changent pas. Les poissons ne « réécrivent » pas leurs mécanismes d'interaction au cours de la vie du banc. Les paramètres varient, mais les règles restent fixes. |
| R5 : Capacité à produire de nouvelles règles | 0 | Le banc ne génère pas de nouvelles règles comportementales. Il n'y a pas d'innovation régulatoire endogène. L'évolution des règles se fait sur des échelles phylogénétiques, pas ontogénétiques. |

**Score A5 = 0.40 / 1.00**

**Hésitations / ambiguïtés :** R2 et R3 sont les zones grises. Les transitions de phase collectives sont spectaculaires mais ne constituent pas une « modification durable » au sens fort : dès que le stimulus cesse, le banc revient à son régime antérieur. La plasticité du banc est essentiellement paramétrique et contextuelle, non structurelle.

---

## Synthèse

| Axe | Score |
|-----|-------|
| A1 | 0.60 |
| A2 | 0.90 |
| A3 | 0.80 |
| A4 | 0.80 |
| A5 | 0.40 |

### Gradients (calculés)

| Gradient | Valeur |
|----------|--------|
| Δ₂₃ = A2 − A3 | +0.10 |
| Δ₄₅ = A4 − A5 | +0.40 |
| Δ₁₂ = A1 − A2 | −0.30 |
| Δ₃₅ = A3 − A5 | +0.40 |
| Δ₄₃ = A4 − A3 | 0.00 |

### Classification (rempli APRÈS scoring)

- **Régime primaire :** Collectif auto-organisé rigide — forte propagation et normativité, faible plasticité
- **Régime secondaire :** Système réactif intégré — bonne intégration et coordination sans capacité d'apprentissage
- **Marge :** Δ₄₅ = +0.40 significatif : le banc maintient bien ses normes mais ne sait pas les réviser. Δ₁₂ = −0.30 : la propagation excède largement la profondeur hiérarchique, typique d'un système « plat mais très couplé ».
- **Surprise par rapport au jugement intuitif :** Pas de surprise majeure. Le profil confirme l'intuition d'un système collectif efficace mais cognitivement simple. Le score A4 élevé (0.80) rappelle cependant que la normativité d'un banc est remarquablement robuste pour un système sans contrôle central. Le contraste A2/A1 souligne que le banc est un système « d'amplification horizontale » plutôt que de profondeur organisationnelle.

---

## Notes libres

Le banc de poissons est un archétype du système auto-organisé biologique : couplage fort, intégration émergente, normativité distribuée, mais plasticité presque nulle au niveau collectif. Le profil (A1 modéré, A2 très élevé, A3-A4 élevés, A5 faible) dessine un système qui excelle à propager et à stabiliser mais qui ne sait pas se transformer. C'est un amplificateur et un régulateur, pas un apprenant.

La comparaison avec d'autres systèmes collectifs (colonies de fourmis, essaims d'étourneaux) serait éclairante : les fourmis ont probablement un A5 plus élevé grâce à la plasticité des pistes phéromonales, tandis que les étourneaux présentent une structure très similaire au banc de poissons.

Question ouverte : un banc soumis à une pression de prédation chronique modifie-t-il ses paramètres d'interaction sur des échelles de quelques générations ? Si oui, cela relèverait d'un A5 phylogénétique non capturé par le cadre actuel (qui se concentre sur l'ontogenèse du système).
