<!-- CECI EST UN COMMENTAIRE -->
# Project Tracker

### Platteforme de tracking pour projets ou dossiers en cours




<!-- ABOUT THE PROJECT -->
## Description
[//]: # (ceci est aussi un commentaire, ligne entre parentheses ci-dessous sert a upload une image dans ton README.)
[//]: # ([![Product Name Screen Shot][product-screenshot]]&#40;https://example.com&#41;)

Il s'agit d'une platteforme minimaliste de gestion, les fonctionalites sont les suivantes:
- Ajout de nouveau projet
- Categorisation du projet
- Assignation et mise a jour du statut
- Annulation de projet

En d'autres termes, nous construirons une platteforme qui applique le principe [CRUD](https://developer.mozilla.org/fr/docs/Glossary/CRUD)

## Mise en place/Installation
Le projet se concentrera plus sur la structure backend, par consequent le frontend sera minimal. Pour cette premiere application, nous n'utiliserons pas de framework autre que REACT. LEs raisons en sont les suivantes:
1- Comme convenu lors de nos discussions, et vu que l'objectif final de ton apprentissage passera potentiellement par d'autres langages de programmation (Python, .Net, Java),  je ne veux donc pas perdre de temps sur des choses qui ne te sont pas utiles a ce stade
2 - A l'avenir, quelque soit le langage que tu utiliseras pour creer ton logiciel, il pourra facilement utiliser mysql, mais PHP ne sera pas necessairement le langage approprie pour le type de  logiciel que tu voudras creer.
3 - Tu as deja passe deux semaines a apprendre Javascript, et le principe derriere les commandes mysql reste le meme, quelque soit la platteforme d'exploitation que tu utiliseras pour interagir avec ta base de donnees. We might as well get you started with what you know so far.

### Frontend
- Navigues vers le dossier de ton choix
- Installes create react app ```npm install -g create-react-app```
- [Crees une nouvelle](https://create-react-app.dev/) application React
  ``` npx create-react-app project-tracker```
### Backend
- Suis [ces instructions](https://www.youtube.com/watch?v=EN6Dx22cPRI&t=804s) pour creer ton serveur et connecter ta base de donnees. Obviously, pas besoin de faire tout le tutoriel, concentres-toi juste sur comment il cree les endpoints et comment il fait des requetes a la db
- 
## Taches
### frontend
- Cree une simple page, avec un **formulaire** 
- Le formulaire contient les champs suivants:
    - Nom du projet
    - Nom du createur du projet
    - Un champ de texte (textarea) pour la description du projet
    - Un `dropdown` avec les options de statut du projet
    - Un bouton de soumission
- Creer un tableau contenant pour chaque rangee les elements du projet
- Nom
- Identifiant (id)
- Description
- Date de creation
- Statut
- Un bouton pour modifier
- Un bouton pour effacer
- Assures-toi que la soumission du formulaire mette a jour le tableau des projets, idealement sans que l'usager doive raffraichir manuellement la page

### backend
- Utilises le fichier de serveur (`app.js`) pour creer les endpoints suivants
  - get-projects
  - get-projects/id
  - create-project
  - update-project/id
  - delete-project/id
-Dans chacun de ces endpoints, ecris la logique appropriee pour connecter l'action a ta base de donnee.

## Prerequis
- [NodeJS](https://nodejs.org/en/download/)
- React
- Git

## Liens utiles
- [Common mysql queries and commands](https://devhints.io/mysql)
- [Git cheat sheet](https://training.github.com/downloads/github-git-cheat-sheet/)
- [Submit form with React](https://www.w3schools.com/react/react_forms.asp)
- [Create an HTML table](https://www.w3schools.com/html/html_tables.asp)


# Good Luck!
