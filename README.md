# 🛡️ Mise en place d’une architecture réseau sécurisée pour entreprise🛡️

Ce projet a pour objectif de mettre en œuvre une infrastructure réseau sécurisée en entreprise, en utilisant des solutions open-source et économiques. Il inclut la création d'une DMZ à trois niveaux avec PFSense, la mise en place d'un VPN Wireguard, ainsi que le développement d'un logiciel de monitoring multi-site pour garantir une surveillance proactive des réseaux.

## 📑 Table des matières 📑

- [Aperçu du Projet](#-aperçu-du-projet)
- [Fonctionnalités Principales](#-fonctionnalités-principales)
- [Technologies Utilisées](#-technologies-utilisées)
- [Configuration](#-configuration)
- [Problèmes Rencontrés et Solutions](#-problèmes-rencontrés-et-solutions)
- [Évolutions Futures](#-évolutions-futures)
- [Remerciements](#-remerciements)

## 🔍 Aperçu du Projet 🔍

Le projet s'articule autour de trois axes principaux pour renforcer la sécurité et la performance des réseaux d'entreprise :

1. **Création d'une DMZ à trois niveaux** : Utilisation de PFsense pour créer une zone démilitarisée (DMZ) qui protège les ressources internes tout en permettant un accès sécurisé depuis l'extérieur.
2. **Mise en place d'un VPN Wireguard itinérant** : Configuration d'un VPN pour sécuriser l'accès distant aux ressources internes de l'entreprise.
3. **Développement d'un logiciel de monitoring multi-site** : Utilisation de Dashy et Uptime Kuma pour surveiller en temps réel la disponibilité et la performance des connexions VPN multi-sites.

## 🌟 Fonctionnalités Principales 🌟

- **DMZ multi-niveaux** : Séparation des réseaux pour une sécurité accrue.
- **VPN sécurisé avec Wireguard** : Accès sécurisé aux ressources de l'entreprise pour les utilisateurs distants.
- **Monitoring en temps réel** : Surveillance des infrastructures réseau à l'aide de Dashy et Uptime Kuma, avec alertes par email pour les incidents.

## 🛠️ Technologies Utilisées 🛠️

- **Proxmox** : Plateforme de virtualisation open-source pour héberger les différentes machines virtuelles.
- **PFsense** : Pare-feu open-source utilisé pour la création de la DMZ.
- **Wireguard** : Solution VPN légère et sécurisée.
- **Dashy et Uptime Kuma** : Outils de monitoring pour une surveillance proactive.

## ⚙️ Configuration ⚙️

- **Fichier de configuration Wireguard** : Exemple de fichier `wg0.conf` pour configurer le serveur et les clients.
- **Tableau de bord Dashy** : Personnaliser le fichier `config.yml` pour afficher les informations de monitoring.
- **Notifications Uptime Kuma** : Configuration pour recevoir les alertes par email en cas de déconnexion VPN.

## 🔧 Problèmes Rencontrés et Solutions 🔧

Des défis, comme les limitations matérielles et la gestion du temps, ont été rencontrés lors de la mise en œuvre du projet. Des optimisations et une gestion rigoureuse des ressources ont permis de surmonter ces obstacles.

## 🚀 Évolutions Futures 🚀

- **Passage à un VPN site à site** : Pour connecter directement plusieurs sites et améliorer la performance et la sécurité.
- **Ajout de Snort** : En tant que système de détection d'intrusion pour surveiller et protéger le réseau de manière proactive.

## 🙏 Remerciements 🙏

Je remercie chaleureusement Monsieur Fabrice Lartaud de MS Solutions pour son soutien et ses conseils tout au long de ce projet, ainsi que l'IUT Réseau et Télécommunications de Montbéliard pour ses enseignements de qualité.
