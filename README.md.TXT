Quantium Chips Analysis — Retail Data & Customer Insights

**Python + Power BI Project
*Auteur : Daouda Sangaré

Objectif du projet

Ce projet vise à analyser les données de vente de chips fournies par Quantium (programme Forage) afin de :

nettoyer et préparer les données (transactions + clients),
analyser les comportements d’achat par segment client,
comprendre la performance des marques et des formats,
créer un tableau de bord Power BI interactif,
formuler des recommandations pour améliorer les ventes.

Contenu du projet

1. Python — Data Cleaning & Exploration

Notebook utilisé : `analysis_python.ipynb`

Étapes principales :

Nettoyage du fichier transactionnel
Correction des valeurs aberrantes
Suppression des incohérences (pack size, prix unitaire)
Fusion des données transaction + clients
Exploration statistique :

Top marques
Segments les plus rentables
Analyse pack size
Analyse temporelle
Préparation des fichiers pour Power BI

2. Power BI — Dashboard & Insights

Fichier : PwBI (quantium_chips_dashboard.pbix)

Contient :

Page KPI (Total Sales, Avg Sales, Pack Size…)
Analyse des ventes par marque
Analyse des tailles de paquet
Tendances mensuelles
Segmentation client :

Lifestage
Premium/Budget/Mainstream
Slicers dynamiques (Brand, Pack Size)
Page "Insights Summary" avec recommandations

Principaux insights

Segment avec le plus grand volume de ventes : Older Families — Budget
Panier moyen le plus élevé : Midage Singles/Couples — Mainstream
Marque dominante : Kettle (~0,38M$)
Taille la plus achetée : 175g
Saisonnalité : Forte hausse en novembre–décembre

Recommandations

Cibler les segments Budget & Mainstream en priorité
Renforcer la présence en rayon des formats 175g
Augmenter les stocks avant la période de fêtes
Mettre en avant Kettle / Smiths / Doritos selon segment

Technologies utilisées

Python : Pandas, Numpy, Matplotlib
Power BI : DAX, Data Modeling, Visual Analytics
Git & GitHub

Auteur

Daouda Sangaré — Data Analyst
📧 sangaredaoudda@gmail.com
🔗 www.linkedIn.com/in/daoud-sangaré


Updated README with full project documentation
