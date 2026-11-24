# Politique de sécurité

La sécurité du projet [`pyreweb/actions`](https://github.com/pyreweb/actions) est une priorité. Ce document explique comment signaler une vulnérabilité, quelles versions bénéficient de correctifs et ce que vous pouvez attendre de notre part après un signalement.

## Versions prises en charge

Seules les versions indiquées ci-dessous reçoivent des correctifs de sécurité.

| Version | Prise en charge |
| ------- | --------------- |
| v1      | Oui             |

## Signaler une vulnérabilité

Ne signalez jamais une faille de sécurité par un ticket, une demande de fusion ou une discussion publique : cela exposerait le projet et ses utilisateurs avant qu'un correctif soit disponible.

Écrivez plutôt aux mainteneurs à l'adresse [support@pyreweb.com](mailto:support@pyreweb.com) en précisant les éléments suivants :

- Une description claire de la vulnérabilité.
- Les étapes pour la reproduire.
- L'impact possible, par exemple l'accès à des données ou l'exécution de code.
- Les versions et l'environnement concernés : version du projet, système d'exploitation, navigateur, version du langage, etc.
- Les journaux, les captures d'écran ou la preuve de concept utiles, sans données personnelles ni secret réels.
- Vos coordonnées, si vous souhaitez être recontacté ou mentionné lors de la publication du correctif.

## Nos engagements

Après réception d'un signalement, les mainteneurs s'engagent à :

- Accuser réception sous 3 jours ouvrés.
- Évaluer la gravité de la vulnérabilité et vous communiquer leur analyse sous 10 jours ouvrés.
- Vous tenir informé de l'avancement du correctif.
- Publier un correctif dans un délai adapté à la gravité de la faille, puis informer les utilisateurs concernés.
- Respecter la confidentialité de votre signalement et de votre identité, sauf si vous acceptez d'être mentionné ou en cas d'obligation légale.

## Divulgation responsable

Nous vous demandons de ne divulguer aucune information sur la vulnérabilité avant la publication du correctif, ou avant l'expiration d'un délai de 90 jours à compter de votre signalement si nous n'avons pas pu convenir d'une date.

Pendant vos recherches, merci de :

- Limiter vos tests à vos propres comptes et à vos propres données.
- Ne pas accéder aux données d'autrui, ni les modifier, les copier ou les supprimer.
- Ne pas perturber le fonctionnement du service, par exemple par une attaque par déni de service.
- Ne pas utiliser de technique d'ingénierie sociale contre les mainteneurs ou les utilisateurs.

Nous n'engagerons aucune action en justice contre une personne qui a agi de bonne foi et dans le respect de ces règles.

## Hors périmètre

Les éléments suivants ne relèvent pas de cette politique :

- Les failles qui touchent uniquement une version non prise en charge.
- Les vulnérabilités des dépendances tierces qui ne sont pas exploitables dans le projet : signalez-les directement à leurs auteurs.
- Les remarques sans impact démontré sur la sécurité, comme l'absence d'un en-tête HTTP facultatif.

## Contact

Pour toute question concernant cette politique de sécurité, vous pouvez écrire à [support@pyreweb.com](mailto:support@pyreweb.com).
