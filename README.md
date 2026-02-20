# ALGOX-FUTUR_HELMET
🗂️ COMPARTIMENT 1 : PHASE 1 - FONDATIONS BACKEND

Objectif : Créer l'API Node.js et la Base de Données PostgreSQL qui vont tout stocker.

🏃‍♂️ SPRINT 1 : Base de Données et Sécurité (Semaine 1)

🎫 Ticket BK-01 : Modélisation PostgreSQL 16

Détail de la tâche : Création du schéma relationnel (Tables : users, health_logs, accidents, trips).

Étiquettes : Backend Database

Priorité : 🔥 Urgente

🎫 Ticket BK-02 : API Core & Auth JWT

Détail de la tâche : Setup de Node.js 20/Express. Implémentation du Login/Register avec cryptage bcrypt et Token JWT.

Étiquettes : Backend Sécurité

Priorité : 🔥 Urgente

🏃‍♂️ SPRINT 2 : Communication Temps Réel (Semaine 2)

🎫 Ticket BK-03 : Serveur WebSockets (Socket.IO)

Détail de la tâche : Création du hub bidirectionnel pour recevoir les alertes IoT/IA et les envoyer au mobile en < 50ms.

Étiquettes : Backend Temps-Réel

Priorité : 🔴 Haute

🗂️ COMPARTIMENT 2 : PHASE 2 - IA ENGINE & VISION

Objectif : Développer le cerveau Python (YOLOv8 + MediaPipe) pour analyser la route et le motard.

🏃‍♂️ SPRINT 3 : Vision Routière (Semaine 3)

🎫 Ticket IA-01 : Pipeline OpenCV & YOLOv8

Détail de la tâche : Capturer le flux webcam, détecter les véhicules/piétons et dessiner les Bounding Boxes.

Étiquettes : IA Python 3.11

Priorité : 🔴 Haute

🎫 Ticket IA-02 : Algorithme Risque Collision

Détail de la tâche : Calculer la distance relative des obstacles et déclencher une alerte visuelle "DANGER".

Étiquettes : IA Vision

Priorité : 🔴 Haute

🏃‍♂️ SPRINT 4 : Biométrie & Boîte Noire (Semaine 4)

🎫 Ticket IA-03 : Algorithme Somnolence (EAR)

Détail de la tâche : Utiliser MediaPipe pour analyser les yeux. Si le ratio EAR est faible pendant 1.5s ➔ Alerte Fatigue.

Étiquettes : IA Biométrie

Priorité : 🔥 Urgente

🎫 Ticket IA-04 : Enregistrement Blackbox (5s)

Détail de la tâche : Buffer circulaire vidéo qui sauvegarde le fichier .mp4 des 5 dernières secondes en cas d'accident.

Étiquettes : IA Sécurité

Priorité : 🟡 Moyenne

🗂️ COMPARTIMENT 3 : PHASE 3 - IOT SIMULATION (WOKWI)

Objectif : Programmer l'ESP32 DevKit v1 pour lire les capteurs virtuels.

🏃‍♂️ SPRINT 5 : Firmware & Capteurs Vitaux (Semaine 5)

🎫 Ticket IOT-01 : Pulse Sensor & DHT22

Détail de la tâche : Code C++ pour lire le rythme cardiaque (BPM) et la température interne du casque.

Étiquettes : IoT Hardware

Priorité : 🔴 Haute

🎫 Ticket IOT-02 : Algorithme Crash (MPU6050)

Détail de la tâche : Détecter une chute libre ou une accélération G brutale via l'accéléromètre.

Étiquettes : IoT C++

Priorité : 🔥 Urgente

🏃‍♂️ SPRINT 6 : Connectivité WiFi (Semaine 6)

🎫 Ticket IOT-03 : Bridge WiFi vers Node.js

Détail de la tâche : Regrouper les données (BPM, Température, État Choc) en un objet JSON et l'envoyer au serveur.

Étiquettes : IoT Réseau

Priorité : 🔥 Urgente

🗂️ COMPARTIMENT 4 : PHASE 4 - APP MOBILE FLUTTER

Objectif : Créer l'application cross-platform pour le motard (iOS/Android).

🏃‍♂️ SPRINT 7 : UI & Dashboard Live (Semaine 7)

🎫 Ticket MOB-01 : Setup Flutter & Provider/Riverpod

Détail de la tâche : Initier le projet, configurer l'état global et lier l'API Login.

Étiquettes : Mobile Flutter 3.x

Priorité : 🔴 Haute

🎫 Ticket MOB-02 : Jauges de Télémétrie

Détail de la tâche : Créer l'interface avec la jauge de Vitesse, la Température, et l'animation du cœur pour le BPM.

Étiquettes : Mobile UI

Priorité : 🔴 Haute

🏃‍♂️ SPRINT 8 : Mode Urgence & Cartographie (Semaine 😎

🎫 Ticket MOB-03 : Overlay "Crash Alert"

Détail de la tâche : Écran rouge prioritaire déclenché par Socket.io (choc ou BPM critique) avec timer de 10s pour annuler les secours.

Étiquettes : Mobile Sécurité

Priorité : 🔥 Urgente

🎫 Ticket MOB-04 : Google Maps Live Tracking

Détail de la tâche : Intégration de la carte pour suivre le trajet et marquer les points d'alertes IA.

Étiquettes : Mobile GPS

Priorité : 🟡 Moyenne

🗂️ COMPARTIMENT 5 : PHASE 5 - E-COMMERCE REACT

Objectif : La vitrine Web professionnelle pour vendre le produit.

🏃‍♂️ SPRINT 9 : Showcase & Catalogue (Semaine 9)

🎫 Ticket WEB-01 : Landing Page & UI

Détail de la tâche : Design React 18 / Vite.js avec présentation détaillée de l'IA et de l'IoT intégrés.

Étiquettes : Web React

Priorité : 🟡 Moyenne

🏃‍♂️ SPRINT 10 : Achat & Portail Client (Semaine 10)

🎫 Ticket WEB-02 : Panier & Paiement Stripe

Détail de la tâche : Tunnel d'achat complet. Simulation du paiement pour valider la commande.

Étiquettes : Web E-commerce

Priorité : 🔴 Haute

🎫 Ticket WEB-03 : Portail de téléchargement APK

Détail de la tâche : Espace sécurisé pour télécharger l'application Flutter après l'achat du casque.

Étiquettes : Web Déploiement

Priorité : 🟡 Moyenne

🗂️ COMPARTIMENT 6 : PHASE 6 - INTÉGRATION & QUALITÉ

Objectif : Valider la fiabilité totale du système pour la soutenance.

🏃‍♂️ SPRINT 11 : Tests E2E & Préparation Jury (Semaine 11)

🎫 Ticket FIN-01 : Test Scénario Accident

Détail de la tâche : Vérifier la chaîne : Choc Wokwi + BPM Elevé ➔ Node.js ➔ Alerte Mobile Flutter.

Étiquettes : QA Tests

Priorité : 🔥 Urgente

🎫 Ticket FIN-02 : Rédaction Rapport & Slides

Détail de la tâche : Finaliser le document Word et préparer un Pitch axé sur la Stack 2025 (100% open source).

Étiquettes : Doc Soutenance

Priorité : 🔴 Haute

