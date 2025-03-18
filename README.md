# Data Challenge: Détection de Comportements Malveillants d'Applications Windows

## Contexte

Ce projet est une réponse à un challenge organisé par l'Université Paris I Panthéon-Sorbonne et le ComCyber du Ministère de l'Intérieur, dans le cadre de la lutte contre les cybermenaces. L'objectif du challenge est de créer un système capable de prédire des comportements malveillants dans des applications Windows en analysant leurs instructions et graphes de contrôle de flux (CFG).

### Objectif du Projet

Le but est de développer un modèle capable de prédire quels comportements suspects ou malveillants peuvent être observés dans un programme à partir des instructions qu'il contient. Le projet utilise des binaires Windows (format PE ou DLL), dont des graphes de contrôle de flux (CFG) ont été extraits et sont utilisés pour prédire les comportements du programme.

## Structure du Projet

Le projet suit une approche en plusieurs étapes pour prétraiter les données, extraire des caractéristiques, entraîner un modèle, et faire des prédictions sur des données de test.
