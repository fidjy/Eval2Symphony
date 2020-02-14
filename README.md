# Eval2Symphony

    ## Qu'est-ce qu'un container de services ? Quel est son rôle ?
      -  Un Container Service (ou conteneur d'injection de dépendance) est simplement un objet PHP qui gère l'exécution des services
      - Il permet de standardiser et centraliser la façon dont les objets sont construits dans votre application

    ## Quelle est la différence entre les commandes make:entity et make:user lorsqu'on utilise la console Symfony ?
    - Permet de créer une entités
    - Permet de crée une classe User

    ## Quelle commande utiliser pour charger les fixtures dans la base de données ?
    - doctrine:fixtures:load

    ## Résumez de manière simple le fonctionnement du système de versions "Semver"
    - c'est une librairie de services

    ## Qu'est-ce qu'un Repository ? A quoi sert-il ?
    - C'est un design patern
    - Utiliser le patron de conception repository dans un projet Symfony permet de mettre en place une meilleure structure et de faciliter l'exécution de tests.

    ## Quelle commande utiliser pour voir la liste des routes ?
    - php bin/console debug:router

    ## Dans un template Twig, quelle variable globale permet d'accéder à la requête courante, l'utilisateur courant  etc...?
    - {{ … }}

    ## Pour mettre à jour la structure de la base de données, quelles sont les 2 possibilités que nous avons abordées en cours ?
    - doctrine:schema:update --force
    - doctrine:schema:update --dump-sql

    ## Quelle commande permet de créer une classe de contrôleur ?
    - php bin/console make:controler brand new controler

    ## Décrivez succintement l'outil Flex de Symfony
    - outil Symfony qui permet d'ajouter des nouvelles briques en déployant le moins d'effort possible.
