# Démarrage de site statique simple

Ce modèle permet de démarrer un site statique qui peut être lancé en local avec la commande `vite`.

Quand il est stocké dans un dépôt Github ou Gitlab, un site statique est publié.

Le contenu présent dans le dossier `public` sera déployé automatiquement en ligne à chaque fois que du code est poussé avec `git push`.

## Utiliser ce template avec Github.

Se rendre sur https://github.com/coda-school/template-site-statique.
Cliquer sur le bouton `Utiliser ce template` puis `Créer un nouveau dépôt`.

Donner un nom et une description au dépôt.
Choisir la visibilité `public`.

### Déploiement sur Github pages

Le dépôt doit avoir la visibilité `public`

Dans les `paramètres` du dépôt, rubrique `Pages`, positionner la source de déploiement à `Github Actions`.

### Afficher le lien de la page dans Github

Revenir à la page principale du dépôt Github.

Dans la rubrique `à propos` (à droite), passer en mode edition.

Dans la rubrique site Web, cocher `Utiliser votre site Web Github Pages`.

Sauvegarder les changements.

L'adresse du site est maintenant affichée dans la rubrique `à propos`.

## Lancer le serveur en local avec vite

Après avoir rempli les prérequis (voir plus bas).

Dans une ligne de commande:
```shell
npx vite
# Ou si vous avez installé vite globalement
vite
```

Ouvrir dans le navigateur : http://localhost:5173

## Prérequis

### Installer nodejs

Installer nodejs : https://nodejs.org/fr/download

### (Optionnel) installer vite globalement

Installer la commande `vite`

Dans une ligne de commande:
```shell
npm install -g vite
```

