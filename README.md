# Forklaring på Variabler

## Hvad er en variabel
Vi opretter en variabel for at kunne tildele den en værdi der kan ændre sig løbende når vi arbejder med den.

## oprettelse af variabler (deklarering af varabler)
```js 
var fornavn = "Camilla";
```
I dette ekesempel opretter jeg en variabel hvor jeg kalder selve varabelen for fornavn og tildeler den værdien "Camilla"

### plinger 
"Camilla" er skrevet i plinger fordi et er en string som betyder at den skal tildelses som en tekst, altså præcis det der står i mellem plingerne.

Hvis ikke der havde været skrevet plinger rundt om "Camilla" havde den troet at Camilla var en variablen som forsøgte at overskrive en tidligere variabel.

Der må derfor heller ikke være plinger rundt om **fornavn** for så ville den tro at det er en tekst som skal tildeles.

```js
var fornavn = "Camilla";

fornavn = "sebastian";

```