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