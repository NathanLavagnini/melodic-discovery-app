# Melodic Discovery

Application statique de découverte musicale avec recherche YouTube et création manuelle de playlists.

## Installation
Publier `index.html` sur un hébergement HTTPS (par exemple GitHub Pages).

## Configuration
- Activer YouTube Data API v3 dans Google Cloud.
- Créer une clé API limitée à YouTube Data API v3 et aux domaines HTTPS autorisés.
- Créer un client OAuth 2.0 de type application Web et autoriser l’origine HTTPS du site dans Google Cloud.
- Saisir la clé API et l’identifiant client OAuth Web dans l’interface.
- Ne jamais publier de secret client, de jeton OAuth ou de fichier `client_secret.json`.

La connexion OAuth et la création de playlists ne fonctionnent pas depuis une page `file://`.
Le Top 50 mensuel n’est pas encore implémenté.
