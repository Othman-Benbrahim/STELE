# STÈLE — Alphabet Performatif des Primitives

> *Système de Transcription Élémentaire des Langages Émergents*
>
> *« Là où vos autres skills développent, STÈLE condense. »*

Un skill Claude qui fournit un alphabet de **25 primitives** (glyphes Unicode + mots-codes) pour compresser toute situation — intérieure, narrative, géopolitique, fictionnelle, oraculaire — en chaînes courtes (3-12 signes) lisibles, comparables, archivables, transmissibles.

---

## Pourquoi STÈLE ?

Dans l'écosystème *Hacking Narratif / Fractales du Destin / LÉR / Signaux du Futur / Oracle Synchromantique*, tous les skills **développent** : ils prennent une entrée courte et produisent une sortie longue (scénarios, tirages commentés, réécritures, analyses).

**STÈLE est l'unique skill qui condense.** Sortie systématiquement plus courte que l'entrée. Fonction écosystémique structurellement absente, qui rend l'expansion soutenable.

### Six rôles objectifs

1. **Calibrage rapide** — coder un état présent en 3-5 glyphes avant d'ouvrir une session longue.
2. **Archivage économique** — une signature glyphique par session, qui rend les centaines d'entrées du journal *scannables*.
3. **Détection trans-domaine** — coder en alphabet une semaine intérieure, l'actualité du jour, un chapitre en cours, un rêve — et voir si la même configuration revient.
4. **Navigation symbolique** — donner un état A et un état B, recevoir un chemin de transformations intermédiaires.
5. **Ritualisation minimale** — produire des sigils courts énonçables, dessinables, gravables.
6. **Test de clarté ontologique** — si on ne peut pas réduire à 5 signes, on n'a pas saisi la structure profonde.

---

## Carte du dépôt

```
stele/
├── README.md                       ← ce fichier
├── SKILL.md                        ← l'agent (frontmatter + pipeline)
└── references/
    ├── alphabet.md                 ← les 25 primitives détaillées
    ├── syntaxe.md                  ← règles de combinaison
    ├── correspondances.md          ← ponts vers LÉR, IRIS∞, IRISxSMIIA, Fractales
    └── protocoles.md               ← P1 Compression · P2 Lecture · P3 Génération · P4 Tirage · P5 Navigation
```

---

## L'alphabet en un coup d'œil

**Strate I — Élémentaire** (substances) : `⊙` SOURCE · `◯` FORME · `Ø` VIDE · `∿` MOUVEMENT · `⊥` LIMITE · `✦` AXE · `◊` TRACE · `⊛` NOEUD

**Strate II — Opérative** (verbes) : `⟁` FRACTURER · `⊗` LIER · `✶` RÉVÉLER · `⊜` SCELLER · `⌒` PLIER · `⥀` INVERSER · `⟶` TRANSMETTRE

**Strate III — Modale** (modulateurs) : `↻` CYCLE · `⌖` LIEU · `▲` INTENSITÉ · `↺` RÉFLEXIVITÉ · `⊘` NÉGATION · `◐` CONDITIONNEL

**Strate IV — Méta** (bornes) : `⟦` OUVERTURE · `⟧` FERMETURE · `◉` AUTO · `◌` SILENCE

Détail complet dans [`references/alphabet.md`](references/alphabet.md).

---

## Les 5 protocoles

| Protocole | Entrée → Sortie |
|---|---|
| **P1 — Compression** | situation complexe → chaîne courte |
| **P2 — Lecture** | chaîne → interprétation |
| **P3 — Génération** | intention → sigil/incantation |
| **P4 — Tirage atomique** | question (ou rien) → 1-5 glyphes tirés |
| **P5 — Navigation** | état A + état B → chemin intermédiaire |

---

## Exemples canoniques

### Compression (P1)
> *« J'ai un blocage tenace sur mon projet, c'est lourd, j'arrive plus à avancer. »*
>
> Compression STÈLE : `⊛⊜▲`
> Lecture : un nœud scellé intensément.

### Génération (P3)
> Intention : *« sceller la fin d'un cycle professionnel difficile. »*
>
> Génération STÈLE : `⟦↻⊜◯◌⟧`
> Lecture : j'énonce-acte : un cycle est scellé en forme, dans le silence.

### Tirage atomique (P4, 3 signes)
> Question : *« état du jour ? »*
>
> Tirage : `⊙∿↻`
> Lecture : une source en mouvement cyclique.
> Question retournée : quelle origine se met en route, et dans quelle répétition ?

### Navigation (P5)
> A : `⊛⊜▲` (blocage scellé intense)
> B : `Ø⊙` (vide ouvert d'où émerge une source)
>
> Chemin :
> A → `⊛⟁` (le nœud est fracturé) → `⊛⟁Ø` (le fracturé laisse place au vide) → B

---

## Comment l'utiliser

### Premiers prompts à essayer

- *« Compresse cette situation en STÈLE : [description] »*
- *« Tire-moi 3 glyphes STÈLE pour [intention/question] »*
- *« Génère un sigil STÈLE pour [intention] »*
- *« Lis cette chaîne : ⟦⊙⟁◯⟧ »*
- *« Trace-moi un chemin STÈLE de ⊛⊜ vers Ø⊙ »*
- *« Compresse mon dernier tirage Fractales en signature STÈLE »*

### Fichiers utilisateur (optionnels)

- **`journal-stele.md`** — Archive des chaînes produites. Le skill lit les 5 dernières au démarrage pour détecter d'éventuelles récurrences.
- **`lexique-perso.md`** — Vos surcouches personnelles : associations propres à votre vocabulaire intérieur.

Sans ces fichiers, le skill fonctionne en mode session autonome.

---

## Articulation avec l'écosystème

STÈLE est **autonome** mais **articulable**. Le fichier [`references/correspondances.md`](references/correspondances.md) propose des mappings vers :

- **LÉR** (5 instructions performatives + 12 archétypes)
- **IRIS∞** (9 familles d'arcanes + 9 modules Codex)
- **IRISxSMIIA** (opérateurs Hacking Narratif : DSF+, CMN+, etc.)
- **Fractales du Destin** (5 positions du tirage)
- **Signaux du Futur** (compression d'analyses OSINT en signature)
- **Oracle Synchromantique** (squelette atomique sous les strates narratives)

Ces correspondances sont des **propositions**, pas des équivalences. STÈLE reste pleinement utilisable sans elles.

---

## Principes

**Atomicité** — chaque primitive est indivisible.

**Combinatoire** — le sens naît de l'enchaînement.

**Économie** — toujours la chaîne la plus courte qui dit vrai.

**Incomplétude assumée** — 25 signes ne disent pas tout, c'est leur force.

**Performativité disciplinée** — énoncer = faire, à condition que la chaîne soit légale et juste. Pas de magie hors-sol.

---

## Limites assumées

- STÈLE ne diagnostique pas, ne prédit pas, ne se substitue à aucun accompagnement professionnel.
- Une chaîne de glyphes n'a de force que pour qui se l'approprie consciemment.
- Le « tirage atomique » (P4) est une génération assistée par Claude, pas un vrai aléatoire — sa valeur tient à la justesse de la configuration produite, pas à un hasard supposé sacré.
- Les correspondances vers les autres systèmes sont indicatives, à ajuster par l'utilisateur.

---

## Licence

À distribuer librement avec mention de la source : *STÈLE — Alphabet Performatif des Primitives, écosystème Othman-Benbrahim*.

---

*Version 0.1 — Première itération. À enrichir au fil des usages.*
