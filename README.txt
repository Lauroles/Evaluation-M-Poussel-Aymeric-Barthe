Documentation POSTMAN : https://documenter.getpostman.com/view/5996803/TWDRqz7M

Ce que j'ai produit : 

La partie Back office est entièrement terminé, avec toutes les requetes nécessaire et demandé pour le projet.

La partie front est entièrement stucturé et les services déjà créé. L'affichage de tous les articles ainsi que l'inscription a été produite.


Ce que je n'ai pas produit : 

Je n'ai pas eu le temps de faire la partie front pour la :

- Modification d'un article
- La connexion
- La suppression d'un article
- L'affichage spécifique d'un article
- Le design

Au niveau technique tout est mis en place, mais il manque l'affichage et les relations entre les différentes de page. Ceci a été du à un manque de temps de ma part, ainsi qu'un énorme problème sur lequel j'ai du reprendre tout mon Front.
De plus j'ai des problèmes CORS, je n'ai donc pas pu tester la connexion entre le back et le Front.

COMMENT DEMARRER LE PROJET :

Installer le dossier Back. Faire un : composer install puis un composer update. Ensuit lancer les migrations avec la commande php bin/console doctrine:migrations:migrate. Ensuite démarrer le serveur : symfony serve

Installer le dossier Front. Faire un npm i puis un npm start