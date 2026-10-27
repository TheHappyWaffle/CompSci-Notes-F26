Before any code in a script, the first thing you will always see is `#include` which is a directive.  A directive <u>always</u> begins with a hashtag, and it tells the compiler to modify the file in some way.

Common Directives:
- `#include`: replaces that line with the contents of the given file name
	- For example, if you had functions declared in script A and included that script inside of script B using `#include "scriptA.h"` you could then call the functions in script A from script B.  Any code in scriptA such as prints will also be executed 
		- `.h` means the file is intended to be included at the top (the header) of the file it's being declared in
		- `#include <file.h>` makes the compiler search the systems standard directory for the file, this should only be used for standard library files such as `math.h`
		- `#include "file.h"` makes the compiler search for the file in the same folder that the script calling it is in 

When using `#include` sometimes the same file can be declared more than once which will cause errors, so it's important to use the following directives to ensure each file is only declared once:
```
#ifndef FILENAME_H // if the file is not defined
#define FILENAME_H // then define the file

// The file's content will be put here upon compilation

#endif // end the conditional
```