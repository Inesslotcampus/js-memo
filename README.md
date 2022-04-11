# js-memo

## Base

### Console:

__Pannel affichage d'importants messages comme les erreurs pour les dev. Si on veut voir des choses apparaitre, on peut faire un print ou log directement sur la console.__

- console keyword fait référence à un objet, une collection d'actions et de données.

- console.log() c'est ce qu'il y a entre les parenthèses qui va être afficher ou log dans la console.
- console.log('blabla')
- console.log(true)
- console.log(null)
- console.log(undefined)

### Commentaire

- (//) = à côté du code
- (*//*) = comment une grande partie du txt

### Arithmetic Operators

- Add: +
- Subtract: -
- Multiply: *
- Divide: /
- Remainder/modulo: %

### String Concatenation

console.log('front ' + 'space'); 
// Prints 'front space'
console.log('back' + ' space'); 
// Prints 'back space'
console.log('no' + 'space'); 
// Prints 'nospace'
console.log('middle' + ' ' + 'space'); 
// Prints 'middle space'

### Properties

console.log('Hello'.length);
//print 5

### Method

- console.log('hello'.toUpperCase()); // Prints 'HELLO'
- console.log('Hey'.startsWith('H')); // Prints true
- console.log('    Remove whitespace   '.trim()); //Print Remove whitespace
- console.log(Math.random()); // Prints a random number between 0 and 1
- console.log(Math.floor(Math.random() * 50)); // Prints random number beteween 0 and 50
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math
- https://www.codecademy.com/resources/docs/javascript


Array.filter


## Variable

- const nmVariable = on ne peut pas modifier la variable; protée dans un bloc; instancier 1 fois
- let nomVariable = on peut modif la variable ; protée dans un bloc; instancier 0 à n fois
- var nomVariable =  instancier 0 à n fois

- var kelvins = prompt("Quelle est la température en Kelvins aujourd'hui ?"); demande à l'utilisateur quelle est la température 

## Conditional Statements

- racourcis de if/else = isNightTime ? console.log('Turn on the lights!') : console.log('Turn off the lights!');
- switch (groceryItem) {
  case 'tomato':
    console.log('Tomatoes are $0.49');
    break;
    
 ## Function
 
 __série d'instruction dans un bloc__
 
 ##Scope
__An important idea in programming is scope. Scope defines where variables can be accessed or referenced.__

## objet 

var nmVar= {};
this = permet de modifier dans 1 objet;

### propriétés 

- attributs
- - method

