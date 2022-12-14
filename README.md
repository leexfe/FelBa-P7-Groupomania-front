## PROJET  7 : GROUPOMANIA

Dossier du frontend pour le projet 7 Groupomania

## Technologies utilisées 

- VueJs3
- Bootstrap-vue-3
- ViteJs 

## Comment utiliser 

1. `git clone` ce repo .

2. Dans votre terminal, sélectionner le dossier enfant front du projet: Bacon_Felix_P7_code_Groupomania_092022:
- cd front
- npm install 
- npm run dev
- cliquer sur -> Local:   http://localhost:5173/ pour être dirigeé vers la page du site

3. Dans votre terminal, sélectionner le dossier enfant back du projet: Bacon_Felix_P7_code_Groupomania_092022:
- cd back
- npm run dev pour lancer nodemon et assurer la connexion avec la Database.

4. Renommer le fichier `.env.development` en `.env`et remplissez-le avec vos variables personnelles d'environnement.

6. Ce repo a été testé avec une database MySQL en ligne sur Planetscale

## Comment utiliser Prisma pour interagir avec la base de donnée

1. La base de donnée a été intégrée au préalable dans le fichier `schema.prisma` qui configure : 
- les générateurs.
- les sources de données.
- les modèles de données.

2. On envoie la base de donnée créée avec Prisma dans la table MySQL de Planetscale avec la commande : 
- `npx prisma db push`

# vue-project

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
