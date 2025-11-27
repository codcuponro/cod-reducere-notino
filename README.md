# Cod Reducere Notino

O colecție de coduri de reducere Notino. Le folosim pentru testarea cuvintelor cheie cod reducere Notino, voucher Notino, cupon Notino, și cod promotional Notino de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-notino` prin NPM:

```bash
npm install cod-reducere-notino
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-notino')

console.log(codes)

// [
//   {
//     site: 'https://www.notino.ro',
//     cod_reducere: 'NOTINO10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la parfumuri'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-notino a fost creat de echipa de la Cuponescu pentru a ajuta cu testarea.

https://www.cuponescu.ro

