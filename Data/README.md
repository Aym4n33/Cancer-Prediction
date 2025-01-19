# Bases de Données Utilisées

Ce projet s'appuie sur deux bases de données principales, combinées pour analyser les relations entre la pollution et les prévalences des cancers dans les départements français.

## 1. **Données de Pathologies**
- **Source** : Assurance Maladie.
- **Contenu** :
  - Effectifs de patients atteints de diverses pathologies (cancers, maladies respiratoires, etc.).
  - Répartition par département, sexe, classe d'âge, et année.
  - Prévalence des pathologies en pourcentage.
- **Objectif** : Fournir une vue précise des impacts sanitaires dans chaque région.
- **Taille** : ~4,6 millions de lignes.
- **Nettoyage** : Gestion des valeurs manquantes (notamment pour certaines sous-catégories de pathologies).

## 2. **Données de Pollution**
- **Source** : Registre Français des Émissions Polluantes.
- **Contenu** :
  - Quantités de polluants émis par département, milieu (air, eau, sol), et type de polluant (CO₂, NH₃, etc.).
  - Informations géographiques et industrielles liées aux émissions.
- **Objectif** : Identifier les polluants critiques et analyser leur impact sur la santé publique.
- **Taille** : ~139 000 lignes.
- **Nettoyage** : Gestion des doublons, normalisation des unités, et traitement des valeurs manquantes.

## Fusion des Données
Les deux bases ont été fusionnées sur la base des départements et des années pour relier les quantités de polluants émises à la prévalence des pathologies. Cette approche permet d'exploiter la relation temporelle entre pollution et santé en considérant un délai de 8 à 10 ans entre l'exposition aux polluants et l'apparition des maladies.

---
## Liens vers les Datasets
Lien 1:  
Lien 2:

