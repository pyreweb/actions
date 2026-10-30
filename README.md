# Actions GitHub

Ce dépôt est la boîte à outils d’automatisation de Pyréweb pour GitHub. Il part d’un constat simple : les projets PHP, qu’ils soient sous Symfony ou Laravel, répètent presque toujours les mêmes étapes de vérification et de livraison. Plutôt que de copier ces étapes d’un dépôt à l’autre, on les définit ici une seule fois, sous forme de briques réutilisables et de workflows prêts à l’emploi que chaque projet peut appeler en quelques lignes.

L’objectif est double. D’un côté, garantir des pipelines homogènes, quel que soit le projet ou le développeur : même façon de lancer les tests, de relire le code, de mettre à jour les dépendances et de publier une version. De l’autre, faciliter la maintenance, puisqu’une amélioration apportée à un workflow ici profite immédiatement à tous les projets qui l’utilisent. Le dépôt est ainsi pensé comme une base commune, évolutive et partagée, qui permet de gagner du temps et de fiabiliser le quotidien de l’équipe.

## Flux automatiques

### Intégrations continues

- [PHP](.github/workflows/php-continuous-integration.yml).
- [Symfony](.github/workflows/symfony-continuous-integration.yml).

### Autres

- [Mise à jour automatique des dépendances](.github/workflows/dependencies-update.yml).
- [Génération de version automatique](.github/workflows/github-release.yml).
- [Relecture automatique pour Laravel](.github/workflows/laravel-lint.yml).
- [Tests automatiques pour Laravel](.github/workflows/laravel-tests.yml).

## Feuille de route

Disponible ici : [`ROADMAP.MD`](ROADMAP.md).

## Licence

Disponible ici : [`LICENSE.md`](LICENSE.md).

## Auteurs

Disponible ici : [`AUTHORS.md`](AUTHORS.md).
