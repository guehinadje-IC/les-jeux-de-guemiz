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

> 🎯 **Le mardi « Monde » est volontairement varié et culturellement riche** (art, sciences, histoire, grandes figures, cultures du monde) — pensé pour intéresser un public d'ados, surtout les jeunes filles, avec un vrai objectif d'apprentissage. Pas seulement de l'actu « chaude » : aussi des repères de culture générale qui resservent toute l'année.

| Sem. | Dates | Thème | Lundi (Guadeloupe) | Mardi (Monde · culture G) | Mercredi (Débat) |
|------|-------|-------|--------------------|----------------|-------------------|
| **S1** ✅ | 24-28 juin | L'été où le monde bouge | Chlordécone : le non-lieu | **Sagrada Família & Gaudí** (art/archi) | IA à l'école : pour/contre ? |
| **S2** ✅ | 29 juin-4 juil | Mer, sciences et grandes questions | Sargasses : fléau ou ressource | **Les pionnières de l'espace** (sciences) | Réseaux sociaux avant 15 ans ? |
| **S3** | 6-11 juil | Femmes qui ont changé le monde | L'accès à l'eau potable en Guadeloupe | **Marie Curie & les femmes prix Nobel** | Faut-il rationner l'eau l'été ? |
| **S4** | 13-18 juil | Mémoire et identité (14 juillet) | Le créole : langue à protéger ? | **La Révolution française & la Déclaration des droits** | Faut-il enseigner les langues régionales ? |
| **S5** | 20-25 juil | Arts et chefs-d'œuvre | Le gwoka, trésor guadeloupéen | **Frida Kahlo & les grandes artistes** | L'art doit-il être « utile » ? |
| **S6** | 27 juil-1 août | Corps et cerveau | Produire local aux Antilles | **Comment fonctionne le cerveau ado** (neurosciences) | Taxer les sodas : bonne idée ? |
| **S7** | 3-8 août | Océans et planète | Cyclones : se préparer en Guadeloupe | **Les océans, poumons de la Terre** (biodiversité) | Voyager en avion : faut-il culpabiliser ? |
| **S8** | 10-15 août | Cultures du monde | Patrimoine antillais & UNESCO | **Langues et écritures du monde** | Faut-il rendre les œuvres d'art volées ? |
| **S9** | 17-22 août | Inventions et numérique | Vie chère aux Antilles | **De l'imprimerie à Internet : les inventions clés** | L'argent de poche : à quel âge, combien ? |
| **S10** | 24-29 août | Droits et avenir | Le tourisme durable en Guadeloupe | **Malala & le droit des filles à l'école** | Les notes à l'école : utiles ou stressantes ? |

*(Les jeudi/vendredi/samedi de chaque semaine reprennent le contenu des trois premiers jours. Idées de figures inspirantes pour les ados : Valentina Terechkova, Katherine Johnson, Marie Curie, Frida Kahlo, Malala, Simone Veil, Ada Lovelace, Wangari Maathai…)*

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
