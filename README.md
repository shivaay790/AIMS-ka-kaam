# AIMS-ka-kaam
## Task1: One-Hot Encoding(OHE) and Ordinal Encoding with Pandas and Numpy

### OHE algo
- Enter category on which to apply OHE
- create a seperte set of cols dimension = (no. of rows of df, no. of unique vals)
- we setting that position as 1 where in the OHE array for each category in the dataframe that matches a unique value.
- create df of OHE data, concat it with df, drop the original category

### Ordinal Encoding algo
- get unique classes in a col & show to user
- tell the order sperated by comma
- split based on ','
- create an encoding scheme using enumerate
- apply encoding
