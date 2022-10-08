# Lab 2
## Repository
https://github.com/JanaClaessens/DEV5-LAB2

## Recente JS feature
String padding zorgt ervoor dat je op een efficiënte manier
getallen of tekst vooraan (padStart) of achteraan (padEnd) kan toevoegen aan reeds ingegeven getallen of tekst.

```js
> '7'.padStart(3, '0')
'007'
> 'hallo'.padEnd(10, '!')
"hallo!!!!!"
> 'hallo :)'.padEnd(10, '!')
"hallo :)!!"
```

Dit kan bv handig zijn wanneer er gevoelige info ingevuld wordt in een formulier en deze niet helemaal leesbaar mag zijn. (bv: gsmnummer, wachtwoord...)

```js
let gsmNummber = "0492773311"
let eersteVier = gsmNummber.substr(0, 4)
eersteVier.padEnd(gsmNummber.length, "*")
> '0492******'
```