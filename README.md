# Bonjour, je suis Abdelkbir Hadioui

 Étudiant ingénieur en **Génie Mécanique et Systèmes Automatisés** à l’ENSA de Fès  
 Passionné par l’**automatisation industrielle**, la **robotique**, la **maintenance industrielle** et l’**Industrie 4.0**  
 Objectif : intégrer un environnement industriel orienté **automatisme, maintenance, robotique et systèmes connectés**

---

##  À propos de moi

Je développe des projets techniques combinant **mécanique**, **automatisme**, **électricité industrielle**, **pneumatique**, **robotique** et **supervision**.

Mon profil est orienté terrain : j’aime transformer un besoin industriel en solution complète, depuis l’analyse fonctionnelle jusqu’à la conception, le dimensionnement, la simulation et la programmation API.

Je m’intéresse particulièrement à :

- Automatisation industrielle avec **Siemens TIA Portal / STEP 7**
- Robotique industrielle et cellules robotisées
- Maintenance industrielle et amélioration de la disponibilité des équipements
- Dimensionnement électrique et pneumatique
- Supervision HMI/SCADA et communication industrielle
- Systèmes embarqués, IoT industriel et Raspberry Pi / ESP32

---

##  Compétences techniques

### Automatisme & Supervision
![TIA Portal](https://img.shields.io/badge/TIA%20Portal-Siemens-blue)
![STEP7](https://img.shields.io/badge/STEP%207-Siemens-green)
![WinCC](https://img.shields.io/badge/WinCC-HMI-blue)
![PLC](https://img.shields.io/badge/PLC-S7--1200%20%7C%20S7--300-orange)

- Programmation API Siemens
- GRAFCET, Ladder, blocs FC/FB/OB
- Supervision HMI avec WinCC
- Communication industrielle : PROFINET, PROFIBUS, Modbus, OPC-UA

### Conception & Simulation
![CATIA](https://img.shields.io/badge/CATIA-V5-darkblue)
![DELMIA](https://img.shields.io/badge/DELMIA-Robot%20Simulation-purple)
![SEE Electrical](https://img.shields.io/badge/SEE%20Electrical-Schematics-yellow)
![Caneco](https://img.shields.io/badge/Caneco-Dimensionnement%20BT-red)

- Conception mécanique sous CATIA V5
- Simulation robotique sous DELMIA / MODOU IDE
- Schémas électriques sous SEE Electrical
- Dimensionnement électrique sous Caneco BT
- Analyse de risque, AMDEC, analyse fonctionnelle

### Électronique & IoT
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-IoT-red)
![ESP32](https://img.shields.io/badge/ESP32-Embedded-black)
![Arduino](https://img.shields.io/badge/Arduino-Microcontroller-blue)
![NodeRED](https://img.shields.io/badge/Node--RED-IoT-red)

- Raspberry Pi, Raspberry Pi Pico, ESP32, Arduino
- Node-RED, capteurs TOR, servomoteurs, actionneurs
- Simulation Wokwi / Proteus

---

#  Projets principaux

## 1.  Cellule robotisée de palettisation de blocs compactés

🔗 **Lien du projet:[Voir[Voir le détail du projet PFE](projects/robot-palletisation.md)

Projet de fin d’études portant sur la conception d’une **cellule robotisée de palettisation** destinée à manipuler des blocs compactés d’aluminium/canettes.

Le projet couvre l’ensemble de la chaîne d’ingénierie :

- Analyse fonctionnelle du système
- Analyse de risque et AMDEC
- Conception mécanique du préhenseur sous CATIA V5
- Dimensionnement pneumatique des vérins de serrage et d’anti-chute
- Étude électrique et schémas sous SEE Electrical
- Dimensionnement électrique sous Caneco BT
- Simulation robotique sous DELMIA / MODOU IDE
- Intégration d’un robot palettiseur EFORT
- Communication robot/API via PROFINET
- Programmation API Siemens et supervision HMI

### Résumé technique

La cellule reçoit les blocs depuis un convoyeur, les positionne précisément, puis un robot palettiseur les saisit à l’aide d’un préhenseur pneumatique.  
Le préhenseur est composé d’un système de serrage avec vérin pneumatique double effet et d’un système anti-chute pour sécuriser le transport du bloc.

Le projet intègre également une logique de sécurité avant levage basée sur :

- Présence du bloc
- Serrage fermé
- Anti-chute fermé
- Pression de serrage correcte
- Pression anti-chute correcte

---

## 2.  Automatisation d’une stockeuse de phosphate – OCP

🔗 **Lien du projet :** [Automatisation stockeuse OCP](https://github.com/USERNAME/stockeuse-phosphate-automation)

Projet réalisé dans le cadre d’un stage d’application chez **OCP Khouribga**, autour de la modernisation du système de translation d’une machine stockeuse de phosphate.

### Objectif du projet

Remplacer une ancienne solution de démarrage par résistances rotoriques par une solution plus moderne basée sur :

- Variateur de vitesse
- Automate Siemens
- Supervision HMI
- Standardisation des variables API
- Amélioration de la maintenance et de la disponibilité

### Résumé technique

L’ancien système utilisait des moteurs asynchrones à rotor bobiné avec élimination progressive des résistances rotoriques par contacteurs.  
La nouvelle solution vise à améliorer le démarrage, réduire les contraintes électriques et mécaniques, et faciliter le diagnostic via une interface HMI.

Compétences mobilisées :

- Étude de l’ancien programme STEP 7
- Analyse des réseaux Ladder
- Timers et séquences de démarrage
- Migration vers une architecture plus moderne
- Choix d’un variateur de vitesse
- Programmation sous TIA Portal
- Création d’une interface de supervision

---

## 3.  Compacteur intelligent de canettes

🔗 **Lien du projet :** [Compacteur de canettes automatisé](https://github.com/USERNAME/can-compactor-automation)

Projet académique de conception d’un système automatisé permettant de compacter des canettes et de gérer leur passage une par une.

### Fonctionnalités principales

- Convoyeur de transport
- Source de stockage des canettes
- Système mécanique pignon-crémaillère
- Vérin électrique pour le compactage
- Capteurs de position
- Détection de la canette compactée
- Commande via Raspberry Pi / ESP32
- Supervision possible avec Node-RED

### Résumé technique

Le système permet d’alimenter automatiquement une zone de compactage, de compacter la canette puis d’autoriser le passage de la canette suivante uniquement lorsque les conditions sont validées.

Ce projet combine :

- Automatisme
- Mécanique
- Capteurs
- Actionneurs
- Systèmes embarqués
- Simulation Wokwi

---

## 4. ⚡ Étude électrique d’une cellule industrielle

🔗 **Lien du projet :** [Dimensionnement électrique industriel](https://github.com/USERNAME/electrical-sizing-industrial-cell)

Projet dédié au dimensionnement électrique d’une cellule robotisée industrielle.

### Contenu du projet

- Bilan de puissance
- Choix du sectionneur général
- Choix des protections par départ
- Départ robot
- Départ moteur convoyeur
- Départ alimentation 24 VDC
- Choix de l’alimentation SITOP
- Intégration d’une réserve d’énergie 24 VDC
- Étude de la chute de tension
- Préparation du schéma électrique sous SEE Electrical
- Dimensionnement sous Caneco BT

### Résumé technique

L’objectif est de construire une architecture électrique claire, sécurisée et conforme aux besoins de la cellule robotisée.  
Chaque départ est protégé séparément afin d’améliorer la sélectivité, la maintenance et la sécurité de l’installation.

---

## 5.  Maintenance industrielle – MK AERO Tanger

🔗 **Lien du projet :** [Maintenance industrielle MK AERO](https://github.com/USERNAME/industrial-maintenance-mk-aero)

Expérience d’observation dans un environnement industriel orienté maintenance des machines-outils.

### Activités principales

- Observation des interventions de maintenance
- Analyse du fonctionnement des machines industrielles
- Compréhension de l’organisation maintenance
- Suivi des opérations préventives et correctives
- Découverte des contraintes de disponibilité et de fiabilité

### Compétences développées

- Maintenance industrielle
- Diagnostic de pannes
- Sécurité machine
- Organisation d’un service maintenance
- Lecture de documentation technique

---

## 6.  Mini-projets automatisme, contrôle et systèmes embarqués

 **Lien du projet :** [Mini-projets automatisme et IoT](https://github.com/USERNAME/automation-embedded-projects)

Ce dépôt regroupe plusieurs travaux pratiques et mini-projets liés à l’automatisme, au contrôle et aux systèmes embarqués.

### Exemples de contenus

- Programmation Arduino
- Raspberry Pi Pico
- ESP32
- Capteurs ultrasoniques
- Servomoteurs
- Simulation Wokwi
- Commande de systèmes simples
- Interfaces Node-RED
- Bases de supervision IoT

---

#  Domaines qui m’intéressent

- Automatisation industrielle
- Maintenance industrielle
- Robotique industrielle
- Systèmes embarqués
- Industrie 4.0
- Supervision HMI/SCADA
- Amélioration continue
- Fiabilité et disponibilité des équipements

---

#  Objectif professionnel

Je cherche à évoluer dans un environnement industriel où je peux contribuer à des projets liés à :

- La modernisation des installations industrielles
- L’automatisation des machines
- L’intégration de robots industriels
- La maintenance intelligente
- La digitalisation des systèmes de production

Mon objectif est de devenir un ingénieur capable de relier la **mécanique**, l’**automatisme**, l’**électricité industrielle** et les **systèmes connectés** pour développer des solutions fiables, sécurisées et adaptées aux besoins du terrain.

---

#  Me contacter

- 💼 LinkedIn : [Abdelkbir Hadioui](https://www.linkedin.com/in/USERNAME)
- 📧 Email : abdelkebirhadioui@gmail.com
- 🌐 Portfolio : [Mon portfolio](https://USERNAME.github.io/portfolio)
- 🧑‍💻 GitHub : [github.com/USERNAME](https://github.com/USERNAME)


