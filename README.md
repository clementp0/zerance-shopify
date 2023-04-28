# README #

Bonjour à toi mon lapin ! 
Bienvenue sur le dépôt des utilitaires du ZaxThème. Celui-ci est indispensable et doit être importée au début projet.

### Installation ###

- Copier/coller le contenu de ce dépôt dans celui de votre projet (sans les fichiers qui lui sont propres : .gitignore, README.md, dossier git.)
- Mettre à jour l'url du store dans le package.json (store_name)
- Commiter les changements avec le message suivant : "[+] AxUtilities"
- Lancer la commande "npm i"
- Puller le thème à l'aide de la commande "npm run pull"
- Comparer les fichiers suivants en gardant bien les modifications du dépôt AxUtilities : 
    ```
    - config/setting_schema.json
    - layout/theme.liquid
    - snippets/script-bundle.liquid
    - snippets/style-bundle.liquid
    ```
- Commiter les changements avec le message suivant : "[+] Theme Init"

### Les commandes de bases ###

* ```npm run build``` (compile une fois pour la prod)
* ```npm run dev``` (compile et watch votre travail)
* ```npm run pull``` (shopify theme pull)
* ```npm run push``` (shopify theme push)
* ```npm run serve``` (shopify theme dev)

***

### Spécificités ###

#### package.json

Les variables de ce fichier s'utilisent différemment en fonction du système d'exploitation.

* Linux/Mac: ```$npm_package_name``` ou ```${npm_package_name}```

* Windows: ```%npm_package_name%```

