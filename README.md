# CinéMRK 🎬

Catalogue de films et séries (~350 titres) avec affiches officielles via l'API TMDB.
Créé par **MOUHAMED RASSOUL KANE**.

## Mettre en ligne sur GitHub Pages
1. Crée un dépôt GitHub (ex. `cinemrk`) et envoie `index.html` et `README.md`.
2. **Settings → Pages → Branch : `main` / `(root)` → Save.**
3. Ton site sera sur `https://TON-PSEUDO.github.io/cinemrk/`.

## Activer les affiches
1. Crée un compte gratuit sur [themoviedb.org](https://www.themoviedb.org), puis **Settings → API** et demande une clé (usage personnel).
2. Ouvre `index.html`, repère la ligne `const TMDB_KEY="";` tout en haut du script et colle ta clé entre les guillemets.
3. Enregistre (commit) : les affiches se chargent à l'affichage et restent en cache dans le navigateur.

> La clé sera visible dans le code public (normal pour TMDB, la clé gratuite est en lecture seule).
> Sans clé, le site fonctionne avec des affiches colorées.

## Fonctions
Recherche, filtres (type, genre, époque, note), tri, « Ma liste », « Vus », notes perso, fiches détaillées,
paramètres (thème, couleurs, taille), export/import, code d'accès pour télécharger les fiches et le catalogue (CSV).

*Ce produit utilise l'API TMDB mais n'est ni approuvé ni certifié par TMDB.*
