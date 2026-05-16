---
name: stele
description: >
  STÈLE — Système de Transcription Élémentaire des Langages Émergents. Alphabet
  performatif de 25 primitives (glyphes + mots-codes) qui compresse toute situation
  — intérieure, narrative, géopolitique, fictionnelle, oraculaire — en chaînes
  courtes (3-12 signes) lisibles, comparables, archivables, transmissibles. À
  déclencher quand l'utilisateur veut : réduire une situation complexe à son
  ossature atomique, comparer deux états hétérogènes, archiver une session sous
  forme de signature dense, détecter une résonance trans-domaine, produire une
  incantation rituelle courte, naviguer symboliquement d'un état A vers un état B,
  tester la clarté ontologique d'une intuition floue, ou tirer 1-5 glyphes pour
  une lecture-éclair. À déclencher aussi sur les mots-clés : alphabet, glyphe,
  primitive, atome symbolique, transcription, compression, signature, sigil,
  mantra, incantation, tirage atomique, navigation symbolique, STÈLE.
---

# STÈLE — Alphabet Performatif des Primitives

> *« Là où vos autres skills développent, STÈLE condense. »*

STÈLE est l'unique skill de l'écosystème dont la sortie est plus courte que l'entrée. Il opère par **compression symbolique** : toute situation est ramenée à une chaîne de 1 à 12 glyphes primitifs, lisible immédiatement, transportable entre domaines, gravable comme signature.

---

## Vue d'ensemble

STÈLE fournit :
- Un **alphabet** de 25 primitives organisées en 4 strates (Élémentaire, Opérative, Modale, Méta), chacune avec un glyphe Unicode, un mot-code, une fonction performative et une pragmatique d'usage.
- Une **syntaxe** de combinaison (énoncés minimaux à incantations longues).
- Cinq **protocoles** opératoires : Compression, Lecture, Génération, Tirage atomique, Navigation.
- Une **table de correspondances** vers LÉR, IRIS∞, IRISxSMIIA et Fractales du Destin, pour s'articuler sans dépendre.

Le skill est **autonome** : il n'appelle aucun autre skill. Les correspondances sont des ponts symboliques, pas des dépendances d'exécution.

---

## ÉTAPE 0 — Initialisation

Avant toute opération :

1. **Charger** `references/alphabet.md` (les 25 primitives + glossaire complet).
2. **Charger** `references/syntaxe.md` (règles de combinaison).
3. **Si l'utilisateur** demande une opération mettant en jeu d'autres skills (LÉR, IRIS∞, etc.) → charger aussi `references/correspondances.md`.
4. **Si fichier externe `journal-stele.md`** présent dans la session → lire les 5 dernières signatures glyphiques pour détecter d'éventuelles récurrences.

---

## ÉTAPE 1 — Détection du protocole

Analyser l'input utilisateur selon ces signaux :

| Signal dans l'input | Protocole probable |
|---|---|
| « code en glyphes », « réduis à », « signature de », « ossature de », « résume en stèle » | **P1 — Compression** |
| L'utilisateur fournit une chaîne de glyphes et demande sens, lecture, interprétation | **P2 — Lecture** |
| « produis une incantation », « formule un sigil », « génère une chaîne pour », « écris un mantra » | **P3 — Génération** |
| « tire-moi », « tirage atomique », « 3 glyphes au hasard », « consulte STÈLE » | **P4 — Tirage atomique** |
| « comment passer de X à Y », « chemin entre », « navigation symbolique », « transformation A → B » | **P5 — Navigation** |
| Aucun protocole clair | Demander UNE seule question de clarification |

Annoncer le protocole détecté en une phrase, puis appliquer le pipeline correspondant de `references/protocoles.md`.

---

## ÉTAPE 2 — Application du protocole

Lire `references/protocoles.md` à la section correspondante. Chaque protocole produit :
- Une **chaîne STÈLE** principale (1-12 glyphes)
- Une **lecture en langue naturelle** (3-7 lignes maximum)
- Un **statut épistémique** explicite (cf. ÉTAPE 4)

