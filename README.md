# 📊 Analyse RH : Répartition Hommes/Femmes par département, âge et niveau hiérarchique

## 🎯 Objectif 
Analyser la parité hommes/femmes dans une entreprise selon trois dimensions :
- Département
- Tranche d'âge
- Niveau hiérarchique

Ce projet s'inscrit dans une démarche RH visant à mieux comprendre les déséquilibres et à formuler des recommandations concrètes.

---

## 🧰 Outils utilisés
- Python (Pandas, Matplotlib)
- Power BI
- Powerpoint

---

## 🛠️ Etapes du projet 

### 1. **Préparation des données**
- Nettoyage d'un fichier CSV (Valeurs manquantes, types, doublons)
- Suppression des colonnes inutiles
- Création de variables :
  - 'TrancheAge' : Jeune (18-30), Adulte (31-45), Senior (46-60)
  - 'Ville' (pour cartographie)
 
### 2. **Analyse exploratoire**
- Vérification des corrélations entre variables
- Détection de valeurs aberrantes par boîte à moustaches
- Calcul des KPIs : effectif total, moyenne d'âge, % de femmes

### 3. **Visualisation**
- Création d'un tableau de bord Power BI dynamique :
  - Répartition H/F par département
  - Par tranche d'âge
  - Par niveau hiérarchique
  - Cartographie par ville
 
---

## 🔍 Résultats clés 

- **Parité global** : 50,72 % de femmes / 49,3 % d'hommes
- **Déséquilibres** selon les départements :
  - Plus d'hommes dans les départements techniques (Hardware, Software, R&D)
  - Plus de femmes dans les RH et le support
- **Tranche d'âge dominante** : 31-45 ans
- **Hiérarchie** : légère surreprésentation féminine au niveau managérial

---

## 💡 Recommandation Rh

- Suivre la parité dans les promotions et formations
- Favoriser la mixité dans les services genrés
- Mettre en place un tableau de bord RH mis à jour régulièrement

---

## 📁 Contenu du dépot

| Fichier/Dossier              | Description                                          |
|------------------------------|------------------------------------------------------|
| 5000_HRA _Records            | Dataset original                                     |
| dataset_rh_analyse_complet   | Données préparées après traitement                   |
| Projet_Final.ipynb           | Code Python (nettoyage, analyse, création variables) |
| Screenshots                  | Visuels du tableau de bord Power BI                  |
| Rapport_soutenance           | Résumé des résultats et recommandations              |
| README.md                    | Présentation complète du projet                      |

---

## Source des données
Dataset IBM RH :
[IBM HR Analytics Dataset - Excel BI Analytics (2021)](https://excelbianalytics.com/wp/downloads-21-sample-csv-files-data-sets-for-testing-till-5-million-records-hr-analytics-for-attrition/)

---

*Projet réalisé dans le cadre de la formation Data Analyst - DataSuits / Certification Panthéon Sorbonne*
*Amen BOUMEDIENE - 2025*
