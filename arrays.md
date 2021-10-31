**Example 1**
```py
import lib
array arr[5] = { 3, 2, 5, 8, 9}               //array is predefined  
out (arr)
```

**Example 2**
```py
import lib
array num[5]
out('enter the numbers\n')
for i in (5)
    in (num[i])
var sum 
for i in (5)
    sum = sum +num[i]

out (sum)
```

**Example 3**
```py
import lib
array a[10] = { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
var key 
out ('enter the key element\n')
in (key)
for i in (10)
    if (key == a[i])
        out ('the key element is found at '  +i )
        exit 

out ('element is not found')
```
**Example 4**
```py
import lib
var n, i, sum=0.0, average
array num[100]
out('Enter the  numbers of elements: ')
in(n)

for i in (n)
    out(i+1 + '.Enter number')
    in(num[i])
    sum = sum + num[i]

average = sum/n
out('Average ' + average)
```
**Example 5**
```py
import lib
array A[2][3] = {3, 3, 3, 3, 3, 3}
array B[2][3] = {1, 1, 1, 1, 1, 1}
array C[2][3]

for i in (2)
    for j in (3)
        C[i][j] = A[i][j] + B[i][j]

for i in (2)
    for j in (3)
        out(C[i][j] + ' ')
    out('\n')
out('\n')
```
**Example 6**
```py
import lib
var n, i, sum=0.0, average
array num[n]                                     // n was not declared 
out('Enter the  numbers of elements: ')
in(n)

for i in (n)
    out(i+1 + '.Enter number')
    in(num[i])
    sum = sum + num[i]

average = sum/n
out('Average ' + average)
```
**Example 7**
```py
import lib
array num[5]
out('enter the numbers\n')
in (num[])                                   //we can't take all array elements like this 
var sum 
for i in (5)
    sum = sum +num[i]

out (sum)
```
**Example 8**
```py
import lib
array A[2][3] = {3, 3, 3, 3, 3, 3}
array B[2][3] = {1, 1, 1, 1, 1, 1}
array C[2][3]

for i in (2)
    for j in (3)
        C[i][j] = A[i][j] + B[i][j]

for i in (2)
    for j in (3)
        out(C[i][j] + ' ')
    out('\n')
out('\n')
```
**Example 9**
```py
import lib
array arr[5] = ( 3, 2, 5, 8, 9 )               //curly brackets should be used for initialisation array elements  
out (arr[])
```
**Example 10**
```py
import lib
array a[10] = { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
var key 
out ('enter the key element\n')
in (key)
for i in (10)
    if (key == a[i])
        out ('the key element is found at '  +i )

out ('element is not found')                               //program will always dispaly element is not found also.
```
