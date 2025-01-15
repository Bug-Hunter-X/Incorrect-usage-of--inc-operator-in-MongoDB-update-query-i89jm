# Incorrect Usage of $inc Operator in MongoDB Update Query

This repository demonstrates an incorrect usage of the `$inc` operator in a MongoDB update query and provides a solution.

## Bug
The original code attempts to increment a field by a string value, which is not allowed by the `$inc` operator.

## Solution
The solution involves changing the value to increment from a string to a number.