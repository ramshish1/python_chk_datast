# 🧮 Projet Python : Calculatrice Simple

Bienvenue dans ce mini-projet Python ! L'objectif ici est de développer une application console permettant d'effectuer des calculs arithmétiques basiques entre deux nombres.

## 🎯 Objectif du Projet

Créer une application de calculatrice simple en Python, capable d'effectuer des opérations d'addition, de soustraction, de multiplication et de division. Le programme doit interagir avec l'utilisateur pour récupérer les nombres ainsi que l'opérateur souhaité, puis effectuer le calcul et afficher le résultat.

### 📝 Exemple d'exécution

```text
Entrez le premier nombre : 10
Entrez le deuxième nombre : 5
Entrez l'opérateur (+, -, *, /) : *

Le résultat est : 50
```

## 🛠️ Instructions d'implémentation

Pour mener à bien ce projet, le script Python devra suivre et respecter les étapes suivantes :

1. **Définition de la fonction** : 
   - Créer une fonction nommée `calculatrice` qui accepte deux arguments numériques (`num1` et `num2`).
2. **Saisie utilisateur** : 
   - Demander à l'utilisateur de saisir un opérateur arithmétique valide parmi `+`, `-`, `*`, `/`.
3. **Logique conditionnelle** : 
   - Utiliser des instructions conditionnelles (`if / elif / else`) pour déterminer l'opération mathématique à appliquer en fonction de l'opérateur saisi.
4. **Retour du résultat** : 
   - La fonction doit effectuer le calcul et retourner le résultat final, qui sera ensuite imprimé à l'écran.
5. **Gestion des Erreurs (Exceptions)** :
   - **Division par zéro** : Prévoir une vérification pour empêcher la division par zéro et afficher un message d'erreur approprié.
   - **Opérateur invalide** : Gérer les cas où l'utilisateur saisit un caractère qui ne correspond à aucun des 4 opérateurs de base.
6. **Fonctionnement en continu (Bonus)** :
   - *Amélioration* : Intégrer une boucle `while` autour de la logique principale pour permettre à l'utilisateur de faire plusieurs calculs à la suite sans avoir à relancer le programme à chaque fois. (N'hésitez pas à agrémenter d'un message convivial pour quitter le programme !).

---
*Note : Ce projet est un excellent exercice pour maîtriser la création de fonctions, l'utilisation des structures conditionnelles et la gestion basique des entrées utilisateur en Python.*
