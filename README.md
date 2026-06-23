# pyreweb/actions

## Concept

Ce repository contient les actions GitHub qui sont utilisés dans les autres repository de l'organisation.

## Liste des workflows disponibles

- [Mise à jour des dépendances](https://github.com/pyreweb/actions/blob/main/.github/workflows/dependencies-update.yml)
- [Création de release GitHub](https://github.com/pyreweb/actions/blob/main/.github/workflows/github-release.yml)
- [Vérification linter dans Laravel](https://github.com/pyreweb/actions/blob/main/.github/workflows/laravel-lint.yml)
- [Vérification des tests dans Laravel](https://github.com/pyreweb/actions/blob/main/.github/workflows/laravel-tests.yml)
- [Intégration continue pour nos projets PHP](https://github.com/pyreweb/actions/blob/main/.github/workflows/php-ci.yml)

## Notes

Merci de mettre toutes les actions dans le dossier `.github/workflows` et de ne surtout pas modifier le chemin des actions existantes vers un autre endroit, puisque GitHub oblige les actions qui sont appelées via d'autres repository d'être dans tout les cas dans le dossier `.github/workflows`.
