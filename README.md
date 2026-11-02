# Ansible Lab

Ce projet contient la configuration d'un laboratoire Ansible.

## Architecture
- **1 nœud de contrôle** : `vm-controle-node` (Ubuntu)
- **3 serveurs cibles** : 
  - `node1` (Ubuntu)
  - `node2` (Debian)
  - `node3` (Rocky Linux)

## Fonctionnalités

Ce projet met en œuvre les concepts clés d'Ansible :
- **Structure professionnelle** : Rôles modulaires (`common`, `nginx`), playbooks et variables (`group_vars`).
- **Multi-OS** : Gestion automatique des différences entre Debian/Ubuntu (`apt`) et Rocky/RedHat (`dnf` + EPEL).
- **Déploiement réel** : Installation de Nginx avec page personnalisée et gestion des services (handlers).
- **Code réutilisable** : Paramétrage complet via variables.

# # Prérequis
- Ansible installé sur le nœud de contrôle.
- Accès SSH par clé configuré entre le nœud de contrôle et les cibles.
