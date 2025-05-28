# Euro Control - Analyse des Données de Vols et Aéroports

Ce projet propose une analyse et une visualisation des données de vols et d'aéroports à l'aide de Python, SQLite, Pandas et Cartopy.

## Fonctionnalités principales

- Création et alimentation d'une base de données SQLite avec des aéroports, compagnies et vols.
- Analyses SQL sur les vols (nombre de vols par aéroport, sélection des vols longs, etc.).
- Visualisation cartographique des aéroports européens sur une carte.
- Notebook Jupyter pour l'exploration interactive des données.

## Structure du projet

- `euro-control.py` : Script principal pour la création de la base, l'analyse et la visualisation.
- `euro-control.db` : Base de données SQLite générée automatiquement.
- `euro_control_aeroports_map.png` : Carte générée des aéroports.
- `euro-control.ipynb` : Notebook Jupyter pour l'analyse interactive.
- `README.md` : Ce fichier.

## Prérequis

- Python 3.x
- Bibliothèques : pandas, matplotlib, cartopy, sqlite3
- Jupyter Notebook (optionnel mais recommandé)

## Utilisation

1. Exécutez `euro-control.py` pour générer la base de données et la carte.
2. Ouvrez `euro-control.ipynb` pour explorer les données de façon interactive.

## Auteur

Projet réalisé par RyanNeuville.
