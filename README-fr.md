# Unity - Jeu Android Snake - XAMK University Online Course Project

---

## Langues README :

[![EN](https://img.shields.io/badge/lang-EN-red.svg)](https://github.com/Ralh19/TheReturn/blob/main/README.md)

---
## Technologies Utilisées :

|<a title="Unity Technologies, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Unity_Technologies_logo.svg"><img width="128" alt="Unity Technologies logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/Unity_Technologies_logo.svg/128px-Unity_Technologies_logo.svg.png"></a>| <a title="Microsoft, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Visual_Studio_Code_1.35_icon.svg"><img width="64" alt="Visual Studio Code 1.35 icon" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/64px-Visual_Studio_Code_1.35_icon.svg.png"></a> | <a title="Jason Groce, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:C_Sharp_wordmark.svg"><img width="64" alt="C Sharp wordmark" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/C_Sharp_wordmark.svg/64px-C_Sharp_wordmark.svg.png"></a> 
|-|-|-|

- [**Unity**](https://unity.com/fr) : Le moteur de jeu utilisé pour ce projet
- [**Visual Studio Code**](https://code.visualstudio.com/) : L'environnement de développement intégré (IDE) utilisé pour saisir les scripts du projet 
- [**C# (CSharp)**](https://fr.wikipedia.org/wiki/C_Sharp#:~:text=C%23%20est%20un%20langage%20de,ou%20des%20bibliothèques%20de%20classes.) : Langage utilisé dans tous les fichiers scripts du projet.

---
## Introduction : 

Ce projet est un simple jeu basé essentiellement sur du texte créé à partir du moteur de jeu Unity. Il s'agit de l'un des devoirs que j'ai dû rendre lors de ma formation en ligne "INTRODUCTION TO VIDEO GAMES CREATION" proposée par "XAMK South-Eastern Finland University of Applied Sciences" (35 ECTS). Ce projet m'a permis de découvrir les bases du moteur de jeux Unity ainsi que du langage C#.

---
## Comment jouer : 

Le jeu possède des mécaniques vraiment simples : Vous avez une interface basique divisée en deux champs distincts, celui d'affichage et celui de saisie de texte. Le champ d'affichage est globalement là où la quasi-totalité du jeu va être affichée : le texte décrivant la situation (où vous êtes, ce que vous voyez, et où vous pouvez aller), toutes les commandes possibles et utilisables (ainsi que le résultat de leur utilisation). Le jeu complet se joue à partir de ces mêmes commandes.

Les commandes sont :
- `help`: Pour afficher toutes les commandes disponibles et utilisables;
- `go + "direction"` ***directions :"north," "south," "east," "west"*** : Pour vous déplacer dans la direction indiquée, tout dépendant la possibilité que votre localisation vous offre;
- `inventory`: Pour accéder à votre inventaire;
- `get`: Pour récupérer un item dans votre inventaire ou dans le lieu où vous vous trouvez;
- `examine`: Pour examiner quelque chose se trouvant dans votre localisation actuelle;
- `talkto`: Pour engager la conversation avec un PNJ se trouvant dans votre localisation;
- `say`: Pour dire quelque chose au PNJ (après avoir engagé la conversation avec la commande `talkto`);
- `use + "nom de l'item"`: Pour utiliser un item.

L'objectif du jeu est tout simplement de suivre toute l'histoire en utilisant correctement les commandes montrées ci-dessus.

---
## Images du Gameplay: 

![theReturn-gameplay](https://github.com/Ralh19/TheReturn/assets/145393792/26cb1340-2099-405a-ae91-dbcad50c3f97)