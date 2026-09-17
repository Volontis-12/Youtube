# YouTube — Développement personnel / Motivation

Ce dépôt est le système de production de contenu pour la chaîne : stratégie de
monétisation, calendrier éditorial, templates réutilisables, et scripts
quotidiens (format long + shorts) prêts à tourner/monter.

Je (Claude) ne peux pas filmer, monter ou publier de vidéos à ta place —
ce dépôt fournit tout le texte (script, hook, SEO, concept de miniature)
pour que la production côté humain (voix off, montage, upload) soit la
plus rapide possible.

## Structure

```
STRATEGIE-MONETISATION.md     Plan de monétisation (AdSense, sponsors, produits, etc.)
calendrier/                   Calendrier éditorial (30 jours, à renouveler)
templates/                    Structures réutilisables (script long, short, SEO)
miniatures/                   Concepts de miniatures par semaine
contenu/
  semaine-01/                 Scripts complets jour par jour (long + 3 shorts/jour + version scènes)
  semaine-02/                 Idem pour la semaine 2
```

Chaque jour contient 3 fichiers :
- `jour-XX-long.md` — script complet avec structure narrative et SEO
- `jour-XX-shorts.md` — les 3 shorts du jour
- `jour-XX-scenes.md` — le script long découpé scène par scène (texte + suggestion
  visuelle par scène), prêt à copier-coller dans un générateur vidéo automatique
  type Pictory ou InVideo AI (voir `templates/script-scenes-template.md`)

**Important sur la durée** : les scripts actuels font ~450-550 mots, soit
environ 3-4 minutes de voix off — pas 10-15 minutes. Pour un vrai format
long, il faudra soit étoffer les scripts (1500-2200 mots), soit accepter ce
format plus court comme référence pour la suite.

## Comment ça avance chaque jour

1. Ouvrir `calendrier/calendrier-30-jours.md` pour voir le sujet du jour.
2. Le script long est dans `contenu/semaine-XX/jour-XX-long.md`.
3. Les 3 shorts du jour sont dans `contenu/semaine-XX/jour-XX-shorts.md`.
4. Le SEO (titre/description/tags) est inclus en bas de chaque script long.
5. Le concept de miniature est dans `miniatures/`.

Pour générer la semaine suivante, redemande-moi (ou mets en place une
automatisation quotidienne — voir la dernière section de
`STRATEGIE-MONETISATION.md`).
