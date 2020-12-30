### Practice Questions Answers

1. Two values of Boolean data type are True and False. The first letter of values of the boolean data type is always capital followed by small letters.

2. Three Boolean operators are and, or, not.

3. 
 | Expression | Evaluates to |
 | ---------- | ------------ |
 | True and True | True |
 | True and False | False |
 | False and True | False |
 | False and False | False |

 | Expression | Evaluates to |
 | ---------- | ------------ |
 | True or True | True |
 | True or False | True |
 | False or True | True |
 | False or False | False |

 | Expression | Evaluates to |
 | ---------- | ------------ |
 | not True | False |
 | not False | True |


4 . 
 ```bash
(5>4) and (3==5) gives False 
not (5>4) gives False 
(5>4) or (3==5) gives True 
not ((5>4) or (3==5)) gives False 
(True and True) and (True==False) gives False 
(not False) or (not True) gives True.
  ```
 5 . Six comparison operators are ==(equal to), !=(not equal to) , <(less than) , >(greater than) , <=(less than or equal to), >=(greater than or equal to).
 
 6 . Equal to(==) operator evaluates whether the two values are same or not.
    Assignment(=)  operator assigns or puts the value on right into the variable on left.
 
 7 . A condition is like boolean data type True or False . If True then it follows one path or if False then another path. We can use it in determining whether the given number is even or odd and whether it is a positive number or negative number and in many other examples.
 
 8 . 
 ``` bash
spam=0
if spam==10: # block 1 
    print('eggs')
    if spam>5: # block 2
        print('bacon') # end of block 2
    else: # block 3
        print('ham') # end of block 3
    print('spam') # end of block 1
print('spam')
 ```
 
 9 . 
 ``` bash
    spam=input("Enter:")
    if spam==1:
        print("Hello")
    elif spam==2:
        print("Howdy")
    else:
        print("Greetings!")
 ```
10 . Ctrl + C is pressed if the program is stuck in an infinite loop.

11 . break is used for exiting the loop whereas continue is used for going back to the start of the loop and continue the loop till end.

12 . range(start,stop,step) is the syntax.
``` bash
When one argument is passed in range(), user gets to decide where the series of number stops.
When two arguments is passed in range(), user gets to decide not only where the series of numbers stops but also where it starts.
wWhen three arguments is passed in range(), user also gets to decide how big the difference will be between one number and the next apart form start and stop.

Therefore, range(10) automatically starts from 0 and ends at 9
range(0,10) starts from 0 as mentioned and ends at 9
range(0,10,1) starts from 0, ends at 9, with 1 as difference between the numbers.

All three of them give same result, the difference is in the arguments.
```

13 . 
``` bash
for loop

for i in range(1,11):
    print(i)

while loop

i=1
while i<=10:
    print(i)
    i+=1
```

14 . spam.bacon() 
