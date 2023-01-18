LeVillageDeGosses
===========

Développé par Illies Douhab & Xavier Moyon
Contact : Illies.douhab.etu@univ-lille.fr & Xavier.moyon.etu

# Présentation de LeVillageDeGosses
Il s'agit d'un jeu ludo-pédagogique de mathématique développé en 2022.

Fonctionnement :

Ce jeu peut se jouer de 1 à 2 joueurs (si il n'y a que 1 joueur alors une IA prendra la place du joueur 2).

Les joueurs jouent l'un après l'autre et enchaine des séries de 5 calculs (le type de calcul étant choisi par le joueur (Addition, Soustraction, Multiplication, Division) et permettant de gagner plus ou moins de points).

Pour chaque series de questions les joueurs possede un nombre de vies (3) à chaque erreurs le joueur concerné perd une vie et ne gagne pas ne remporte pas les points de la questions mais peut toujours continuer. Cependant si le joueur perd toutes ses vies il perd la moitié des points qu'il aurait pu gagner (si il avait reussi toutes les questions).

La partie se termine lorsque un joueur atteind les 500 points, un historique de la partie s'affiche alors.


    Partie professeur :
il est possible lors du lancement du jeux de consulter l'historique en mettant '2' ou '3' au lancement du logiciel avec le mot de passe : "WeLoveEL"



# Utilisation de ConjuGator

Afin d'utiliser le projet, il suffit de taper les commandes suivantes dans un terminal :

```
./compile.sh
```
Permet la compilation des fichiers présents dans 'src' et création des fichiers '.class' dans 'classes'

```
./run.sh LeVillageDeGosses
```
Permet le lancement du jeuS
