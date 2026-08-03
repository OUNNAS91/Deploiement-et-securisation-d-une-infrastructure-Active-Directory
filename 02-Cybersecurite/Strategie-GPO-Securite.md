# Stratégie de sécurité avec les GPO

## Objectif

Les Group Policy Objects (GPO) sont des outils puissant pour gérer les utilisateur et leur environnement. Ils permettent d'appliquer automatiquement des règles de sécurité à l'ensemble des utilisateurs ou des ordinateurs d'un domaine Active Directory.

Dans ce projet, une GPO a été mise en place afin de renforcer la sécurité des postes de travail.

# GPO créée

Nom de la stratégie :

Interdire Panneau de configuration

Cette GPO a été liée à l'unité organisationnelle concernée (IT_Employees) afin que l'utilisateur Alexendre Dupont ne puisse plus accéder au Panneau de configuration.

# Pourquoi cette mesure ?

Le Panneau de configuration permet de modifier de nombreux paramètres du système.

En empêchant son accès, on réduit le risque qu'un utilisateur modifie la configuration de son poste ou désactive certains paramètres de sécurité.

# Résultat obtenu

Après l'application de la GPO et la mise à jour des stratégies avec la commande `gpupdate /force`, un test a été réalisé sur CLIENT01.

Le message indiquant que l'accès était restreint a confirmé que la stratégie était correctement appliquée.

# Bénéfices en cybersécurité

- Réduction des risques liés aux modifications non autorisées.
- Centralisation de la gestion des règles de sécurité.
- Application automatique des politiques sur les postes du domaine.
- Renforcement de la sécurité des postes utilisateurs.