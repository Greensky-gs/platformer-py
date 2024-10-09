# Cahier des charges

Cahier des charges des attentes du projet

## Librairie et modules

Le projet doit être codé en [Python 3.10](https://www.python.org/downloads/release/python-3100/), avec la librairie [p5](https://pypi.org/project/p5/)

## Cahier des charges

| Fonctionnalité | Implémentation | État |
|:--:|:--:|:--:|
| [Niveau de plateformer](#niveau) | Implémentation par Classe | ❌ |
| [Plateforme](#plateforme) | Implémentation par une classe | ❌ |
| [Porte](#porte) | Implémentation par une classe | ❌ |
| [Personnage](#personnage) | Implémentation par une classe | ❌ |
| [Liste des cadeaux](#cadeaux) | Implémentation par une pile ou une file | ❌ |
| [Organisation en modules](#organisation) | Différents dossiers et fichiers dans le projet | 🚧 |

##### Signification des signes

| Signe | Signification |
|:--:|:--:|
| ❌ | Non-implémenté |
| ✅ | Implémenté |
| 🚧 | En cours d'implémentation |
| 🚫 | Non-implémentable |
| ➖ | Fonctionnalité abandonnée |

## Liste détaillée des fonctionnalités

La liste détaillée des fonctionnalités à implémenter

> Le jeu doit avoir une taille de `800` par `600` pixels

### Niveau

Un niveau comporte une [porte d'entrée](#porte) en bas et une [porte de sortie](#porte) en haut.
> Le fond est noir, avec potentiellement des décorations telles que des étoiles ou des petites formes.
> ⚠️ Le fond ne **doit pas** être trop chargé.

Il doit y avoir plusieurs [plateformes](#plateforme) qui permettent au joueur de se déplacer verticalement et horizontalement.
> Le nombre de plateformes dans un niveau doit être compris entre **8** et **12**.

#### Porte

Une porte est un passage entre avant le niveau, qui permet l'apparition du joueur, ou après le niveau qui permet de marquer la fin du niveau et ainsi permettre la "sortie" du joueur.

> Design: La porte doit être noire, rectangulaire avec les coins supérieurs arrondis de façon à former un arc de cercle sur le dessus.

#### Plateforme 

Une plateforme est un sol semi-solide, que le joueur peut traverser uniquement en passant par dessous. Si il passe par dessus

### Personnage

### Cadeaux

### Organisation
