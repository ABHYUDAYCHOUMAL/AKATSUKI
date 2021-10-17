**Example 1**
```py
import lib
var n, sum=0
out ('Enter a no.\n')
in (n)


for i=1:i++ (i<=n)
    sum = sum + i

out ('Sum to First ', n, ' Natural no.s is ', sum)
```
**Example 2**
```py
import lib
var n
out ('Enter a no. \n')
in (n)

for i=1:i++ (i<=n)
    if(n%i==0)
        out(i, ' ')
```

**Example 3**
```py
import lib
var n,count=0
out ('Enter a no. ')
in (n)

for i=1:i++ (i<=n)
    if(n%i==0)
        count++

if (count==2)
    out ('It's a Prime\n')
else 
    out ('It's not a Prime\n')
```

**Example 4**
```py
import lib
var n, r
out ('Enter a no. \n')
in (n)

while (n!=0)
    r=n%10
    n=n/10
    out(r, ' ')

out ('\n')
```
**Example 5**
```py
import lib
var m,n
out ('Enter two no.s \n')
in (m, n)

while (m!=n)
    if (m>n)
        m=m-n
    else
        n=n-m


out ('GCD is ',m )
```
**Example 6**
```py
import lib
var n, sum=0
out ('Enter a no.\n')                   
in (n)

for (var i=1; i<=n; i++)                                // use predefined syntax for "for as initialisation : increment (condition)"
    sum = sum + i

out ('Sum to First ', n, ' Natural no.s is ', sum)
```

**Example 7**
```py
import lib
var n
out ('Enter a no. \n')
in (n)

for  var i=1:i++ (i<=n)                                 // no need to declare the variable   
    if(n%i==0)
        out(i, ' ')
```

**Example 8**
```py
import lib
var n,count=0
out ('Enter a no. ')
in (n)

for i=1:i++ i<=n                                     // condition should be inside the brackets
    if(n%i==0)
        count++

if (count==2)
    out ('It's a Prime\n')
else 
    out ('It's not a Prime\n')
```

**Example 9**
```py
import lib
var n, r
out ('Enter a no. \n ')
in (n)

while n!=0                                       //condition should be in brackets
    r=n%10
    n=n/10
    out(r, ' ')

out ('\n')
```

**Example 10**
```py
import lib
var m,n
out ('Enter two no.s \n')
in (m, n)

while (n!=n)                                   // loop will never execute
    if (m>n)
        m=m-n
    else
        n=n-m


out ('GCD is ',m )
```
