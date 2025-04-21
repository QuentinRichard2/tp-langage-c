 Projet : Application de Calcul Mental en C
 Description du projet
Ce projet est une application en langage C qui propose à l'utilisateur une série d'exercices de calcul mental : addition, soustraction, multiplication et division. L’objectif principal est d’entraîner les utilisateurs à effectuer rapidement des opérations arithmétiques simples tout en introduisant des concepts fondamentaux de programmation.

L’application est interactive, propose un système de score dynamique, enregistre les performances de l’utilisateur dans un fichier, et permet de les recharger à chaque session.

⚙ Instructions d’installation et d’utilisation
1. Installation
Aucune installation spécifique n’est requise. Il suffit d’avoir un compilateur C installé sur votre système.

2. Compilation du programme
Sur un terminal (Linux, macOS ou Windows avec MinGW) :

gcc -o calcul_mental main.c

ou si vous avez plusieurs fichiers :

gcc -o calcul_mental main.c fonctions.c -Wall

3. Lancement de l’application
./calcul_mental

Une fois le programme lancé, l'utilisateur peut choisir le type d'opération qu'il souhaite pratiquer. À la fin des exercices, le score est affiché et sauvegardé.

 Prérequis et outils utilisés
 Prérequis
Connaissances de base en C (variables, fonctions, boucles, conditions)

Notions d’arithmétique élémentaire

 Outils utilisés
Langage C

Compilateur GCC

Éditeur de texte (comme VS Code, Code::Blocks, Sublime Text ou autre)

Bibliothèques standards C : stdio.h, stdlib.h, time.h, string.h
