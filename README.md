# Challenge Machine Learning

A l'issue de ce troisième module concernant la classification supervisée, voici un challenge que vous allez relever en binomes. Il vous permettra de comprendre par la pratique plusieurs subtilités de la classification supervisée.

Vous êtes contactés par un négociant en vins. Il veut repérer les excellents vins parmi une sélection de plus de 3000 vins différents sur base d'analyses physico-chimiques uniquement, sans devoir faire apple à un coûteux panel d'experts (`wine2`).

Pour entraîner votre classifieur, vous avez le jeu de données `data/wine.rds` à disposition qui rassemble les caractéristiques physico-chimiques de 1500 vins différents de `wine2`, choisis au hasard, ainsi que leur qualité (`quality`) telle qu'établie selon un consensus parmi un panel d'œnologues.

Votre objectif sera de déployer votre classifieur sur le jeu de données `data/wine2.rds` pour en extraire le plus possible des meilleurs vins (donc, dont `quality == "excellent"`).

Vos classifications doivent être soumises via l'interface dans le cours : entrez le nom de votre équipe (le même que celui choisi lors de l'assignation GitHub Classroom), ensuite un nom évocateur mais court pour votre modèle, et soumettez votre classification de `wine2`. Vous avez un document R Markdown exemple dans `docs` pour vous y aider. Vous pouvez soumettre autant de classifications que vous voulez. Vos résultats et votre progression seront affichés dans le tableau des scores (toujours dans le cours). Pour chaque modèle soumis, vous devrez commiter une document .Rmd du même nom dans votre dépôt GitHub.

**Votre objectif est de trouver le plus possible d'excellent vins dans `wine2`, mais attention, votre client ne tolère pas que vous lui indiquiez plus de 3/4 de vins qui ne seraient pas excellents dans votre liste de suggestions !**

Les meilleures équipes seront nominées à la fin de la séance, et elles viendront exposer leur modèle devant la classe.
