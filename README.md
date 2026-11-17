# Cairn – carnet de trail

Application web (installable sur téléphone) qui analyse une archive Strava : carte de tes sorties sur fond IGN, forme et VO2max estimée, préparation de course et carnet de route.

**Tes données restent sur ton appareil.** L'archive Strava est lue dans ton navigateur et stockée uniquement sur ton téléphone ou ton ordinateur. Rien n'est envoyé sur ce site.

## Utiliser Cairn

1. Demande ton archive Strava : sur strava.com, Paramètres → Mon compte → « Télécharger ou supprimer votre compte » → « Demander une archive ». Tu reçois un lien par e-mail (fichier `export_….zip`).
2. Ouvre l'adresse de Cairn et installe-le :
   - **iPhone (Safari)** : bouton Partager → « Sur l'écran d'accueil ».
   - **Android (Chrome)** : menu ⋮ → « Installer l'application ».
3. Dans Cairn, importe ton fichier `export_….zip` (de préférence en Wi-Fi, l'archive est lourde).

Pour mettre tes données à jour, refais une archive Strava et utilise « ⟳ Données ».

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | L'application |
| `manifest.webmanifest` | Nom, icône et couleurs de l'app installée |
| `sw.js` | Fonctionnement hors ligne et mises à jour automatiques |
| `icons/` | Icônes |
| `.nojekyll` | Indique à GitHub Pages de publier les fichiers tels quels |

## Versions

| Version | Date | Contenu |
|---|---|---|
| v2.2 | 17/11/2026 | Première mise en ligne : version installable (affichage téléphone, hors ligne, mises à jour automatiques) ; FC sur toutes les sorties, VO2max par la FC, charge d'entraînement, calendrier de 621 formats de course |
