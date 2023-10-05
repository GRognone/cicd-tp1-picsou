Parce que c'est notre super projet.

Intégration Continue
Travaux dirigés
Exercices d'introduction à la démarche DevOps.

Les projets à réaliser concernent la gestion d'une liste de voitures.

Vous pouvez vous inpirer de la liste de voitures de ce fichier JSON : https://api.devoldere.net/dataset/cars.json

Le projet .NET
Vous devez développer une applicaiton .NET (Console) permettant de gérer une liste de voitures et gérer l'automatisation des tests unitaires lorsque le code est mis à jour.

Au démarrage, l'application propose à l'utilisateur :

D'ajouter une voiture.
De lister les voitures enregistrées.
De quitter le programme.
A la fermeture, le programme sauvegarde la liste des voitures dans un fichier mes-voitures.json. Ces données, si elles existent, sont évidemment chargées au démarrage du programme.

Une voiture est caractérisée par une marque, un modèle et un prix.

Consignes
Créer un dépôt et inviter ses collègues en tant que collaborateurs.
Créer les tickets correspondants à la demande ci-dessous afin de vous répartir le travail.
Développer l'application (restez simple)
Votre application doit contenir à minima une classe Voiture.
Marque (chaine de caractères, obligatoire, 4 caractères minimum).
Modèle (chaine de caractères, obligatoire, 2 caractères minimum).
Prix (nombre entier, obligatoire, valeur comprise entre 5000 et 500000).
Créer un projet de Tests unitaires
Tester la validité d'une instance de Voiture.
La marque est-elle valide ?
Le modèle est-il valide ?
Le prix est-il valide ?
Ajouter les actions nécessaires pour lancer les tests unitaires de votre projet :
Lorsqu'un push est effectué sur la branche develop.
Lors d'une pull request vers la branche main.
Lors d'une fusion de la branche develop vers la branche main.
Le projet Web
Vous devez développer un petit site web qui sera déployé sur github-pages.

Le site contient 3 pages web :

index.html qui contient une liste de voitures.
ajouter.html qui contient un petit formulaire pour ajouter une voiture.
a-propos.html qui contient la liste des contributeurs du projet.
Consignes
Créer un dépôt et inviter ses collègues en tant que collborateurs.
Créer les tickets correspondants à la demande ci-dessous afin de vous répartir le travail.
Développer les pages web (restez simple).
Ajouter les actions nécessaires pour déployer automatiquement vos pages web lorsque le code est mis à jour sur la branche principale.
