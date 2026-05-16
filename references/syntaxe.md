# Syntaxe STÈLE — Règles de combinaison

L'alphabet n'a de pouvoir que combinatoire. Ce fichier fixe **comment** les 25 primitives s'enchaînent pour former des énoncés lisibles, économes et justes.

---

## 1. Niveaux d'énoncé

| Niveau | Longueur | Nom | Statut typique |
|---|---|---|---|
| L0 | 1 signe | **Atome** | Descriptif (état pur) |
| L1 | 2-3 signes | **Diade / Triade** | Descriptif ou faiblement performatif |
| L2 | 4-6 signes | **Phrase** | Descriptif ou performatif |
| L3 | 7-12 signes | **Incantation** | Performatif fort (rituel) |
| L4 | > 12 signes | **Hors-registre** | Trop verbeux : découper en plusieurs énoncés liés |

> **Règle d'or** : toujours préférer la chaîne la plus courte qui dit vrai. STÈLE est un alphabet d'économie.

---

## 2. Lecture par défaut

- **Sens de lecture** : de **gauche à droite**.
- **Tempo** : un signe = une unité de sens, lue lentement comme une syllabe rituelle.
- **Pause** : un espace entre deux signes marque une micro-pause de lecture (non syntaxique).

---

## 3. Composition légale

Une chaîne est **légale** si elle respecte les quatre règles suivantes.

### Règle 1 — Sujet obligatoire pour toute opérative

Une opérative (strate II) **doit** avoir un sujet — c'est-à-dire une substance (strate I) ou un sous-énoncé scellé — qui la précède ou la suit immédiatement.

- ✅ `⊙⟁` (la source est fracturée) — légal : SOURCE est sujet de FRACTURER.
- ✅ `⟁◯` (fracturer aboutit à une forme) — légal : FORME est complément de FRACTURER.
- ❌ `⟁⊜` (fracturer sceller, sans sujet) — illégal : deux opératives sans substance.

### Règle 2 — Modale postposée

Une modale (strate III) **modifie le signe qui la précède immédiatement**, jamais celui qui suit.

- ✅ `∿↻` (mouvement en cycle) — légal : CYCLE modifie MOUVEMENT.
- ❌ `↻∿` (cycle puis mouvement) — illégal : la modale ne peut être en tête.

### Règle 3 — Bornes appariées

Les bornes méta `⟦` et `⟧` doivent être **appariées** (jamais l'une sans l'autre) et toujours en positions extrêmes.

- ✅ `⟦⊙⟁◯⟧` — légal.
- ❌ `⟦⊙⟁◯` — illégal (fermeture manquante).
- ❌ `⊙⟦⟁⟧◯` — illégal (bornes au milieu).

### Règle 4 — Pas d'enchaînement de plus de 3 substances sans opérative

Une chaîne longue qui n'aligne que des substances sans verbe devient inerte. À partir de la 4ᵉ substance consécutive, il faut une opérative.

- ✅ `⊙∿◯⊛⟁` (source, mouvement, forme, nœud, fracturer) — légal : opérative en position 5.
- ❌ `⊙∿◯⊛◊⊥` (six substances sans verbe) — illégal : à reformuler.

---

## 4. Schémas canoniques

Quelques structures-types qui couvrent 80 % des usages.

### Schéma SUJET–VERBE (L1)
```
[substance] [opérative]
Ex : ⊛⟁ — le nœud est fracturé.
```

### Schéma SUJET–VERBE–OBJET (L2)
```
[substance] [opérative] [substance]
Ex : ⊙⟶◊ — la source transmet vers la trace.
```

### Schéma TRANSFORMATION (L2)
```
[substance A] [opérative] [substance B]
Lecture : « A devient B par l'action de l'opérative ».
Ex : Ø✶◯ — du vide on révèle une forme.
```

### Schéma PERFORMATIF FORT (L2-L3)
```
⟦ [chaîne interne] ⟧
Ex : ⟦⊙⟁◯⟧ — j'énonce-acte : la source est fracturée vers la forme.
```

### Schéma INCANTATION (L3)
```
⟦ [substance] [opérative] [substance modulée] [opérative] [substance] ⟧
Ex : ⟦⊙⟁◯↻⊜⟧ — j'énonce-acte : source fracturée en forme cyclique, scellée.
```

### Schéma RÉSONANCE (L2-L3, sans bornes)
```
[substance] [substance] [opérative auto-réflexive]
Ex : ⊙⊙✶↺ — deux sources se révèlent l'une à l'autre.
```

---

## 5. Lectures spéciales

### Lecture verticale (superposition)

Quand l'utilisateur veut signifier que **plusieurs plans coexistent simultanément**, on note les signes verticalement empilés (ou en notation `signe ⊕ signe` à l'horizontale, où `⊕` ici sert de marqueur de superposition typographique, *pas* de la primitive LIER — distinguer par le contexte ou utiliser `/` comme séparateur).

```
⊙
∿     = au même moment : source ET mouvement ET nœud (trois plans simultanés)
⊛
```

### Lecture circulaire (cycle clos)

Pour un énoncé qui se referme sur lui-même, encadrer la chaîne par `↻ ... ↻` :

```
↻ ⊙∿◯⥀⊙ ↻
Lecture : source devient forme, s'inverse, redevient source — en boucle.
```

### Lecture en miroir (réflexivité forte)

Une chaîne palindromique signale une auto-réflexion :

```
⊙∿⊛∿⊙
Lecture : la source vient à elle-même par le détour du nœud.
```

---

## 6. Modulateurs combinés

Plusieurs modales peuvent affecter le même signe en s'enchaînant :

- `∿↻▲` = mouvement cyclique intense (devenir répété et amplifié).
- `⊙◐↺` = source possible et auto-référée (potentialité d'origine qui se vise elle-même).

L'ordre des modales **ne change pas** le sens (elles sont commutatives), mais une convention de lisibilité recommande : **temps → lieu → intensité → réflexivité → négation → conditionnel**.

---

## 7. Anti-patterns à éviter

| Anti-pattern | Pourquoi c'est mauvais | Correction |
|---|---|---|
| Chaîne > 12 signes | Hors-registre, retour à la prose | Découper |
| Empilement de modales sans substance | Inerte | Ajouter une substance |
| `⟦…⟧` autour d'un seul signe | Solennité disproportionnée | Retirer les bornes |
| Mélange de glyphes hors-alphabet | Casse la convention | S'en tenir aux 25 |
| Chaîne sans aucune opérative | Description seule, pas performatif | Ajouter un verbe ou assumer le statut Descriptif |

---

## 8. Test de justesse pragmatique

Avant de livrer une chaîne, se poser ces trois questions :

1. **Si je lis cette chaîne à voix haute, que produit-elle en moi ?** (Test corporel.)
2. **Quelqu'un d'autre lirait-il la même chose ?** (Test de stabilité conventionnelle.)
3. **Cette chaîne *fait-elle* ce que je prétends ?** (Test de performativité.)

Si l'un des trois tests échoue, reformuler.
