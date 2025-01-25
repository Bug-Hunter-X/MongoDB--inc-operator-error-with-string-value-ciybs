# MongoDB $inc operator error with string value

This repository demonstrates an example of an uncommon error that occurs when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment numeric values only. Attempting to increment a string value results in an error. 

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected implementation.