# MongoDB $inc operator type error
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation.  The `$inc` operator is used to increment a numerical field by a specified value.  However, in this case, a string value ("1") is used, which leads to an error.

The solution shows the correct usage, providing a numerical value for incrementing the counter.