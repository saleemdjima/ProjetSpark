# Big data: A spark project and transfer learning project with keras

## Projet Spark : Prévision de trafic

Ce projet vise à analyser (catégorie de titre, fluctuation du trafic, impact du confinement) le trafic sur le réseau ferré de la région île-de-France en utilisant Apache Spark pour analyser des données de validation de titres de transport. Dans la suite, nous essayons de modéliser le trafic dans les 7 prochinas jours. 

## Objectifs

1. **Collecte des données** : Récupérer et traiter des données de validation quotidiennes provenant du portail Open Data de Mobilités île-de-France.
2. **Analyse préliminaire** : Explorer les données pour constituer un historique de 2019 à 2021.
3. **Préparation et traitement** : Nettoyer et préparer les données pour la modélisation.

## Prérequis

- **Python 3.7+**
- **Apache Spark** (PySpark)
- Google Colab ou une installation locale avec les modules nécessaires
- Accès à Internet pour télécharger les données

## Analyse des données

### Exploration initiale
- Identifier les colonnes disponibles et leurs types.
- Détecter les valeurs manquantes ou anomalies.

### Constitution d’un historique
- Fusionner les données des semestres pour créer un ensemble complet.

### Statistiques descriptives
- Calculer les moyennes, médianes et tendances des validations.

## Conclusion

Ce projet démontre l'utilisation d'Apache Spark pour analyser des volumes importants de données et extraire des informations pertinentes sur le trafic.