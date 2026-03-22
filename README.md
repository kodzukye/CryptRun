# CryptRun

> Prototype de Top Down Shooter développé lors d'un stage de 2 mois chez **Cariality Studio** (Janvier – Février 2026)
 
![Unreal Engine 5](https://img.shields.io/badge/Unreal%20Engine-5-black?style=flat&logo=unrealengine)
![Blueprint](https://img.shields.io/badge/Blueprint-Visual%20Scripting-blue?style=flat)
![Status](https://img.shields.io/badge/Status-Prototype-orange?style=flat)
 
---

## Description
 
**CryptRun** est un prototype de Top Down Shooter développé sous Unreal Engine 5 en Blueprint.  
Le joueur progresse de salle en salle, élimine les ennemis et collecte des armes ou des collectables qui lui confèrent des bonus ou malus. L'objectif est de survivre et d'avancer le plus loin possible.
 
---

## Mécaniques développées
 
Voici les systèmes qu'on a conçu et implémentés en Blueprint :
 
### Character Controller
- Déplacements fluides en vue du dessus (Top Down)
- Gestion des animations liées aux mouvements
- Rotation du personnage orientée vers la visée
 
### Système de caméra
- Caméra Top Down fixée au-dessus du joueur
 
### Système de combat
- Tirs et attaques dirigés vers la cible visée
- Gestion des dégâts
 
### Système de drop & pickup d'arme
- Le joueur peut ramasser les armes au sol
- Gestion du changement d'arme
 
### Système de collectables (bonus / malus)
- Objets ramassables dispersés dans les salles
- Effets variés sur le joueur : bonus (vie, vitesse, dégâts...) ou malus
- Gestion des effets temporaires ou permanents sur le personnage
 
### IA Ennemis
- Détection et poursuite du joueur
- Comportements d'attaque et de patrouille
 
### Système de checkpoint
- Respawn du joueur au dernier checkpoint atteint

---

## Technologies utilisées
 
| Outil | Usage |
|---|---|
| **Unreal Engine 5** | Moteur de jeu |
| **Blueprint** | Implémentation de toutes les mécaniques |
| **Git / Gitea** | Contrôle de version |

 ---
 
## Code source complet
 
Le projet Unreal Engine complet est volumineux et hébergé sur mon serveur Git personnel :
 
👉 **[Accéder au code source complet](https://git.jahyna-universe.com/kodzukye/CryptRun)**

---

 ## Crédits
 
Développé lors d'un stage chez **[Cariality Studio](https://carialitystudios.com/)**  
