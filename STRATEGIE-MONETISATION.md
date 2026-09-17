# Stratégie de monétisation — Chaîne développement personnel / motivation

## 1. Où tu en es et objectif immédiat

Pour activer le **YouTube Partner Program (AdSense)**, il faut atteindre l'UN
des deux seuils suivants sur 12 mois glissants :
- 1 000 abonnés + 4 000 heures de visionnage (contenu long format), OU
- 1 000 abonnés + 10 millions de vues sur les Shorts (90 derniers jours)

**Priorité #1 : atteindre 1 000 abonnés le plus vite possible.** Les Shorts
sont le levier le plus rapide pour ça (algorithme de découverte agressif),
le format long construit la rétention et les heures de visionnage.

C'est pourquoi la cadence choisie (1 long/jour + plusieurs shorts/jour) est
cohérente : les shorts font le volume et la découverte, le long fait la
fidélisation et la watch time.

## 2. Les sources de revenus, dans l'ordre où elles arrivent réellement

| Étape | Source | Prérequis approximatif |
|---|---|---|
| 1 | Dons ponctuels (liens externes type Ko-fi/Buy Me a Coffee en description) | 0 abonné |
| 2 | Affiliation (livres dev perso, apps de productivité, formations) | Quelques centaines de vues/vidéo |
| 3 | AdSense (pub) | 1 000 abonnés + seuils ci-dessus |
| 4 | Super Thanks / Super Chat (si lives) | Monétisation activée |
| 5 | Memberships / contenu exclusif | Communauté engagée (5-10k abonnés) |
| 6 | Sponsors (apps de méditation, journaling, coaching, formations en ligne) | 10-20k abonnés avec bonne rétention |
| 7 | Produit propre (e-book, notion template, mini-formation, coaching) | Le plus rentable à terme, ne dépend d'aucun seuil YouTube |

**Recommandation** : ne pas attendre AdSense pour monétiser. Dès la
première semaine, mettre en place l'affiliation (étape 2) et préparer un
produit propre simple (étape 7 — ex: un PDF "30 jours de discipline"),
qui devient l'aimant à email / la vraie source de revenu stable.

## 3. Positionnement pour maximiser le CPM

Le dev perso a un CPM correct mais très variable selon le sous-thème.
Sous-niches à privilégier pour un meilleur CPM et une audience qui achète :
- Argent / liberté financière + mindset (CPM élevé)
- Productivité pour professionnels / entrepreneurs (audience qui a du pouvoir d'achat)
- Stoïcisme appliqué au travail/à la vie moderne (evergreen, très demandé en FR actuellement)

Éviter de rester uniquement sur de la motivation générique ("citations sur
fond de coucher de soleil") : c'est saturé et le CPM y est plus faible.
Le calendrier fourni mélange motivation générique (pour le volume/reach)
et sous-niches à forte valeur (pour la conversion et le CPM).

## 4. Format long vs shorts — rôle de chacun

- **Format long (8-15 min)** : vidéo-essai avec voix off, structure
  narrative (hook → promesse → développement → histoire concrète →
  synthèse actionable → CTA). Génère la watch time et le référencement
  YouTube (SEO recherche).
- **Shorts (30-60 sec)** : 
  - 2 shorts "extraits" recyclés du meilleur moment du long format du jour
    (grosse punchline, statistique choc, histoire en 40 sec)
  - 1 short "autonome" (citation commentée, mini-conseil actionnable,
    format "3 signes que...")
  
  Cette approche permet de tenir la cadence quotidienne sans tripler la
  charge de travail : le long format nourrit les shorts.

## 5. Check-list de croissance (à suivre chaque semaine)

- [ ] 1 vidéo longue publiée avec titre/description/tags optimisés (voir `templates/seo-checklist.md`)
- [ ] Au moins 5 shorts publiés dans la semaine
- [ ] Miniature testée (contraste fort, visage/émotion si possible, texte court)
- [ ] 1 lien d'affiliation pertinent en description (livre/outil cité dans la vidéo)
- [ ] Réponse aux 10 premiers commentaires de chaque vidéo dans les 24h (boost l'algorithme)
- [ ] Suivi des vidéos qui performent le mieux → dupliquer l'angle la semaine suivante

## 6. Automatiser la génération de contenu quotidienne

Ce dépôt peut être alimenté automatiquement chaque jour (nouveau script
long + shorts + SEO) via une tâche planifiée dans Claude Code, qui commit
le contenu du jour dans `contenu/semaine-XX/`. Dis-le si tu veux que je
mette ça en place — sinon, il suffit de redemander une nouvelle semaine
de contenu quand celle-ci est terminée.
