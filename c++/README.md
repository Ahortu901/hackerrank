# C++ hackerrank project
<hr>

1.[Hello World!](https://github.com/Ahortu901/hackerrank/blob/main/c%2B%2B/hello.cpp):

* Discprition
```
Objective
This is a simple challenge to help you practice printing to stdout. You may also want to complete Solve Me First in C++ before attempting this challenge.

We're starting out by printing the most famous computing phrase of all time! In the editor below, use either printf or cout to print the string

to stdout.

The more popular command form is cout. It has the following basic form:

cout<<value_to_print<<value_to_print;

Any number of values can be printed using one command as shown.

The printf command comes from C language. It accepts an optional format specification and a list of variables. Two examples for printing a string are:

printf("%s", string); printf(string);

Note that neither method adds a newline. It only prints what you tell it to.

Output Format

Print

to stdout.

Sample Output

Hello, World!
```

2.[Input Output](https://github.com/Ahortu901/hackerrank/blob/main/c%2B%2B/i%26o.cpp):

* Discprition
```
Objective
In this challenge, we practice reading input from stdin and printing output to stdout.

In C++, you can read a single whitespace-separated token of input using cin, and print output to stdout using cout. For example, let's say we declare the following variables:

string s;
int n;

and we want to use cin to read the input "High 5" from stdin. We can do this with the following code:

cin >> s >> n;

This reads the first word ("High") from stdin and saves it as string
, then reads the second word ("") from stdin and saves it as integer

. If we want to print these values to stdout, separated by a space, we write the following code:

cout << s << " " << n << endl;

This code prints the contents of string
, a single space (), then the integer

. We end our line of output with a newline using endl. This results in the following output:

High 5

Task
Read

numbers from stdin and print their sum to stdout.

Input Format

One line that contains
space-separated integers: , , and

.

Constraints

Output Format

Print the sum of the three numbers on a single line.

Sample Input

1 2 7

Sample Output

10

Explanation

The sum of the three numbers is 1 + 2 + 7= 10
```

3.[Basic Data Type](https://github.com/Ahortu901/hackerrank/blob/main/c%2B%2B/data_type.cpp):

* Discription:
```
Some C++ data types, their format specifiers, and their most common bit widths are as follows:

    Int ("%d"): 32 Bit integer
    Long ("%ld"): 64 bit integer
    Char ("%c"): Character type
    Float ("%f"): 32 bit real value
    Double ("%lf"): 64 bit real value

Reading
To read a data type, use the following syntax:

scanf("`format_specifier`", &val)

For example, to read a character followed by a double:

char ch;
double d;
scanf("%c %lf", &ch, &d);

For the moment, we can ignore the spacing between format specifiers.

Printing
To print a data type, use the following syntax:

printf("`format_specifier`", val)

For example, to print a character followed by a double:

char ch = 'd';
double d = 234.432;
printf("%c %lf", ch, d);

Note: You can also use cin and cout instead of scanf and printf; however, if you are taking a million numbers as input and printing a million lines, it is faster to use scanf and printf.

Input Format

Input consists of the following space-separated values: int, long, char, float, and double, respectively.

Output Format

Print each element on a new line in the same order it was received as input. Note that the floating point value should be correct up to 3 decimal places and the double to 9 decimal places.

Sample Input

3 12345678912345 a 334.23 14049.30493

Sample Output

3
12345678912345
a
334.230
14049.304930000

Explanation

Print int 3,
followed by long 12345678912345,
followed by char a,
followed by float 334.230,
followed by double 14049.304930000.
```

4.[Condition Statement](https://github.com/Ahortu901/hackerrank/blob/main/c%2B%2B/i%26o.cpp):

* Discriptipon:
  ```
  if and else are two of the most frequently used conditionals in C/C++, and they enable you to execute zero or one conditional statement among many such dependent conditional statements. We use them in the following ways:

   1. if: This executes the body of bracketed code starting with statement1 if evaluates to true.

if (condition) {
    statement1;
    ...
}

  2. if - else: This executes the body of bracketed code starting with statement1
if evaluates to true, or it executes the body of code starting with if statement2

evaluates to false. Note that only one of the bracketed code sections will ever be executed.

if (condition) {
    statement1;
    ...
}
else {
    statement2;
    ...
}

    3. if - else if - else: In this structure, dependent statements are chained together and the condition
for each statement is only checked if all prior conditions in the chain evaluated to false. Once a condition evaluates to true, the bracketed code associated with that statement is executed and the program then skips to the end of the chain of statements and continues executing. If each condition in the chain evaluates to false, then the body of bracketed code in the else block at the end is executed.

    if(first condition) {
        ...
    }
    else if(second condition) {
        ...
    }
    .
    .
    .
    else if((n-1)'th condition) {
        ....
    }
    else {
        ...
    }

Given a positive integer

, do the following:

    If 1 <= n <= 9, print the lowercase English word corresponding to the number (e.g., one for , two for
, etc.).
If n > 9, print Greater than 9.

Input Format

A single integer,n.

Constraints
1 <= n <= 10^9

Output Format

If 1 <= n <= 9 then print the lowercase English word corresponding to the number (e.g., one for 1, two for 2, etc.); otherwise, print Greater than 9.

Sample Input 0

5

Sample Output 0

five

Explanation 0

five is the English word for the number 5.

Sample Input 1

8

Sample Output 1

eight

Explanation 1

eight is the English word for the number 8.

Sample Input 2

44

Sample Output 2

Greater than 9

Explanation 2

n = 44 is greater than , so we print Greater than 9.
  ```