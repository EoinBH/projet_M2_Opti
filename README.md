# Mini-projets — Optimisation (M2)

Trois mini-projets réalisés pour le cours d'Optimisation, à partir des notebooks du cours
[EE 227C (UC Berkeley, 2018)](https://ee227c.github.io/) :

| Dossier | Projet | Notebook | Rapport |
|---|---|---|---|
| `mini-projet-1` | Projet 1 — Gradient et gradient stochastique pour le modèle logistique | `Projet_1_Regression_Logistique.ipynb` | `Rapport/main.pdf` |
| `mini-projet-2` | Projet 3 — Gradient et gradient stochastique pour le SVM | `Projet_3_SVM.ipynb` | `Rapport/main.pdf` |
| `mini-projet-3` | Projet 6 — Algorithme EM pour un mélange de Gaussiennes | `Projet_6_EM.ipynb` | `Rapport/main.pdf` |

Les projets 1 et 3 reproduisent également les vérifications d'hypothèses de
[K. Leung](https://github.com/kennethleungty/Logistic-Regression-Assumptions).

## Données
- **Titanic** : `Kenneth-Leung/data/train.csv`, repris du dépôt de K. Leung (lu par les notebooks 1 et 3).
- **Irish Educational Transitions** : `data/irish.csv` dans `mini-projet-1` et `mini-projet-2`
  ([OpenML n° 451](https://www.openml.org/d/451), téléchargé automatiquement s'il est absent).
- **Iris** : fourni par scikit-learn (projet 6).

## Exécution
Python 3 avec `numpy`, `pandas`, `scipy`, `matplotlib` et `scikit-learn`. Exécuter chaque notebook depuis son
dossier : les figures sont enregistrées dans `Rapport/Figures/`, puis le rapport se compile avec `pdflatex main.tex`
depuis `Rapport/`.
