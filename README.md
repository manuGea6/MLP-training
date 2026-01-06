# TP MLP — Perceptron Multicouche

## Objectif
Ce TP a pour objectif de comprendre le fonctionnement d’un **réseau de neurones multi-couches (MLP)** en implémentant explicitement les différentes étapes d’un modèle de classification simple, depuis la prédiction jusqu’à l’entraînement.

Le TP met l’accent sur la compréhension du **rôle de l’entraînement** dans l’amélioration des performances du modèle.

---

## Contenu du TP

Le TP s’appuie sur un notebook Python dans lequel sont implémentées et manipulées les étapes suivantes.

---

## 1. Modèle MLP

- Définition d’un perceptron multicouche composé :
  - d’une couche d’entrée,
  - d’une ou plusieurs couches cachées,
  - d’une couche de sortie.
- Utilisation de fonctions d’activation simples.

Le modèle prend en entrée des vecteurs de caractéristiques et produit une prédiction.

---

## 2. Propagation avant (Forward pass)

- Calcul des sorties couche par couche
- Application des fonctions d’activation
- Production d’une prédiction finale

Cette étape permet d’obtenir la sortie du modèle pour une entrée donnée.

---

## 3. Fonction de perte

- Définition d’une fonction de perte adaptée au problème (classification)
- Calcul de l’erreur entre la prédiction du modèle et la vraie étiquette

La perte mesure la qualité de la prédiction.

---

## 4. Entraînement du modèle

L’entraînement consiste à :
- parcourir les données d’entraînement,
- effectuer une propagation avant pour chaque exemple,
- calculer la perte,
- mettre à jour les poids du réseau à l’aide d’un algorithme d’optimisation (descente de gradient).

Cette étape est répétée sur plusieurs itérations (epochs) afin de réduire progressivement la perte.

---

## 5. Évaluation

- Calcul des métriques de performance (ex. accuracy)
- Comparaison des performances avant et après entraînement

L’évaluation permet de vérifier que l’entraînement améliore effectivement les prédictions du modèle.

---

## Résultats attendus

À la fin du TP, l’étudiant est capable de :
- expliquer le fonctionnement d’un MLP,
- décrire le rôle de la propagation avant et de la perte,
- comprendre comment l’entraînement ajuste les poids du réseau,
- interpréter les performances du modèle.

---

## Exécution

```bash
pip install -r requirements.txt
jupyter notebook tp_ml_solution.ipynb
