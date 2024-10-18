# JEDHA-Projet-3-Steam


[Databricks project](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5383531717423793/1759678405639776/7944816009331814/latest.html)(available 6 month after april 2024)


# Consignes

# Description de l'entreprise 📇
Steam est un service de distribution numérique de jeux vidéo et une plateforme de vente de Valve. Lancé en septembre 2003 en tant que client logiciel pour fournir des mises à jour automatiques pour les jeux de Valve, il s'est étendu à la distribution de titres tiers à la fin de 2005. Steam propose diverses fonctionnalités telles que la gestion des droits numériques (DRM), le matchmaking des serveurs de jeu avec des mesures anti-triche de Valve, des réseaux sociaux et des services de streaming de jeux. Les fonctions du client Steam incluent l'automatisation des mises à jour de jeu, le stockage cloud pour la progression des jeux et des fonctionnalités communautaires telles que la messagerie directe, les fonctions de superposition en jeu et un marché virtuel de collection d'objets.

# Projet 🚧
Vous travaillez pour Ubisoft, un éditeur de jeux vidéo français. Ils aimeraient sortir un nouveau jeu vidéo révolutionnaire ! Ils vous ont demandé de mener une analyse globale des jeux disponibles sur le marché de Steam afin de mieux comprendre l'écosystème des jeux vidéo et les tendances actuelles.

# Objectifs 🎯
L'objectif ultime de ce projet est de comprendre quels facteurs affectent la popularité ou les ventes d'un jeu vidéo. Mais votre patron vous a demandé de profiter de cette opportunité pour analyser le marché des jeux vidéo à l'échelle mondiale.

Pour mener à bien ce projet, vous devrez adopter différents niveaux d'analyse. Votre patron vous a donné une liste d'exemples de questions qui seraient intéressantes :

## Analyse au niveau "macro"

- Quel éditeur a sorti le plus de jeux sur Steam ?
- Quels sont les jeux les mieux notés ?
- Y a-t-il des années avec plus de sorties ? Y a-t-il eu plus ou moins de sorties de jeux pendant la Covid, par exemple ?
- Comment sont distribués les prix ? Y a-t-il beaucoup de jeux en promotion ?
- Quelles sont les langues les plus représentées ?
- Y a-t-il beaucoup de jeux interdits aux moins de 16/18 ans ?

## Analyse des genres

- Quels sont les genres les plus représentés ?
- Y a-t-il des genres qui ont un meilleur ratio d'avis positifs/négatifs ?
- Certains éditeurs ont-ils des genres préférés ?
- Quels sont les genres les plus lucratifs ?

## Analyse des plateformes

- La plupart des jeux sont-ils disponibles sur Windows/Mac/Linux ?
- Certains genres ont-ils tendance à être préférentiellement disponibles sur certaines plateformes ?

Vous êtes libre de suivre ces lignes directrices ou de choisir un angle d'analyse différent, tant que votre analyse révèle des informations pertinentes et utiles. 🤓

# Portée de ce projet 🖼️
Vous devrez utiliser Databricks et PySpark pour mener cette EDA (Exploratory Data Analysis). En particulier, vous devrez utiliser l'outil de visualisation de Databrick pour créer les visualisations.

Le jeu de données est disponible dans notre bucket S3 de JEDHA.

# Aides 🦮
Pour vous aider à réaliser ce projet, voici quelques conseils qui devraient vous aider :

- Pour adopter différents niveaux d'analyse, il peut être utile de créer différents dataframes.
- Comme le jeu de données a un schéma semi-structuré avec une structure imbriquée, les méthodes de PySpark telles que getField() et explode() peuvent vous aider.
- Il y a des champs texte et date dans ce jeu de données : PySpark offre des fonctions utilitaires pour manipuler ces types de données efficacement 💡
- Vous pouvez utiliser des fonctions d'agrégation et groupBy pour mener des analyses segmentées.

# Livrable 📬
Pour mener à bien ce projet, vous devez livrer :

Un ou plusieurs notebooks comprenant la manipulation des données avec PySpark et la visualisation des données avec l'outil de création de tableaux de bord de Databricks.
