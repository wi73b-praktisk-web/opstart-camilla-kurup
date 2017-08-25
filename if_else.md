# Forklaring på if og else 

En if sætning bruges til at få en specefik handling igenenm som vi bestemmer. 

## if eksempel

```js
if(true){
    console.log ("kodeblokken udføres");
}
```
I koden ovenfor bestemmer vi at hvis udsagnet (som vil være angivet i en varianel) længere oppe er sand, skal koden udøres. inde i krølleparanteserne fortæller vi så at den skal udskrive i consollen (terminalen) med teksten (en string) at "koden udføres"

Efter if starter og lukker vi altid først en () og {} når dette er gjort arbejder vi med indeholdet i disse paranteser

## else eksempel

```js
if(true){
    console.log ("kodeblokken udføres");
}else{
    console.log ("kodeblokken springes over");
}
```
når vi giver vores if sætning en else fortæller vi hvad koden skal gøre hvis den ikke er true, altså i dette tilfælde falsk. Vi bruger ingen () men kun {}

## var - if - else eksempel

```js
var navn = "Carl";

if(navn == "Albert"){
   console.log('lander kun her hvis navn er Albert');
}else if(navn == "Benny"){
   console.log('lander kun her hvis navn er Benny');
}else{
   console.log('lander her hvis navn noget andet end Albert eller Benny');
}
```