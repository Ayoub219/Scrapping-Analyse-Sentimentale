# Performance des Vendeurs & Analyse Sentimentale

## Description

Ce projet porte sur l'analyse de la performance des vendeurs et l'analyse sentimentale des commentaires clients dans l'industrie des montres. L'objectif est d'extraire des informations sur la performance des vendeurs et la satisfaction des clients, en utilisant des techniques d'analyse de données avancées et d'analyse sentimentale.

Le projet inclut :
- Le scraping des données à partir de différentes sources.
- Le nettoyage et la structuration des données.
- La réalisation d'une analyse globale et d'une analyse sentimentale des commentaires clients.
- La création de tableaux de bord pour visualiser les résultats.

## Structure du projet

1. **Introduction & Problématique** :  
   L'industrie de la vente de montres doit se tenir à jour avec les dernières avancées technologiques pour répondre aux attentes des consommateurs. L'analyse des commentaires des clients et la surveillance des performances de vente sont cruciales pour optimiser la production et améliorer la satisfaction des clients.

2. **Jeu de données** :
   - **Table Vendeurs** : Inclut des attributs comme le nom du vendeur, le nombre de commentaires, les notes globales, et les scores de livraison.
   - **Table Commentaires** : Inclut les commentaires des acheteurs, le nom de la marque, le degré de sentiment, et si le commentaire est positif, neutre ou négatif.

3. **Nettoyage & Structuration des données** :
   - Scraping des noms de marques avec `BeautifulSoup` et correspondance avec le dataset.
   - Utilisation de jeux de données externes pour compléter les marques manquantes.

4. **Analyse Globale** :
   - Analyse de la performance des vendeurs par pays, en se concentrant sur des indicateurs clés comme la communication, la livraison, et la description des produits.

5. **Analyse Sentimentale** :
   - Traduction des commentaires en anglais avec l'API Google Translate.
   - Attribution des scores de sentiment avec la bibliothèque `TextBlob`.
   - Classification des commentaires en positifs, neutres, et négatifs.
   - Visualisation de la répartition des sentiments à l'aide de nuages de mots et de graphiques.
