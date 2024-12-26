# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB updates.  The `$inc` operator is used to increment a numeric field.  However, an incorrect usage, like supplying a string instead of a number, will lead to issues.

The `bug.js` file contains the incorrect code.  The `bugSolution.js` file demonstrates the correct implementation.

**Problem:**
Attempting to increment a field using a string value with `$inc` will not increment the field as expected; instead, it could result in unexpected behavior or errors.

**Solution:**
Ensure that the value passed to `$inc` is a valid number to get correct field increment behavior.