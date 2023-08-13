# Générateur de Nombres Premiers - PRIME1

## Description

Ce programme Python vise à aider Peter à générer des nombres premiers pour son cryptosystème. La tâche consiste à générer tous les nombres premiers entre deux nombres donnés pour plusieurs cas de test.

## Entrée

L'entrée se compose du nombre de cas de test, 't', sur la première ligne. Chacune des 't' lignes suivantes contient deux entiers 'm' et 'n' (1 <= m <= n <= 1000000000, n-m <= 100000), séparés par un espace. 'm' et 'n' représentent l'intervalle pour lequel les nombres premiers doivent être générés.

## Sortie

Pour chaque cas de test, le programme affichera tous les nombres premiers 'p' tels que m <= p <= n, chaque nombre étant affiché sur une ligne distincte. Les cas de test seront séparés par une ligne vide.

## Algorithme

L'algorithme utilisé pour générer les nombres premiers dans l'intervalle donné est le Crible d'Eratosthène. C'est une méthode efficace pour trouver tous les nombres premiers jusqu'à une limite donnée 'n'.

## Complexité

La complexité temporelle du programme est approximativement O((n - √n) log log n), où 'n' représente la borne supérieure de l'intervalle donné.

## Comment exécuter

1. Assurez-vous d'avoir Python installé sur votre système.
2. Enregistrez le code dans un fichier nommé 'prime_generator.py'.
3. Ouvrez un terminal ou une invite de commande dans le répertoire contenant le fichier 'prime_generator.py'.
4. Exécutez le programme en lançant la commande : `python prime_generator.py`.
5. Entrez le nombre de cas de test et les valeurs 'm' et 'n' correspondantes lorsqu'ils sont demandés.
6. Le programme affichera les nombres premiers dans l'intervalle spécifié pour chaque cas de test.

