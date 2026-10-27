A function must first be declared just like a variable, like seen below:
```
returnType FunctionName(parameterType parameterName); // function 1
void NewFunction(int numDogs); // function 2
```

Then you can define the function OUTSIDE of int(main)
```
void NewFunction(int numDogs){
	printf("%d", numDogs);
}
```
or if it's a return function...
```
float NewFunction(int numDogs){
	return numDogs + 1;
}
```

Then call the function wherever (you do not need to define a function on a line before the line where the function is called)
```
NewFunction(12);
```
or if it's a return function...
```
int someVariable = NewFunction(12);
```

Functions are not only limited to changing local variables however, they can directly modify global variables without declaring a specific global variable to modify.  Let me explain:
```
char newCharacter;
void NewFunction(int number, int* letter);

void NewFunction(int number int* letter){
	number = 5;
	letter = C;
}

NewFunction(5, &newCharacter);
```
The above code would set the functions local 'number' variable to be 5, however since the memory address of 'newCharacter' was passed in using & and \*, newCharacter would be set to C rather than a new local variable 'letter' being set to C