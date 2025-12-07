# Gomoku IA Min-Max

**IA minimax pour le jeu Gomoku (5 alignés), développée en Java dans le cadre du cours Intelligence Artificielle à Grenoble INP-ESISAR.** Basée sur une implémentation initiale de Thomas Cohen, améliorée avec algorithme minimax et élagage alpha-bêta. [![Licence MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Table des matières
- [À propos](#à-propos)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Technologies](#technologies)
- [Auteurs](#auteurs)
- [Licence](#licence)

## À propos
Projet réalisé pour le cours d'**Intelligence Artificielle** à **Grenoble INP-ESISAR**. L'IA joue au Gomoku (aligner 5 pions) contre un humain ou une autre IA, utilisant l'algorithme **minimax** avec **élagage alpha-bêta** pour optimiser les coups.

## Prérequis
- **Java 11 LTS** (vérifié : version 11.0.29) ✅
- IDE : **VSCode** (avec extension Java) ou **Eclipse**

## Installation
Cloner le repo :
```
git clone [https://github.com/Sacha-Lecomte/GomokuAI](https://github.com/Sacha-Lecomte/GomokuAI)
cd GomokuAI/gomoku
```

## Utilisation
1. Ouvre le dossier dans **VSCode** ou **Eclipse**
2. Lance directement le fichier principal : **`/src/game/Game.java`**
- VSCode : `Ctrl+F5` ou bouton "Run"
- Eclipse : Clic droit sur `Game.java` → **Run As → Java Application**
3. Joue en alternant les tours (**W=joueur**, **B=IA**)

Exemple de sortie console :
```
Tour 2: NOIR
Ligne: 7
Colonne: 7

   00 01 02 03 04 05 06 07 08 09 10 11 12 13 14
00 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
01 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
02 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
03 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
04 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
05 -  -  -  -  -  W  -  -  -  -  -  -  -  -  -
06 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
07 -  -  -  -  -  -  -  B  -  -  -  -  -  -  -
08 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
09 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
10 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
11 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
12 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
13 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  
14 -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
```

## Technologies
- **Langage** : Java 11 TLS
- **Algorithmes** : Minmax, Alpha-Bêta
- **Outils** : VSCode, Eclipse

## Auteurs
- **Sacha Lecomte** - [LinkedIn](https://www.linkedin.com/in/sachalecomte/) - Élève-ingénieur 2e année Grenoble INP-ESISAR
- **Base initiale** : Thomas Cohen (étudiant ESISAR) et Jean-Baptiste Cagnaert (professeur ESISAR)

## Licence
Ce projet est sous licence [MIT](LICENSE) - voir [LICENSE](LICENSE) pour plus de détails.
