## Snowman :snowman:  [Command Line Javascript Application]
**_A guessing game in which you attempt to guess a word, letter by letter._**
![Gameplay Giphy](https://github.com/teyannaearle/Snowman-Game/blob/main/SnowmanGiphy.gif?raw=true)

### Local Setup 
1. Clone to a local repo of your choosing: 
```$ git clone https://github.com/teyannaearle/Snowman-Game.git```
2. Cd into directory: ```$ cd Snowman-Game```
3. Install NPM: ```$ npm install```
4. Run and Play Snowman!! ```$ node Snowman.js ``` 

### Dependencies

* __readlineSync__ Used to communicate with user via console

``` const readline = require('readline-sync'); ``` 

```javascript 
readline.keyInYNStrict("Want to play again?") ? replay() : quitGame() 

// User enters Y or N to either replay or quit game
```
