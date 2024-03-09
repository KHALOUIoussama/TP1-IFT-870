# Rapport TP1 : Quantitative Structure-Activity Relationship (QSAR)

## Description

Ce dossier rend compte du travail demandé pour le TP1 concernant le Quantitative Structure-Activity Relationship (QSAR), mettant en application la science des données pour déterminer les classes de molécules étudiées.

## Utilisation et exécution

### Fichiers du dossier

Voici la liste des fichiers contenu dans ce dossier

- **Datasets**:

  - **clean_QSAR_dataset.xlsx** : fichier nettoyé de QSAR_dataset.xlsx
  - **QSAR_dataset.xlsx** : Données de base utilisées pour ce rapport
  - **test_TP1.xlsx** : Échantillons de données dont on doit déterminer la classe

- **Src**:
  - **Groupe11_tp1.ipynb** : Rapport du TP1 contenant les réponses aux questions de l'énoncé
  - **model.py** : Fichier python utilisé pour la distribution gaussienne
- **README.md**
- **requirements.txt** : Fichier contenant les pckages nécessaires pour installer l'environnement d'exécution du code

### Installation du package

Le fichier requirements.txt contenant les packages, pour installer ces derniers il suffit d'éxécuter le code suivant :

```
pip install -r requirements.txt
```

### Execution du programme

- Lancer l'exécution du fichier **Groupe11_tp1.ipynb**

## Authors

Chakiya AHAMADA (ahac1101)\
Oussama KHALOUI (khao1201)\
Matthieu TAILLEUR (taim1201)\
Caroline WANG (wanc1101)\

**Lien git :** https://github.com/KHALOUIoussama/TP1-IFT-870.git

## Références

Références utilisées dans ce rapport

1. https://stefvanbuuren.name/fimd/sec-MCAR.html
2. https://medium.com/analytics-vidhya/different-types-of-missing-data-59c87c046bf7
3. https://www.datacamp.com/tutorial/techniques-to-handle-missing-data-values
4. https://scikit-learn.org/stable/modules/generated/sklearn.impute.KNNImputer.html
5. https://www.linkedin.com/advice/3/what-most-effective-distance-metrics-optimizing-xndwc
6. https://medium.com/@Kavya2099/optimizing-performance-selectkbest-for-efficient-feature-selection-in-machine-learning-3b635905ed48#:~:text=SelectKBest%20is%20a%20type%20of,score%20and%20rank%20the%20features.
