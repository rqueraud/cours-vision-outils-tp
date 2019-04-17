# Partie 3 : Services AWS pour la Vision

Sur AWS, on trouve toute une série de services utilisables soit directement depuis la console, soit interrogeables depuis une API. Nous allons nous intéresser ici à l'utilisation de ces services via la librairie `boto3` en python.

## Exercice 1 : Intérrogation de l'API AWS

Il vous faudra vous créer un **IAM User** :

  - Allez dans le service **IAM** sur AWS, dans l'onglet **Users** puis créez un nouvel User avec un **Programmatic access**.
  - Pour ajouter des permissions, cela se passe en selectionnant **Attach existing policies directly** dans la partie 2 de la création. Vous pouvez attacher la policiy **AmazonRekognitionFullAccess**.
  - Une fois créé, vous pouvez récuperer l'**Access key ID** et la **Secret access key** qui vous permettront de requêter l'API directement avec python (vous pouvez télecharger le .csv).

## Exercice 2 : Utilisation de rekognition pour les images

Utilisez la (documentation)[https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html] de boto3 pour analyser l'image dans data.

## Exercice 3 : Utilisation de rekognition pour les videos

Utiliser ce coup-ci le service de video de Rekognition sur la vidéo de voitures. Vous en servir pour compter le nombre de voiture différentes !