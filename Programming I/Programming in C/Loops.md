A while loop is typed as follows, and executes while the inputted Boolean is true
```
while (Boolean){
	executeCode();
}
```

A for loop is typed as follows, it until the number in the middle statement satisfies the expression it is apart of.  Works the exact same way as if you wrote a while loop with the centre expression as the condition, the right most expression at the end of the loop, and the left most expression right before the loop.
```
int i;

for (i = 0; i < N; ++i) {        // N can be any number
   executeCode();
}
```
you can use the line ``break;`` to immediately exit any loop.  It is recommended to use these in conjunction with if statements