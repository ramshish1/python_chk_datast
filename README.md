# 🐍 Projet Python : Structures de Données et Fonctions Intégrées

Bienvenue dans cette série d'exercices Python. L'objectif de ce projet est de développer et de renforcer votre compréhension de la programmation Python, en mettant un accent particulier sur la manipulation des structures de données fondamentales (Listes, Tuples, Dictionnaires, Ensembles) et l'utilisation des fonctions intégrées.

## 🚀 Liste des Exercices

Ce répertoire contient (ou contiendra) les scripts et solutions répondant aux 6 défis suivants :

### 1. Multiplication des éléments d'une liste
- **Objectif** : Écrire un programme Python qui parcourt une liste numérique et calcule le produit de tous ses éléments.
- **Exemple d'entrée** : `[2, 3, 6]`
- **Résultat attendu** : `36`

### 2. Tri personnalisé d'une liste de tuples
- **Objectif** : Obtenir une liste triée par ordre croissant en se basant exclusivement sur le **dernier élément** de chaque tuple. L'utilisation de la méthode `sort()` ou de la fonction `sorted()` avec une clé personnalisée (ex: fonction `lambda`) est recommandée.
- **Exemple d'entrée** : `[(2, 5), (1, 2), (4, 4), (2, 3), (2, 1)]`
- **Résultat attendu** : `[(2, 1), (1, 2), (2, 3), (4, 4), (2, 5)]`

### 3. Fusion de dictionnaires avec addition des valeurs
- **Objectif** : Combiner deux dictionnaires distincts. Pour les clés qui sont communes aux deux dictionnaires, le programme doit additionner leurs valeurs respectives.
- **Exemple d'entrée** : 
  - `d1 = {'a': 100, 'b': 200, 'c': 300}`
  - `d2 = {'a': 300, 'b': 200, 'd': 400}`
- **Résultat attendu** : `{'a': 400, 'b': 400, 'd': 400, 'c': 300}`

### 4. Génération de dictionnaire (Carrés)
- **Objectif** : À partir d'un nombre entier `n` donné, générer un dictionnaire dont les clés vont de `1` à `n` (inclus) et les valeurs correspondent au carré de chaque clé (`i*i`).
- **Exemple d'entrée** : `8`
- **Résultat attendu** : `{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}`

### 5. Tri par élément flottant
- **Objectif** : Trier une liste de tuples (où chaque tuple contient un nom d'item et une valeur sous forme de chaîne de caractères) en fonction de l'élément flottant (le 2ème élément) par ordre décroissant.
- **Exemple d'entrée** : `[('item1', '12.20'), ('item2', '15.10'), ('item3', '24.5')]`
- **Résultat attendu** : `[('item3', '24.5'), ('item2', '15.10'), ('item1', '12.20')]`

### 6. Manipulation avancée des Ensembles (Sets)
- **Objectif** : Explorer les fonctionnalités des ensembles (`set`) en Python. Le script doit effectuer les opérations suivantes :
  1. Créer un ensemble (ex : `{0, 1, 2, 3, 4}`).
  2. Itérer sur les éléments de cet ensemble (ex: avec une boucle `for`).
  3. Ajouter un ou plusieurs nouveaux membres à l'ensemble.
  4. Retirer (supprimer) des éléments spécifiques de l'ensemble de départ.
