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