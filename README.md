# Python Training

This is the practical cases for Python training I provide. Intended for french
trainee, the rest of the explanations are in french.

Ce référentiel complète la formation que je propose et est donc destiné à
mes stagiaires. 

Ces sources sont organisées pour suivre le déroulement de la formation tout en
respectant l'organisation d'un package.

**Important** : depuis janvier 2017, mes formations sont orientées Python3, ces
exercices et illustrations sont donc portés vers Python3 et une compatibilité
Python2 n'est plus garantie.

## Exercices pratiques formation Python

Ces sources contiennet un *corrigé* des exercices pratiques proposés en cours.
Rappelez-vous que bien que la devise de Python soit *Il y a une manière évidente
de faire*, il n'y a pas qu'une manière de faire.

Historiquement certains modules contiennent le sujet.

La documentation accompagnant les sources contient les sujets d'exercice pour
une mise en pratique pendant la formation. Pour y accéder, vous devez la
générer.

## Mise en place de l'environnement

Il faut donc commencer par récupérer les sources en local.

Assurez-vous que [pip](https://pypi.python.org/pypi/pip) soit installé. Créez
si vous le souhaitez un [virtualenv](https://virtualenv.pypa.io/en/stable/)
dédié à la formation. Placez vous alors à la racine du projet et saisissez

```
pip install -r requirements.txt
```

Votre environnement contient alors toutes les dépendances nécessaires. Il ne
reste plus qu'à générer la documentation. Placez-vous dans le répertoire *docs*
 et exécutez
 
```
make html
```

La documentation est alors dispoible dans le sous répertoire *_build/html*.

## Cahiers d'exercices

Le répertoire *notebooks* contient des *cahiers d'exercices*. Ceux-ci sont
des documents type *Jupyter Notebooks* générés à l'aide de
[Jupyter](http://jupyter.org/). Ce dernier est inclus dans les dépendances.
 
Placez-vous dans le répertoire *notebooks* et exécutez la commande

```
jupyter notebook 00_presentation.ipynb
```

Vous pouvez maintenant travailler avec les *notebooks*. Ceux-ci sont proposés
comme outil pour vous aider à vous familiariser avec le langage.

## Ressources

Le répertoire *assets* contient des fichiers issus de
l'[Opendata de la SNCF](https://data.sncf.com/). Les droits appartiennent
évidemment à la SNCF et ces fichiers sont présents ici pour disposer de documents
 texte volumineux à parcourir et explorer.