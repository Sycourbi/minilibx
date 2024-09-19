# MiniLibX

![MiniLibX](https://img.shields.io/badge/graphics-MiniLibX-yellow)
![C Language](https://img.shields.io/badge/language-C-blue)
![2D Graphics](https://img.shields.io/badge/graphics-2D%20Rendering-orange)
![Platforms](https://img.shields.io/badge/platforms-Linux%20%7C%20MacOS-lightgrey)
![42](https://img.shields.io/badge/school-42-green)
![42 Paris](https://img.shields.io/badge/42-Paris-blue)



# Description
MiniLibX est une bibliothèque graphique légère conçue pour les environnements UNIX-like. Elle est utilisée principalement pour la création d'applications graphiques simples et de jeux 2D. MiniLibX facilite la gestion des fenêtres, des images, et des événements utilisateur, et est souvent utilisée dans des projets de programmation académique ou personnelle.

# Fonctionnalités
Création et gestion de fenêtres graphiques.
Dessin d'images et de formes géométriques simples.
Gestion des événements de l'utilisateur tels que les clics de souris et les frappes clavier.
Support des images au format XPM.

# Inclure MiniLibX dans votre projet

Assurez-vous que votre Makefile inclut les options de compilation pour MiniLibX. Par exemple :
```
CFLAGS = -I/usr/include -I/usr/local/include
LDFLAGS = -L/usr/lib -lmlx -lXext -lX11 -lz -lm
```
# Exemples d'utilisation

- **[so_long](https://github.com/Sycourbi/so_long)** : Un projet qui utilise MiniLibX pour afficher et gérer un jeu de labyrinthe en 2D.
- **[cub3d](https://github.com/Sycourbi/cub3d)** : Un projet qui utilise MiniLibX pour créer un moteur de jeu 3D simple en utilisant la technique de raycasting.
