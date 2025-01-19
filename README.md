# Prédiction des Prévalences du Cancer en France à partir des Quantités de Polluants

Ce projet a pour objectif d'analyser les relations entre les niveaux de pollution et les prévalences de différents types de cancer dans les départements français. En utilisant des techniques de science des données et des modèles prédictifs de Machine Learning, cette étude vise à fournir des informations exploitables pour les agences régionales de santé (ARS).


## Contexte
La pollution de l'air et de l'eau représente un défi majeur en France, ayant un impact significatif sur la santé publique, notamment en augmentant les risques de cancers. Ce projet cherche à établir des liens entre les polluants environnementaux et les prévalences des cancers dans les différents départements, en utilisant des données historiques pour prédire ces prévalences et proposer des mesures ciblées.

## Objectifs
1. Identifier les polluants les plus critiques liés aux prévalences des cancers.
2. Prédire les taux de prévalence du cancer dans les départements français.
3. Fournir des outils analytiques pour aider les ARS à optimiser leurs ressources médicales.
4. Soutenir les efforts de sensibilisation et de prévention en matière de santé publique.

## Sources de Données
1. **Données sur les pathologies** : Informations fournies par l'Assurance Maladie, incluant les prévalences de cancers par région et par tranche d'âge.
2. **Données sur la pollution** : Émissions de polluants extraites du Registre Français des Émissions Polluantes.

## Méthodologie
1. **Préparation et Compréhension des Données** :
   - Fusion des datasets de pollution et de santé par département et par année.
   - Nettoyage des données et traitement des valeurs manquantes.
2. **Analyse Exploratoire** :
   - Visualisation des prévalences par département.
   - Étude des corrélations entre les polluants et les cancers en utilisant les coefficients de Spearman et Pearson.
3. **Modélisation** :
   - Test de plusieurs modèles de régression (Arbres de Décision, Random Forest, Gradient Boosting, etc.).
   - Sélection de l'Arbre de Décision pour ses performances et son interprétabilité.
   - Optimisation des hyperparamètres et simplification via post-pruning.

## Résultats
- Identification des polluants les plus associés aux cancers bronchopulmonaires et colorectaux.
- Développement de modèles prédictifs avec des erreurs faibles (MSE et MAE).
- Propositions d'interventions pour réduire les risques liés aux polluants.

## Technologies Utilisées
- **Python** : Pandas, NumPy, Scikit-learn
- **Visualisation** : Matplotlib, Seaborn
- **Modélisation** : Arbres de Décision, Random Forest, Gradient Boosting,...
- **Collaboration** : Google Docs, GitHub
## Contributeurs
- AIT M'BARK Aymane.
- AMAMOU Aya.
- TLILI Ramy.
- BEN HADJ SLAMA Sarra.
