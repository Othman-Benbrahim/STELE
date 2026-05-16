# Protocoles STÈLE — Les 5 fonctions opératoires

Chaque protocole décrit un pipeline complet : entrée, étapes, sortie. STÈLE n'a que cinq protocoles ; toute opération s'y ramène.

---

## P1 — COMPRESSION

> *Prendre une situation complexe et la réduire à une chaîne de 3 à 7 glyphes.*

### Entrée
- Récit, description, sortie d'un autre skill, intuition floue, événement, état intérieur.

### Pipeline

**P1.1 — Décanter** : extraire de l'entrée les éléments structurels (qui ? que se passe-t-il ? avec quelle dynamique ? vers quoi ?), ignorer les détails narratifs.

**P1.2 — Identifier les substances** : déterminer 1 à 3 substances STÈLE (Strate I) actives. Test : si on devait nommer le « sujet » de la situation en un seul mot abstrait, ce serait quelle substance ?

**P1.3 — Identifier les opérations** : déterminer 1 ou 2 opératives STÈLE (Strate II). Test : quel verbe agit ? Que *fait* la dynamique ?

**P1.4 — Ajouter les modulateurs** : si nécessaire, 0 à 2 modales (Strate III) pour préciser cycle, intensité, lieu, etc.

**P1.5 — Composer** : agencer en respectant la syntaxe. Vérifier la légalité.

**P1.6 — Encadrer ou non** : si l'utilisateur veut une simple description → pas de bornes. S'il veut un énoncé performatif fort → `⟦…⟧`.

### Sortie type
```
ENTRÉE (résumée) : [3-10 mots]
CHAÎNE STÈLE : ⊛⟁⊙∿
TRANSCRIPTION : NOEUD.FRACTURER.SOURCE.MOUVEMENT
LECTURE : un nœud se fracture, libérant une source en mouvement.
STATUT : Descriptif.
```

### Cas d'usage
- Résumer une session Hacking Narratif en signature.
- Compresser un événement de la journée pour journal.
- Transcrire une intuition floue pour en tester la clarté.

---

## P2 — LECTURE

> *Prendre une chaîne STÈLE et l'interpréter en langue naturelle.*

### Entrée
- Une chaîne de glyphes (1 à 12 signes).

### Pipeline

**P2.1 — Vérifier la légalité** : la chaîne respecte-t-elle la syntaxe (voir `syntaxe.md`) ? Si non, signaler avant de lire.

**P2.2 — Identifier les bornes** : la chaîne est-elle encadrée par `⟦…⟧` ? Si oui, lecture performative. Sinon, lecture descriptive par défaut.

**P2.3 — Lire signe par signe** : traduire chaque glyphe par son mot-code, puis sa fonction.

**P2.4 — Composer le sens** : agencer les fonctions en une phrase en langue naturelle qui respecte la dynamique de la chaîne.

**P2.5 — Lecture en strates (optionnel)** : produire trois niveaux de lecture — littérale (mots-codes), structurelle (relations), symbolique (résonance possible).

### Sortie type
```
CHAÎNE : ⟦⊙⟁◯↻⟧
TRANSCRIPTION : OUVERTURE.SOURCE.FRACTURER.FORME.CYCLE.FERMETURE
LECTURE LITTÉRALE : une source est fracturée vers une forme cyclique.
LECTURE STRUCTURELLE : un commencement s'ouvre par rupture vers une manifestation qui se répète.
LECTURE SYMBOLIQUE : un cycle de naissance par fracture — schéma classique du dépassement.
STATUT : Performatif (présence des bornes).
```

### Cas d'usage
- L'utilisateur a archivé une chaîne dans son journal et veut la relire.
- Quelqu'un a partagé une chaîne et l'utilisateur veut comprendre.
- Vérifier qu'une chaîne dit bien ce que l'auteur croyait qu'elle disait.

---

## P3 — GÉNÉRATION

> *Prendre une intention et produire une chaîne (sigil, incantation, mantra).*

### Entrée
- Une intention en langue naturelle : « ouvrir un cycle », « clore un projet », « marquer un seuil », « invoquer une stabilité », etc.

### Pipeline

