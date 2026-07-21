# 📚 Base de données Étudiants

Petite application web pour gérer une liste d'étudiants. **Un seul fichier** (`index.html`), aucune installation, fonctionne **hors ligne** — les données sont sauvegardées dans le navigateur (localStorage).

## Comment l'utiliser

**Option 1 — Local :** télécharger `index.html` et l'ouvrir dans un navigateur (Chrome, Safari, Firefox...).

**Option 2 — GitHub Pages :** activer GitHub Pages (Settings → Pages → branche `main`), puis ouvrir
`https://elrey97.github.io/Elrey97/students-app/`.

> ⚠️ Les données sont stockées dans le navigateur utilisé. Utiliser toujours le même navigateur pour garder les données.

## Fonctionnalités

- ➕ **Ajouter / modifier / supprimer** un étudiant (prénom, nom, classe, âge, email, téléphone, moyenne /20, notes)
- 🔍 **Recherche** en temps réel (nom, email, classe, notes...)
- 🎓 **Filtre par classe** et **tri** par nom, moyenne, classe ou âge
- 📊 **Statistiques** : nombre d'étudiants, moyenne générale, nombre de classes
- 🎨 Avatars colorés avec initiales, badge de moyenne (vert ≥16 · orange ≥10 · rouge <10)
- ⬇️ **Export / import JSON** (sauvegarde) et **export CSV** (Excel)
- ✨ **Données de démo** pour tester rapidement
- 📱 Interface responsive, adaptée au mobile

## Champs d'un étudiant

| Champ | Description |
|-------|-------------|
| Prénom / Nom | Obligatoires |
| Classe | ex : « 3ème A » (auto-complétée) |
| Âge | Nombre |
| Email / Téléphone | Contact |
| Moyenne | Note sur 20 |
| Notes | Remarques libres |
