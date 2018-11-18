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

## Problem 2: Optimize it!

![function graph](https://github.com/AndranikSargsyan/Programming-for-economists/blob/master/Week4/Resources/graph_1.png)

Approximate the minimum point of the following function using Newton–Raphson method and compute the value at that point (minimum).

![0.05 * x ^ 4 + 0.1 * x ^ 3 + 0.5 * x ^2 + 10 * x + 5](https://github.com/AndranikSargsyan/Programming-for-economists/blob/master/Week4/Resources/equation_1.png)


**Requirements**
* Program should ask to give an initial x_min value and number of iterations to make
* Program should print the estimated value of x_min for each iteration
```
Estimated value of x_min after iteration 1:     6.27
Estimated value of x_min after iteration 2:     3.54
Estimated value of x_min after iteration 3:     1.08
Estimated value of x_min after iteration 4:    -3.89
Estimated value of x_min after iteration 5:    -3.75
```
* Program should print both minimum point and minimum value
```
x_min = -3.739
y_min = -20.855
```

**Hints:**

* Use this equation to approximate the minimum point

![x_{k+1} = x_k - f'(x) / f''(x)](https://github.com/AndranikSargsyan/Programming-for-economists/blob/master/Week4/Resources/equation_2.png)

* Define these functions and do the calculations using them

```python
# calculates and returns value of the given function at point x
def f(x):
    pass

# calculates and returns value of the first
# derivative of the given function at point x
def f_d1(x):
    pass

# calculates and returns value of the second
# derivative of the given function at point x
def f_d2(x):
    pass
```