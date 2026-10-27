An array contains a set of variables and the size of the array is static and cannot be changed at runtime.  An array is declared as follows:
```
variableType arrayName[lengthOfArray]; // general syntax
int numDogs[4]; // real world example
```
The array's first index is actually 0.  Note that the above array is of length 4, meaning it has indexes 0, 1, 2, and 3.  So if you wanted to reference the third item in the array you'd say `numDogs[2]` 

An arrays indexes can be modified one at a time like so: `array[2] = 4;`.  This changes the number in the third position of the array to be 4. 

However entire arrays can also be set without having to modify each individual index, like so: `array[3] = {2, 10, 25};`