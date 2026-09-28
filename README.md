# Frog Biodiversity Prediction

Prédiction de la présence d'espèces de grenouilles en Australie à partir de coordonnées géographiques et de variables climatiques TerraClimate.

## Objectif

Prédire `Occurrence Status` pour des points d'observation à partir de données GBIF et de variables climatiques extraites du Microsoft Planetary Computer.

## Méthodes

- extraction de variables raster TerraClimate ;
- feature engineering spatial et climatique ;
- analyse exploratoire et visualisation ;
- régression logistique, Random Forest, XGBoost et LightGBM ;
- gestion du déséquilibre avec SMOTE ;
- évaluation avec F1-score et rapports de classification.

## Structure

- `data/raw/` : données d'observations et de test ;
- `data/interim/` : raster TerraClimate utilisé pour l'extraction ;
- `notebooks/` : benchmark, solutions et extraction climatique ;
- `submissions/` : prédictions produites et variantes ;
- `docs/` : documentation du challenge ;
- `requirements.txt` : dépendances Python.

Les notebooks doivent être ouverts depuis leur emplacement dans `notebooks/`. Les chemins relatifs pointent vers `../data/` et `../submissions/`.