---

## ÉTAPE 3 — Vérification de cohérence interne

Avant livraison, appliquer ces tests :

1. **Économie** — La chaîne fait-elle ≤ 12 signes ? Sinon, comprimer davantage ou découper en deux énoncés liés.
2. **Composition légale** — Chaque opérative (strate II) a-t-elle un sujet (strate I) ? Chaque modale (strate III) modifie-t-elle bien le signe qui la précède ? Cf. `references/syntaxe.md`.
3. **Justesse pragmatique** — La chaîne *fait-elle* ce que prétend l'utilisateur ? Une signature de blocage ne doit pas se lire comme une signature d'ouverture.
4. **Non-doublonnage** — STÈLE ne réplique pas une Phrase FdD, un tirage Fractal ou une instruction LÉR. Si la sortie ressemble à une autre, c'est qu'on est sorti du registre atomique. Reformuler ou rediriger.

> Si la chaîne échoue à l'un de ces tests → reformuler avant livraison, en expliquant brièvement la correction.

---

## ÉTAPE 4 — Statut épistémique

STÈLE n'opère pas dans la causalité. Toute sortie doit porter mention de son statut :

- **Descriptif** — la chaîne *décrit* un état (lecture, transcription).
- **Performatif** — la chaîne *agit* sur le champ symbolique de celui qui l'énonce (incantation, sigil, navigation).
- **Spéculatif** — la chaîne *propose* une configuration possible (génération à partir d'intention floue).

Préciser systématiquement le statut en fin de sortie.

> **Limite absolue** : STÈLE ne diagnostique pas, ne prédit pas, ne se substitue à aucun accompagnement professionnel. Une chaîne de glyphes n'a de force que pour qui se l'approprie consciemment.

---

## ÉTAPE 5 — Génération du Bloc-Stèle (log)

À la fin de chaque interaction, produire ce bloc que l'utilisateur peut coller dans son `journal-stele.md` :

```
=== ENTRÉE STÈLE ===
Date : [DATE]
Protocole : [P1/P2/P3/P4/P5]
Entrée (résumée) : [3-10 mots]
Chaîne STÈLE : [glyphes]
Mots-codes : [transcription verbale]
Statut : [Descriptif/Performatif/Spéculatif]
Notes : [résonances détectées, signaux à surveiller]
====================
```

---

## Format de sortie standard

```
🜲 PROTOCOLE : [P1-P5]

⟦ CHAÎNE STÈLE ⟧
[glyphes en ligne]
[transcription mots-codes]

📖 LECTURE
[3-7 lignes en langue naturelle]

⚖ STATUT
[Descriptif / Performatif / Spéculatif]

📜 BLOC-STÈLE
[bloc formaté]
```

---

## Fichiers de référence

| Fichier | Quand le lire |
|---|---|
| `references/alphabet.md` | **Toujours**, dès l'initialisation |
| `references/syntaxe.md` | **Toujours**, dès l'initialisation |
| `references/protocoles.md` | À chaque opération, section du protocole détecté |
| `references/correspondances.md` | Si l'utilisateur évoque LÉR, IRIS∞, Fractales, Hacking Narratif, ou demande à articuler |

## Fichiers externes (gérés par l'utilisateur)

| Fichier | Rôle |
|---|---|
| `journal-stele.md` | Archive des chaînes produites — alimente la détection de récurrences |
| `lexique-perso.md` | Surcouches personnelles : associations propres à l'utilisateur (optionnel) |

---

## Principes opératoires

**Atomicité** — Chaque primitive est indivisible. On ne sous-décompose pas.

**Combinatoire** — Le sens naît de l'enchaînement, pas d'un signe isolé.

**Économie** — Toujours préférer la chaîne la plus courte qui dit vrai.

**Incomplétude assumée** — 25 signes ne disent pas tout. C'est leur force, pas leur limite.

**Performativité disciplinée** — Énoncer = faire, *à condition que* la chaîne soit légale syntaxiquement et juste pragmatiquement. Pas de magie hors-sol.
