# Foggy Wallpaper — HUB Void Smoke

Fond d'écran animé généré en HTML/Canvas pour le HUB Institute. Il affiche une simulation de fumée brumeuse avec un logo centré flottant, le tout rendu en temps réel via l'API Canvas.

## Aperçu

- Fond sombre (`#010130`) avec particules de fumée animées
- Logo HUB Institute centré avec effet corona lumineux
- Animation fluide en pur JavaScript, sans dépendance externe

## Structure

```
.
├── HUB_VoidSmoke_Wallpaper.html   # Page principale (animation Canvas)
├── server.js                      # Serveur HTTP Node.js minimal
├── package.json                   # Métadonnées du projet
└── Procfile                       # Commande de démarrage (Heroku / Railway)
```

## Lancer en local

Assure-toi d'avoir **Node.js ≥ 18** installé, puis :

```bash
npm start
```

Le serveur démarre sur [http://localhost:3000](http://localhost:3000).

La variable d'environnement `PORT` est respectée si elle est définie.

## Déploiement

Le `Procfile` inclus permet un déploiement direct sur des plateformes compatibles (Heroku, Railway, Render…) :

```
web: node server.js
```
