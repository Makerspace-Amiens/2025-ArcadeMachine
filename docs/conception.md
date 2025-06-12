---
layout: default
nav_order: 5
title: Conception et prototypage
---

# Conception et prototypage

## Contraintes de conception
La conception de la borne d’arcade a dû prendre en compte plusieurs contraintes techniques et matérielles :

Format de la découpeuse laser : les dimensions maximales utilisables étaient de 49 cm x 29 cm, limitant la taille des panneaux.

Dimensions de l’écran : l’écran MSI de 15,6 pouces (36 cm x 23 cm) a directement influencé les proportions globales de la borne.

Ergonomie : la borne a été pensée pour un joueur assis, avec une position confortable des commandes.

Épaisseur des matériaux :

Contreplaqué de 5 mm pour les panneaux principaux.

Acrylique de 3 mm pour certains éléments transparents.

Facilité de maintenance :

Accès à l’arrière de la borne pour manipuler les câbles HDMI, l’alimentation et l’intérieur du boîtier.

Possibilité d’ajouter un deuxième joueur via des commandes déportées.

## Modélisation 3D
Pour garantir une découpe précise et un assemblage optimal :

La modélisation a été réalisée sur le logiciel OnShape.

Chaque pièce a été conçue à partir des dimensions réelles des composants.

Des ouvertures spécifiques ont été prévues pour l’écran, les boutons, les câblages et la ventilation.

Les fichiers finaux ont été exportés au format DXF, compatible avec la découpe laser.

## Assemblage physique de la borne
Les panneaux découpés ont été assemblés avec un mélange de collage et de vissage pour garantir la solidité de l’ensemble.

Les cartes de contrôle USB, l’écran et le Raspberry Pi ont été fixés à l’intérieur de la structure.

Une multiprise interne permet d’alimenter l’ensemble du système avec un seul câble extérieur.

Le système de refroidissement a été positionné directement sur le Raspberry Pi pour stabiliser la température.

## Problème rencontré

Les pièces modélisées étaient parfois trop grandes pour passer en une seule découpe.

Le bois de 5 mm était trop fin pour certaines fixations par vis.

Difficulté d’accès au câble HDMI pendant l’installation.

La conception initiale ne prévoyait qu’un seul joueur.

## Solution mise en place

Les pièces ont été découpées en plusieurs parties, puis repensées pour faciliter l’assemblage.

Renforcement des zones fragiles par collage de doubles épaisseurs pour solidifier les fixations.

Agrandissement de l’ouverture arrière et ajout d’un panneau supérieur en acrylique transparent pour un meilleur accès.

Un module de manette externe a été conçu pour permettre le jeu à deux.
