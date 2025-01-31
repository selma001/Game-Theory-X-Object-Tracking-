# Suivi d'objets avec YOLOv8 et bruit

## Description

Ce projet explore l'impact du bruit sur la détection d'objets en utilisant YOLOv8, en le modélisant comme un jeu à somme nulle. Le projet analyse les stratégies des deux joueurs (YOLO et le bruit) et évalue les performances en termes d'IoU (Intersection over Union). Des visualisations des résultats sont générées pour illustrer l'impact du bruit sur la précision de la détection.

## Objectifs

- Modéliser le suivi d'objets avec YOLOv8 comme un jeu à somme nulle.
- Analyser l'impact de différents niveaux de bruit sur la performance de détection.
- Calculer l'IoU pour évaluer la précision des stratégies.
- Visualiser les résultats avec des graphiques IoU .

## Fonctionnalités

- Suivi d'objets avec YOLOv8 en ajoutant du bruit Perlin pour perturber les détections.
- Calcul des matrices de gain à somme nulle pour les stratégies de YOLO et du bruit.
- Génération de graphiques d'IoU pour illustrer l'impact du bruit.
- Identification de l'équilibre du jeu avec des stratégies pures.
