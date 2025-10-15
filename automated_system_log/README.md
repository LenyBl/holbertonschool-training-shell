# System Report Script

[![Bash](https://img.shields.io/badge/Language-Bash-blue.svg)](https://www.gnu.org/software/bash/) [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Description
`system_report.sh` est un script Bash qui génère un rapport système complet et lisible dans un fichier `system_report`.  
Le script collecte et enregistre les informations suivantes :  

- Date et heure de l'exécution  
- Nom de l'utilisateur  
- Utilisation du disque  
- Mémoire disponible  
- Temps d'activité du système  

Le rapport est formaté avec des colonnes alignées et un en-tête. Chaque exécution ajoute une nouvelle ligne au fichier, facilitant le suivi historique.

---

## Prérequis
- Système Unix/Linux ou macOS  
- Bash (version ≥ 4 recommandée)  

---

## Installation
1. Téléchargez ou clonez le script :  
   ```bash
   git clone <URL_DU_REPO>
