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