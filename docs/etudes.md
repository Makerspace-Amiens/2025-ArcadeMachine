---
layout: default
nav_order: 4
title: Études et choix techniques
---

# Études et choix techniques

## Choix de conception physique

Format bartop retenu pour sa compacité et sa facilité de transport.

Conception sur OnShape, export des pièces au format DXF pour la découpe laser.

Prise en compte des contraintes :

Dimensions maximales de la découpeuse laser (49 cm x 29 cm).

Ergonomie pour un joueur assis.

Accessibilité aux câbles et maintenance.

Renforcement des fixations avec du collage sur les zones trop fines pour les vis.

## Choix du système central : Raspberry Pi 5

Afin de faire fonctionner la borne d’arcade, nous avons comparé plusieurs micro-ordinateurs de type Raspberry Pi. Après étude, nous avons retenu le Raspberry Pi 5 pour plusieurs raisons :

Performances supérieures : processeur quad-core ARM Cortex-A76 cadencé à 2.4 GHz, bien plus rapide que le Raspberry Pi 4 (Cortex-A72 à 1.5 GHz).

Mémoire vive : possibilité de choisir jusqu’à 8 Go de RAM, offrant de meilleures performances pour l’émulation et la stabilité des jeux.

Connectique améliorée :

Ports micro-HDMI 4K à 60 Hz, adaptés à notre écran.

Port PCIe permettant l’ajout de stockage SSD (si besoin).

USB 3.0 plus rapide pour les périphériques (manettes, cartes de contrôle).

Compatibilité parfaite avec Recalbox, le système d’exploitation choisi.

Prix raisonnable par rapport aux performances et à la concurrence.

Les alternatives étudiées (Raspberry Pi 4 et Orange Pi 5) ont été écartées :

Le Raspberry Pi 4 présentait des performances inférieures et moins de possibilités d’évolution.

L'Orange Pi 5, bien que performant, offrait moins de compatibilité avec Recalbox et demandait plus de configuration logicielle.

## Choix de l'écran : MSI PRO MP161 E2

L’écran devait répondre à plusieurs contraintes d’encombrement et de qualité :

Taille idéale : 15.6 pouces (39,62 cm) pour une bonne visibilité sans rendre la borne trop encombrante.

Résolution Full HD assurant un affichage net.

Haut-parleurs intégrés simplifiant l’audio.

Alimentation en USB-C, réduisant le câblage.

Connexion simple avec le Raspberry Pi 5 via un câble micro-HDMI vers mini-HDMI.

## Choix des commandes : Kit de Joystick USB

Pour la gestion des commandes de la borne, nous avons utilisé un kit de joystick et boutons arcade relié à des cartes de contrôle USB :

Compatibilité universelle en USB (aucun pilote nécessaire).

Reconnaissance automatique par Recalbox dès le branchement.

Réactivité et fiabilité des commandes pendant les sessions de jeu.

Facilité de branchement et de maintenance.

## Choix de l’alimentation

Pour assurer la stabilité électrique :

Double alimentation secteur 5.1V–5A : une pour le Raspberry Pi 5, une pour l’écran.

Organisation interne via une multiprise intégrée, permettant de n’avoir qu’un seul câble de sortie vers l’extérieur.

Sécurité électrique renforcée et meilleure stabilité lors des longues sessions d’utilisation.

## Choix du système d’exploitation : Recalbox

Nous avons sélectionné Recalbox comme système d'exploitation pour plusieurs raisons :

Simplicité d’installation et de configuration.

Interface claire et intuitive, adaptée au grand public et aux démonstrations.

Large compatibilité avec les émulateurs de consoles rétro (NES, SNES, Megadrive, MAME...).

Prise en charge immédiate du kit de commandes USB (joystick + boutons).

Moins complexe que RetroPie et plus personnalisable que Batocera pour nos besoins.

