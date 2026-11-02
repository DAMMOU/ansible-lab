# Ansible Lab

Ce projet contient la configuration d'un laboratoire Ansible.

## Architecture
- **1 nœud de contrôle** : `vm-controle-node` (Ubuntu)
- **3 serveurs cibles** : 
  - `node1` (Ubuntu)
  - `node2` (Debian)
  - `node3` (Rocky Linux)

## Prérequis
- Ansible installé sur le nœud de contrôle.
- Accès SSH par clé configuré entre le nœud de contrôle et les cibles.
