# MongoDB $inc operator error
This example demonstrates an incorrect use of the `$inc` operator in a MongoDB update operation.
The `$inc` operator is used to increment a numeric field by a specified value.  However, the provided code attempts to increment the field using a string value, which will result in an error.
The solution shows the correct usage, using a numeric value for the increment.