# Architecture de l'infrastructure Active Directory

## Présentation

Cette partie décrit l'architecture mise en place
pour le déploiement d'un domaine Active Directory
dans un environnement virtualisé.

# Environnement de virtualisation

Hyperviseur utilisé :

- VirtualBox

Réseau virtuel :

- EntrepriseLAN
- Type : Réseau interne

# Serveur Active Directory

## DC01 - Contrôleur de domaine

Rôle :

- Contrôleur de domaine Active Directory
- Serveur DNS

Système :

- Windows Server 2022

Adresse IP :

- 192.168.10.10

Domaine :

- formation.local

Nom NetBIOS :

- FORMATION

# Poste client

## CLIENT01

Rôle :

- Poste utilisateur membre du domaine

Système :

- Windows 11

Domaine rejoint :

- formation.local

# Communication réseau

Le serveur DC01 fournit les services :

- Authentification des utilisateurs
- Résolution DNS
- Gestion centralisée des comptes

Le poste CLIENT01 communique avec DC01
afin de permettre l'authentification
des utilisateurs du domaine.