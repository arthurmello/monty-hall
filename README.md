# Monty Hall Simulator

This is a simulation of the famous Monty Hall problem, done in R.

## Full description
Monty Hall was the original host of a television show called "Let's Make a Deal". The format is quite simple:
There are 3 doors. Behind one of them there's a car, and behind 2 of them there's a goat. You have to pick one of the doors
and your prize will be whaterver's behind it (obviously you want the car).

Once you have picked a door, the host - Monty Hall - chooses, out of the 2 other doors left, one that has a goat behind it.
Then, he gives you the choice between sticking to your previously chosen door, or switching. What do you do?

Here is where this problem has raised a lot of furor: our intution tells us there is no difference between changing
doors or sticking to our choice, both hold a 50% of hiding the car. A closer look reveals, however, that it is indeed
beneficial to change - it will actually double your chances of winning.

Here is a full description of the problem and its solution: https://en.wikipedia.org/wiki/Monty_Hall_problem.

If you don't believe it, however, this script simulates the game 1000 times and show the winning rates for each strategy:
changing doors or sticking to the first door. As expected, results are consistent with the calculations.
