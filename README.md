# JEE-Activite-4

Cett activité nous permet d'exercer la sécurité d'une application en établissant un systeme d'authentification basé sur Spring security avec les trois stratégies : InMemoryAuthentication, JdbcAuthentication et UserDetailsService

### Travail à faire ###

- Récupérer le code source de l'application non sécurisé qui permet de gérer les patients (résultat de l'activité pratique N°3). Le code source de cette application se trouve dans le repository suivant : https://github.com/mohamedYoussfi/unsecured-hospital-app.git
- Sécuriser cette application en intégrant un système d'authentification basé sur Spring security avec les trois stratégies : InMemoryAuthentication, JdbcAuthentication et UserDetailsService

Vidéo à utiliser comme ressource principale : https://www.youtube.com/watch?v=7VqpC8UD1zM

### Présentation de Spring Security ### 

Spring Security est un framework de sécurité qui fournit des fonctionnalités d'authentification, d'autorisation et de protection contre les attaques de sécurité pour les applications basées sur Spring. Il est basé sur le modèle de sécurité JEE et fournit des fonctionnalités de sécurité telles que la gestion des sessions, la protection contre les attaques CSRF et XSS, la gestion des mots de passe, l'intégration avec des systèmes d'authentification externes tels que OAuth et LDAP, et bien plus encore.

Avec Spring Security, les développeurs peuvent facilement configurer et personnaliser la sécurité de leurs applications en utilisant une variété de mécanismes d'authentification, tels que les formulaires de connexion, les jetons d'accès, les certificats numériques et les clés API. En outre, il est hautement extensible et peut être facilement intégré avec d'autres frameworks et bibliothèques Spring pour une gestion efficace de la sécurité.

![2](https://user-images.githubusercontent.com/60039200/232334960-24988d89-72d4-4a5a-b77a-068d80fb634c.PNG)


### La configuration du projet ### 
- SDK : 1.8 Oracle OpenJDK version 18.0.2
- Java : 17
- Type : Maven 
- Packaging : Jar 

### Les dépendances utilisées ### 
- Spring Web : pour créer des applications Web, y compris RESTful, à l'aide de Spring MVC. Utilise Apache Tomcat comme conteneur intégré par défaut.
- Spring DATA JPA : Pour conserver les données dans ‘SQL stores‘ avec Java Persistance API à l’aide de Spring Data et Hibernate. C'est un module qui facilite le ORM basé sur JPA. Il est utilisé avec les bases de données relationnelles.
- H2 Database : Une base de données intégrée, open source et en mémoire. C'est un système de gestion de base de données relationnelle écrit en Java. C'est une application client/serveur et elle est généralement utilisée dans les tests unitaires.
- MySQL : MySQL est l'un des systèmes de bases de données relationnelles les plus populaires et il est souvent utilisé dans les applications Spring Boot.
- Lombok : Un outil de bibliothèque Java qui génère du code pour minimiser le code ‘boilerplate’. La bibliothèque remplace le code ‘boilerplate’ par des annotations faciles à utiliser (Exemples : @NoArgsConstructor, @Getter, @Setter…).
- Thymeleaf : Un moteur de modèle Java moderne coté serveur qui nous permet d’afficher correctement des pages HTML qui peuvent fonctionner comme des prototypes statiques.
- thymeleaf-extras-springsecurity6
- spring-boot-starter-security
- spring-boot-starter-validation
- Bootstrap
- Bootstrap icons
- spring-boot-devtools

