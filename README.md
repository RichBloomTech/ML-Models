---

# Prédiction de la DREN d'un Établissement Scolaire Secondaire en Côte d'Ivoire

Ce projet utilise un modèle de machine learning pour prédire la Direction Régionale de l'Éducation Nationale (DREN) d'un établissement scolaire en se basant sur des caractéristiques disponibles dans le dataset.

## Dataset

Le dataset utilisé pour ce projet est open source et peut être consulté [ici](https://data.gouv.ci/datasets/liste-detablissements-scolaires-dabidjan-etab-ci). Il contient des informations sur les établissements secondaires en Côte d'Ivoire, y compris :

- Nom d'établissement
- Situation géographique
- DREN
- Statut
- Type

### Prétraitement des Données

Les données contiennent des valeurs manquantes dans les colonnes **Situation géographique** et **Type**, qui ont été traitées avant l'entraînement du modèle.

## Modèle

Le modèle utilisé pour la prédiction est une régression logistique optimisée. Les étapes d'entraînement incluent :

1. Nettoyage des données
2. Encodage des variables catégorielles
3. Séparation des données en ensembles d'entraînement et de test
4. Entraînement du modèle avec validation croisée
5. Évaluation des performances du modèle

### Performance du Modèle

Le modèle a atteint une précision de **93%** lors de l'évaluation sur l'ensemble de test.

## Comment Utiliser

1. Clonez le dépôt.
2. Assurez-vous d'avoir installé les dépendances nécessaires (voir `requirements_DREN.txt`).
3. Exécutez le notebook Jupyter pour effectuer des prédictions sur de nouveaux établissements.

## Contribuer

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une demande de tirage (pull request).
