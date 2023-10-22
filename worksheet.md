
# Computer Science I 
## Lab 2.0 Worksheet

Name(s) and Login(s):



1. Dennis Ritchie, the creator of the C programming language,
was born on September 9th, 1941.  If he were still alive,
how old would he be today?  Find out by running the `birthday`
program on the appropriate inputs and enter your solution here.
Hello, dennis.  You are 82 years, 6 weeks, and 1 days old today



2. Bjarne Stroustrup, the creator of the C++ programming
language, the object-oriented extension of C, was born on
December 30th, 1950.  How old is he today?
Hello, Bjarne.  You are 72 years, 42 weeks, and 2 days old today



3. Software testing often involves testing code with known
"bad" input in an attempt to break it (sometimes this is
referred to as *fuzzing*).  Try breaking the `birthday_cli`
program by giving it "bad" input and observe the consequences.
Give at least two examples of potentially bad input and the
results you observe.
Please Enter Your First Name (no spaces) followed by ENTER: dennis
Enter the year in which you were born: 20002
Enter the month in which you were born (1-12): 13
Enter the day of the month in which you were born (1-31): 1
Today is 2023/10/22
Your birthday was
Hello, dennis.  You are 0 years, 0 weeks, and 0 days old today



4. Complete all the size and range entries below.

* `char`
size: 1 byte
range: -128 to 127
* `short int`
Size: Typically 2 bytes (16 bits)
Range: -32,768 to 32,767
* `int`
Size: Typically 4 bytes (32 bits)
Range: -2,147,483,648 to 2,147,483,647
* `long int`
Size: Typically 4 bytes or 8 bytes (32 or 64 bits, depending on the system)
Range: -2,147,483,648 to 2,147,483,647 for 4-byte
* `float`
Size: Typically 4 bytes
Range: Approximately 7 digits of accuracy
* `double`
Size: Typically 8 bytes
Range: Approximately 15 digits of accuracy

5. Use your working currency conversion to determine
the exchange amounts for the following inputs:

  a) $250.25

  b) $1,000.52

  c) $968,410.12



6. Suppose that you had used only `int` types
in your conversion program.  Would you be able
to use it to convert the US national debt
(which as of 2020 was \$26,009,754,625,487)?
Why or why not?




7. Mixed types

a) Run the `area` program with 3 and 4 as inputs.  
What value do you get?  Is this result correct?


b) Execute the program again with inputs 3 and 5.
Does the program give correct results?  Why not?


c) Fix the program by editing the `area.c` source
code so that the program produces correct results.
