# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The incorrect usage uses dot notation within the `$inc` operator which will lead to an error.

## Incorrect Usage
The incorrect usage demonstrates using dot notation directly within the `$inc` operator without proper quoting. This can lead to unexpected behavior or errors. 

## Correct Usage
The correct usage shows the proper syntax for using the `$inc` operator. The correct syntax requires using double quotes to enclose the field name for the counter. 

## How to Reproduce
1.  Clone this repository.
2.  Run MongoDB.
3.  Execute the code in `bug.js` and observe the error.
4.  Execute the code in `bugSolution.js` and observe the correct behavior. 