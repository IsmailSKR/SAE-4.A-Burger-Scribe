# Burger Scribe

Burger Scribe est une application de livraison de burgers personnalisables développée en Java. Elle utilise une API pour gérer les commandes et les paiements. Les utilisateurs peuvent créer leur propre burger et modifier à leur convenance des burgers parmi une liste de recettes prédéfinies en choisissant les ingrédients qu'ils préfèrent et passer une commande pour se faire livrer.

## Installation

Pour utiliser l'application, vous devez d'abord cloner le repo de l'application depuis Github :

    git clone https://github.com/DUT-Info-Montreuil/SAE-4.A-Burger-Scribe.git
    
Ensuite, vous devrez cloner le repo de l'API depuis Github aussi :

    git clone https://github.com/DUT-Info-Montreuil/SAE-4.A-Burger-Scribe-API.git

Pour finir, ouvrez le projet dans votre environnement de développement préféré (nous recommandons Android Studio) et installez toutes les dépendances nécessaires.

## Utilisation

Pour lancer l'application, créez un émulateur avec l'API 32 Android (version minimale requise) et exécutez l'application depuis Android Studio. Cela va démarrer l'application sur l'émulateur.

L'API utilisée par l'application nécessite que MongoDB soit installé sur votre machine. Assurez-vous que MongoDB est installé et que le service est en cours d'exécution.

Ouvrez le terminal et naviguez jusqu'au dossier où le repo de l'API a été cloné. Ensuite, exécutez la commande suivante pour démarrer l'API :

    node index.js

À partir de là, vous pouvez commencer à créer votre propre burger personnalisé et passer une commande pour la livraison.

## API

L'API utilisée par l'application permet de s'inscrire, de se connecter, de fournir la liste de burgers et de créer un panier afin de passer une commande.

## Aperçu

 |![](/images/landingPage.png)|![](/images/loginPage.png)|![](/images/homePage.png)|
 |:--------------------------:|:------------------------:|:-----------------------:|
 |Premier lancement de l'application|Connexion / Inscription|Page d'acceuil|
 
 
 |![](/images/productPage.png)|![](/images/cartPage.png)|![](/images/settingsPage.png)|
 |:--------------------------:|:------------------------:|:-----------------------:|
 |Page de details des produits|Panier|Paramètres et compte|