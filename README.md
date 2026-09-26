# DestoriaRP — Wiki

Site statique (une seule page HTML) pour le wiki communautaire de DestoriaRP.

## Déploiement sur Railway

1. Pousser ce dépôt sur GitHub.
2. Sur [railway.app](https://railway.app), cliquer sur **New Project → Deploy from GitHub repo** et choisir ce dépôt.
3. Railway détecte le `package.json` et lance automatiquement `npm start`, qui sert `index.html` via le paquet `serve`.
4. Dans les **Settings** du service, cliquer sur **Generate Domain** pour obtenir une URL publique.

Aucune variable d'environnement n'est nécessaire — Railway fournit automatiquement la variable `PORT`.
