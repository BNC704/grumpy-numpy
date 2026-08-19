# Grumpy NumPy v6

Tutor routing fixed.

Specific requests now route correctly:
- NP.ZERO / np.zero / np.zeros -> Creating Arrays
- NP.ONES / np.ones -> Creating Arrays
- np.full -> Creating Arrays
- np.arange -> Creating Arrays
- np.linspace -> Creating Arrays
- np.where -> np.where
- np.unique -> np.unique
- argsort -> Sorting
- argmax / argmin -> Extremes
- broadcasting -> Broadcasting
- copy / view -> Copy vs View

Specific function keywords are matched before generic words such as "numpy".
JavaScript syntax check: PASSED.
