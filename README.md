# Python à Diderot
## A propos
Ce répertoire contient l'environnement de développement utilisées par les élèves et les professeurs du lycée Denis Diderot à Marseille afin de travailler, entre autres, sur la partie algorithmique et programmation. Le projet est hébergé sur ce dépot [github](https://github.com/cspaier/thonny).

## Documentation
La documentation (en cours de construction) est disponible [ici](https://pydiderot.readthedocs.io/).

## Environnement
Thonny est un environnement de développement python simple téléchargeable sur [https://thonny.org/](https://thonny.org/).

Le langage de programmation est python version 3.7.1rc1. Nous utilisons la version 3.0.8 de Thonny avec Tk 8.6.8.


![](https://thonny.org/img/screenshot.png)


## Installation
Télécharger le dossier compréssé en zip avec ce [lien](https://github.com/cspaier/thonny/archive/diderot.zip). Le décomprésser et double cliquer sur le raccourci `thonny - raccourci`. Cela fonctionne sous Windows© uniquement.

Si vous êtes sous Linux ou MacOSX, il vous faut installer thonny par vos propre moyens en suivant le [site officiel](https://thonny.org) et ensuite rajouter les librairies du lycée dans votre dossier personel.

## Utilisation

Thonny est simple d'utilisation. Ses fonctionnalitées sont documentées, en anglais, sur son [site internet](https://thonny.org/).
Voici quelques remarques utiles.


### Affichage des variables
<div style="float: right;"> <img src="https://thonny.org/img/variables.png"></div>

Thony propose un affichage dynamique du contenu des variables qui peut être particulierement utile dans un cadre pédagogique.

Son utilisation n'est **pas compatible avec l'import de librairies**. En effet, l'onglet affichera le contenu de toutes les fonctions et variables importées ce qui peut ralentir considérablement l'utilisation.

### Importer des Librairies
* **Sous Windows©**: Le dossier de travail est le dossier `python` qui se trouve dans votre dossier personnel. Il suffit d'y mettre un fichier `exemple.py` pour pouvoir l'importer avec la commande `from exemple import *`

* **Sous Unix**: Vous utilisez la version officielle de thonny. Le dossier de travail est donc votre dossier personnel.

## Librairies
Afin de faciliter l'apprentissage de python dans l'enseignement secondaire, nous construisons quelques librairies qui ont pour objectif de cacher certaines difficultés liées au langage de programmation afin de pouvoir cibler certains points pédagogiques.

- [repere](/librairies/graphique/): Permet l'affichage d'un repère du plan intéractif (zoom, déplacer).
- [entree_tk](/librairies/entree_tk/): Fonctions d'entrées utilisateur avec des fenêtres tkinter.
- [lycee](/libraries/lycee/) : Regroupe les fonctions principales que sont amenés à utiliser les élèves de lycée en mathématiques (toutes filières confondues).


## Quoi de neuf?

Les modifications effectuées par l'équipe de math sont:

- Ajout des librairies [pygame 1.9.4](https://www.pygame.org/), [scipy 1.2.0](https://www.scipy.org/), [numpy 1.16.0rc2](http://www.numpy.org/), [matplotlib 3.0.2](https://matplotlib.org/).

- [customize.py](https://github.com/cspaier/thonny/blob/diderot/Thonny/Lib/site-packages/thonny/customize.py): Le dossier de configuration est dans `%HOMESHARE%/python/.thonny`
- [configuration.ini](https://github.com/cspaier/thonny/blob/diderot/Thonny/Lib/site-packages/thonny/user_dir_template/configuration.ini): Utilisation de l'environement python du frontend.
- [workbench.py](https://github.com/cspaier/thonny/blob/f1c57d3062d60841dea3bdf7e2af93243cd742c9/Thonny/Lib/site-packages/thonny/workbench.py#L205-L208): Le dossier de travail est `%HOMESHARE%/python/`

À ce jour, les modifications permettent de travailler sous Windows©.

## Questions fréquentes
- **Comment télécharger et utiliser thonny?**
Télécharger le dossier compréssé en zip avec ce [lien](https://github.com/cspaier/thonny/archive/diderot.zip). Le décomprésser et double cliquer sur le raccourci `thonny - raccourci`. Cela fonctionne sous Windows© uniquement.
- **Peut-on importer ses propres librairies avec thonny?**
 Oui! Le dossier de travail est le dossier `python` qui se trouve dans votre dossier personnel. Il suffit d'y mettre un fichier `exemple.py` pour pouvoir l'importer avec la commande `from exemple import *`

- **Et pour linux/MacOS ?** Il vous faut installer thonny par vos propre moyens en suivant le [site officiel](https://thonny.org) et ensuite rajouter les librairies du lycée dans votre dossier personel.


## Les versions
- La branche **Diderot**: C'est la version téléchargeable et installée sur les machines du lycée Diderot.
- La branche **dev**: La version en développement. N'hésitez pas à communiquer vos remarques et critiques.
- La branche **thonny-2.17.0** contient la version 2.17.0 de thonny utilisée au lycée jusqu'à janvier 2019.
