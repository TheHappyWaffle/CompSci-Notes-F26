**Every program needs to go like this:**
`
```
#include <stdio.h>
int main(){

	[Code Goes Here]
	
return(0);
}
```
You can also add "\#include \<math.h>" to add functions like pow();

<u>Useful lines of code:</u>
- printf("This prints a word and a variable by using %d", variableName);
-  scanf("This prints this text while also getting user input and assigning it to this variable %d", &variableName);
- \n
	- Using this inside of a print or scan makes any text that prints after it go onto a new line
- Assignment of variables in scans and prints:
	- %d = integers
	- %u = unsigned integers (non-negative whole numbers only)
	- %f = floats
	- %lf = doubles (more precise version of floats)
	- %c = char
	- %s = string
	- %p = pointer
	- Bools:
		- Using "%s" outputs the bool as a string
		- Using "%d" outputs the bool as either a 1 or 0, for true and false respectively
- pow(x, y)
	- same as x^y, make sure to include math.h

<u>If Statements:</u>
``` 
if (condition){
     code;
  } else if (condition){
	 code;
  } else {
	 code;
  }
```
|| = or            && = and            ! = not

An if statement can be written as a conditional statement as show below, both statements produce the exact same result:
```
// Option 1:
if (condition) {
  myVar = 1;
}
else {
  myVar = 2;
}



// Option 2:
myVar = (condition) ? 1 : 2; // Left side of colon is true, right side is false
```



<u>Switch Statements:</u>
Assuming 'a' was an integer, a switch statement would look like this:
```
switch (a) {
  case 0:
     // Print "zero"
     break;
  case 1:
     // Print "one"
     break;
  case 2:
     // Print "two"
     break;
  default: // default runs if 'a' doesn't match any of the cases
     // Print "unknown"
     break;
}
```
By not putting a break, it can cause the variable to "fall through" to the next case which could be useful if the value of the variable could execute multiple cases.  Not putting breaks would be the equivalent of putting multiple if statements one after another.



<u>Functions:</u>
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