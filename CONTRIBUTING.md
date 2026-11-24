# Guide de contribution

Merci de l'intérêt que vous portez au projet [`pyreweb/actions`](https://github.com/pyreweb/actions). Ce guide explique comment proposer une modification, les règles à respecter et la manière dont les contributions sont relues et intégrées. En participant au projet, vous vous engagez à respecter le [code de conduite](CODE_OF_CONDUCT.md).

## Façons de contribuer

Vous pouvez contribuer au projet de plusieurs manières :

- Signaler une anomalie.
- Proposer une amélioration ou une nouvelle fonctionnalité.
- Corriger ou compléter la documentation.
- Proposer une modification du code ou du contenu.
- Relire les demandes de fusion des autres contributeurs.

Les évolutions prévues sont consultables dans la [feuille de route](ROADMAP.md).

## Avant de commencer

- Vérifiez qu'aucun ticket ou aucune demande de fusion n'existe déjà pour le même sujet.
- Pour une modification importante, ouvrez d'abord un ticket afin d'en discuter avec les mainteneurs avant de commencer le travail.
- Pour une faille de sécurité, ne créez pas de ticket public : suivez la [politique de sécurité](SECURITY.md).

## Signaler une anomalie

Ouvrez un ticket en précisant les éléments suivants :

- Un titre clair et précis.
- Le comportement attendu et le comportement constaté.
- Les étapes pour reproduire le problème.
- L'environnement concerné : version du projet, système d'exploitation, navigateur, version du langage, etc.
- Les messages d'erreur ou les captures d'écran utiles.

## Proposer une amélioration

Ouvrez un ticket en décrivant :

- Le besoin ou le problème que l'amélioration résout.
- La solution envisagée et, le cas échéant, les alternatives étudiées.
- L'impact possible sur l'existant.

## Proposer une modification

### 1. Préparer son environnement

1. Réalisez une copie du dépôt (fork) ou clonez-le si vous disposez des droits nécessaires :

    ```bash
    git clone https://github.com/pyreweb/actions.git
    cd actions
    ```

### 2. Créer une branche

Créez une branche à partir de `main`, nommée selon le format `type/description-courte` :

```bash
git switch -c type/description-courte
```

Exemples de types : `feat`, `fix`, `docs`, `refactor`, `test`, `chore`.

### 3. Réaliser la modification

- Limitez-vous à un seul sujet par demande de fusion.
- Respectez les [conventions de code](#conventions-de-code).
- Ajoutez ou mettez à jour les tests lorsqu'un comportement change.
- Mettez à jour la documentation lorsque le changement le justifie.
- Ne versionnez aucun secret (mot de passe, clé d'API, jeton, fichier d'environnement local).

Aucune erreur ne doit subsister.

### 4. Valider les modifications

Les messages de commit suivent la spécification [Conventional Commits](https://www.conventionalcommits.org/fr/v1.0.0/) et sont rédigés en français :

```text
type(portée): description courte à l'impératif

Corps du message facultatif pour expliquer le pourquoi du changement.
```

Exemples :

```text
feat(auth): ajouter la connexion par lien magique
fix(facture): corriger l'arrondi du total toutes taxes comprises
docs(readme): préciser les étapes d'installation
```

### 5. Ouvrir une demande de fusion

1. Envoyez votre branche sur votre dépôt :

    ```bash
    git push origin type/description-courte
    ```

2. Ouvrez une demande de fusion vers la branche `main`.
3. Renseignez un titre clair et une description qui précise :
    - Le contexte et l'objectif de la modification.
    - Les changements principaux.
    - La manière de la tester.
    - Les tickets concernés, par exemple `Closes #123`.
4. Vérifiez que les contrôles automatiques sont au vert.

## Conventions de code

- Le code, les commentaires et la documentation sont rédigés en français.

## Relecture et intégration

- Au moins une personne parmi les mainteneurs relit chaque demande de fusion.
- Les mainteneurs peuvent demander des modifications : répondez aux commentaires et mettez à jour votre branche.
- Une fois la demande approuvée et les contrôles validés, un mainteneur l'intègre à la branche `main`.
- Les mainteneurs se réservent le droit de refuser une contribution qui ne correspond pas aux objectifs du projet, en en expliquant les raisons.

## Licence

En contribuant au projet, vous acceptez que votre contribution soit diffusée sous la [licence](LICENSE.md) du projet.

## Reconnaissance

Une fois votre contribution acceptée, vous pouvez demander à figurer dans le fichier [AUTHORS.md](AUTHORS.md).

## Contact

Pour toute question concernant la contribution au projet, vous pouvez écrire à [support@pyreweb.com](mailto:support@pyreweb.com).
