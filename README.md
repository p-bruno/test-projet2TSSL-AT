# EatSmart

## Description
**EatSmart** est une application web permettant la gestion des commandes dans un restaurant. Elle comprend deux parties principales :
- **eatSmartFront** : un front-office destiné aux clients, pour passer des commandes en ligne.
- **eatSmartBack** : un back-office destiné aux restaurateurs, pour gérer les commandes et les plats.

## Fonctionnalités principales
### Front-office (eatSmartFront)
- **Affichage du menu** : Les clients peuvent visualiser les plats disponibles.
- **Passage de commande** : Les clients peuvent sélectionner des plats et passer une commande en ligne.
- **Notification** : Les clients sont informés lorsque leur commande est prête.

### Back-office (eatSmartBack)
- **Gestion des commandes** : Les restaurateurs peuvent gérer les commandes (accepter/refuser, suivi).
- **Suivi des commandes** : Indication de l'état des commandes et gestion de l'historique.
- **Gestion du menu** : Les restaurateurs peuvent ajouter, modifier ou supprimer des plats.

## Installation

### Prérequis
- **Serveur web local** avec support PHP (ex : XAMPP)
- **SGBD MySQL**
- **Git** (pour la gestion des versions)

### Étapes d'installation

1. Clonez ce dépôt :
   ~~~bash
   git clone https://github.com/[NomUtilisateur]/EatSmart.git
   ~~~

2. Déplacez-vous dans le répertoire du projet :
   ~~~bash
   cd EatSmart
   ~~~

3. Configurez la base de données :
   - Créez une base de données MySQL nommée `eatsmart_db`.
   - Importez le fichier `eatsmart_db.sql` dans la base de données.

4. Configurez les variables d'environnement :
   - Modifiez le fichier `config.php` pour y ajouter vos informations de connexion à la base de données.

5. Lancez le projet :
   - Ouvrez `index.html` pour accéder à la partie client.
   - Accédez au back-office via `admin/index.html`.

## Utilisation

1. **Client** : Naviguez sur le front-office pour consulter le menu et passer une commande.
2. **Restaurateur** : Utilisez le back-office pour gérer les commandes et le menu.

## Technologies utilisées

- **Frontend** : HTML, CSS, JavaScript
- **Backend** : PHP, API REST
- **Base de données** : MySQL

## Contributeurs
- **Développeurs** : (Noms des membres de l'équipe)
