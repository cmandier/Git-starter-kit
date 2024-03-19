# Git-starter-kit

## Modalités de la formation

Cette formation s'adresse au personne de toute communauté voulant débuter dans la gestion de version de script et la sécurisation de leurs travaux. Cette formation est sous forme d'atelier pratique. Un dépôt GitHub est disponible avec les examples mis en place.

### Prérequis

- Système d'exploitation demandé : Linux ou Windows (avec WSL2)
- Notions de script
- Notion de commandes bash (navigation dans linux)

### Objectifs 

- Créer un dépôt local et distant 
- Modifier / ajouter / supprimer des fichiers
- Gestion des commits
- Notion de branch / merge
- Ouverture vers la collaboration


## Partie théorique

Un gestionnaire de version est un logiciel qui permet aux utilisateurs de conserver un historique des modifications et des versions de tous leurs fichiers. 
Il va garder :
-	une trace de chaque modification réalisée sur chaque fichier, 
-	un descriptif de cette modification donné par l’utilisateur
-	le nom de l’utilisateur qui l’a modifié.

Les gestionnaires de versions sont utiles aussi bien en travail personnel qu’en collaboration. Leurs objectifs seront légèrement différents suivant l’utilité que vous en ferez.

-	Travail personnel : il permet de garder un suivi des modifications que vous avez apporté et de revenir à une version précédente au besoin.
-	Travail en équipe : Permet de fusionner les modifications de chaque membres du groupe en gardant une trace des actions de chacun. Et bien évidemment, il permet de revenir à des versions précédentes également afin d'éviter de supprimer le travail des autres.

Ici nous introduirons le gestionnaire de version Git, ainsi que les plateformes en ligne associées.

**Reprenons avec ces outils !**

Git est le gestionnaire, il sert pour la création d’un dépôt local et pour gérer les versions des fichiers. GitHub / GitLab /  Bitbucket sont donc des services en ligne, qui héberge le dépôt distant. Il permet de stocker les différentes versions de votre code afin de garder un historique délocalisé pour assurer d’avoir une copie sur un réseau de vos travaux. 
Vous allez donc avoir deux copies de votre projet, une en local et une en distanciel. C’est en local que les modifications des fichiers vont être réalisées et c’est en distanciel que les fichiers vont être stockés et diffusés au besoin si le dépôt est en public. 

Mais du coup quelle est la différence entre GitHub, GitLab et Bitbucket ?

GitHub est donc une interface web permettant la communication et la collaboration entre plusieurs développeurs, il permet de contribuer à des projets open source (projets où le code est conçu pour être accessible au public). Cependant, il est sous la tutelle de Microsoft ainsi pas mal de fonctionnalités gratuites sont limités et Microsoft peut avoir accès à toutes vos ressources. Afin de contrer ça GitLab a été créé.
GitLab est l’alternative à GitHub, qui propose une version gratuite plus développée, GitLab peut être hébergé par les services de GitLab ou peut être hébergé directement sur vos propres serveurs.

Il faut savoir qu'il existe une dernière plateforme Bitbucket en version gratuite qui est la préférence des utilisateurs de Atlassian (éditeur de logiciel). 

Pour notre atélier, nous vous proposons l'utilisation de GitHub / GitLab.


