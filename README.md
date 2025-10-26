# Démarrage de site statique simple

Ce modèle permet de démarrer un site statique qui peut être lancé en local avec la commande `vite`.

Quand il est stocké dans un dépôt Github ou Gitlab, un site statique est publié.

Le contenu présent dans le dossier `public` sera déployé automatiquement en ligne à chaque fois que du code est poussé avec `git push`.

## Lancer le serveur en local avec vite

Dans une ligne de commande:
```shell
npx vite
# Ou si vous avez installé vite globalement
vite
```

Ouvrir dans le navigateur : http://localhost:5173

## Déploiement sur Github pages

Le dépôt doit avoir la visibilité `public`

Dans les `paramètres` du dépôt, rubrique `Pages`, positionner la source de déploiement à `Github Actions`.


## Installation des prérequis

### Installer nodejs

- Installer nodejs : https://nodejs.org/fr/download

### (Optionnel) installer vite globalement

Installer la commande `vite`

Dans une ligne de commande:
```shell
npm install -g vite
```

