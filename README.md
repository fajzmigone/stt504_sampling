# STT504 - Théorie des Sondages / Survey Theory

Ce dépôt contient les ressources du cours STT504 - Théorie des Sondages de l'Université Soumaré. Il couvre les aspects théoriques et pratiques des méthodes d'échantillonnage et d'analyse de données d'enquête.

## Structure du Cours (2025)

### Théorie et Concepts Fondamentaux
1. Sondage stratifié 
   - Concepts et principes
   - Allocation optimale
   - Estimation et variance

2. Sondage à probabilités inégales
   - Méthodes de sélection
   - Estimateurs et leurs propriétés
   - Applications pratiques

3. Sondage à plusieurs degrés
   - Conception et mise en œuvre
   - Estimation des paramètres
   - Considérations pratiques

### Méthodes Avancées d'Analyse
1. Estimation de la variance par linéarisation
   - Techniques de linéarisation
   - Applications aux enquêtes complexes

2. Pseudo-vraisemblance en sondage complexe
   - Théorie et concepts
   - Applications pratiques

3. Analyse de données catégorielles avec enquêtes
   - Méthodes spécifiques
   - Traitement des données qualitatives

4. Régression dans les enquêtes complexes
   - Modèles adaptés
   - Interprétation des résultats

### Aspects Pratiques
- Non-réponse et redressement
- Traitement des données manquantes
- Méthodes de correction et d'ajustement

## Ressources Complémentaires

- Compositions et examens (Term 1)
- Corrections détaillées
- Supports de cours et présentations

## Ressources Années Précédentes

Pour accéder aux ressources de l'année 2025, veuillez consulter [ce lien](https://drive.google.com/drive/folders/1pIxl006PqexmSK4P1N-PGzMDBx3trPgJ?usp=sharing).

## Contact

Pour toute question ou clarification, n'hésitez pas à ouvrir une issue dans ce dépôt ou à contacter directement les enseignants.

## Outils Informatiques et Implémentation

### R
- **survey** : Package principal pour l'analyse de données d'enquêtes complexes
  - Gestion des plans de sondage (`svydesign`)
  - Estimation de totaux, moyennes, ratios (`svytotal`, `svymean`, `svyratio`)
  - Régression pour données d'enquête (`svyglm`)
- **sampling** : Sélection d'échantillons et calcul de poids
  - Tirage d'unités (`srswor`, `srswr`, `pps`)
  - Stratification (`strata`)
- **Calibration** : Calibration des poids d'échantillonnage
  - `Rgenesees`
- **tidyverse** : Pour la manipulation et visualisation des données

### Python
- **scipy.stats** : Fonctions statistiques de base
- **statsmodels** : 
  - Modèles de régression adaptés aux données d'enquête
  - Gestion des poids d'échantillonnage
- **pandas** : 
  - Manipulation des données d'enquête
  - Calculs avec poids de sondage (`weighted_mean`, `weighted_sum`)

Les codes et exemples pratiques sont disponibles dans les notebooks Jupyter et scripts R correspondant à chaque chapitre.

## Licence

Ce matériel est fourni à des fins éducatives. Tous droits réservés.