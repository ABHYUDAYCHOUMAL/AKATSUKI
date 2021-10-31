Example 1

import lib
void display():
    out('hello \n')

display()

Example 2 

import lib
var add(var x, var y)
    var z 
    z = x + y 
    return z

var x = 2, y = 5 , z
z = add(x , y)
out(z)


Example 3 

import lib
var maxi(var a, var b, var c)
    if (a > b and a > c )
        return a 
    else if ( b > c )
        return b 
    else 
        return c 
var a, b, c, d
out ('enter three numbers:\n')
in (a, b, c)
d = maxi (a, b, c)
out ('maximum is: ' + d)

Example 4

import lib
var factorial(n)
    if n== 0 
        return 1 
    else 
        return n * factorial(n-1)

var n, m 
n = 10
m = factorial(n)
out('the factorial of n: ' +m)


Example 5

import lib 
var maxi(var a , var b)
    if (a > b)
        return a 
    else 
        return b 

var maxi(var a, var b, var c)
    if (a > b and a > c )
        return a 
    else if ( b > c )
        return b 
    else 
        return c

var maxi(var a, var b, var c = INT_MIN)
    if (a > b and a > c )
        return a 
    else if ( b > c )
        return b 
    else 
        return c 

var a , b , c 
out('enter two numbers:\n')
in (a , b )
c = maxi (a, b )
out('maximum is:  ' +c  )


Example 6 

import lib
void display():
    out('hello \n')

display                                      //function calling is wrong 


Example 7

import lib
var add( x, y)                     // variable parameter is not defined 
    var z 
    z = x + y 
    return z

var x = 2, y = 5 , z
z = add(x , y)
out(z)


Example 8 

import lib
var maxi(var a, var b, var c)
    if (a > b and a > c )
        return a 
    else if ( b > c )
        return b 
    else 
        return c 
var a, b, c, d
out ('enter three numbers:\n')
in (a, b, c)
d = maxi (a, b)                            //number of parameters required to calling the functions are not complete
out ('maximum is: ' + d)

Example 9

import lib
var 10_factorial( var n)                       //function name can not be started with integer 
    if n== 0 
        return 1 
    else 
        return n * factorial(n-1)

var n, m 
n = 10
m = 10_factorial(n)
out('the factorial of n: ' +m)

Example 10

import lib 
var maxi(var a , var b)
    if (a > b)
        return a 
    else 
        return b 

var maxi(var a, var b, var c)
    if (a > b and a > c )
    return a                             // indentation wrong 
    else if ( b > c )
        return b 
    else 
        return c

var maxi(var a, var b, var c = INT_MIN)
    if (a > b and a > c )
        return a 
    else if ( b > c )
        return b 
    else 
        return c 

var a , b , c 
out('enter two numbers:\n')
in (a , b )
c = maxi (a, b )
out('maximum is:  ' +c  )

