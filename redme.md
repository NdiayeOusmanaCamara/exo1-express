# Gestion des Commandes - Application Express
## Description

Cette application est un serveur Express qui gère les clients, les produits, les commandes et les détails de commande. L'application permet de créer, modifier, et supprimer des clients, des produits et des commandes, ainsi que d'afficher les informations associées.

## Fonctionnalités

- **Clients** : Créer, modifier, afficher et supprimer un client.
- **Produits** : Créer, modifier et afficher des produits.
- **Commandes** : Créer, modifier et supprimer des commandes, associant plusieurs produits à un client.
- **Détails de la commande** : Afficher les informations sur chaque commande (produit, quantité, prix).

## Prérequis
Avant d'exécuter ce projet, assurez-vous d'avoir les éléments suivants installés :
- [Node.js](https://nodejs.org/fr) (version 14 ou supérieure)
- [npm](https://www.npmjs.com/)  (généralement inclus avec Node.js)

## Installation
1. Clonez le projet à partir du dépôt :

```
git clone https://github.com/NdiayeOusmanaCamara/exo1-express
```
2. Accédez au dossier du projet :
```
cd exo1-express
```
3. Installez les dépendances :
```
npm install
```

## Lancer le serveur
1. Exécutez l'application en mode développement avec Nodemon :
```
npm start
```
2. Le serveur sera accessible sur `http://localhost:3081/`.

## Gestion des Clients
- **Créer un client** : Utilise la méthode `createCustomer({ name, email })`.
- **Modifier un client** : Utilise la méthode `editCustomer({ name, email })`.
- **Supprimer un client** : Utilise la méthode `destroyCustomer({ name })`.
- **Obtenir les informations d'un client** : Utilise la méthode `getCustomer()`.

## Gestion des Produits
- **Créer un produit** : Utilise la méthode `createProduct({ name, quantity, price })`.
- **Modifier un produit** : Utilise la méthode `editProduct({ name, quantity, price })`.
- **Afficher les informations d'un produit** : Utilise la méthode `getProduct()`.

## Gestion des Commandes

- **Créer une commande** : Utilise la méthode `createOrder({ date, amount, customer, details })`.
- **Modifier une commande** : Utilise la méthode `editOrder({ date, amount, customer, details })`.
- **Supprimer une commande** : Utilise la méthode `destroyOrder()`.899+
- **Obtenir les informations d'une commande** : Utilise la méthode `getOrder()`.

# Auteur
[N'Diaye Ousmane Camara](https://github.com/NdiayeOusmanaCamara)