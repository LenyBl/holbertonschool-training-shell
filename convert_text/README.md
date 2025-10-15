# convert_text.sh

[![Bash](https://img.shields.io/badge/Language-Bash-blue.svg)](https://www.gnu.org/software/bash/) [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Description
`convert_text.sh` est un script Bash qui lit un fichier texte passé en argument et crée un nouveau fichier contenant le contenu transformé selon une option choisie par l’utilisateur.

Le script propose trois types de transformations :  

- `--upper` : conversion du texte en **majuscules**  
- `--lower` : conversion du texte en **minuscules**  
- `--reverse` : **inversion de l’ordre des lignes**  

Le nom du fichier de sortie est dérivé du fichier d’entrée, par exemple :  
`input.txt` → `input_upper.txt`, `input_lower.txt` ou `input_reverse.txt`.

---

## Prérequis
- Système Unix/Linux ou macOS  
- Bash (version ≥ 4 recommandée)  

---

## Installation
1. Cloner le dépôt ou télécharger le script :  
   ```bash
   git clone <URL_DU_REPO>
