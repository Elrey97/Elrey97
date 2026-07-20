# 💪 Mon Gym — Application de suivi d'entraînement

Application web personnelle pour suivre le programme d'entraînement, la nutrition et les courses. **Un seul fichier** (`index.html`), aucune installation, fonctionne hors ligne — toutes les données sont sauvegardées dans le navigateur (localStorage).

## Comment l'utiliser

**Option 1 — Sur le téléphone / ordinateur :** télécharger `index.html` et l'ouvrir dans le navigateur (Chrome, Safari...). Ajouter à l'écran d'accueil pour l'utiliser comme une appli.

**Option 2 — GitHub Pages (recommandé) :** activer GitHub Pages dans les paramètres du dépôt (Settings → Pages → branche `main`), puis ouvrir `https://elrey97.github.io/Elrey97/gym-app/`.

**Installer comme une vraie application (PWA) :** en ouvrant l'adresse GitHub Pages sur le téléphone :
- **Android (Chrome)** : menu ⋮ → « Installer l'application » (ou « Ajouter à l'écran d'accueil »)
- **iPhone (Safari)** : bouton Partager → « Sur l'écran d'accueil »

L'application s'ouvre alors en plein écran avec sa propre icône 💪, et fonctionne **hors ligne** grâce au service worker.

> ⚠️ Les données sont stockées dans le navigateur utilisé. Utiliser toujours le même navigateur pour garder l'historique.

## Fonctionnalités

### 🏋️ Entraînement
- Programme sur 6 jours organisé par groupes musculaires :
  - **J1 Push** : 2 exercices pectoraux · 2 épaules · 2 triceps + abdos
  - **J2 Pull** : dos · trapèzes · biceps + cardio
  - **J3 Legs** : jambes + abdos
  - **J4 Repos actif** : marche, étirements
  - **J5 Haut du corps** : 2 pectoraux · 2 dos · 2 épaules · 1 triceps · 1 biceps + abdos
  - **J6 Legs** : chaîne postérieure + cardio
  - Onglets **Cardio +** et **Abdos +** pour en faire davantage
- Chaque exercice a un objectif (séries × répétitions) et affiche la dernière performance
- Saisir séries / reps / poids et appuyer sur **Terminer ✓** → notification avec le résumé de ce qui a été fait
- Bouton **Terminer la séance** → notification récap (exercices, volume total, minutes de cardio)
- Possibilité d'ajouter ses propres exercices à chaque jour

### ⏰ Rappel & ⏱ chrono
- **Rappel d'entraînement** : choisir une heure → notification quotidienne avec la séance du jour (l'application doit être ouverte ou en arrière-plan)
- **Chrono de repos** : bouton flottant ⏱ avec durées 1:00 / 1:30 / 2:00 / 3:00, démarrage automatique après chaque exercice terminé (désactivable), bip + vibration + notification à la fin

### 💪 Entraînement avancé
- Enregistrement **série par série** (bouton « + Série »), le chrono de repos démarre après chaque série
- **Records personnels** : notification 🏆 quand une charge dépasse l'ancien record
- **1RM estimé** (charge maximale théorique, formule d'Epley) par exercice
- **Suggestion de progression** : quand l'objectif de répétitions est atteint, l'appli propose +2,5 kg

### 📈 Évolution
- Statistiques : séances terminées, volume total soulevé, séances de la semaine
- **Calendrier du mois** avec jours d'entraînement colorés et série de jours consécutifs 🔥 (un jour de repos ne casse pas la série)
- **Volume par groupe musculaire** sur 30 jours (barres comparatives)
- **Comparaison semaine par semaine** (séances et volume)
- Graphique de progression de la charge par exercice (avec vue tableau)
- Suivi du poids corporel avec **objectif de poids**
- **Mensurations** (bras, poitrine, taille, cuisse) avec évolution
- **Export / import des données** (fichier de sauvegarde JSON)
- Historique des 15 dernières performances

### 🎯 Nutrition avancée
- **Calculateur de besoins** (Mifflin-St Jeor) : calories et protéines selon sexe, âge, taille, poids, activité et objectif (sèche / maintien / masse)
- **Journal alimentaire du jour** avec barres de progression vers les objectifs
- **Scanner de code-barres** 📷 (caméra + base Open Food Facts) pour ajouter un produit automatiquement — sur la version en ligne (GitHub Pages), Chrome Android ; saisie manuelle du code en secours
- **Compteur d'eau** 💧 (objectif 10 verres / 2,5 L)

### 🍽️ Repas
- Programme alimentaire sur 7 jours, adapté au programme d'entraînement (protéines les jours de muscu, plus léger au repos), avec des plats disponibles localement (tvorog, grechka, kéfir, syrniki...)

### 🛒 Courses
- Liste de courses **mensuelle** basée sur le programme alimentaire
- Prix estimés en **roubles biélorusses (BYN)**, modifiables selon le magasin
- Total estimé + total déjà acheté, cases à cocher, bouton « Nouveau mois »
- Ajout / suppression d'articles

### 👨‍🍳 Recettes
- 16 recettes riches en protéines avec calories, ingrédients et étapes de préparation
- Filtres par objectif : **💪 Prise de masse** (plats caloriques : plov, pâtes crémeuses, bol gainer, porridge...), **🍃 Perte de poids** (plats légers : salades, poisson vapeur, soupes, tvorog...) et **⚖️ Équilibré**

## Notifications

À la première utilisation du bouton **Terminer ✓**, le navigateur demande l'autorisation d'envoyer des notifications. Accepter pour recevoir les notifications système ; sinon, un message s'affiche quand même dans l'application.
