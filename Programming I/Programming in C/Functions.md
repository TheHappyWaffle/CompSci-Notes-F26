A function must first be declared just like a variable, like seen below:
```
returnType functionName(parameterType parameterName); // function 1
void newFunction(int numDogs); // function 2
```

Then you can define the function OUTSIDE of int(main)
```
void newFunction(int numDogs){
	printf("%d", numDogs);
}
```

Then call the function wherever (you do not need to define a function on a line before the line where the function is called)
```
newFunction(12);
```
