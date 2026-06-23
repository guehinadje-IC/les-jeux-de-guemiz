# 🌴 Les Jeux de Guémiz — Plan éditorial de l'été 2026

Jeu familial interactif autour de l'actualité (Guadeloupe + monde), des débats d'idées et de la culture générale. Public : **ados + adultes (11-99 ans)**. Du **lundi au samedi**, avec un **bonus spécial le samedi**.

---

## 🎯 Le rituel de la semaine (la même structure chaque semaine)

| Jour | Rendez-vous | Format | But pédagogique |
|------|-------------|--------|-----------------|
| **Lundi** | 🏝️ **L'Actu Locale** | Présentation journalistique (Guadeloupe) + mini-quiz | S'ancrer dans son territoire |
| **Mardi** | 🌍 **Le Monde en Bref** | Présentation journalistique (international) + mini-quiz | Ouverture au monde |
| **Mercredi** | 💬 **Le Grand Débat** | Débat d'idées : arguments POUR / CONTRE + relances famille | Esprit critique, argumentation |
| **Jeudi** | 🧠 **Quiz Actu** | Quiz qui révise lundi + mardi + mercredi | Mémorisation active |
| **Vendredi** | 📚 **Culture G** | Quiz culture générale ado (géo, sciences, histoire, arts) | Repères durables, utiles à l'école |
| **Samedi** | 🏆 **Défi Famille (BONUS)** | Récap de toute la semaine (**points ×2**) + Défi Express (débat, énigme, jeu) | Consolidation + plaisir partagé |

**Système de points** : 10 pts / bonne réponse, 15 pts / débat mené, ×2 le samedi. Rangs : Mousse → Matelot → Navigateur → Capitaine → **Amiral des Antilles**. Une « série » 🔥 récompense les sans-faute.

> Le quiz **Culture G du vendredi** et le **récap du samedi** reprennent volontairement les points clés vus dans la semaine : on apprend l'actu *et* on la transforme en culture générale solide.

---

## 🗓️ Calendrier des thèmes (10 semaines : 24 juin → 29 août)

> **✅ Semaines 1 et 2 : déjà entièrement écrites dans le jeu.**
> Semaines 3 à 10 : thèmes proposés ci-dessous, à remplir chaque semaine (≈ 30 min, voir guide plus bas).

| Sem. | Dates | Thème | Lundi (Guadeloupe) | Mardi (Monde) | Mercredi (Débat) |
|------|-------|-------|--------------------|----------------|-------------------|
| **S1** ✅ | 24-28 juin | L'été où le monde bouge | Chlordécone : le non-lieu | Coupe du Monde 2026 | IA à l'école : pour/contre ? |
| **S2** ✅ | 29 juin-4 juil | Mer, sport et grandes questions | Sargasses : fléau ou ressource | Finale du Mondial approche | Réseaux sociaux avant 15 ans ? |
| **S3** | 6-11 juil | Eau et ressources | L'accès à l'eau potable en Guadeloupe | Sécheresses dans le monde | Faut-il rationner l'eau l'été ? |
| **S4** | 13-18 juil | Mémoire et identité (14 juillet) | Le créole : langue à protéger ? | Fête nationale : d'où vient le 14 juillet ? | Faut-il enseigner les langues régionales à l'école ? |
| **S5** | 20-25 juil | Sciences et espace | Volcan de la Soufrière : surveillance | Exploration spatiale 2026 | Coloniser Mars : rêve utile ou gaspillage ? |
| **S6** | 27 juil-1 août | Alimentation et santé | Produire local aux Antilles | Malbouffe et sucre dans le monde | Taxer les sodas : bonne idée ? |
| **S7** | 3-8 août | Climat et nature | Cyclones : se préparer en Guadeloupe | Records de chaleur mondiaux | Voyager en avion : faut-il culpabiliser ? |
| **S8** | 10-15 août | Culture et patrimoine | Le gwoka, trésor guadeloupéen | Patrimoine mondial UNESCO | Faut-il rendre les œuvres d'art volées ? |
| **S9** | 17-22 août | Argent et numérique | Vie chère aux Antilles | Cryptomonnaies et arnaques | L'argent de poche : à quel âge, combien ? |
| **S10** | 24-29 août | Bilan et rentrée | Le tourisme durable en Guadeloupe | Rentrée scolaire dans le monde | Les notes à l'école : utiles ou stressantes ? |

*(Les jeudi/vendredi/samedi de chaque semaine reprennent le contenu des trois premiers jours.)*

---

## 🛠️ Guide de mise à jour hebdomadaire (≈ 30 min / semaine)

Tu peux le faire toi-même, ou me redemander « **Prépare la semaine 3 du jeu Guémiz** » et je le génère.

**Étape 1 — Veille (10 min).** Repère 1 actu Guadeloupe + 1 actu internationale de la semaine (sources fiables : Karibinfo, RCI, France Info La 1ère, Le Monde, Courrier International).

**Étape 2 — Ouvrir le fichier `index.html`** et trouver l'objet `DATA` (en haut du `<script>`).

**Étape 3 — Copier-coller un bloc semaine existant** (par ex. tout le bloc `S2: { ... }`), le renommer `S3`, et remplir les 6 jours. Les types disponibles :

- `presentation` → titre, sous-titre, `article` (liste de `{h:"sous-titre"}` ou `{p:"paragraphe"}`), `saviez`, `source`, `quiz`.
- `debat` → `contexte`, `pour` (4 arguments), `contre` (4 arguments), `prompts` (relances), `points`.
- `quiz` → liste de questions `{q, opts:[...], correct: index, exp:"explication"}`.
- `bonus` → `recapTitre`, `quiz` (récap), `defiTitre`, `defis` (liste).

**Étape 4 — Sauvegarder**, ouvrir le fichier dans un navigateur pour vérifier, puis pousser sur GitHub (glisser-déposer le fichier mis à jour dans le dépôt). Le site se met à jour tout seul en 1-2 min.

**Règle d'or contenu** : 1 idée par paragraphe, vocabulaire accessible à un ado de 11 ans, toujours une explication après chaque réponse de quiz (c'est là qu'on apprend), et au moins un « Le savais-tu ? » surprenant par présentation.

---

## 💡 Idées d'évolution (plus tard)

- Mode « 2 équipes » avec score séparé (parents vs enfants).
- Un **badge imprimable** de fin d'été « Amiral des Antilles ».
- Version audio des présentations (lecture à voix haute en famille).
- Bouton « partager mon score » sur les réseaux.

*Conçu pour Nadjé — Ivory Consulting · apprendre en s'amusant, en famille.*
