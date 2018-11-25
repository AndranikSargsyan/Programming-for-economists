## Problem 1: Factorial

Write a function which takes an integer as an argument and **recursively** generates and returns the factorial of that number. Program should ask for a natural number from the user, calculate it's factorial using written funtion and print the result. Program should ask the user for a new input and print it's factorial unless user types "exit". Use caching to speed up computations.

## Problem 2: Palindrome reconstruction

*A **palindrome** is a word or a phrase that is the same whether you read it backwards or forwards, for example the word 'refer'.*

You are given a word consisting of lowercase Latin letters. You need to rearrange the letters of the word so that a palindrome results. If there are several possible resulting palindromes, output the lexicographically smallest one (the one that would come first in a standard dictionary). If it is impossible to rearrange the letters into a palindrome, output the word “impossible”.

*Sample input-output*

|    Input          |  Output          |
|:------------------|:-----------------|
| dblolod           | dlobold          |
| abababcd          | impossible       |
| abababbacadacad   | aaabbcdadcbbaaa  | 