**P3.1 — Clarifier l'intention** : si l'intention est floue, poser UNE question (« acte de clôture ou acte d'ouverture ? » / « concerne soi ou un tiers ? »).

**P3.2 — Choisir le niveau** : sigil court (L1-L2, 2-4 signes) ou incantation longue (L3, 7-12 signes) ?

**P3.3 — Sélectionner les primitives porteuses** : quelle substance porte l'intention ? Quelle opérative l'incarne ? Quelle modale la colore ?

**P3.4 — Composer plusieurs variantes** : produire 2 ou 3 chaînes possibles, brèves, qui disent l'intention selon des angles différents.

**P3.5 — Choisir la plus juste** : critère = la chaîne la plus économe qui produit l'effet à la lecture-test à voix haute.

### Sortie type
```
INTENTION : ouvrir consciemment un nouveau cycle de travail
VARIANTES :
  V1 : ⟦Ø✶⊙∿↻⟧ (du vide on révèle une source en mouvement cyclique)
  V2 : ⟦⊙⟁∿⟧ (la source est fracturée en mouvement)
  V3 : ⟦◌⊙↻⟧ (du silence émerge une source en cycle)
CHAÎNE RETENUE : V1 — la plus complète, équilibrée entre ouverture et structure.
STATUT : Performatif.
USAGE SUGGÉRÉ : prononcer à voix haute en début de session, ou inscrire visible.
```

### Cas d'usage
- Sceller un engagement personnel.
- Marquer le début ou la fin d'un cycle.
- Produire une signature pour un projet.
- Créer un mantra court pour une période donnée.

---

## P4 — TIRAGE ATOMIQUE

> *Tirer 1 à 5 glyphes pseudo-aléatoirement et lire la configuration.*

### Entrée
- Une question ouverte (« qu'est-ce qui m'habite là ? » / « état du jour ? ») ou rien (tirage à vide).

### Pipeline

**P4.1 — Définir le nombre de signes** :
- 1 signe = lecture-éclair (état pur, contemplatif)
- 3 signes = micro-tirage (configuration courte)
- 5 signes = tirage complet atomique (structure d'une situation)

**P4.2 — Tirer** : sélectionner les glyphes de manière à respecter une distribution équilibrée entre les strates. **Convention** : sur 5 signes, viser environ 2 substances, 1 opérative, 1 modale, 1 méta. Sur 3 signes : 1 substance, 1 opérative, 1 modale.

> Note technique : le « tirage » se fait par génération assistée par Claude — il n'y a pas de vrai aléatoire. Claude module pour produire une configuration **syntaxiquement légale** et **lisible**, ce qui est plus précieux qu'un aléatoire pur qui produirait des chaînes inertes.

**P4.3 — Vérifier la légalité** : la chaîne tirée respecte-t-elle la syntaxe ? Si non, retirer.

**P4.4 — Lire en double voix** :
- Voix d'**énoncé** : ce que la chaîne dit littéralement.
- Voix de **questionnement** : ce que la chaîne demande à celui qui a tiré (« qu'est-ce qui en toi correspond à cette configuration ? »).

### Sortie type
```
TIRAGE : 3 signes
CHAÎNE : ⊛∿⊘
TRANSCRIPTION : NOEUD.MOUVEMENT.NÉGATION
LECTURE-ÉNONCÉ : un nœud se met en mouvement, sous le signe de la négation.
LECTURE-QUESTIONNEMENT : quel nœud refuses-tu de voir bouger ?
STATUT : Spéculatif (le tirage est une proposition de configuration, pas un diagnostic).
```

### Cas d'usage
- Lecture-éclair en début ou fin de journée.
- Consultation rapide entre deux sessions de travail.
- Échauffement avant une session plus longue (Hacking Narratif, Fractales).

---

## P5 — NAVIGATION

> *Donner un état A et un état B, produire un chemin de glyphes intermédiaires.*

### Entrée
- État A (chaîne STÈLE actuelle, 1-5 signes).
- État B (chaîne STÈLE cible, 1-5 signes).

### Pipeline

**P5.1 — Diagnostiquer la distance** : combien de transformations séparent A de B ?
- Distance 1 : une seule opération suffit.
- Distance 2-3 : un chemin intermédiaire nécessaire.
- Distance 4+ : trop loin — découper en deux navigations successives.

**P5.2 — Identifier l'opérative clé** : quelle opérative principale fait basculer A vers B ? (Souvent `⥀` INVERSER ou `⟁` FRACTURER pour les transitions.)

**P5.3 — Construire la chaîne intermédiaire** : produire 1 à 3 états intermédiaires (chaque état est une chaîne courte L1-L2).

**P5.4 — Vérifier la praticabilité** : chaque étape est-elle atteignable depuis la précédente ? Le chemin est-il *vivable* — c'est-à-dire transformable en geste, en réflexion, en parole ?

**P5.5 — Proposer un protocole d'usage** : suggérer à l'utilisateur comment habiter le chemin (pas seulement le lire).

### Sortie type
```
ÉTAT A : ⊛⊜▲ (un nœud scellé intensément — un blocage marqué)
ÉTAT B : Ø⊙ (du vide une source — disponibilité ouverte)
DISTANCE : 3.

CHEMIN :
A : ⊛⊜▲
↓ étape 1 : ⊛⟁ (le nœud est fracturé)
↓ étape 2 : ⊛⟁Ø (le nœud fracturé laisse place à du vide)
B : Ø⊙ (du vide émerge une source)

OPÉRATIVE CLÉ : ⟁ FRACTURER.
PROTOCOLE D'USAGE : sur trois semaines, une étape par phase. La phase 1 consiste à
nommer ce qui est scellé pour qu'il puisse être fissuré ; la phase 2 à habiter
l'ouverture sans la remplir trop vite ; la phase 3 à laisser émerger.
STATUT : Spéculatif (proposition de chemin, pas prescription).
```

### Cas d'usage
- Visualiser une transformation personnelle souhaitée.
- Planifier symboliquement un changement de projet.
- Cartographier les étapes d'un travail intérieur.

---

## Choix du protocole selon l'input utilisateur

| Si l'utilisateur dit… | Protocole |
|---|---|
| « résume / compresse / code en glyphes » | P1 |
| « lis-moi / que dit / interprète » + chaîne fournie | P2 |
| « produis / génère / écris une incantation / sigil » | P3 |
| « tire / consulte / 3 glyphes » | P4 |
| « comment passer de / chemin entre / navigation » | P5 |

---

## Combinaisons de protocoles

Certains usages combinent deux protocoles :

- **P1 + P3** : compresser une situation puis générer une incantation pour la dépasser.
- **P4 + P2** : tirer puis lire de manière approfondie.
- **P1 + P5** : compresser l'état actuel, l'utiliser comme point A de navigation.
- **P3 + P4** : générer une incantation, tirer un signe pour la moduler.

Dans ces cas, suivre les pipelines dans l'ordre et concaténer les sorties.
