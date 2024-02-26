# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1. Text representation
2. Graphical representation
3. Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
Consider a Situation Lizard(AGENT) crawling on the wall.The goal of lizard is to catch the insect which is on the same wall.

### State Space
{B,A,C,D,E,F,G}->{0,1,2,3,4,5,6}

These are state to the frog to reach the goal.

### Sample State
{2,3}

### Action Space
{0}->LEFT

{1}->UP

{2}->RIGHT

### Sample Action
{1}->UP

{2}->RIGHT

### Reward Function
 To reach Goal->+!(REWARD)

 otherwise->0

### Graphical Representation
![OUTPUT](/Graph.png)

## PYTHON REPRESENTATION:
```python
#Name: Harshavardhan
#RegNo: 212222240114
P = {

    0 : {
        0 : [(1.0 , 0 , 0.0 , False)],
        1 : [(1.0 , 0 , 0.0 , False)],
        2 : [(0.7 , 1 , 0.0 , False), (0.3 , 0 , 0.0 , False)]
    },

    1 : {
        0 : [(0.7 , 0 , 0.0 , False),(0.3 , 1 , 0.0 , False)],
        1 : [(0.7 , 4 , 0.0 , False),(0.3 , 1 , 0.0 , False)],
        2 : [(0.7 , 2 , 0.0 , False),(0.3 , 1 , 0.0 , False)]
    },

    2 : {
        0 : [(0.7 , 1 , 0.0 , False),(0.3 , 2 , 0.0 , False)],
        1 : [(1.0 , 2 , 0.0 , False)],
        2 : [(1.0 , 2 , 0.0 , False)]
    },

    3 : {
        0 : [(1.0 , 3 , 0.0 , False)],
        1 : [(1.0 , 3 , 0.0 , False)],
        2 : [(0.7 , 4 , 0.0 , False),(0.3 , 3 , 0.0 , False)]
    },
    4 : {
        0 : [(0.7 , 3 , 0.0 , False),(0.3 , 4 , 0.0 , False)],
        1 : [(0.7 , 6 , 1.0 , True),(0.3 , 4 , 0.0 , False)],
        2 : [(0.7 , 5 , 0.0 , False),(0.3 , 4 , 0.0 , False)]
    },
    5 : {
        0 : [(0.7 , 4 , 0.0 , False),(0.3 , 5 , 0.0 , False)],
        1 : [(1.0 , 5 , 0.0 , False)],
        2 : [(1.0 , 5 , 0.0 , False)]
    },
    6 : {
        0 : [(1.0 , 6 , 0.0 , True)],
        1 : [(1.0 , 6 , 0.0 , True)],
        2 : [(1.0 , 6 , 0.0 , True)]
    },
}

P

```

## OUTPUT:
![OUTPUT](/Python.png)

## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:
Graphical Representation and Python Representation.
