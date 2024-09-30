# TP3 : Support Vector Machines (SVM)

## Description

Ce travail pratique explore l’utilisation des **machines à vecteurs de support (SVM)** pour la classification de données, en utilisant le package `scikit-learn` et la base de données `Iris`. Différents noyaux, tels que les noyaux **linéaire** et **polynomial**, ont été comparés afin d’examiner diverses stratégies de **séparation des classes**. La validation croisée a été mise en œuvre pour évaluer les performances des modèles et analyser l’influence du **paramètre de régularisation C** sur ces performances.

Une interface graphique a été développée pour visualiser l’effet du paramètre **C** sur les frontières de décision des modèles. Cette interface a été compilée à partir du fichier `svm_gui.py`, situé dans le dossier `src`.

Enfin, les SVM ont été appliqués à une [base de données de visages](http://vis-www.cs.umass.edu/lfw/) pour résoudre un problème de **reconnaissance faciale**. L’ajout de variables bruitées a permis d’examiner leur impact sur les performances des modèles, tandis que l’analyse en composantes principales (ACP) a été utilisée pour réduire la dimensionnalité des données et améliorer la robustesse des modèles face au bruit.

## Arborescence

Le dossier `src` contient les fichiers suivants :

- `svm_gui.py` : interface graphique
- `svm_script.py` : script principal du TP
- `svm_source.py` : code source

Le dossier `docs` contient les fichiers suivants :

- `TP_SVM.tex` : le fichier `.tex` du rapport
- `TP_SVM.pdf` : le rapport au format PDF

Le dossier `images` contient les images nécessaires à la compilation du rapport.

## Prérequis

Pour exécuter l'ensemble du code présent dans ce projet, il est nécessaire d'avoir une version récente de Python ainsi que les packages suivants :

- `numpy`
- `matplotlib`
- `scikit-learn`
- `pillow`
- `seaborn`
- `pandas`

Un compilateur LaTeX est également requis pour générer le fichier PDF du rapport.

## Installation et Exécution

Pour cloner le dépôt, exécutez la commande suivante :

```bash
git clone git@github.com:MaxenceLamure/TP_SVM.git
```

## Auteur

[Maxence Lamure](https://github.com/MaxenceLamure)