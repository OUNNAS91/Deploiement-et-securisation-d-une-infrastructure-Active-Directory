# Audit des événements Windows

## Objectif

L'audit des événements Windows permet de surveiller les activités réalisées sur le domaine Active Directory.

Les journaux de sécurité enregistrent les connexions, les échecs d'authentification, la création de comptes et d'autres actions importantes.

## Outil utilisé

Les événements ont été consultés à l'aide de l'Observateur d'événements (Event Viewer).

Chemin : eventvwr.msc dans la boîte de dialogue "executer"

Journaux Windows → Sécurité

## Événements analysés

### Event ID 4624

Signification :

Connexion réussie.

Cet événement permet de vérifier qu'un utilisateur s'est authentifié avec succès.


### Event ID 4625

Signification :

Échec de connexion.

Cet événement est utile pour détecter des erreurs de mot de passe ou des tentatives d'accès non autorisées.

### Event ID 4740

Signification :

Compte utilisateur verrouillé.

Dans ce projet, cet événement a été observé après plusieurs tentatives de connexion incorrectes, conformément à la politique de verrouillage configurée.

## Intérêt en cybersécurité

L'analyse des événements Windows permet de :

- détecter des activités inhabituelles ;
- identifier les échecs de connexion ;
- vérifier le fonctionnement des politiques de sécurité ;
- faciliter les investigations en cas d'incident.

## Conclusion

La surveillance des journaux Windows constitue un élément essentiel de la sécurisation d'une infrastructure Active Directory.