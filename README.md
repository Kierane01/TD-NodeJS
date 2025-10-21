# TD-NodeJS
TD sur TypeScript et la création d'API avec node.js

# À qooi sert se TD ?

Ce td nous à permis de comprendre comment gerer des API grâce à NodeJS et les fichiers JSON.

Nous avons vu comment recuperer des informations contenues dans des fichiers JSON grâce à la méthode GET.
Nous avons aussi vu comment modifier des informations grâce à la méthode POST.

# Dépendances nécessaires :

Principale :
express, dotenv

Developpement :
typescript ts-node

# Comment installer les dependances ?

Avec nmp :

npm install express dotenv

npm install -D typescript ts-node @types/node @types/express nodemon

# Demarrer l'API :

npm run dev

# Recuperer les informations du JSON :

curl -X GET http://localhost:4000/users
