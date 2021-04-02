# Cultura Scraping

## Sujet
Parcourir les indispensables à petits prix [IKEA](https://www.ikea.com/fr/fr/campaigns/les-indispensables-a-petits-prix-pub0d9cd6c0?icid=fr|20210315|menu|indispensables).

Pour chaque `indispensables` de la page :
- Cliquer sur le lien
- Récupération des éléments *(maximum 100)*
    - Nom
    - Description
    - Note *(si existante)*
    - Prix
    - Nombre d'avis
- Retour à la page des `indispensables` pour le prochain lien

## Installation
!pip install seaborn

Avec Anaconda : ouvrir anaconda prompt et executer : "conda install -c conda-forge selenium" \
Avec le gestionnaire de package pip:  pip install selenium

Télécharger webdriver: https://chromedriver.chromium.org/downloads . \ 
Rangez-le dans un dossier et rajoutez le path du fichier chromedriver.exe dans vos variables d'environnement système (puis redémarrer).

## Pour l'affichage et la visualisation:
- [Pyplot](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html) , [Seaborn](https://seaborn.pydata.org/introduction.html) *PANDAS*