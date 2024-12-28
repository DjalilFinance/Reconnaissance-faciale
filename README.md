Reconnaissance Faciale


Description

Ce projet implémente un système de reconnaissance faciale basé sur des techniques de détection et d'extraction de caractéristiques faciales. Il utilise des modèles pré-entraînés et des algorithmes comme les cascades Haar, 

HOG (Histogram of Oriented Gradients), et des prédicteurs de formes pour localiser et analyser les visages dans des images ou en temps réel via une webcam.


Structure du projet

images/ : Dossier contenant les exemples d'images pour la détection faciale.

dlib_shape_predictor.py : Script pour extraire les points clés du visage à l’aide de Dlib.

haarcascade_frontalface_default.xml : Fichier XML de cascade Haar pour la détection de visages.

hog.py : Implémentation de l’algorithme HOG pour la détection faciale.

shape_predictor_68_face_landmarks.dat : Modèle pré-entraîné pour la prédiction des landmarks faciaux.

webcam-face-detection-tutorial.py : Détection des visages en temps réel via webcam.

Fonctionnalités clés

Détection faciale : Utilise des cascades Haar et HOG pour localiser les visages.

Extraction des landmarks faciaux : 68 points clés pour analyser les caractéristiques du visage.

Détection en temps réel : Reconnaissance faciale à l’aide d’une webcam.

Pré-traitement des images : Identification des visages dans des images statiques ou des flux vidéo.

Installation


Clonez ce dépôt :


bash

Copier le code

git clone https://github.com/ton_profil/Reconnaissance-faciale.git

cd Reconnaissance-faciale

Installez les dépendances nécessaires :


bash

Copier le code

pip install -r requirements.txt

Lancez la détection en temps réel avec la webcam :


bash

Copier le code

python webcam-face-detection-tutorial.py

Utilisation

Images : Placez vos images dans le dossier images/ et utilisez les scripts pour détecter les visages.

Webcam : Exécutez webcam-face-detection-tutorial.py pour détecter les visages en direct.

Technologies utilisées

Langages : Python.

Bibliothèques : OpenCV, Dlib, NumPy.

Modèles : Cascade Haar, prédicteurs Dlib.

Contributeurs

Salah Bey Abdeldjalil
