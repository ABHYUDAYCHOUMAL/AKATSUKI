**Example 1** 
```py
import lib 
var a, b
out ('enter value of a and b')
in (a , b )
if (a=b)
	out ( 'numbers are equal' )
```

**Example 2** 
```py
import  lib
var roll
out('enter your roll number\n')
in(roll)
if (roll > 0)
    out('valid roll number\n')
else 
    out('invalid roll number\n')
```

**Example 3**
```py
import lib
var a, b, c
out('enter two numbers\n')
in( a , b)
if (b == 0)
    out('invalid denominator\n')
else 
    c = a/b
    out  (c)
```

**Example 4**
```py
import lib
var age 
out('enter your age\n')
in (age)
if (age >=12 and <= 50)
    out ('young\n')
else 
    out("not young\n')
if(age<12 or age>50)
    out('Eligible for the offer\n')
else
    out('Not Eligible for the offer\n')
```
**Example 5**
```py
import lib
var a,b,c
out('Enter 3 no.s\n')
in(a,b,c)
if(a>b and a>c)
    out(a,'\n')
else if(b>c)
    out(b,'\n')
else
    out(c,'\n')
```
**Example 6** 
```py
import lib 
var a, b;                                       //semi colon was not required 
out ('enter value of a and b\n')
in (a , b )
if (a=b)
    out ( 'numbers are equal' )
```
**Example 7**
```py
import lib
var a, b, c
out (enter two numbers\n)                         // out statement requires single quote around a strings
in( a , b)
if (b == 0)
    out ('invalid denominator\n')
else 
    c = a/b
    out  (c)
```
**Example 8**
```py
import  lib
var roll
out('enter your roll number\n')
in(roll)
if (roll > 0)
    out('valid roll number\n')
    else                                         // indentation of else should be same as if condition
    out('invalid roll number\n')
```

**Example 9**
```py
import lib
var a,b,c
out('Enter 3 no.s\n')
in(a,b,c)
if(a>b && a>c)                                 // use predefined keywords "and" instead of using "&&"
    out(a,'\n')
else if(b>c)
    out(b,'\n')
else
    out(c,'\n')
```
**Example 10**
```py
import  lib
int  roll                                        //no need to define variable types
out('enter your roll number\n')
in(roll)
if (roll > 0)
    out('valid roll number\n')
else 
    out('invalid roll number\n')
```
