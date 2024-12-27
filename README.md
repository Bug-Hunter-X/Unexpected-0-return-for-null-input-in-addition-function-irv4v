# Unexpected 0 return for null input in addition function

This repository contains a JavaScript function that demonstrates an uncommon bug. The function `foo` takes two numbers as input and returns their sum. However, if either input is `null`, the function returns 0 instead of handling the `null` value appropriately (e.g., treating it as 0 or throwing an error).

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version.

## Bug Description
The function returns 0 when one or both input parameters are null.  This is counter-intuitive as null does not equate to 0 for many users.