# MarryMe

Application web de préparation de mariage, réalisée de bout en bout par une équipe de 4 développeurs dans le cadre d'une formation en développement full-stack.

Contexte

Le projet de fin de formation consistait à imaginer une application web, puis à la concevoir et la développer entièrement en équipe, avant de la présenter devant un public.

Nous avons choisi le thème du mariage parce qu'une collègue de la promotion s'était mariée quelques mois plus tôt : son expérience de l'organisation nous a donné l'idée d'un outil pour faciliter la préparation de ce type d'événement.

Organisation de l'équipe
Équipe de 4 personnes, avec un partage des tâches tout au long du projet.
Chaque membre a travaillé sur les trois couches de l'application : front-end, back-end et base de données.
Présentation finale du projet devant un public (support : MarryMe.pptx).
Mon rôle

En tant que membre de l'équipe, j'ai participé à :

la conception de l'application et au choix des fonctionnalités ;
le développement d'interfaces en Angular ;
le développement de services back-end en Java / Spring Boot ;
la conception et l'exploitation de la base de données MySQL ;
la présentation finale du projet.
Technologies
Couche	Technologies
Front-end	Angular, TypeScript, HTML, CSS
Back-end	Java, Spring Boot, API REST
Base de données	MySQL
Outils	Git, GitHub
Structure du dépôt
MarryMe/
├── marryMe-angular/   # Application front-end Angular
├── marryMe-front/     # Front-end (version initiale)
├── marryMe-back/      # API back-end Java / Spring Boot
├── marryMe-Full/      # Version complète de l'application
└── MarryMe.pptx       # Support de la présentation finale
Lancer le projet en local
Prérequis
Node.js et Angular CLI
Java (JDK) et Maven
MySQL
Base de données

Créer une base MySQL, puis renseigner l'URL, l'utilisateur et le mot de passe dans le fichier application.properties du back-end.

Back-end
bash
cd marryMe-back
mvn spring-boot:run
Front-end
bash
cd marryMe-angular
npm install
ng serve

L'application est ensuite accessible sur http://localhost:4200.

Auteurs

Projet réalisé en équipe de 4 dans le cadre d'une formation de développeur full-stack. Dépôt d'origine : bonninmanon/MarryMe.
