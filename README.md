# Projet2 DAAR 
# Sujet : ElasticSearch

# Binome :

Nom: Lamzaoui
Prénom: Amar
Numéro étudiant : 21109486

Nom: BA
Prénom: Mouhamadou Moustapha    
Numéro étudiant: 28615624

Dans ce projet, il est question d'un exemple d'utilisation d'ElasticSearch pour indexer des données avec Spring Boot (Java 8). 
On utilise Vue.js pour le client.

Utilisation : 
- Lancer ElasticSearch
- Lancer la commande `npm install` puis `npm run start` dans `client/es_app`
- Lancer Maven avec la commande `mvn spring-boot:run` dans le dossier principal (là où est le `pom.xml`)

L'application se lance sur le port 8083.

L'application permet d'envoyer des CVs au format \*.pdf, \*.doc et \*.docx, ils sont indexés toutes les 10 secondes.
L'application permet également de chercher des termes présents dans les CV, des compétences par exemples.
