# Atelier d'initiation au la reconnaissance d'entités nommées avec Spacy

Activité conçue pour le consortium HumaNum Ariane, pour une formation à Lyon le 9 novembre 2023.

| 🏃 Accès direct aux supports 👇 | |
|-------|-------|
| [![](https://img.shields.io/badge/Pr%C3%A9sentation-Ouvrir%20dans%20Google%20Slides-orange?logo=googleslides)](https://docs.google.com/presentation/d/1_RycfOOeQo8XZNojsx7SzaSDyhepj-8n8w7xMpf9UGI/edit) | [![](https://img.shields.io/badge/Notebook-Ouvrir%20dans%20Google%20Colab-blue?logo=googlecolab)](https://colab.research.google.com/github/jchazalon/hn-ariane-ner-tuto-2023/blob/main/preparation/30-draft-final.ipynb)  | 

## Contenu de l'activité

Cette activite repose sur 2 ressources pédagogiques auto-contenues :
1. un [jeu de *slides*](https://docs.google.com/presentation/d/1_RycfOOeQo8XZNojsx7SzaSDyhepj-8n8w7xMpf9UGI/edit#slide=id.p),
2. un [notebook](https://colab.research.google.com/github/jchazalon/hn-ariane-ner-tuto-2023/blob/main/preparation/30-draft-final.ipynb) qu'il est possible d'utiliser directement sur Google Colab.

Cette activité est sensée durer un peu **moins d'une heure** pour une exploration en surface.

Elle s'adresse à un public de **jeunes chercheurs en sciences humaines et sociales** souhaitant **renforcer leurs compétences en humanités numériques**.

Les **pré-requis** sont les suivants :
- Niveau débutant en Python
- Connaissance de Jupyter/Colab (notebooks)
- Connaissance des tâches classiques en TAL
- Notions en apprentissage artificiel (ML)

La **méthode pédagogique** retenue est celle de la résolution d'un problème concret simplifié de bout en bout, de façon à rendre les apprenants autonomes dans la réutilisation de ces connaissances et outils sur des données qui les intéressent.
L'utilisation de la bibliothèque [Spacy](https://spacy.io/) a été retenue pour sa polyvalence, sa maturité et la qualité de sa documentation.

## Sources, licences et auteurs
Cet atelier est largement tiré du cours “[NLP avancé avec Spacy](https://course.spacy.io/fr)” réalisé par [Ines Montani](https://twitter.com/_inesmontani) (créatrice de [Spacy](https://spacy.io/)) sous [licence MIT](https://www.tldrlegal.com/license/mit-license).
Cette licence nous autorise à reprendre, modifier et diffuser son contenu tant que nous indiquons la licence originale :

>The MIT License (MIT)
>Copyright (C) 2019 Ines Montani
>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Les données de cet atelier sont adaptées du “[French ELTEC NER Open Dataset](http://hdl.handle.net/20.500.11752/OPEN-986)” par Carmen Brando, Francesca Frontini, et Ioana Galleron sous licence [Creative Commons - Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/). 

> Brando, Carmen; Frontini, Francesca and Galleron, Ioana, 2022, French ELTEC NER Open Dataset, ILC-CNR for CLARIN-IT repository hosted at Institute for Computational Linguistics "A. Zampolli", National Research Council, in Pisa, [http://hdl.handle.net/20.500.11752/OPEN-986](http://hdl.handle.net/20.500.11752/OPEN-986).

Ce cours et les données associées sont sous licence [Creative Commons - Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/).
Pour citer ce travail, merci d'indiquer :

> Consortium HumaNum Ariane, Joseph Chazalon, Atelier d'initiation à l'extraction d'entités nommées, en ligne: <https://github.com/jchazalon/hn-ariane-ner-tuto-2023>, 9 novembre 2023, Lyon.


## Préparation des supports à destination des apprenants

TODO décrire l'organisation des fichiers

FIXME décrire fonctionnement script makefile? procédure export? hébergement des données via github releases? plutôt faire un git clone directement ?
(jupyter filter pour supprimer les cellules taggées "Teacher" du notebook et produire fichier de sortie à commit également ici pour simplifier, + dataset dans la release ou y accéder en raw via github)

