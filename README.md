# API Albums et Photos

Cette API offre divers endpoints permettant de gérer des albums et les photos qui y sont associées. Elle permet aux utilisateurs de créer, consulter, mettre à jour et supprimer des albums ainsi que leurs photos.

## Fonctionnalités

- Gérer (créer, lire, modifier, supprimer) des albums.
- Gérer (créer, lire, modifier, supprimer) des photos associées à chaque album.
- Utiliser MongoDB pour stocker et gérer les données.

## Endpoints

### Albums

- `GET /albums`  
  Obtenir la liste de tous les albums.

- `GET /albums/:id`  
  Obtenir un album spécifique par son ID.

- `POST /albums`  
  Créer un nouvel album.

- `PUT /albums/:id`  
  Mettre à jour les informations d'un album existant.

- `DELETE /albums/:id`  
  Supprimer un album par son ID.

### Photos

- `GET /albums/:albumId/photos`  
  Obtenir toutes les photos d'un album donné.

- `GET /albums/:albumId/photos/:photoId`  
  Obtenir une photo spécifique par son ID au sein d'un album.

- `POST /albums/:albumId/photos`  
  Ajouter une nouvelle photo dans un album.

- `PUT /albums/:albumId/photos/:photoId`  
  Mettre à jour les informations d'une photo existante dans un album.

- `DELETE /albums/:albumId/photos/:photoId`  
  Supprimer une photo d'un album en fonction de son ID.

## Prise en Main

### Prérequis

- Avoir [Node.js](https://nodejs.org/) installé.
- Avoir une instance [MongoDB](https://www.mongodb.com/) opérationnelle.

### Installation

1. Cloner le repository :
    ```bash
    git clone https://github.com/Moha935/API.git
