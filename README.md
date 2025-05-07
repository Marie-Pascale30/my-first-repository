# my-first-repository
console.log("bonjour!")

// Declaration de variables
//1. utilisation du let
/*
"let" permet de declarer une variable dont la valeur va lui etre reassignee plus tard
*/

let nombre = 5; // 1ere affectation
console.log(nombre);

// on peut reassigner sns redeclarer

nombre = 50;

console.log(nombre);

let prenom = "Marie"
console.log(prenom);

/*
Les noms de variable ne commencent jamais par un chiffre
par exemple "1er nbre" serait incorrect, on prefere "premierNombre"
*/

// 2. Utilisation du var
/*
var est l'ancienne facon de declarer des variables en javascript.
*/

var x=10;
console.log(x)
var x=20;     

// 3. Utilisation du const
/*
Le const sert  a declarer une constante
*/
const pi = 3.14;
console.log(pi);

//=============================================================
// Types de donnees courants
//=============================================================

// --------- A) Les nombres (integer, float)

let nbreEntier = 42;
let nbreFlottant = 13.5;

// ---------- B) Le Boolean
let isMajeur = false;
let isAdmin = true;

// ---------- C) Les chaines de caracteres 

let nomSio = "Mukilan";
let prenomCiel = "Ghadji";
let age = 20;

// Concatenation

let presentation = "je m'appelle "+ prenomCiel +" "+nomSio+" et j'ai "+age+" ans. "

console.log(presentation)

// concatenation moderne et lisible

let presentation2 = `Je m'appelle ${prenomCiel} ${nomSio} et j'ai ${age} ans`;

console.log(presentation2)

//=================================================================
// 4. Verification du type de variables
//=================================================================

console.log(typeof nombre);
