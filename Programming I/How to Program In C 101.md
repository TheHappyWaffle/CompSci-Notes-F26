**Every program needs to go like this:**
`
\#include \<stdio.h>
int main(){

	[Code Goes Here]
	
return(0);
}

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
	- %p = pointer
- pow(x, y)
	- same as x^y, make sure to include math.h

- if (condition){
     code;
  } else if (condition){
	 code;
  } else {
	 code;
  }