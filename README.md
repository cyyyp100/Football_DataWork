# Football Data Work

Ce dépôt organise les ressources du projet d'analyse de données footballistiques dans une structure claire et extensible.

## Structure du projet

- `notebooks/` : cahiers Jupyter pour l'exploration et la modélisation.
  - `Code_Etude_technique-1.ipynb` : étude technique principale.
- `src/` : scripts Python et modules applicatifs (à créer au besoin).
- `data/`
  - `raw/` : jeux de données bruts ou importés.
  - `processed/` : jeux de données transformés prêts pour la modélisation.
- `code/` et `DataEtMonCode/` : sous-modules historiques contenant du code ou des données externes.

## Prise en main

1. Créez un environnement Python (par exemple via `venv` ou `conda`).
2. Installez les dépendances nécessaires aux notebooks (pandas, numpy, matplotlib, scikit-learn, etc.).
3. Lancez Jupyter Lab ou Notebook :
   ```bash
   jupyter lab
   ```
4. Ouvrez les notebooks dans le dossier `notebooks/` pour reproduire l'analyse.

## Bonnes pratiques

- Conservez les données sources dans `data/raw/` et n'ajoutez pas de fichiers volumineux (>100 Mo) au dépôt.
- Placez vos scripts réutilisables dans `src/` et importez-les dans les notebooks pour garder un code clair.
- Utilisez des branches thématiques pour développer de nouvelles fonctionnalités et documentez vos modifications dans le présent fichier.

