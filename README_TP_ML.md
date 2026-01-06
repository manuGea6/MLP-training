# TP ML – Notebook complété (solution)

Ce dossier contient une version **complétée et exécutable** du notebook `ml.ipynb` (TP Machine Learning / bases de réseaux de neurones).

## Contenu
- `tp_ml_solution.ipynb` : notebook complété (fonctions manquantes, utilitaires d'algèbre linéaire en Python pur, corrections mineures)
- `requirements.txt` : dépendances minimales
- `README_TP_ML.md` : ce fichier

## Prérequis
- Python 3.9+ recommandé

## Installation
```bash
pip install -r requirements.txt
```

## Lancement
```bash
jupyter notebook tp_ml_solution.ipynb
```

## Points complétés/corrigés
- Classifieur linéaire : `pred_linear`
- Métrique : `accuracy`
- Outils matrices/vecteurs (Python pur) : `dot_product`, `transpose`, `matrix_multiplication`, etc.
- Couche forward : `forward_layer` (calcul `XW + b`)

> Note : le notebook conserve l'approche pédagogique « sans NumPy pour les matrices » pour la partie réseau de neurones (produits matriciels en listes), tout en acceptant des entrées NumPy provenant de `sklearn` (conversion ligne par ligne).
