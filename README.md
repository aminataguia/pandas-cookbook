# Modifications apportées au projet

Ce repository contient des modifications apportées aux fichiers de données et aux notebooks dans le cadre de l'analyse des données des Oscars.

## Fichiers CSV

### Données brutes :

- `csv/oscar_age_female_raw.csv` : Données brutes initiales pour les Oscars, catégorie femmes.
- `csv/oscar_age_male_raw.csv` : Données brutes initiales pour les Oscars, catégorie hommes.

### Données traitées :

- `csv/oscar_age_female_processed.csv` : Données nettoyées et traitées pour les Oscars, catégorie femmes.
- `csv/oscar_age_male_processed.csv` : Données nettoyées et traitées pour les Oscars, catégorie hommes.
- `csv/oscar_age_processed.csv` : Fusion des données traitées des catégories femmes et hommes.

### Données supplémentaires :

- `csv/oscar_all_nominations.csv` : Fichier de données fourni initialement.

## Notebooks

### Analyse des nominations :

- `Notebook/all_nomination_analyse.ipynb` : Analyse du fichier `oscar_all_nominations.csv`.

### Analyse des Oscars :

- `Notebook/oscar_analyse.ipynb` : Graphiques et visualisations basées sur les données traitées des Oscars.

### Intégration des données :

- `Notebook/Oscar.ipynb` : Combinaison des données brutes et mise à jour avec des informations provenant de Wikipedia.

### Nettoyage des données :

- `Notebook/cleaned_oscar.ipynb` : Commandes utilisées pour nettoyer les données brutes.
