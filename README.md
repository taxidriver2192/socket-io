# socket-io

Det er det bliver første opgave ud af mange, for at forstå hvordan framework'et virker.
Hvad er fordelen ved socket-io?

Normalt er det ikke svært at give en update ud til en Person, en update på fx en user id?

Problemet er bare ofte at for at jeg kan gøre dette, skal jeg have et script der kontrollere om der er sket en update hvert sekund på siden.
Det er ikke noget problem hvis det kun er en user, men forestille dig at 1000 bruger på samtidig..

Her der laver jeg ikke åbne forbindelse, og den sender beskeden ud kun hvis der skete en update. 
Dette kommer til at kunne have nogle fede funktionaliteter, som jeg først er klar over når jeg har fundet ud af hvordan man bruger det er det mest optimale!

## Hvad kan dette program?

Dette program er ganske simpel en simpel chat, det er eneste du skal gøre for at få den til at virke.
```
git clone https://github.com/taxidriver2192/socket-io.git
```
der efter instller alle dependencies
```
npm i
```
køre programmet.
```
node index.js

Besøge siden på localhost:3000
