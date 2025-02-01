# MongoDB $inc Operator Error
This example demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value.  However, using a string value as the increment leads to an error.

## Bug
The provided JavaScript code attempts to increment the `field` using a string value '1' instead of the number 1.

## Solution
The solution involves correctly providing a numerical value to the `$inc` operator.
