
# Analyse et détection d’incidents de sécurité

## Présentation du projet
Ce projet académique a été réalisé dans le cadre d’une initiation à la cybersécurité, à l’analyse réseau et à la détection d’incidents de sécurité.

L’objectif principal du projet est de comprendre comment analyser des logs systèmes et réseau afin d’identifier des comportements suspects, des anomalies et des tentatives d’intrusion dans un environnement simulé.

Le projet a été réalisé dans un environnement virtualisé sous VirtualBox afin de reproduire une architecture réseau proche d’un environnement d’entreprise.



# Contexte

Dans une infrastructure informatique, les systèmes, serveurs et équipements réseau génèrent continuellement des journaux appelés logs.

Ces logs contiennent différentes informations :
- connexions utilisateurs
- erreurs système
- événements réseau
- accès aux ressources
- authentifications
- activités applicatives

L’analyse de ces journaux est essentielle en cybersécurité afin de :
- détecter des incidents
- identifier des comportements anormaux
- repérer des tentatives d’accès suspectes
- améliorer la supervision sécurité

Ce projet permet donc de reproduire les bases d’un système de détection d’incidents inspiré du fonctionnement d’un SOC (Security Operations Center).



# Objectifs du projet

## Objectifs principaux
- Comprendre le fonctionnement des logs
- Analyser des journaux systèmes et réseau
- Détecter des activités suspectes
- Identifier des vulnérabilités
- Automatiser l’analyse avec Python
- Comprendre les bases de la supervision sécurité

## Objectifs techniques
- Utiliser un environnement virtualisé
- Simuler un réseau d’entreprise
- Réaliser des scans réseau
- Développer des scripts d’analyse
- Générer des alertes simples



# Environnement de travail

## Virtualisation
Le projet a été réalisé dans un environnement virtualisé sous VirtualBox.

Cette solution a permis de créer une architecture réseau simulée et isolée afin de reproduire un environnement d’entreprise.

## Machines virtuelles utilisées
L’architecture comportait plusieurs machines virtuelles :
- machine Linux
- machine Windows
- poste utilisateur
- serveur simulé

## Réseau simulé
Les machines communiquaient via un réseau local virtuel permettant :
- les échanges réseau
- les connexions utilisateurs
- la génération de logs
- l’analyse du trafic



# Architecture du projet

## Infrastructure simulée
- poste client
- serveur
- système Linux
- système Windows
- réseau local virtuel

## Objectif de l’architecture
Cette architecture permettait :
- de générer des événements réseau
- de produire des logs
- de simuler des incidents simples
- d’analyser les comportements réseau



# Analyse des logs

## Types de logs analysés
- logs systèmes
- logs réseau
- logs d’authentification
- journaux de connexions

## Objectif de l’analyse
L’analyse des logs permettait de :
- détecter des anomalies
- identifier des comportements suspects
- repérer des connexions inhabituelles
- comprendre les incidents de sécurité

## Exemples d’activités surveillées
- tentatives de connexion échouées
- connexions répétées
- accès inhabituels
- activité anormale depuis une adresse IP



# Automatisation avec Python

## Utilisation de Python
Python a été utilisé afin d’automatiser l’analyse des journaux.

Les scripts développés permettaient :
- de lire les fichiers de logs
- de filtrer les événements
- de rechercher des mots clés
- de détecter des anomalies
- de générer des alertes simples

## Exemple de détection
Le script pouvait identifier :
- plusieurs “failed login”
- des connexions répétées
- des activités suspectes

## Avantages de l’automatisation
- gain de temps
- réduction de l’analyse manuelle
- détection plus rapide
- traitement de grandes quantités de données

---

# Utilisation de Nmap

## Présentation
Nmap est un outil de scan réseau utilisé en cybersécurité afin d’identifier les services exposés et les ports ouverts.

## Utilisation dans le projet
Nmap a été utilisé pour :
- scanner les machines virtuelles
- identifier les services actifs
- détecter les ports ouverts
- comprendre les risques de sécurité

## Exemples de ports identifiés
- port 22 → SSH
- port 80 → HTTP
- port 443 → HTTPS

## Objectif du scan réseau
- identifier la surface d’attaque
- comprendre les services exposés
- repérer des vulnérabilités potentielles



# Réseaux et protocoles

## Concepts utilisés
- TCP/IP
- modèle OSI
- DNS
- DHCP
- ports réseau

## Objectif
Comprendre comment les données circulent dans un réseau et comment des incidents peuvent être détectés à partir du trafic réseau.



# Détection d’incidents

## Méthode
Le projet consistait à :
1. collecter les logs
2. analyser les événements
3. identifier les anomalies
4. générer des alertes simples

## Types d’incidents simulés
- tentatives de connexion suspectes
- brute force simple
- activité réseau inhabituelle



# Résultats obtenus

Le projet a permis :
- d’automatiser une partie de l’analyse
- de détecter des activités suspectes
- de comprendre les bases de la supervision sécurité
- d’améliorer les compétences en analyse réseau et cybersécurité



# Compétences développées

## Cybersécurité
- analyse de logs
- détection d’incidents
- identification de vulnérabilités
- supervision sécurité

## Réseaux
- architecture réseau
- protocoles réseau
- services réseau

## Développement
- Python
- automatisation
- traitement de données

## Virtualisation
- VirtualBox
- machines virtuelles
- environnement simulé

---

# Difficultés rencontrées
- compréhension des formats de logs
- filtrage des événements pertinents
- interprétation des résultats réseau
- automatisation des traitements



# Perspectives d’amélioration
- intégration d’un tableau de bord
- détection en temps réel
- centralisation des logs
- utilisation d’un SIEM
- amélioration des scripts d’analyse



# Conclusion

Ce projet m’a permis de développer une première expérience pratique en cybersécurité opérationnelle à travers l’analyse de logs, la détection d’incidents et l’identification de vulnérabilités dans un environnement virtualisé.

Il m’a également permis de mieux comprendre les enjeux liés à la supervision sécurité, à l’analyse réseau et au fonctionnement des systèmes d’information en entreprise.
