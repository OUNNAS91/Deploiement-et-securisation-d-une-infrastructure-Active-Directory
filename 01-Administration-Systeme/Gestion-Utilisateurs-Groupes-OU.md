# Gestion des utilisateurs, groupes et unités organisationnelles

## Objectif

Organiser les objets Active Directory afin de faciliter
l'administration des comptes utilisateurs et l'application
des règles de sécurité.

# Unités Organisationnelles (OU)

Les OU permettent de structurer les objets Active Directory.

Elles permettent également d'appliquer des stratégies
de groupe (GPO) à un ensemble d'utilisateurs ou d'ordinateurs.


OU créées :

- Informatique
- Utilisateurs
- Groupes

# Création des utilisateurs

Un compte utilisateur a été créé dans Active Directory.

## Alexandre Dupont

Type :

- Compte utilisateur du domaine

## Alexandre Dupont

Identifiant :

- adupont

Ce compte permet à l'utilisateur
de s'authentifier sur les postes clients
du domaine formation.local.

# Gestion des groupes

Un groupe Active Directory a été créé :

IT_Employes

Objectif :

Regrouper les utilisateurs appartenant
au service informatique.

Avantage :

Les permissions peuvent être attribuées
au groupe plutôt qu'à chaque utilisateur.

# Principe de sécurité appliqué

La gestion par groupes respecte le principe :

"Donner uniquement les droits nécessaires
aux utilisateurs."

Cela permet de limiter les risques
en cas de compromission d'un compte utilisateur.

# Résultat

Active Directory contient maintenant :

- Une organisation par OU
- Un utilisateur configuré
- Des groupes permettant la gestion des droits

Cette organisation facilite l'administration
et la sécurisation du domaine.