### Practice Projects

##### Comma Code
``` bash
def code():
    n=eval(input("Enter a list:"))
    try:
        for i in range(len(n)-1):
            n[i]=n[i]+', '
        if len(n)!=1:
            n[-1]='and '+n[-1]
        c=str(n[0])
        for j in range(1,len(n)):
            c=c+n[j]
        return c
    except IndexError:
        print("Empty List!")
a=code()
print(a)

```

##### Coin Flip Streaks
``` bash
import random
count=0
sub_count=0
for i in range(10000):
    a=[]
    for j in range(100):
        a.append(random.choice('H''T'))
        prev=''
        new=''
    for k in range(100):
        if k==0:
            prev=a[k]
        new=a[k]
        if new==prev:
            sub_count+=1
        else:
            sub_count=1
        prev=new
        if sub_count==6:
            count+=1
            sub_count=0
print(count/10000)

```

##### CharacterPicture Grid
``` bash
grid=[['.', '.', '.', '.', '.', '.'],
      ['.', 'O', 'O', '.', '.', '.'],
      ['O', 'O', 'O', 'O', '.', '.'],
      ['O', 'O', 'O', 'O', 'O', '.'],
      ['.', 'O', 'O', 'O', 'O', 'O'],
      ['O', 'O', 'O', 'O', 'O', '.'],
      ['O', 'O', 'O', 'O', '.', '.'],
      ['.', 'O', 'O', '.', '.', '.'],
      ['.', '.', '.', '.', '.', '.']]
for i in range(6):
    for j in range(len(grid)):
        print(grid[j][i], end='')
    print('\n')

```