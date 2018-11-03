## Problem 1: Odd or even? That is the question

Ask the user for a number. Depending on whether the number is even or odd, print out an appropriate message to the user.

**Hints:**

* Use input() function to ask for an input from the user and use int() function to convert the returned string into an integer this way
```python
num = int(input("Enter an integer: "))
```
* You should probably use the modulus operator
```python
>>> 5 % 2
1
>>> 4 % 2
0
```

## Problem 2: Guess the number 

Generate a random number between 1 and 100 (including 1 and 100). Ask the user to guess the number, then tell him/her whether he/she guessed too low, too high, or exactly right. Keep the game going until the user types “exit” or guesses the right number․

**Bonus:**

 Keep track of how many guesses the user has taken, and when the game ends, print that out.

**Hints:**
* Use random module to generate a random number
```python
import random
num = random.randint(1, 100)
```

* Use `while` loop to keep the game going
```python
while guess != num:
  ...
```
