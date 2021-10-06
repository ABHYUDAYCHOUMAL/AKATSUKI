TEAM :-  AKATSUKI

Introduction of Programming language (Bego)

Programming paradigm :- Imperative (multiparadigm)

Designing a programming language:- 
     We are designing a programming language which is inspired by C and its descendants, but simpler. As we know the compilable language are easier to debug, So we are going to design a compile language BEGO. The programming paradigm of this language is imperative as the program written in this language simply gives the solution to the specific problem. This language is going to be specify how to be done control flow of computation. 

U.S.P. for the language:- 
1.To make learning of programming language simpler. 
2.To avoid unnecessary syntax error while writing the program. 
3.To make the code length smaller.   

To do’s and don’ts in programming language:-

Do’s :-  
1.He has to declare the variable before using it anywhere.  
2.He has to just focus on writing the program, don’t have to worry about the syntax.
3.He has to mention the library which he is going to use in his program.  
4.He has to use indentation for opening and closing of functions and loops.
5.Predefined Keywords are case insensitive.

Don’ts :- 
1.Don’t use symbols instead use English words (ex. && => and  ,  || => or)
2.Don’t have to define the main function.
3.Don’t use predefined keywords.
4.Don’t use special characters in defining identifiers other than underscore.


Examples :-

1.Helloworld

import lib
out ('hello world!')

2.Add two numbers

import lib
var a , b , c     // Type of variable is automatically taken by compiler
out ('enter two numbers')
in (a , b )
c = a + b
out (' the sum is : ' + c) 

3.Find greater number 

import lib
var a , b					  								
out ('enter value of a and b')
in (a , b )
if (a=b)
	out ( 'numbers are equal' )
else if (a>b)
	out (' a is greater than b')
else 
	out (' b is greater than a')
