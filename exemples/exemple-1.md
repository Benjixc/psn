## Méthode Agile

### Formez des groupes

Nous vous invitons à former des groupes de 4 personnes. Vous
travaillerez ensemble pour la durée du projet.

### Stand-up!

Chaque début de séance, vous faites un "Stand-up". Vous vous mettez en
cercle, debout. À tour de rôle, chaque membre de l'équipe fait le point
sur:

* ce qu'il a fait lors de la dernière séance, 
* ce qu'il compte faire lors de cette séance,
* indique si quelque chose l'empêche d'avancer.

Le "Stand-up" ne doit pas durer plus de 5 minutes.

### TDD, Git et Pull-Requests

À chaque fonctionnalité, créez une branche spécifique commençant par le
numéro de la fonctionnalité. Exemple: `F-1-pokemon-repond-pikapika`

Nous vous invitons à développer en faisant du Développement guidé par
les tests (TDD in english): 

* 1 - Écrivez un test, regardez le échouer.
* 2 - Écrivez le code correspondant, regardez le test passer.
* 3 - Refactorez le code pour qu'il soit plus simple, plus expressif, plus
lisible.
* 4 - Committez ce nouveau test.
* 5 - Retour au 1.

**Note:** Afin de faciliter le suivi du projet, nous vous demandons
de commencer vos messages de commit par le numéro de la fonctionnalité
que vous implémentez. Exemple: `F-1 - Pokemon répond "Pika Pika"` ou
`F-1 - Correction des tests`

Une fois que la fonctionnalité est développée, créez une pull request!

Un autre étudiant de l'équipe devra vérifier la pull request:

* les tests passent?
* le code est compréhensible?
* chaque classe possède sa classe de tests?
* il y a suffisament de tests?
* la fonctionnalité implémenté correspond à la story?

Si tout est bon, mergez la Pull-Request dans master! Sinon, faites vos
commentaires via Github. Il suffit de continuer de travailler sur la
même branche et la pusher pour mettre à jour la pull request.

