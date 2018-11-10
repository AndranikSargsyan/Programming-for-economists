## Problem 1: The maximum difference

Get a list of integers from the user. Calculate and print difference between the largest and the smallest integers of the list. **Do not use max and min built-in functions**

*Sample input-output*

|    Input         |  Output        |
|:----------------:|:---------------|
| 1 5 6 7 4 11     | 10             |
| 4 -42 11 6 13    | 55             |
| 12               | 0              | 

**Hints:**

* Use the split() method to split the string by the space character (' ') and to get a list of strings. Then use the map() function to make a map of integers out of a list of strings. And finally use the list() function to make a list out of a map object. 
```python
list_of_nums = list(map(int, input('Enter integers separated by spaces: ').split()))
```

## Problem 2: Primes, primes and primes

Write a function which returns the list of all prime numbers less than or equal to a given number. Ask a positive integer from the user, get all the primes up to the given number using the written function and print them out on one line separated by spaces.

*Sample input-output*

|  Input  |  Output             |
|:------- |:--------------------|
| 10      | 2 3 5 7             |
| 20      | 2 3 5 7 11 13 17 19 |
| 2       | 2                   |

**Hints:**

* Prime number is a number that is divisible only by itself and 1 (e.g. 2, 3, 5, 7, 11).

* Use `end` keyword argument for printting numbers on one line
```python
print(2, end=' ')
print(3, end=' ')
print(5)
```