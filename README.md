# Mongo-Rust

## Objectif

Ce projet a pour objectif de mettre en place une API REST en Rust qui permet de
manipuler une base de données MongoDB le tout en suivant la methode TDD. Il
s'agit d'un projet d'apprentissage pour découvrir le langage Rust et la base de
données MongoDB. Il n'y a pas d'api pour communiquer avec la base de données,
tout est fait en Rust. L'application doit :

- se lancer
- se connecter a la base de données
- y recuperer des données
- faire des operrations
- et les sauvegarder dans un fichier json

## Prérequis

- [MongoDB](https://www.mongodb.com/): Base de données NoSQL orientée documents
- [Rust](https://www.rust-lang.org/): Langage de programmation système

## Etape 1 : Organisation du projet (TDD)

- Créer un projet Rust
- Créer un fichier `lib.rs`
- Créer un fichier `database.rs`
- Créer un fichier `database_test.rs`

## Etape 2 : Connexion à la base de données

- Créer une fonction `connect` dans `database.rs`
- Créer une fonction `connect_test` dans `database_test.rs`
- Créer une fonction `disconnect` dans `database.rs`
- Créer une fonction `disconnect_test` dans `database_test.rs`

## Etape 3 : Récupération des données

- Créer une fonction `get` dans `database.rs`
- Créer une fonction `get_test` dans `database_test.rs`

## Etape 4 : Opérations

- Créer une fonction `insert` dans `database.rs`
- Créer une fonction `insert_test` dans `database_test.rs`
- Créer une fonction `update` dans `database.rs`
- Créer une fonction `update_test` dans `database_test.rs`
- Créer une fonction `delete` dans `database.rs`
- Créer une fonction `delete_test` dans `database_test.rs`

## Etape 5 : Sauvegarde des données

- Créer une fonction `save` dans `database.rs`
- Créer une fonction `save_test` dans `database_test.rs`

## Etape 6 : Lancement de l'application

- Créer un fichier `main.rs`
- Créer une fonction `main` dans `main.rs`

## Etape 7 : Documentation

- Créer un fichier `README.md`
- Ajouter une description du projet
- Ajouter les prérequis
- Ajouter les étapes
- Ajouter des exemples d'utilisation
- Ajouter des captures d'écran
- Ajouter des liens utiles

## Etape 8 : Tests

- Lancer les tests avec `cargo test`

## Etape 9 : Lancement

- Lancer l'application avec `cargo run`

## Etape 10 : Améliorations

- Ajouter des fonctionnalités
- Ajouter des tests
- Ajouter des commentaires
- Ajouter des logs
- Ajouter des erreurs
- Ajouter des messages
- Ajouter des options
- Ajouter des arguments
- Ajouter des variables
- Ajouter des constantes
- Ajouter des structures
- Ajouter des énumérations
- Ajouter des traits
