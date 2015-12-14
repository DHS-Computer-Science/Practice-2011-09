# Practice 2011 - 09: Lifeboat Balancing

## Background
Six Virginia Tech engineers recently designed and built a large cruise ship.
Because of its many obvious flaws, it has just begun to sink on its first
voyage. There are two lifeboats on board, each of which can fit half of the
passengers on board. The only problem is that the total weight of the people
on each of the lifeboats needs to be as equal as possible so that neither
lifeboat weighs too much and risks sinking. It is your job to determine how
people should be distributed between lifeboats so that the weight is as equal
as possible and there is an equal number of people on each boat. All passengers
must make it onto a lifeboat.

## Description

### Input
The first number in the input will be C, the number of test cases.

For each of the C following test cases, the first line will be an integer N,
the total number of people that need to go on the lifeboats ( 1 ≤ N ≤ 5000 ).
The following N lines will contain an integer weight, W, representing the weight
of one passenger ( 1 ≤ W ≤ 1000 ).

### Output
For each of the test cases, determine the sum of the weights of all the people
on each lifeboat given the most equal distribution of weights. If the weights on
each boat are not equal, then output the lower number first. Both weights should
be output on the same line, separated by a space.

## Sample
### Input
```
2
4
20
10
15
10
5
17
13
25
4
6
```

### Output
```
25 30
31 34
```
