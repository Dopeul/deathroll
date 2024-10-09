# Deathroll Discord Bot

**Deathroll** est un bot Discord qui recrée le jeu de paris de World of Warcraft, le "Deathroll". Il permet à deux utilisateurs de s'affronter dans une partie où le perdant est celui qui atteint **1** lors de ses jets.

## Fonctionnalités

- Lancer une partie de Deathroll avec la commande `/deathroll @utilisateur`.
- Créer un salon privé pour les deux joueurs mentionnés.
- Simuler les jets de dés via la commande `/roll X`, où X est la valeur maximale du jet.
- La partie se termine quand un joueur atteint **1** lors d'un jet.

## Règles du Deathroll

1. Un joueur lance la commande `/deathroll @joueur2`.
2. Un salon privé est automatiquement créé, et les deux joueurs sont mentionnés pour rejoindre la partie.
3. Les deux joueurs lancent chacun `/roll 100`. Le joueur ayant obtenu le plus grand nombre commence le "deathroll".
4. Le joueur qui commence fait un `/roll 666`.
5. Chaque joueur, à tour de rôle, doit faire un `/roll` avec la valeur maximale du jet précédent.
   - Par exemple, si un joueur obtient 400 sur son jet précédent, le prochain jet devra être `/roll 400`.
6. Le jeu continue ainsi jusqu'à ce qu'un joueur obtienne **1**. Ce joueur perd la partie.

*Optionnel : le joueur perdant est censé payer un montant d'or selon l'accord initial entre les joueurs !*

## Commandes disponibles

### `/deathroll @utilisateur`
- Crée un nouveau channel privé et mentionne les deux joueurs.
- Prépare le terrain pour la partie.

### `/roll X`
- Effectue un jet de dé avec une valeur maximale de `X`. 
- Le résultat du jet détermine la valeur maximale du prochain roll de l'autre joueur.

## Prérequis

- Node.js (version 14+)
- Discord.js
- Un serveur Discord avec les autorisations nécessaires pour créer des salons et mentionner des utilisateurs.

## Installation

Le projet n'est toujours pas terminé.
