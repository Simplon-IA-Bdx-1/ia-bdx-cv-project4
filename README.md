# Brief Computer Vision - mercredi 11 et jeudi 12 décembre 2019

## Restitution de veille

Au menu : les RNN

## Retour et partage d'expérience sur OpenCV

## Lecture sur les cascades de Haar : [ici](https://pymotion.com/detection-objet-cascade-haar/)

## Intermède 1 : [Haar cascade with OpenCV](https://www.youtube.com/watch?v=88HdqNDQsEk)

## Intermède 2 : [CV](https://www.youtube.com/watch?v=-4E2-0sxVUM)

## Galaxy Zoo


Objectif à terme : avec Keras, résoudre au mieux le problème de classification des images de galaxies en 3 classes (rondes, à disque ou pas une galaxie), à l'aide de CNNs et de transfer learning. Dans un deuxième temps, affiner la classification morphologique pour les galaxies à disque.

Travail par groupe de 4

* Récupérer les images
* Explorer la base d'images
* Chercher des heuristiques pour améliorer les baselines avec des méthodes classiques de Computer Vision
* Chercher des stratégies pour réduire le nombre de dimensions et faciliter l'apprentissage d'un modèle
* Définir et implémenter une architecture simple de CNN adaptée aux données réduites en termes de dimensions et de taille du dataset
* Explorer les temps de calcul en fonction de l'architecture et de l'étape de réduction des dimensions
* Entraîner le modèle (tester d'abord sur un sous-ensemble), évaluer avec une  métriques adaptée
* Réfléchir à l'utilisation du data augmentation
* Implémenter le data augmentation, évaluer
* Identifier les hyper-paramètres les plus prometteurs pour une optimisation du CNN
* Choisir une méthode d'optimisation des hyper-paramètres et l'appliquer à son modèles
* INTERMEDE : utiliser la méthode k-NN pour classer le dataset (éventuellement après PCA) et établir une nouvelle baseline
* Chercher des modèles pré-entraînés qui pourraient servir pour ce problème de classification
* Réfléchir au périmètre d'architecture sur lequel appliquer le transfer learning
* Appliquer à l'entraînement d'un modèle, évaluer convergence et performance des prédictions
* Optimiser les hyper-paramètres pour le modèle provenant d'un modèle pré-entraîné
* Réfléchir à des stratégies d'amélioration des résultats : pré-traitement, feature engineering, combinaison de modèles/méthodes, etc.

Dans un deuxième temps, on cherchera à identifier la présence d'une forme spiralée ou non lorsque la galaxie aura été identifiée comme appartenant à la classe 2, c'est-à-dire une galaxie à disque (voir [arbre de décision](https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/overview/the-galaxy-zoo-decision-tree)).