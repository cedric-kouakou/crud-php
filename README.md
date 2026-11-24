
# PHP CRUD Application

Application web de gestion des données développée avec PHP et MySQL. Elle permet d'effectuer les opérations CRUD : Create, Read, Update et Delete.

## Fonctionnalités

- Ajouter des données (Create)
- Afficher les données (Read)
- Modifier les données (Update)
- Supprimer les données (Delete)
- Gestion des erreurs

## Technologies utilisées

- PHP
- MySQL
- HTML5
- CSS3

## Structure du projet

```text
├── create.php
├── delete.php
├── error.php
├── index.php
├── phpcrud.sql
├── read.php
└── update.php
```

## Installation

### 1. Cloner le projet

```bash
git clone https://github.com/TON-USERNAME/TON-REPOSITORY.git
```

### 2. Configurer XAMPP

- Installer XAMPP.
- Démarrer Apache et MySQL.
- Placer le projet dans le dossier `htdocs`.

### 3. Créer la base de données

Ouvrir phpMyAdmin :

```text
http://localhost/phpmyadmin
```

Importer le fichier `phpcrud.sql`.

La base de données utilisée est :

```sql
CREATE DATABASE crudphp;
```

### 4. Configuration de la connexion

Vérifier les paramètres de connexion à MySQL :

```php
$host = "localhost";
$username = "root";
$password = "";
$database = "crudphp";
```

### 5. Lancer le projet

Accéder à l'application depuis le navigateur :

```text
http://localhost/NOM-DU-PROJET/
```

## Auteur

**Cedric Kouakou**

Développeur Full-Stack Web et Mobile
