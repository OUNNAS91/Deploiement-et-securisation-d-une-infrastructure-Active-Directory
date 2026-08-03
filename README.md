# Déploiement et sécurisation d'une infrastructure Active Directory

## Présentation

Ce projet présente le déploiement d'une infrastructure Active Directory sous Windows Server 2022 dans un environnement virtualisé avec VirtualBox.

L'objectif est de mettre en pratique les compétences en administration système et en cybersécurité à travers la création d'un domaine, la gestion des utilisateurs, la mise en place de stratégies de sécurité et l'audit des événements Windows.

---

## Objectifs du projet

- Installer Windows Server 2022
- Installer le rôle Active Directory Domain Services (AD DS)
- Créer un domaine Active Directory
- Intégrer un poste client Windows 11 au domaine
- Créer des utilisateurs, groupes et unités organisationnelles (OU)
- Configurer des partages réseau et les permissions NTFS
- Déployer des stratégies de groupe (GPO)
- Mettre en place une politique de mots de passe
- Surveiller les événements de sécurité avec l'Observateur d'événements

---

## Environnement technique


| Hyperviseur | VirtualBox |
| Serveur | Windows Server 2022 |
| Poste client | Windows 11 |
| Contrôleur de domaine | DC01 |
| Domaine | formation.local |

---

## Arborescence du projet

Deploiement-et-securisation-d-une-infrastructure-Active-Directory
│
├── README.md
├── 01-Administration-Systeme
│   ├── Architecture-Infrastructure.md
│   ├── Installation-Active-Directory.md
│   ├── Gestion-Utilisateurs-Groupes-OU.md
│   └── Partages-et-Permissions-NTFS.md
│
├── 02-Cybersecurite
│   ├── Strategie-GPO-Securite.md
│   ├── Politique-Mots-de-Passe.md
│   ├── Audit-Evenements-Windows.md
│   └── Bonnes-Pratiques-Securite.md
│
└── 03-Captures-d-ecran
```

---

## Compétences développées

### Administration système

- Installation et configuration de Windows Server
- Déploiement d'Active Directory
- Gestion des utilisateurs et des groupes
- Organisation des unités organisationnelles (OU)
- Gestion des permissions NTFS
- Configuration des partages réseau

### Cybersécurité

- Déploiement de stratégies de groupe (GPO)
- Mise en place d'une politique de mots de passe
- Verrouillage des comptes utilisateurs
- Audit des événements Windows
- Analyse des Event ID 4624, 4625 et 4740
- Application du principe du moindre privilège

---

## Technologies utilisées

- Windows Server 2022
- Windows 11
- Active Directory Domain Services (AD DS)
- DNS
- Group Policy Objects (GPO)
- NTFS
- Event Viewer
- VirtualBox

---

## Auteur
OUNNAS Amar
Projet personnel réalisé dans le cadre de ma montée en compétences en administration système et cybersécurité.
