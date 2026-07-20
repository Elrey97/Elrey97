# 💪 Mon Gym — Application de suivi d'entraînement

Application web personnelle pour suivre le programme d'entraînement, la nutrition et les courses. **Un seul fichier** (`index.html`), aucune installation, fonctionne hors ligne — toutes les données sont sauvegardées dans le navigateur (localStorage).

## Comment l'utiliser

**Option 1 — Sur le téléphone / ordinateur :** télécharger `index.html` et l'ouvrir dans le navigateur (Chrome, Safari...). Ajouter à l'écran d'accueil pour l'utiliser comme une appli.

**Option 2 — GitHub Pages :** activer GitHub Pages dans les paramètres du dépôt (Settings → Pages → branche `main`), puis ouvrir `https://elrey97.github.io/Elrey97/gym-app/`.

> ⚠️ Les données sont stockées dans le navigateur utilisé. Utiliser toujours le même navigateur pour garder l'historique.

## Fonctionnalités

### 🏋️ Entraînement
- Programme sur 6 jours : **J1 Push · J2 Pull · J3 Legs · J4 Repos · J5 Haut du corps · J6 Legs**, plus **Cardio** et **Abdos**
- Chaque exercice a un objectif (séries × répétitions) et affiche la dernière performance
- Saisir séries / reps / poids et appuyer sur **Terminer ✓** → notification avec le résumé de ce qui a été fait
- Bouton **Terminer la séance** → notification récap (exercices, volume total, minutes de cardio)
- Possibilité d'ajouter ses propres exercices à chaque jour

### 📈 Évolution
- Statistiques : séances terminées, volume total soulevé, séances de la semaine
- Graphique de progression de la charge par exercice (avec vue tableau)
- Suivi du poids corporel
- Historique des 15 dernières performances

### 🍽️ Repas
- Programme alimentaire sur 7 jours, adapté au programme d'entraînement (protéines les jours de muscu, plus léger au repos), avec des plats disponibles localement (tvorog, grechka, kéfir, syrniki...)

### 🛒 Courses
- Liste de courses **mensuelle** basée sur le programme alimentaire
- Prix estimés en **roubles biélorusses (BYN)**, modifiables selon le magasin
- Total estimé + total déjà acheté, cases à cocher, bouton « Nouveau mois »
- Ajout / suppression d'articles

### 👨‍🍳 Recettes
- 6 recettes riches en protéines avec calories, ingrédients et étapes de préparation

## Notifications

À la première utilisation du bouton **Terminer ✓**, le navigateur demande l'autorisation d'envoyer des notifications. Accepter pour recevoir les notifications système ; sinon, un message s'affiche quand même dans l'application.
