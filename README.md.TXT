Projet Quantium – Analyse des ventes de croustilles

Ce projet est réalisé dans le cadre du programme virtuel “Retail Strategy & Analytics” de Quantium.
L’objectif de la première phase est de nettoyer, fusionner et analyser les données de transactions et de clients relatives à la catégorie Chips (croustilles).

🎯 Objectifs de la Task 1

Nettoyer les jeux de données transactionnels et clients

Fusionner les deux jeux de données

Créer de nouvelles variables (PACK_SIZE, BRAND)

Réaliser une analyse descriptive et statistique :

Total des ventes

Ventes par taille de paquet

Ventes par marque

Ventes par segment client

Test T pour comparer Premium vs Mainstream

Générer des visualisations et formuler des insights stratégiques

🧹 Nettoyage des données

Conversion du format de date Excel en datetime

Suppression de deoublons et des transactions anormales (quantité > 10 ou ventes > 100 $)

Vérification des produits (catégorie Chips uniquement)

Nettoyage et uniformisation du fichier client

Fusion des deux sources de données sur LYLTY_CARD_NBR

Extraction des variables : PACK_SIZE, BRAND

📊 Résultats principaux
Indicateur	Résultat
Période analysée	Juillet 2018 – Juin 2019
Nombre de transactions	≈ 246 800
Total des ventes	≈ 1,8 M$
Taille la plus vendue	175g
Marque dominante	Smiths
Segments les plus rentables	Older Families - Budget (168 363.25) & Young Singles/Couples - Mainstream (157 621.60)
🧪 Analyse statistique (Test T)

Le test T a comparé les ventes entre les clients Premium et Mainstream :

Indicateur	Résultat
T-statistic : -7.912461410084792
p-value : 	2.538392195853852e-15

➡️Puisque la p-value ( 2.54×10−15 ) est nettement inférieure au seuil de signification commun 
( α=0.05  ou même  α=0.01 ), on rejete l'hypothèse nulle ( H0 ).

💡 Insights stratégiques

Les formats 175g génèrent le plus de ventes : bon équilibre prix/quantité.

Les marques Dorito, Old et Kettle dominent le marché.

Les clients Older Families - Budget et les Young Singles/Couples - Mainstream sont les plus rentables.
Cela indique que, même si les clients Premium peuvent avoir un panier moyen plus élevé (plus de produits chers par visite), 
ils sont moins nombreux ou achètent moins souvent
 que les clients Budget ou Mainstream, ce qui fait que leur contribution aux ventes totales est plus faible

Recommandation : L'entreprise devrait examiner le produit ou la catégorie de produits vendus en 175g pour comprendre
 pourquoi il est associé à des transactions si coûteuses et essayer de reproduire ce comportement d'achat sur d'autres tailles..

🧰 Outils et technologies

Python : Pandas, NumPy, Matplotlib, Seaborn, SciPy

Google Colab : développement et tests

GitHub : versionnement et documentation

📁 Structure du projet
quantium-chips-analysis/
├── data/
├── notebooks/
├── outputs/
├── README.md
└── requirements.txt

📈 Étapes suivantes (Task 2)

Analyse détaillée des comportements d’achat

Tests statistiques additionnels (t-test multi-segments)

Création de visualisations Power BI

Recommandations finales pour le Category Manager

👤 Auteur

Daouda Sangaré
Analyste de données | Intelligence d’affaires
📧 sangaredaoudda@gmail.com
🌐 https://github.com/SDaoudy