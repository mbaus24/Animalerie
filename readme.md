# Projet Animalerie

Ce projet est une application web pour une animalerie qui permet de gérer les animaux et les clients. L'application est développée en utilisant Django, un framework web en Python, et suit le design pattern MVC (Modèle-Vue-Contrôleur).

## Modèles

Les modèles suivants sont utilisés pour stocker les données de l'application:

- `Animal`: représente un animal dans l'animalerie, avec les attributs suivants:
    - `nom`: le nom de l'animal
    - `espece`: l'espèce de l'animal
    - `age`: l'âge de l'animal
    - `description`: une description de l'animal
- `Client`: représente un client de l'animalerie, avec les attributs suivants:
    - `nom`: le nom du client
    - `email`: l'adresse email du client
    - `telephone`: le numéro de téléphone du client

## Vues

Les vues suivantes sont utilisées pour afficher les données de l'application:

- `animal_list`: affiche la liste de tous les animaux dans l'animalerie

## Contrôleurs

Les contrôleurs suivants sont utilisés pour gérer les requêtes de l'utilisateur:

- `animal_list`: récupère la liste de tous les animaux dans l'animalerie à partir de la base de données et renvoie la réponse HTTP correspondante avec le template `animal_list.html`

## Comment exécuter l'application

1. Cloner le dépôt Git: `git clone https://github.com/mbaus24/animalerie.git`
2. Installer les dépendances: `pip install -r requirements.txt`
3. Appliquer les migrations: `python manage.py migrate`
4. Lancer le serveur: `python manage.py runserver`
5. Accéder à l'application dans un navigateur web à l'adresse `http://localhost:8000/`

