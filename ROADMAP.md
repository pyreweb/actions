# Feuille de route

## Nouveautés (feat)

- Création du workflow `laravel-continuous-integration` qui utilise le workflow `php-continuous-integration`.

## Modifications (refactor)

- Dans le workflow `php-continuous-integration`, il manque un cache composer.
- Dans le workflow `php-continuous-integration`, il manque les permissions.
- Dans le workflow `dependencies-update.yml`, mettre l'étape `Restoring the Composer cache directory` dans une action dans le fichier `.github/actions/composer/cache/restore/action.yml`.
- Dans le workflow `dependencies-update.yml`, mettre l'étape `Composer Caching` dans une action dans le fichier `.github/actions/composer/cache/action.yml`.
- Dans le workflow `dependencies-update.yml`, mettre l'étape `Creating the .env file` dans une action dans le fichier `.github/actions/env/create/example/action.yml`.
- Dans le workflow `dependencies-update.yml`, mettre l'étape `Generating the application key` dans une action dans le fichier `.github/actions/laravel/key/generate/action.yml`.
- Dans le workflow `dependencies-update.yml`, mettre l'étape `Backend testing` dans une action dans le fichier `.github/actions/laravel/test/action.yml`.

## Corrections (fix)

- Aucun élément pour le moment.
