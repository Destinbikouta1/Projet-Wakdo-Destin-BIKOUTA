# Projet-Wakdo-Destin-BIKOUTAWakdo – Support ou Borne de commande & Back-office
Présentation de mon projet
Le projet est fait dans le cadre de la certification RNCP 37805 – Développeur Web.
Il est à concevoir une solution de digitalisation pour un restaurant fast-food (Wakdo), vu du fonctionnement des bornes de commande modernes.
Cette application permettra aux clients de se passer des serveurs (euses) et de commander de manière autonome à l'aide d'un support (borne) tactile, puis de récupérer les commandes directement au comptoir grâce à un numéro unique.
Le projet comprend également un back-office permettant aux équipes de gérer les produits, le menu et les commandes.
Architecture du projet
Le projet est structuré en 3 parties principales :
Front borne Partie 1 : interface client avec utilisation de HTML, CSS, JavaScript
Back-office & API Partie 2  : gestion des données avec utilisation de Node.js, Express, MySQL
Application React Partie 3 : recherche de restaurants sur carte avec utilisation de React + Vite
Fonctionnalités principales
Borne (Support) de commande :
Parcours utilisateur simple et intuitif
Navigation par catégories (menus, burgers, boissons, desserts…)
Composition de menus (burger + accompagnement + boisson + sauce)
Personnalisation des produits
Gestion du panier en temps réel
Validation de la commande avec un numéro
Back-office :
Authentification des utilisateurs
Gestion des rôles (administration, préparation, accueil)
Gestion des produits et menus
Suivi des commandes
Mise à jour des statuts (en préparation, prêt, livré)
 API :
Récupération des produits et menus
Envoi des commandes (POST /api/orders)
Communication entre le front et le back
Application React :
Recherche de ville
Affichage sur carte (react-leaflet)
Sélection d’un restaurant
Interaction utilisateur dynamique
Base de données :
Une base de données MySQL a été mise en place pour gérer :
les utilisateurs
les produits
les menus
les commandes
Initialisation via :
schema.sql
seed.sql
Sécurité
Le projet inclut :
authentification des utilisateurs
gestion des rôles et permissions
validation des données côté serveur
protection des routes API
