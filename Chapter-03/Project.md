### Practice Projects

##### The collatz sequence

``` bash
def collatz(n):
    if n%2==0:
        n=n//2
        print(n)
        return n
    else:
        n=3*n+1
        print(n)
        return n
x=int(input("Enter:"))
y=int(collatz(x))
while y!=1:
    y=int(collatz(y))
```

##### Input Validation
``` bash
def collatz(n):
    if n%2==0:
        n=n//2
        print(n)
        return n
    else:
        n=3*n+1
        print(n)
        return n

try:
    x=int(input("Enter:"))
    y=int(collatz(x))
    while y!=1:
        y=int(collatz(y))
except ValueError:
    print("Error: Enter an integer")

```
