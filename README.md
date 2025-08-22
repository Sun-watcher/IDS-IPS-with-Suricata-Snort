# IDS/IPS Lab - Suricata & Snort

## Introduction

Ce projet est un laboratoire pratique de sécurité réseau visant à expérimenter la **détection d’intrusions (IDS)** et la **prévention d’intrusions (IPS)** à l’aide de **Suricata** et **Snort**.  

L’objectif principal était de **concevoir et tester des règles personnalisées** pour la détection d’attaques sur deux types de vecteurs :  

1. **Network-Based Attacks**  
   - Scans réseau (TCP SYN, UDP)  
   - ICMP Flood et tunnels ICMP  
   - Tentatives de brute-force SSH  

2. **Web-Based Attacks**  
   - Cross-Site Scripting (XSS)  
   - SQL Injection (SQLi)  
   - Directory Traversal  
   - File Inclusion  
   - Command Injection  

Le lab inclut également des instructions pour :  
- Déployer un environnement de test avec **Docker** (DVWA, Metasploitable, conteneurs SSH)  
- Lancer **Suricata et Snort** en mode IDS et IPS  
- Lire les logs et observer les alertes générées par les règles  

Ce projet a pour but de fournir une **expérience pratique et reproductible** pour comprendre le fonctionnement et la configuration des systèmes IDS/IPS.
