📊 Analyse de l'Évolution du Marché de l'Or – Dashboard Power BI & R

📌 Contexte : 

Ce projet de Business Intelligence a été réalisé dans le cadre académique, avec pour objectif d’analyser l’évolution historique du marché de l’or à l’aide d’outils de data reporting. L’enjeu consistait à produire des visualisations interactives permettant d'identifier des tendances financières significatives, d'expliquer les cycles économiques et d’anticiper les mouvements futurs du marché.

🎯 Objectifs : 

Explorer et analyser des données financières historiques liées au prix et au volume de l’or

Concevoir un dashboard interactif dans Power BI pour la visualisation des tendances temporelles

Nettoyer et préparer les données en R afin d’assurer leur fiabilité

Fournir des insights utiles à la prise de décision dans un contexte d’investissement ou de veille financière

🛠️ Technologies utilisées : 

Power BI Desktop : pour la visualisation et la modélisation des données

Langage R : utilisé pour le nettoyage des données (traitement des doublons, valeurs manquantes)

CSV Dataset : dataset financier téléchargé depuis Kaggle (plus de 5700 lignes avec indicateurs financiers : Open, Close, High, Low, Volume, Currency, Date)

🔍 Description du projet
Nettoyage en R : chargement des données via read.csv(), vérification et suppression des valeurs manquantes et doublons à l’aide des fonctions is.na() et duplicated()

Exploration des données : création de graphiques temporels pour étudier les périodes de hausse et de baisse du marché de l’or

Analyse temporelle : mise en évidence de trois cycles principaux :

📈 Hausse marquée de 2000 à 2010

📉 Chute entre 2010 et 2020, liée à la stagnation économique et à la pandémie

📈 Reprise fulgurante entre 2020 et 2022

Dashboard Power BI :

Graphiques dynamiques par période

Filtres temporels pour explorer les tendances

Indicateurs financiers : Volume, Prix moyen, Variation

Mise en page interactive et épurée pour faciliter la prise de décision

📈 Résultats & Insights
Identification de corrélations entre événements macroéconomiques (Covid-19, relance économique) et variations du marché de l’or

Capacité à formuler des prédictions basées sur les cycles précédents

Visualisation claire des pics, creux, et transitions de marché pour guider l’analyse de risque

🖼️ Capture d’écran
(Ajouter ici une capture du dashboard Power BI ou un GIF montrant l’interaction avec les filtres)

▶️ Exécution du projet
💻 Prérequis :

Power BI Desktop installé

Environnement R

📁 Démarrage rapide :

Ouvrir le fichier dashboard_or.pbix dans Power BI

Rafraîchir les données pour lancer les scripts R intégrés

👤 Auteur
Mohammed Fassi Fehri

LinkedIn

GitHub

mohammed.fassifehri@outlook.fr

📚 Source des données
Dataset Kaggle : Daily Gold Price Historical Data
