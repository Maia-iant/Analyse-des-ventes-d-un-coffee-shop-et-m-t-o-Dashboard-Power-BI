# Analyse des ventes d’un coffee shop et météo – Dashboard Power BI

## 🎯 Objectif du projet

Ce projet a pour objectif d’analyser les ventes quotidiennes d’un coffee shop en les croisant avec des données météorologiques (température, précipitations, vent), afin de comprendre comment la météo, le week‑end et la saisonnalité influencent la performance commerciale.  

Le livrable principal est un **dashboard Power BI interactif** permettant d’aider à la décision (stocks, staffing, pilotage de l’activité).

---

## 🗂 Données utilisées

### Données de ventes

- Chiffre d’affaires quotidien  
- Nombre de transactions  
- Panier moyen  
- Jour de la semaine  
- Indicateur week‑end / semaine  
- Mois, année  

### Données météo

- Températures (min / max)  
- Précipitations  
- Vitesse du vent  
- Code météo / conditions générales  

Les données sont agrégées à la **journée** et alignées sur la même période d’analyse.

---

## 🧹 Méthodologie

### Collecte des données

- Récupération des données de ventes et de la série météo correspondante sur la même période.

### Nettoyage et préparation

- Harmonisation des formats de date  
- Vérification des valeurs manquantes ou aberrantes  
- Création de variables dérivées (jour de la semaine, indicateur week‑end, mois, année, etc.)

### Fusion des sources

- Jointure des données de ventes et des données météo **par date** pour obtenir une table analytique unique.

### Analyse exploratoire

- Étude des tendances de ventes dans le temps  
- Comparaison semaine vs week‑end  
- Analyse par période de l’année (saisonnalité)  
- Première exploration des effets météo (température, pluie, etc.) sur les ventes  

### Modélisation dans Power BI

- Import et modèle de données  
- Création de mesures (CA, transactions, panier moyen, variations, etc.)  
- Mise en place de filtres et segments (dates, météo, périodes, jours de semaine)

### Construction du dashboard

- Page de synthèse avec KPI principaux  
- Visuels temporels (évolution des ventes)  
- Visuels mettant en relation ventes et météo  
- Navigation entre pages pour explorer différents angles d’analyse  

---

## 📊 Dashboard Power BI

Le **dashboard Power BI** permet de :

- Suivre les **KPI clés** : chiffre d’affaires, nombre de transactions, panier moyen  
- Visualiser les **tendances** dans le temps (jour, semaine, mois)  
- Comparer les résultats **semaine vs week‑end**  
- Analyser l’impact de la **météo** (température, pluie…) sur les performances  
- Filtrer facilement pour explorer une période ou une condition météo en particulier  

  
> - https://app.powerbi.com/groups/me/reports/5969815e-e132-405a-bae0-aca1129deaf5/7d1f9dc54a1d24a17a74?experience=power-bi 

---

## 🔑 Résultats clés

- Les **week‑ends** montrent des niveaux de ventes plus élevés que les jours de semaine, ce qui souligne l’importance du trafic client sur ces périodes.  
- Les journées avec une **météo clémente** (températures agréables, peu ou pas de pluie) sont associées à une hausse du chiffre d’affaires.  
- On observe une **forte saisonnalité** : certaines périodes de l’année concentrent une part significative des ventes.  
- Le dashboard Power BI permet d’**anticiper** les besoins en stocks et en personnel en fonction du calendrier et des conditions météo.

---

## ✅ Recommandations

À partir des analyses, plusieurs recommandations opérationnelles peuvent être formulées :

### Adapter les effectifs

- Renforcer le staffing (en caisse, en salle, en production) les week‑ends et sur les périodes historiquement les plus fortes.

### Ajuster les stocks en fonction de la météo

- Anticiper une montée en stock sur les produits les plus demandés lors des journées annoncées comme favorables (temps doux, peu de pluie).

### Intégrer la météo dans la prévision de la demande

- Construire ou améliorer les modèles de prévision en intégrant des variables météo (prévisions à court terme) en plus de l’historique de ventes.

### Utiliser le dashboard comme outil de pilotage

- Consulter régulièrement le dashboard pour suivre les indicateurs, détecter les tendances et ajuster rapidement les décisions opérationnelles.

---

## 🛠️ Stack et compétences mobilisées

**Outils :**

- Power BI (modélisation & visualisation)  
- Python pour la préparation des données  

**Compétences data :**

- Nettoyage et préparation de données  
- Fusion de sources hétérogènes (ventes + météo)  
- Analyse exploratoire  
- Construction de KPI  
- Data visualisation et storytelling métier
