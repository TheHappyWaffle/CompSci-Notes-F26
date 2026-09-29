1. Open PowerShell and run the command: **<u>ssh avogel01@linux.socs.uoguelph.ca</u>**
	1. If you are off campus you must be using the Campus VPN found here: https://uoguelphca.sharepoint.com/sites/ccs/SitePages/anyconnect-vpn-user-guide.aspx
2. Type in your password (note, the password is invisible and it looks like you aren't typing anything)
3. Then just type "nano" into the console, and you're in :)

<u>Useful commands:</u>
- "<u>cd [Name]</u>" goes into the \[Name] folder
- "<u>mkdir [Name]</u>" makes a folder called \[Name]
- "<u>gcc -Wall -std=c99  [Name].c -o [Name]</u>" compiles the \[Name] program
- "<u>nano [Name].c</u>"opens the \[Name] file in nano
- "<u>./[Name]</u>" runs the file called \[Name]


<u>Command Breakdown:</u>
- gcc -Wall -std=c99  lab2.c -o lab2 -lm
	- <u>gcc</u> = compiler, compiles the code into machine language
	- <u>-Wall</u> = "Warnings All", prevents the code from silently failing and presents any errors in the compiles
	- <u>-std</u> = enforced the use of standard c99 (no clue what that actually means)
	- <u>lab2.c</u> = the name of the file to be compiled
	- <u>-o lab2</u> = creates an .exe file named lab2.  
	- <u>-lm</u> = links the math library to the program allowing the use of functions like pow()
	- Lab2 and Lab2.c are completely different files, as Lab2.c is in C and Lab2 is in machine code and looks like gibberish