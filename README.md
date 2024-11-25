# 5.16 Activité Pratique : Service GraphQL avec Spring Boot

## Description du projet
Ce projet consiste à développer une API GraphQL en utilisant Spring Boot et des technologies associées. L'application permet de gérer des entités telles que des comptes bancaires, en exploitant une base de données embarquée (H2) et en intégrant des fonctionnalités de visualisation et manipulation des données via GraphiQL.

## Prérequis
- **JDK** : Version 17 ou supérieure
- **IDE** : IntelliJ IDEA ou Eclipse
- **Maven** : Pour la gestion des dépendances

## Étape 1 : Création du projet Spring Boot
1. **Génération du projet** :
   - Accédez à [Spring Initializr](https://start.spring.io/).
   - Configurez les options suivantes :
     - **Project** : Maven Project
     - **Language** : Java
     - **Spring Boot Version** : 3.5.0
     - **Group** : `com.example`
     - **Artifact** : `banque-service`
     - **Packaging** : Jar
     - **Java Version** : 17
2. **Ajout des dépendances** :
   - Spring for GraphQL
   - Spring Web
   - Spring Data JPA
   - H2 Database
   - Lombok



https://github.com/user-attachments/assets/9e7c1390-ed4b-4c03-a990-80b821b92fd5

