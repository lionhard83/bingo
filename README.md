# bingo-tombola
## Installation

    npm install bingo-tombola

## Usage

By popular demand, `bingo-tombola`!

```js
var bingo = require('bingo-tombola');

console.log(bingo.createTable())
var players = bingo.createPlayers(2) // create two players
console.log(bingo.createMatch(players)); // create a new match
console.log(bingo.table.getExtracted()); // get the extracted number
bingo.table.reset(); // start a new match
console.log(bingo.table.getBag()); // get the not extracted number
console.log(bingo.table.extract()); // extract a number

```
Good Luck!
