# Title : ML-LAB_EXP ( Author : Vishal Kumar )
<br>

## This Repo has created to host my ML Lab Experiments.

## This Repo consist List of the following supervised learning algorithm experiments.
1. FIND-S Algorithm
2. Candidate Elimination Algorithm
3. Naive Bayes Algorithm
4. ID3 (Iterative Dichotomiser 3) Algorithm
5. K-Nearest Neighbors Algorithm

## Exp-1 : FIND-S
### Aim: 
To implement FIND-S algorithm.

### Algorithm 
1. Initialize h to the most specific hypothesis in H
2. For each positive training instance x
    For each attribute constraint a, in h
        If the constraint a, is satisfied by x
        Then do nothing
        Else replace a, in h by the next more general constraint that is satisfied by x
3. Output hypothesis h

## Coding
### Importing 
```python
import pandas as pd
import numpy as np

```
### Reading Data

```python 
data = pd.read_csv('data.csv')
```

