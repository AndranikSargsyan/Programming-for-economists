## Problem 1: Monty Hall problem

![Image of Monty Hall problem](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Monty_open_door.svg/1200px-Monty_open_door.svg.png)

**The Monty Hall problem** is a brain teaser, in the form of a probability puzzle, loosely based on the American television game show *Let's Make a Deal* and named after its original host, Monty Hall.
The problem is as follows:

*Suppose you're on a game show, and you're given the choice of three doors: Behind one door is a car; behind the others, goats. You pick a door, say No. 1, and the host, who knows what's behind the doors, opens another door, say No. 3, which has a goat. He then says to you, "Do you want to pick door No. 2?" Is it to your advantage to switch your choice?*

**Objective**

Create Monte Carlo simulation of Monty Hall problem and print the probabilites of finding car when switching the choice and when not switching.

**Requirements**
* Ask the user of how many iterations to make for simulation
* Make the simulation verbose. For each iteration of simulation print the door number behind which is the car, print contestant's choice, print which door host opens from remaining two, print whether contestant switches his choise and print if he wins or looses. Result should be something like this for each iteration:

```
Prize is behind door 2
Contestant chooses door 1
Host opens door 3
Contestant switches from door 1 to door 2
Contestant Won!

Prize is behind door 3
Contestant chooses door 2
Host opens door 1
Contestant doesn't switch the door
Contestant Lost!
```
* After simulation is complete print the probabilites of winning a car when switching the choice and when not switching the choice:
```
Probability of winning when switching: 66.7%
Probability of winning when NOT switching: 33.3%
```