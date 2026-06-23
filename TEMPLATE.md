Voici à quoi doit ressembler un fichier `.github/workflows/*.yml` dans un repository extérieur à celui ci :

```yml
name: pyreweb/action

on:
  schedule:
    # Se lance tous les jours à 6h, 12h et 18h (UTC+2/Paris)
    - cron: '0 4,10,16 * * *'
  workflow_dispatch:

permissions:
  contents: write
  pull-requests: write

jobs:
  job:
    uses: pyreweb/github_actions/.github/workflows/ACTION.yml@main
```
