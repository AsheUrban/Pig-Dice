## Pig Dice

#### By _Ashe Urban,_ _Mitchell Gantz,_ _Jackson Levine,_ _Jacob Maier_ & _John Lenz_

## Technologies Used

* _HTML_
* _CSS_
* _JS_

## Description

#### _A game of chance!_

_Write a program where two users can play Pig dice against each other. Start with your business logic, and once it is completed move onto your user interface logic._

_Make sure that your user interface and business logics are clearly separated, and practice separation of concerns when designing your user interface function._

_Link to lesson:_ https://www.learnhowtoprogram.com/intermediate-javascript/object-oriented-javascript/game-of-choice-two-day-project


## Setup/Installation Requirements
* _Clone or download this repository to your local._
* _Navigate to the top level of the directory and launch live server._

## Known Bugs

* _None_

## License
* MIT

## Contact Information
_If you run into any issues or have any concerns, feel free to [Contact me: ashe@goldentounge.com](mailto:ashe@goldentongue.com), or request to make any contributions to my code._

Copyright (c) _February 2023_ _Ashe Urban_


## Manual Testing
Describe: Dice

Test: It should create a dice object
Code: let newDice = new Dice()
Expected Output: newDice(0)

Test: It should roll a random number between 1-6
Code: Math.random()*6
Expected Output: a random number between 1-6

Test: It should add a random number to the roundScore
Code: this.roundScore += this.number
Expected Output: this.roundScore += this.number

Test: It should 0 out roundScore if this.number === 1
Code: if(this.number ===1), this.roundScore = 0
Expected Output: this.number =1, this.roundScore =0

Test: It should add roundScore to TotalRound
Code: Dice.prototype.TotalRound();
Expected Output: this.totalScore += this.roundScore

Test: It should determine a winner after 10+ points
Code: if(this.totalScore >10)
Expected Output: console.log(totalScore);