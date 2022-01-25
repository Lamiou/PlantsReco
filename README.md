# PlantsReco


FR : Le projet PlantsReco a pour but d'utiliser le Machine Learning pour reconnaitre différents type de plantes, juste en prenant une photo.

## Pour commencer


## Pré-requis
Afin de pouvoir éxécuter l'application sur votre poste, vous devez installer (si ce n'es pas déjà le cas) les dépendences suivante: 
  * Python => 3.10
  * Numpy => Last version stable 
  * Pandas => Last version stable 
  * matplotlib.pyplot => Last version stable
  * Fastai
  * 

## Installation 
Afin de pouvoir affiner le model il vous faut donc installer les dépendences ci-dessus.

Installation Fast AI:
``` pip install -Uqq fastbook ```

Veuillez importer les features suivant si elle ne le sont pas :
```
from fastai.vision.widgets import *
from fastai.vision.all import *
import fastbook
fastbook.setup_book()
```

## Exécution
Pour utiliser le model déjà préentrainer veuillez télécharger le fichier suivant :
https://drive.google.com/file/d/1fV7sV09nsrzp1GIm_CqgQIl81KnvO2mH/view?usp=sharing

Pour éxécuter le model veuillez procéder de la façon suivante:
```learner = load_learner('<pathToModel>/models.pkl')
   <yourVariable>,_,probs = learner.predict(img)
```

## Versions 

Dernière version stable : None 
Dernière version unstable : 0.3

## Auteurs 

* **Adrien REYMANN** _alias_ [@Lamiou](https://github.com/Lamiou)

