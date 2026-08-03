# Politique des mots de passe

## Objectif

La politique des mots de passe permet de renforcer la sécurité des comptes utilisateurs du domaine Active Directory.

Elle est configurée à l'aide de la stratégie **Default Domain Policy**, qui applique les mêmes règles à tous les utilisateurs du domaine.

# Paramètres configurés

Les paramètres de sécurité définissent notamment :

- Une longueur minimale du mot de passe (8 caractères).
- L'utilisation de mots de passe complexes (activé).
- Une durée de validité des mots de passe (90 jours).
- Un historique empêchant la réutilisation immédiate des anciens mots de passe (5 mots de passe mémorisés).

# Verrouillage des comptes

Une politique de verrouillage a également été mise en place.

Après 5 tentatives de connexion incorrectes, le compte utilisateur est temporairement verrouillé (15 minutes).

Cette mesure limite les risques d'attaques par force brute.

# Test réalisé

Un test a été effectué avec plusieurs tentatives de connexion échouées.

Le compte utilisateur a été verrouillé conformément à la politique définie.

# Intérêt en cybersécurité

La mise en place d'une politique de mots de passe permet de :

- protéger les comptes utilisateurs ;
- limiter les risques de compromission ;
- appliquer des règles homogènes à l'ensemble du domaine ;
- renforcer la sécurité de l'infrastructure Active Directory.