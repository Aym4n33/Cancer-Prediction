# README

## Description
Ce projet utilise plusieurs bibliothèques Python pour effectuer des tâches de **prétraitement des données**, **visualisation**, **modélisation de régression**, et **évaluation des modèles**. Ces outils permettent une analyse efficace des données, une modélisation robuste et une optimisation des hyperparamètres.

---

## Bibliothèques utilisées

### 1. **Manipulation des données**
- **`pandas`** : Manipulation et analyse des ensembles de données structurées, tels que les fichiers CSV ou Excel.
- **`numpy`** : Calcul numérique avec des tableaux et des fonctions mathématiques.

### 2. **Visualisation**
- **`matplotlib.pyplot`** : Visualisation des données sous forme de graphiques et courbes.
- **`seaborn`** : Visualisation statistique avancée et esthétique.
- **`missingno`** : Visualisation des données manquantes.

### 3. **Statistiques**
- **`scipy.stats`** :
  - `pearsonr` : Calcul du coefficient de corrélation de Pearson.
  - `spearmanr` : Calcul du coefficient de corrélation de Spearman.

### 4. **Prétraitement des données**
- **`sklearn.preprocessing.StandardScaler`** : Normalisation des données en les mettant à l'échelle.

### 5. **Modélisation et évaluation**
- **`sklearn.model_selection`** :
  - `train_test_split` : Division des données en ensembles d'entraînement et de test.
  - `GridSearchCV` : Optimisation des hyperparamètres par recherche en grille.
  - `KFold` : Validation croisée avec découpage des données.
- **`sklearn.metrics`** :
  - `r2_score` : Coefficient de détermination (\( R^2 \)).
  - `mean_squared_error` : Erreur quadratique moyenne (MSE).
  - `mean_absolute_error` : Erreur absolue moyenne (MAE).

### 6. **Réduction de dimensionnalité**
- **`sklearn.decomposition.PCA`** : Analyse en composantes principales pour réduire le nombre de variables.

### 7. **Analyse des facteurs d'influence**
- **`statsmodels.stats.outliers_influence.variance_inflation_factor`** : Calcul du facteur d'inflation de variance (VIF) pour détecter la multicolinéarité.

### 8. **Modèles de régression**
- **Régressions d'ensemble** :
  - `RandomForestRegressor`
  - `AdaBoostRegressor`
  - `GradientBoostingRegressor`
- **Autres modèles** :
  - `DecisionTreeRegressor` : Régression basée sur des arbres de décision.
  - `SVR` : Régression par machine à vecteurs de support.
  - `KNeighborsRegressor` : Régression basée sur les \( k \)-plus proches voisins.
  - `MLPRegressor` : Régression par réseaux de neurones multi-couches.
  - `XGBRegressor` : Régression basée sur XGBoost.

---


