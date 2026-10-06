# ML Assignment 1 — NumPy: vectorised computation

Notebook: `assignment1_numpy.ipynb` (all outputs visible, no Python `for` loop over NumPy array elements).

## Question 8 — speed-up

`np.bincount` vs a plain Python loop on 1,000,000 random integers (0–99):

**Speed-up: 32.1x** (bincount is about 32.1 times faster than the loop)

Note: the loop in Q8 runs over a Python list (`arr.tolist()`), not over the NumPy array, so the "no loop over array elements" rule still holds.
