# Gestion des partages et permissions NTFS

## Objectif

Mettre en place un partage réseau permettant
aux utilisateurs du domaine d'accéder aux ressources
selon leurs autorisations.


# Création d'un dossier partagé


Un dossier partagé a été créé sur le serveur
afin de centraliser les ressources accessibles
aux utilisateurs du domaine.

Par exemple :

Nom du partage :

\\DC01\Partage

Ce partage est accessible depuis les postes
clients connectés au domaine.

# Gestion des permissions NTFS

Les permissions NTFS permettent de contrôler
les actions autorisées sur les fichiers et dossiers.

Les droits disponibles sont :

- Lecture
- Modification
- Écriture
- Contrôle total

# Attribution des droits

Les permissions sont attribuées principalement
aux groupes Active Directory.

Par exemple :

le Groupe : IT_Employes

Droits :

- Lecture
- Modification

# Principe de sécurité appliqué


L'utilisation des groupes permet :

- Une administration simplifiée
- Une meilleure traçabilité
- Une réduction des erreurs de configuration

Les utilisateurs ne reçoivent pas directement
des permissions individuelles.

# Résultat

Les utilisateurs du domaine peuvent accéder
aux ressources nécessaires à leur activité.

Les droits sont contrôlés grâce à Active Directory
et aux permissions NTFS.