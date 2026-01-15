# Supply Chain Performance Dashboard

## 🎯 Business Context
L'objectif principal de ce projet est d'optimiser l'efficacité opérationnelle de la chaîne logistique. Le focus est mis sur deux axes majeurs :
1. **Réduction du Lead Time** : Diminuer l'écart entre la date de commande et la date de livraison réelle.
2. **Optimisation de la Rentabilité** : Analyser et maximiser le profit généré par article.

## 📊 KPIs & DAX
Voici les principaux indicateurs de performance développés :
* **Total Sales** : Somme globale du chiffre d'affaires.
* **Total Profit** : Marge nette réalisée.
* **Total Orders** : Volume total des commandes traitées.
* **Late Delivery Rate** : Pourcentage de commandes livrées après la date promise.
* **Suspected Fraud Count** : Identification des transactions à risque.
* **Shipping Analysis** : Analyse des dates d'expédition pour identifier les goulots d'étranglement.

## 🛠️ Data Cleaning (Power Query)
Le nettoyage a été effectué pour garantir l'intégrité des données logistiques :
* **Gestion des types de données** : Conversion des formats de date pour les calculs de durée de livraison.
* **Traitement des valeurs manquantes** : Suppression ou imputation des données de livraison incomplètes.
* **Standardisation** : Harmonisation des noms de produits et des catégories de transport.
* **Calcul des délais** : Création de colonnes personnalisées pour mesurer l'écart entre commande et livraison.

## 🚀 Tools Used
* **Power BI** (Power Query & DAX)
* **Excel** (Source de données brute)
