# Funksjoner

> **MDN-dokumentasjon**:
* [Function statements (function declarations) ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function)
* [Function expressions ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function)
* [Arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

Man kan definere en funksjon i JavaScript på ulike måter, som igjen kan gi ulik oppførsel. Sjekk MDN-dokumentasjonen vi har lenket til øverst for å bli kjent med hva som skiller dem fra hverandre og ikke minst *hvorfor* de oppfører seg sånn.

```javascript
// Function statement
function myFunction() {
}

// Function expression
const myFunction = function() {
}

// Arrow function
const myFunction = () => {};
```

## Arrow functions
Arrow functions er kanskje syntaksen som er mest fremmed av måtene man kan definere funksjoner på over. De er kortere, og dermed mer lesbare i enkelte situasjoner, som her hvor vi sender en anonym funksjon inn til map:

```javascript
// Klassisk funksjonsdeklarasjon
[1,2,3].map(function(n) {
   return n * 2;
 });

// Arrow function
[1,2,3].map(n => n * 2);
```

> En [anonym funksjon](https://en.wikipedia.org/wiki/Anonymous_function) er en funksjon som bare finnes akkurat der den er definert, og som ikke er bundet til noen variabel.

> Du kan lese mer om `map`-funksjonen som brukes over i seksjonen om nyttige [listeoperasjoner]().

## Oppgaver
* [Funksjoner](http://jsbin.com/nahugen/4/edit?js,console)
* [Arrow functions](http://tddbin.com/#?kata=es6/language/arrow-functions/basics)
