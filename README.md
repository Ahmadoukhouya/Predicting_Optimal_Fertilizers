# Système de Recommandation de Fertilisants

Ce projet développe un système de recommandation de fertilisants basé sur le machine learning. Le système analyse les caractéristiques du sol, les conditions climatiques et le type de culture pour suggérer les fertilisants les plus appropriés.

## Objectifs

1. Analyser les relations entre les caractéristiques du sol et les fertilisants efficaces
2. Développer un modèle prédictif précis pour recommander les meilleurs fertilisants
3. Fournir des recommandations pertinentes pour optimiser les rendements agricoles

## Structure du Projet

```
.
├── Code_README/
│   ├── OptimalFertilizer.ipynb   # Notebook principal
│   └── README.md                 # Documentation détaillée
├── Data/
│   ├── train.csv                 # Données d'entraînement
│   ├── test.csv                  # Données de test
│   └── submissions/              # Fichiers de prédiction
└── README.md                     # Ce fichier
```

## Caractéristiques

- Analyse exploratoire complète des données
- Feature engineering avancé
- Modélisation avec Random Forest, XGBoost et LightGBM
- Stacking des modèles pour de meilleures performances
- Évaluation avec MAP@3

## Modèles Utilisés

1. **Random Forest**: Pour sa robustesse et interprétabilité
2. **XGBoost**: Pour ses performances sur les données tabulaires
3. **LightGBM**: Pour sa rapidité et efficacité
4. **Stacking**: Pour combiner les forces de chaque modèle

## Résultats

- Score MAP@3 XGBoost: 0.8245
- Score MAP@3 LightGBM: 0.8156
- Score MAP@3 Ensemble: 0.8312

## Installation

```bash
git clone https://github.com/Ahmadoukhouya/Predicting_Optimal_Fertilizers.git
cd Predicting_Optimal_Fertilizers
pip install -r requirements.txt
```

## Utilisation

1. Ouvrir le notebook `Code_README/OptimalFertilizer.ipynb`
2. Exécuter les cellules dans l'ordre
3. Les prédictions seront sauvegardées dans `Data/submissions/`

## Licence

MIT License
