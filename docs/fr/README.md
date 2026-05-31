# Data Science Labs

## Vue d'ensemble

Ce dépôt est un laboratoire central d'études en analyse de données, statistique, science des données et machine learning. Les contenus sont des labs pédagogiques et des exercices pratiques, pas des projets professionnels prêts pour la production.

Le contenu des notebooks existants a été préservé sans modification.

## Structure

```text
notebooks/
├── pandas/
├── numpy/
├── statistics/
├── visualization/
├── machine-learning/
└── deep-learning/
datasets/
└── numpy/
```

## Études disponibles

### Pandas

[`notebooks/pandas/tratamento_enem_2019.ipynb`](../../notebooks/pandas/tratamento_enem_2019.ipynb) est un lab sur le traitement et l'exploration initiale des microdonnées ENEM 2019 avec pandas et NumPy.

Le notebook dépend d'un fichier externe `microdados_enem_2019_sp.csv` qui n'est pas versionné dans ce dépôt.

### NumPy

[`datasets/numpy/`](../../datasets/numpy/) contient des datasets de support pour les études NumPy :

- `apples_ts.csv`
- `bytebank.csv`
- `citrus.csv`

Les fichiers ont été réorganisés sans modification de contenu.

### Domaines préparés

Des dossiers sont prêts pour de futurs labs en statistique, visualisation, machine learning et deep learning.

## Exécution des labs

```bash
pip install -r requirements.txt
jupyter notebook
```

Exécutez les notebooks depuis la racine du dépôt et vérifiez les éventuels datasets externes requis.

## Directives

- Classez les notebooks selon le sujet principal d'apprentissage.
- Conservez les notebooks comme traces pédagogiques.
- N'inventez pas de résultats ou de conclusions.
- Ne versionnez pas de datasets sensibles, d'identifiants ou de fichiers locaux.
- Documentez les dépendances externes nécessaires à la reproduction d'un lab.
