# Crunching_de_data
Projet de traitement de données et de visualisation avec Python, Pandas.

## Contexte et objectifs
Le projet a pour objectif d'explorer et d'analyser un historique de tickets de transport (train, bus, covoiturage) afin de :

* analyser les prix et durées des trajets
* comparer les modes de transport selon la distance
* identifier des tendances et incohérences dans les données
* proposer des analyses et visualisations pertinentes

## Outils utilisés
* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* (Bonus) Plotly, Scikit-learn

## Données
* cities.csv
* providers.csv
* stations.csv
* ticket_date.csv

## Mise en place de l'environnement

### Etapes de configuration de l'environnement local

#### 1. Création de l'environnement virtuel.
Cela permettra de gérer les dépendances lié au projet:

python -m venv myenv
ou
python3 -m -m venv myenv

Activation de l'environnement virtuel:
Sur Windows :
myenv\Scripts\activate

Sur macOS/Linux:
source myenv/bin/activate

Pour désactiver l'environnement virtuel:
Sur Windows:
myenv\Scripts\deactivate.bat

Sur macOS/Linux:
deactivate

#### 2. Installation des bibliothèques nécessaires
Avec l'environnement virtuel activé, intaller les bibliothèques du fichier requirements.txt:
pip install -r requirements.txt

##### Bibliothèques
###### Manipulation de données
*pandas* - Structure les données en tableaux (DataFrames), lit/écrit CSV/Excel, nettoie, filtre, groupe, pivote. 
*numpy* - Calculs numériques rapides sur tableaux multidimensionnels, base de pandas et scikit-learn.
*plotly* - Graphiques interactifs (zoom, hover, partage web)

###### Visualisation
*matplotlib* - Crée tous types de graphiques (lignes, barres, histogrammes, scatter plots)


###### Machine Learning
*scikit-learn* - Prédictions de prix, clustering, régression

###### Jupyter
*jupyter* - Lance Jupyter Notebook 
*ipykernel* - Noyau Python pour Jupyter (nécessaire pour exécuter du code Python dans les cellules notebook)


#### 3. Création d'un Jupyter Notebook
Créer un fichier Jupyther Notebook dans l'éditeur de code:
    Dans VS Code, créer un nouveau fichier et sauvegarder le fichier avec une extension .ipynb


## Auteur
Hajatiana Rabemananjara
