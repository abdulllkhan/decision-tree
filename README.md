# Decision Tree
Decision tree classifier created without using any powerful library functions.

This decision tree classifier does not use libraries like scikitlearn, numpy and pandas. 

## Input

Example input is:

<img src="https://github.com/abdulskhan47/decision-tree/blob/main/images/input.PNG">

The first column is the input, and the remaining columns follow the format [attribute_label] : [attribute_value]. If the label == -1 the row is added to the testing dataset, all other rows are added to training dataset.
The attribute values are categorical.

## Output

The output for the above given example is:

{'1': '100%'}
{'1': '100%'}

The output is a dictionary for each predicted row, which contains the row predicttion as the key value, and the probabability as the value for the key.
