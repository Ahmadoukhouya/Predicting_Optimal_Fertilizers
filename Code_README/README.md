# Optimal Fertilizer Recommendation System

## 📝 Description
Un système de recommandation intelligent basé sur le Machine Learning pour suggérer les fertilisants optimaux en fonction des caractéristiques du sol, des conditions climatiques et du type de culture.

## 🎯 Objectifs
- Analyser les relations sol-fertilisant
- Prédire les 3 meilleurs fertilisants recommandés
- Optimiser les rendements agricoles
- Réduire le gaspillage de fertilisants

## 🔧 Technologies Utilisées
- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- XGBoost, LightGBM
- Matplotlib, Seaborn

## 📊 Dataset
Le dataset contient les features suivantes :
- **Caractéristiques du sol**: N, P, K
- **Conditions climatiques**: Température, Humidité, Moisture
- **Catégories**: Type de Sol, Type de Culture
- **Target**: Nom du Fertilisant

## 🚀 Installation

```bash
git clone https://github.com/Ahmad-Oukhouya/optimal-fertilizer.git
cd optimal-fertilizer
pip install -r requirements.txt
```

## 💻 Structure du Projet
```
optimal-fertilizer/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   ├── Import_CleanData.ipynb
│   └── OptimalFertilizer.ipynb
│
├── requirements.txt
└── README.md
```

## 📈 Modélisation
1. **Preprocessing**
   - Encodage des variables catégorielles
   - Standardisation des variables numériques
   - Feature engineering (ratios NPK)

2. **Modèles utilisés**
   - Random Forest (MAP@3: 0.7534)
   - XGBoost (MAP@3: 0.8245)
   - LightGBM (MAP@3: 0.8156)
   - Stacking Ensemble (MAP@3: 0.8312)

## 📊 Résultats
- Performance finale (MAP@3): 0.8312
- Meilleure précision pour les sols équilibrés
- Bonne généralisation sur différents types de cultures
- Robustesse aux conditions climatiques variées

## 🔍 Features Importantes
1. Ratio N/P
2. Humidité du sol
3. Type de sol
4. Température

## 🤝 Comment Contribuer
1. Fork le projet
2. Créez votre branche (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📝 License
Ce projet est sous licence MIT - voir le fichier [LICENSE.md](LICENSE.md) pour plus de détails.

## ✨ Auteurs
- Ahmad Oukhouya - [@Ahmad-Oukhouya](https://github.com/Ahmad-Oukhouya)

## 🙏 Remerciements
- Remerciements à la communauté ML
- Sources des données
- Contributeurs du projet

## 📞 Contact
- Email: oukhouyaahmad@gmail.com
- LinkedIn: [Ahmad Oukhouya](https://linkedin.com/in/ahmad-oukhouya)
- Téléphone: +212762305512
- Twitter: [@votretwitter](https://twitter.com/votretwitter)
