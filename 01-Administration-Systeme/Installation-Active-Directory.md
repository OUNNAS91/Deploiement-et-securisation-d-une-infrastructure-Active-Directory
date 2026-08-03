# Installation et configuration d'Active Directory

## Objectif

Mettre en place un domaine Active Directory
afin de centraliser la gestion des utilisateurs,
des ordinateurs et des règles de sécurité.

# Installation du rôle Active Directory

Le serveur DC01 utilise Windows Server 2022.

Le rôle installé est :

- Active Directory Domain Services (AD DS)

Ce rôle permet de transformer le serveur
Windows Server en contrôleur de domaine.

# Promotion du serveur en contrôleur de domaine

Après l'installation du rôle AD DS,
le serveur a été promu en contrôleur de domaine.

Configuration réalisée :

Nom du domaine :

formation.local

Nom NetBIOS :

FORMATION

Nom du contrôleur de domaine :

DC01

# Création de la forêt Active Directory

Une nouvelle forêt Active Directory a été créée :

formation.local

La forêt représente la structure principale
qui contient le domaine et les objets Active Directory.

# Services configurés

Le contrôleur de domaine fournit :

## Service Active Directory

Gestion :

- Utilisateurs
- Groupes
- Ordinateurs
- Unités organisationnelles

## Service DNS

Il permet :

- La résolution des noms du domaine
- La localisation du contrôleur de domaine

# Résultat

Le serveur DC01 fonctionne maintenant
comme contrôleur de domaine.

Les postes clients peuvent rejoindre
le domaine formation.local
et utiliser l'authentification centralisée.