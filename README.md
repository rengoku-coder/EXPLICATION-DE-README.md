// EXPLICATION DE PACKAGE-LOCK.JSON
Le fichier package.json est comme la carte d'identité de tre projet. Il contient les informations et les paramètres nécessaires pour gérer ton application Node.js.

Il peut contenir ;

name : le nom du projet;

version : la version du projet;

description : une description du projet;

main : le fichier principal du projet;

scripts : les commandes pour exécuter certaines tâches;

dependencies : les bibliothèques nécessaires au projet;

//EXPLICATION DE INDEX.JS

Le fichier index.js contient le code JavaScript qui réalise les actions de ton programme;

Voici ce qu'il fait ;

require('node:readline') importe le module qui permet de lire les réponses saisies au clavier;

readline.createInterface(...) prépare la lecture et l'affichage dans le terminal;

rl.question(...) demande à l'utilisateur de saisir un nombre;

Number(answer) convertit la réponse en nombre;

console.log(...) affiche le résultat;

rl.close() ferme l'interface de lecture;