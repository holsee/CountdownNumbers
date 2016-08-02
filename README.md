# CountdownNumbers
Code Kata: Countdown Numbers Game Solver

You are given 6 numbers, chosen at random from the set {1, 2, 3, 4, 5, 6, 8, 9, 10, 25, 50, 75, 100}, 
and a random target number between 100 and 999. 

The aim is to use the six given numbers and the four common arithmetic operations 
(addition, subtraction, multiplication, division; all over the rational numbers) to generate the target 
- or as close as possible either side. 

Each number may only be used once at most, while each arithmetic operator may be used any number of times 
(including zero.) Note that it does not matter how many numbers are used.

Write a function that takes the target number and set of 6 numbers (can be represented as list/collection/array/sequence) 
and returns the solution in any standard numerical notation (e.g. infix, prefix, postfix). 

The function must always return the closest-possible result to the target, 
and must run in at most 1 minute on a standard PC. 

Note that in the case where more than one solution exists, any single solution is sufficient.
