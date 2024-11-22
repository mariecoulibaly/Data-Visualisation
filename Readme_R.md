# Analyse des données du marché du logement avec R  
Ce projet explore les données du marché immobilier à l'aide de **R** en appliquant des analyses exploratoires, 
des visualisations, des tests d'hypothèses, et des régressions linéaires. 
L'objectif est de comprendre les relations entre différentes variables du marché immobilier pour fournir des insights exploitables.

## 📝 Contenu du projet  
### 1. **Analyse exploratoire des données (EDA)**  
   - Chargement et exploration des données.  
   - Calcul de statistiques descriptives (moyennes, médianes, modes, etc.).  
   - Création d'une matrice de corrélation pour identifier les relations entre les variables.  
   - Imputation des données manquantes à l'aide de la moyenne.

### 2. **Visualisations des données**  
   - Histogrammes pour visualiser la distribution des prix médians des logements.  
   - Graphiques construits avec **ggplot2** pour une représentation claire et esthétique des données.  

### 3. **Tests d'hypothèses**  
   - Test t de Student pour comparer les prix médians des logements entre zones à forte et faible criminalité.  
   - Conclusion : Pas de différence significative trouvée entre les deux groupes.

### 4. **Régressions linéaires**  
   - Modélisation de la relation entre le nombre moyen de pièces et la valeur médiane des logements.  
   - Résultats principaux :  
     - Une augmentation du nombre moyen de pièces entraîne une hausse significative du prix médian.  
     - Le modèle présente un coefficient de détermination élevé (R² ≈ 0,76), suggérant une bonne capacité prédictive.  

### 5. **Interprétation des résultats**  
   - Les prix des maisons sont influencés principalement par leur taille, mais d'autres facteurs comme l'accès aux transports et la qualité des écoles jouent également un rôle.  
   - Suggestions pour améliorer les analyses futures en intégrant des variables qualitatives telles que l'emplacement exact ou la qualité des infrastructures.

## 🔗 Plus de détails  
Pour une présentation complète et le code utilisé, consultez le [rapport PDF](./PROJET_1_R.pdf)
