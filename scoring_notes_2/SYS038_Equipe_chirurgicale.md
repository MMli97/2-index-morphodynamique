# Scoring Notes — SYS038 Équipe chirurgicale

## Identification

- **System ID :** SYS038
- **System name :** Équipe chirurgicale (bloc opératoire)
- **Domain :** social / institutional
- **Subdomain :** organisation de soins, travail d'équipe à haute fiabilité
- **Scale :** micro
- **Date scored :** 2026-04-04
- **Scorer :** CL
- **Confidence globale :** medium

## Sources

1. Edmondson, A. C. (2003). *Speaking Up in the Operating Room: How Team Leaders Promote Learning in Interdisciplinary Action Teams*. Research in Organizational Behavior, 25, 83–137.
2. Lingard, L. et al. (2004). *Communication Failures in the Operating Room: An Observational Classification of Recurrent Types and Effects*. Quality & Safety in Health Care, 13(5), 330–334.
3. Catchpole, K. et al. (2007). *Improving Patient Safety by Identifying Latent Failures in Successful Operations*. Surgery, 142(1), 102–110.

---

## A1 — Profondeur hiérarchique

| Sous-critère | Score | Justification |
|---|---|---|
| H1 : ≥ 2 niveaux causaux distincts | 1 | Au minimum deux niveaux nets : le chirurgien-chef (pilotage stratégique de l'intervention) et les exécutants spécialisés (instrumentiste, aide-opératoire) qui agissent sous ses directives causales directes. |
| H2 : ≥ 3 niveaux causaux distincts | 1 | Troisième niveau : l'anesthésiste gère un sous-système physiologique autonome (ventilation, hémodynamique) dont les décisions contraignent le rythme chirurgical. Lingard et al. documentent ces flux de communication entre trois « silos » fonctionnels distincts (chirurgie, anesthésie, nursing). |
| H3 : ≥ 4 niveaux causaux distincts | 0.5 | On peut distinguer un quatrième niveau — les protocoles institutionnels (checklist OMS, règles du bloc) qui encadrent l'ensemble — mais ce niveau est largement externe à l'équipe elle-même ; il ne constitue un niveau causal interne que dans la mesure où l'équipe se l'approprie activement (Catchpole et al. montrent que l'application réelle varie). |
| H4 : Niveaux fonctionnellement différenciés | 1 | Différenciation fonctionnelle forte : l'anesthésiste ne peut pas remplacer l'instrumentiste, le chirurgien ne gère pas la ventilation. Chaque niveau a des compétences, instruments et responsabilités irréductibles. |
| H5 : Causalité bidirectionnelle entre niveaux | 1 | Edmondson décrit les boucles montantes (infirmière signalant un problème au chirurgien) et descendantes (directives chirurgicales). L'anesthésiste peut interrompre ou ralentir le geste chirurgical ; le chirurgien peut demander un changement de paramètres anesthésiques. La causalité circule dans les deux sens. |

**Score A1 = 0.90 / 1.00**

**Hésitations / ambiguïtés :** Le quatrième niveau (protocoles institutionnels) est à la frontière entre contrainte exogène et niveau intégré au système. Scoré 0.5 par prudence — dans une équipe très mature, ce niveau est pleinement internalisé ; dans une équipe dysfonctionnelle, il reste purement externe.

---

## A2 — Capacité de propagation (formulation V2.1.1 : invariance d'échelle)

| Sous-critère | Score | Justification |
|---|---|---|
| P1 : Perturbation locale affecte ≥ 1 autre module fonctionnel | 1 | Lingard et al. montrent qu'un échec de communication dans un module (ex. mauvais comptage de compresses par le nursing) se propage immédiatement au module chirurgical. Un événement local ne reste presque jamais confiné. |
| P2 : Propagation traverse ≥ 1 niveau hiérarchique | 1 | Une décision anesthésique (ex. hypotension induite) traverse le niveau hiérarchique vers le champ opératoire ; une hémorragie imprévue remonte du geste chirurgical vers l'anesthésiste qui doit adapter la réanimation. |
| P3 : Propagation modifie l'état global observable | 1 | Catchpole et al. documentent que des défaillances latentes même mineures modifient le déroulement global de l'opération (durée, séquençage, issue). L'état global « intervention en cours nominal » bascule vers « gestion de crise ». |
| P4 : Isolement difficile sans modification structurelle | 0.5 | Le couplage est serré pendant l'acte chirurgical, rendant l'isolement difficile. Cependant, certaines phases (induction anesthésique vs. préparation du champ) sont relativement découplables temporellement. L'isolement complet est impossible sans restructurer la procédure, mais un isolement partiel existe naturellement par séquençage temporel. |
| P5 : Couplage fonctionnel non trivial | 1 | Le couplage est hautement non trivial : la relation entre geste chirurgical, paramètres hémodynamiques, et vigilance de l'équipe est non-linéaire. Lingard et al. montrent que 36 % des échecs de communication ont des effets visibles sur le déroulement, souvent de manière imprévisible. |

**Score A2 = 0.90 / 1.00**

**Hésitations / ambiguïtés :** P4 scoré 0.5 car le séquençage temporel naturel de la chirurgie offre des « fenêtres » de découplage partiel (pré-op, induction, geste, fermeture, réveil), même si pendant chaque phase le couplage est très serré.

---

## A3 — Intégration

| Sous-critère | Score | Justification |
|---|---|---|
| I1 : Mécanisme explicite de coordination | 1 | Briefing pré-opératoire, checklist chirurgicale, « time-out » avant incision, communication verbale codifiée (« clamp », « on peut fermer »). Edmondson et Catchpole documentent abondamment ces mécanismes explicites. |
| I2 : Réduction de variance observable | 0.5 | Catchpole et al. montrent que les checklists et protocoles réduisent la variabilité des processus. Cependant, Lingard et al. documentent un taux élevé d'échecs de communication (31 % des échanges observés), indiquant que la réduction de variance est réelle mais incomplète. |
| I3 : Synchronisation multi-niveaux | 1 | La synchronisation entre anesthésiste, chirurgien et nursing est essentielle et active : le chirurgien ne coupe pas avant que l'anesthésiste confirme la profondeur d'anesthésie ; l'instrumentiste anticipe le geste suivant. Cette synchronisation traverse les niveaux hiérarchiques. |
| I4 : Boucles de rétroaction globales | 0.5 | Des boucles existent en temps réel (monitoring, communication verbale), mais Edmondson montre que les boucles de rétroaction « montantes » (du personnel junior vers le chirurgien-chef) sont souvent inhibées par les gradients d'autorité. Les boucles descendantes fonctionnent bien ; les boucles montantes sont fragiles. |
| I5 : Maintien d'un état global cohérent | 1 | Malgré les défaillances, l'équipe maintient un état global cohérent — l'opération progresse vers sa complétion. Les trois sources confirment que même en présence de « latent failures », l'état global est maintenu la grande majorité du temps (Catchpole : opérations réussies malgré des défaillances latentes). |

**Score A3 = 0.80 / 1.00**

**Hésitations / ambiguïtés :** I2 et I4 à 0.5 reflètent la tension centrale documentée par ces sources : l'équipe chirurgicale possède des mécanismes d'intégration puissants mais leur efficacité réelle est compromise par les dynamiques de pouvoir et les échecs de communication.

---

## A4 — Normativité

| Sous-critère | Score | Justification |
|---|---|---|
| N1 : Attracteur dynamique existant | 1 | L'attracteur est clair : mener l'intervention à son terme avec le patient vivant et dans un état amélioré. Toute déviation est perçue comme telle et déclenche des réponses correctives. |
| N2 : Correction active d'écart | 1 | L'équipe corrige activement les écarts : hémorragie → hémostase, hypotension → vasopresseurs, erreur de latéralité → time-out. Catchpole et al. documentent les mécanismes de récupération (« recovery strategies ») face aux défaillances identifiées. |
| N3 : Hiérarchie de priorités régulatoires | 1 | Hiérarchie claire : survie du patient > succès technique de l'intervention > respect du planning > confort de l'équipe. En cas de crise, les priorités inférieures sont sacrifiées sans hésitation. |
| N4 : Mécanisme interne de stabilisation | 0.5 | Les protocoles et la hiérarchie d'autorité stabilisent le système. Cependant, Edmondson montre que cette stabilisation repose fortement sur le leader (chirurgien-chef) : si le leader est défaillant, le mécanisme de stabilisation est fragilisé. Ce n'est pas un mécanisme distribué et robuste mais plutôt centralisé et personnalisé. |
| N5 : Résistance aux perturbations prolongées | 0.5 | L'équipe résiste bien aux perturbations aiguës (hémorragie, panne d'équipement). Mais face à des perturbations prolongées (fatigue lors d'une intervention de 12h, conflit interpersonnel chronique, sous-effectif durable), la résistance se dégrade significativement. Le système est optimisé pour des perturbations intenses mais brèves. |

**Score A4 = 0.80 / 1.00**

**Hésitations / ambiguïtés :** N4 et N5 à 0.5 car la stabilisation est fortement dépendante du leader et la résilience temporelle est limitée.

**Distinction normativité endogène / imposée :** Mixte. La normativité immédiate (garder le patient en vie, corriger les écarts per-opératoires) est largement endogène — elle émerge de la dynamique de l'équipe en situation. La normativité procédurale (checklists, protocoles) est imposée institutionnellement mais internalisée à des degrés variables. Edmondson montre que le degré d'internalisation dépend fortement du style de leadership.

---

## A5 — Capacité de révision (formulation V2.1.1 : plasticité endogène)

| Sous-critère | Score | Justification |
|---|---|---|
| R1 : Ajustement paramétrique local | 1 | Ajustements constants en temps réel : modifier la posologie anesthésique, changer d'instrument, adapter la technique de suture. Ces ajustements sont routiniers et continus. |
| R2 : Modification durable de configuration interne | 0.5 | Une équipe peut modifier ses habitudes de travail après un incident (ex. adopter un nouveau protocole de comptage). Mais Edmondson montre que cette modification dépend fortement du « psychological safety » : dans les équipes où le climat est défavorable, les configurations internes se figent. La capacité existe mais n'est pas systématique. |
| R3 : Reconfiguration de réseau ou de structure | 0.5 | En situation de crise, l'équipe peut se reconfigurer (appel de renfort, changement de rôles, passage en mode « damage control »). Catchpole et al. documentent ces reconfigurations. Cependant, en dehors de la crise, la structure est rigide (rôles fixes, hiérarchie stable). La reconfiguration est réactive, non proactive. |
| R4 : Modification des mécanismes de régulation | 0 | L'équipe chirurgicale en tant que système micro ne modifie pas ses propres mécanismes de régulation. Les changements de protocoles, de checklists, de règles de fonctionnement viennent du niveau institutionnel (hôpital, sociétés savantes, autorités de santé). L'équipe applique ou n'applique pas, mais ne crée pas ses propres mécanismes régulateurs. |
| R5 : Capacité à produire de nouvelles règles | 0 | Même logique : une équipe chirurgicale ne produit pas de nouvelles règles formelles. Elle peut développer des normes informelles (habitudes, routines), mais la production de règles est une fonction institutionnelle, pas une fonction de l'équipe micro. |

**Score A5 = 0.40 / 1.00**

**Hésitations / ambiguïtés :** R4 et R5 à 0 peuvent sembler sévères. On pourrait arguer que certaines équipes très autonomes développent leurs propres micro-normes. Mais au niveau d'analyse « équipe chirurgicale typique » tel que décrit par les sources, la production de règles est clairement une fonction du niveau institutionnel supérieur, pas de l'équipe elle-même.

---

## Synthèse

| Axe | Score |
|-----|-------|
| A1 | 0.90 |
| A2 | 0.90 |
| A3 | 0.80 |
| A4 | 0.80 |
| A5 | 0.40 |

### Gradients (calculés)

| Gradient | Valeur |
|----------|--------|
| Δ₂₃ = A2 − A3 | +0.10 |
| Δ₄₅ = A4 − A5 | +0.40 |
| Δ₁₂ = A1 − A2 | 0.00 |
| Δ₃₅ = A3 − A5 | +0.40 |
| Δ₄₃ = A4 − A3 | 0.00 |

### Classification (rempli APRÈS scoring)

- **Régime primaire :** Système intégré-rigide — forte structure hiérarchique, propagation et intégration élevées, mais faible plasticité endogène.
- **Régime secondaire :** Système normatif-centralisé — la normativité est robuste mais dépend fortement du leader et des protocoles imposés.
- **Marge :** Le Δ₄₅ = +0.40 est le gradient dominant : le système « sait ce qu'il veut » (normativité forte) mais « ne sait pas se transformer » (révision faible). Profil typique d'un système opérationnel optimisé pour l'exécution, pas pour l'adaptation.
- **Surprise par rapport au jugement intuitif :** Non. L'équipe chirurgicale est intuitivement un système hautement coordonné mais rigide, et le scoring confirme ce profil. La seule légère surprise est le score relativement élevé de A1 (0.90) — on pourrait s'attendre à moins de profondeur hiérarchique pour un micro-système, mais la différenciation fonctionnelle forte entre anesthésie, chirurgie et nursing crée une réelle profondeur.

---

## Notes libres

L'équipe chirurgicale est un cas d'école de « système à couplage serré et hiérarchie rigide » au sens de Perrow. Le gradient Δ₄₅ = +0.40 capture bien la tension fondamentale documentée par les trois sources : un système qui fonctionne remarquablement bien en régime nominal grâce à sa normativité forte, mais qui est vulnérable aux situations imprévues précisément parce qu'il manque de plasticité endogène.

Le travail d'Edmondson sur le « psychological safety » éclaire directement le score A5 : la capacité de révision existe en puissance (les individus savent ce qu'il faudrait changer) mais est inhibée par la structure d'autorité. C'est un cas intéressant où le même mécanisme (hiérarchie forte) qui produit les scores élevés en A1, A3 et A4 est aussi celui qui plafonne A5.

Question ouverte : une équipe chirurgicale pratiquant systématiquement le débriefing post-opératoire (comme le recommande Catchpole) verrait-elle son score A5 monter significativement ? Probablement R2 passerait à 1 et R3 à 1, ce qui donnerait A5 ≈ 0.60 — un gain notable mais qui ne changerait pas fondamentalement le profil du système.
