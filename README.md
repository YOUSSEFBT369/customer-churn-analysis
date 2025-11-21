# **📊 SYSTÈME DE PRÉDICTION ET ANALYSE DE LA DÉSAFFECTION CLIENT**

## **🎯 Aperçu du projet**
Un système avancé de machine learning pour prédire et analyser la désaffection client avec une précision de 80%+. Ce projet complet de data science transforme les données brutes clients en insights actionnables pour les entreprises de télécommunications.

## **📈 Impact Métier**
- **Prédire** la désaffection client 30 jours à l'avance avec haute précision
- **Identifier** les facteurs clés de churn pour optimiser les stratégies de rétention
- **Réduire** le taux d'attrition grâce à des actions ciblées et personnalisées
- **Optimiser** les campagnes marketing et l'allocation des ressources client

## **🏆 Résultats Clés & Performance**
- **Précision du modèle :** 80%+ en prédiction de la désaffection
- **Échelle des données :** Analyse de 7,043+ clients télécom
- **Feature Engineering :** 15+ fonctionnalités élaborées incluant comportement, contrat et facteurs démographiques
- **Prédicteurs principaux :** Ancienneté client, type de contrat, support technique identifiés comme facteurs critiques

## **📁 Structure du projet**

customer-churn-analysis/
├── 📓 analyse_churn_clients.ipynb      # Analyse complète & pipeline ML
├── 📊 churn_analysis_results.csv       # Dataset enrichi (7K+ clients)
├── 📁 data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset original
└── 📋 README.md                        # Documentation du projet


## **🚀 Démarrage Rapide**

### **Prérequis**
- Python 3.8+
- Jupyter Notebook ou Google Colab

### **Installation et utilisation**
1. **Téléchargez** tous les fichiers du projet
2. **Lancez l'analyse :** Ouvrez `analyse_churn_clients.ipynb` dans Jupyter/Colab
3. **Exécutez** toutes les cellules pour reproduire l'analyse complète
4. **Explorez** les résultats et recommandations business

## **🔬 Architecture Technique**

### **Pipeline de Données**

Données Brutes → Nettoyage → Feature Engineering → Entraînement Modèle → Prédiction → Insights Business


### **Stack Machine Learning**
- **Cadre de référence :** Scikit-learn
- **Algorithme :** Classificateur Random Forest
- **Feature Engineering :** Encodage one-hot, sélection de variables, traitement des valeurs manquantes
- **Validation :** Validation croisée avec échantillonnage stratifié

### **Caractéristiques Clés Analysées**
- **Démographiques :** Âge, situation familiale, localisation
- **Contrat :** Type, durée, modalités de paiement
- **Comportementales :** Ancienneté, services souscrits, historique des charges
- **Support :** Accès au support technique, sécurité en ligne

## **📈 Performance du Modèle**

| Métrique | Score | Interprétation Métier |
|----------|-------|----------------------|
| **Précision** | 80%+ | Prédictions de désaffection fiables |
| **Précision (Précision)** | 79%+ | Faible taux de faux positifs |
| **Rappel (Recall)** | 83%+ | Capturer la majorité des désaffections réelles |
| **Importance des fonctionnalités** | Ancienneté (45%) | La fidélité client est le facteur clé |

## **🛠 Technologies utilisées**
- **Traitement des données :** Pandas, NumPy
- **Apprentissage automatique :** Scikit-learn
- **Visualisation :** Matplotlib, Seaborn
- **Environnement :** Jupyter Notebook, Google Colab

## **👨‍💻 Auteur**
**youssef** - Data Analyst & Machine Learning Engineer**  
Transformer les données clients en stratégies de rétention efficaces

## **📄 Licence**
Ce projet est disponible pour des usages académiques et de recherche. Pour une utilisation commerciale, veuillez contacter l'auteur.

