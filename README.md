# Challenge Machine Learning - trouver les excellents vins

A l'issue de ce troisième module concernant la classification supervisée, voici un challenge que vous allez relever en binômes. Il vous permettra de comprendre par la pratique plusieurs subtilités de la classification supervisée.

Vous êtes contactés par un négociant en vins. Il veut repérer les excellents vins parmi une sélection de plus de 3000 vins différents sur base d'analyses physico-chimiques uniquement, sans devoir faire appel à un coûteux panel d'experts (`wine2`).

Pour entraîner votre classifieur, vous avez le jeu de données `wine` dans `data/wine.rds` à disposition qui rassemble les caractéristiques physico-chimiques de 1500 vins, tous différents de ceux repris dans `wine2`, ainsi que leur qualité (`quality`) telle qu'établie selon un consensus parmi un panel d'œnologues.

Votre objectif sera de déployer votre classifieur sur le jeu de données `data/wine2.rds` pour en extraire le plus possible des meilleurs vins (donc, dont `quality == "excellent"`).

**Lisez bien les instructions ci-dessous et assurez-vous de les avoir bien comprises avant de commencer votre travail !**

Vos classifications doivent être soumises via l'interface dans le cours : soumettez le fichier `.rds` qui est généré dans `/results`. Vous avez un document R Markdown exemple dans `docs` pour vous y aider. Vous pouvez soumettre autant de classifications que vous voulez, mais **vous devez donner un nom différent à chaque fois.** Vos résultats et votre progression seront affichés dans le tableau des scores. Pour chaque modèle soumis, vous devrez commiter un document `.Rmd` du même nom dans votre dépôt GitHub qui reprend votre analyse pour ce modèle en particulier. Démarrez toujours à partir d'une copie de `docs/adl_simple.Rmd` (ou de votre analyse précédente) que vous renommez. À partir du moment où vous avez soumis vos résultats, **n'éditez plus le fichier `.Rmd` qui a servi à la générer.**

**Votre objectif est de trouver le plus possible d'excellent vins dans `wine2`, mais attention, votre client ne tolère pas que vous lui indiquiez plus de 3/4 de vins qui ne seraient pas excellents dans votre liste de suggestions !**

Les meilleures équipes seront nominées à la fin de la séance, et elles viendront exposer leur modèle devant la classe.
