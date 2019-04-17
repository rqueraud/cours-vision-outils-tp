# Cours YNOV - Outils pour la Vision - 18 avril 2019

Ce dépôt constitue une suite d'exercices, sur le même format que le cours d'outils sur le NLP.

## Pour démarrer

Vous devez disposer, à minima, d'un environnement `python 3.6` avec `pipenv`. Vous pouvez ensuite lancer jupyter en faisant :

```bash
pipenv install  # Installe les dépendances
pipenv run jupyer-notebook .
```

Une fois lancé, les exercices sont sous la forme de notebooks.

## TP1 : OpenCV

OpenCV est la boîte à outils en ce qui concerne le traitement d'images. On y retrouve des fonctions pour charger des images et appliquer les transformations génériques.

Deux parties sur ce TP :

  - La première permet de se familiariser avec les fonctions de base d'openCV et de tester d'implémenter quelques morphologies.
  - La seconde fait travailler avec une vidéo et l'extraction d'objets.

## TP2 : PyTorch

PyTorch permet d'implémenter des réseaux de neurones. Ce TP en 3 parties va permettre de :

  - Se familiariser avec la structure de Tensors en pytorch.
  - Implémenter une structure avec un Linear Layer pour calculer une regression linéaire
  - Observer une structure de classifier et l'appliquer sur le Dataset d'images MNIST.

## TP3 : AWS

AWS propose toute une suite d'outils pour l'intelligence artificielle. Parmi elle, AWS Rekognition est la partie chargée de l'analyse d'images et de vidéos.

Vous allez devoir utiliser la librairie boto3 en python pour analyser vos images et vidéos et ainsi pour compter le nombre de voitures circulant sur la vidéo du premier TP.

## TP4 : Structures géométriques

Nous souhaitons créer un script permettant de prendre en entrée des images contenant différentes formes géométriques et de ressortir la liste des formes contenues dans l'image.
