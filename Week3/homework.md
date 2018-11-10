## Problem 1: The difference

Get a list of integers from the user. Calculate and print difference between the largest and the smallest integers of the list. **Do not use max and min built-in functions**

*Sample input-output*

|    Input         |  Output        |
|:----------------:|:---------------|
| 1 5 6 7 4 11     | 10             |
| 4 -42 11 6 13    | 55             |
| 12               | 0              | 

**Hints:**

* Use the split() method to split the string by the space character (' ') and to get a list of strings. Then use the map() function to make a list of integers out of a list of strings. And finally use the list() function to make a list out of a map object. 
```python
list_of_nums = list(map(int, input('Enter integers separated by spaces: ').split()))
```      