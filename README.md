# dataFormations

Ce dépôt contient des données et un outil de visualisation liés aux **formations proposées par FAIRE ESS Occitanie**. Ces données sont utilisées dans le chatbot de FAIRE ESS pour orienter les utilisateurs vers des parcours adaptés, en fonction de leur niveau et des compétences comportementales recherchées.

## Contenu du dépôt

- `formations.json` :  
  Fichier principal contenant les données sur les formations :
  - **Nom complet** de la formation  
  - **Nom abrégé**  
  - **Niveau** (ex : débutant, intermédiaire, avancé...)  
  - **Soft skills associées** (compétences comportementales liées à chaque formation)

- `index.html` :  
  Interface HTML permettant de visualiser les données du fichier JSON de manière lisible et interactive. Idéal pour parcourir ou valider visuellement les données.

## Utilisation dans le chatbot FAIRE ESS

Les données présentes dans `formations.json` sont directement exploitées dans le **chatbot de FAIRE ESS Occitanie** pour :
- suggérer des formations en fonction du profil utilisateur,
- filtrer les résultats selon le niveau de compétence,
- proposer des formations alignées avec certaines soft skills.

## Aperçu de l'affichage

Ouvrez le fichier `index.html` dans un navigateur pour afficher la liste des formations et explorer les données intégrées au JSON.

## Exemple de structure JSON

```json
[
  {
    "nom_complet": "Titre professionnel de développeur web et web mobile",
    "nom_abrege": "TP DWWM",
    "niveau": "5",
    "softskill 1": true,
    "softskill 2": false...
  }
]
```

## Structure

```
dataFormations/
│
├── formations.json      # Données sur les formations (utilisées par le chatbot)
├── index.html           # Visualisation des données
└── README.md            # Documentation du projet
```

## Visualisation

Pour visualiser les données des formations, vous pouvez consulter la page de visualisation en ligne ici :  
[Visualiser les formations](https://htmlpreview.github.io/?https://raw.githubusercontent.com/Alec34pi/dataFormations/ma-premiere-branche/visualisation.html)

---
