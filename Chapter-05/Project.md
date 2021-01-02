### Practice Projects

##### Chess Dictionary Validator
``` bash
x=eval(input("Enter:"))
def VCB(n):
    y={'bking':1,'bqueen':1,'brook':2,'bbishop':2,'bknight':2,'bpawn':8,
       'wking':1,'wqueen':1,'wrook':2,'wbishop':2,'wknight':2,'wpawn':8}
    z=['1a','1b','1c','1d','1e','1f','1g','1h',
       '2a','2b','2c','2d','2e','2f','2g','2h',
       '3a','3b','3c','3d','3e','3f','3g','3h',
       '4a','4b','4c','4d','4e','4f','4g','4h',
       '5a','5b','5c','5d','5e','5f','5g','5h',
       '6a','6b','6c','6d','6e','6f','6g','6h',
       '7a','7b','7c','7d','7e','7f','7g','7h',
       '8a','8b','8c','8d','8e','8f','8g','8h',]
    a=list(n.keys())
    b=list(n.values())
    c=list(y.keys())
    if (set(a).issubset(set(z))):
        if (set(b).issubset(set(c))):
            for i in b:
                y[i]=y.get(i,0)-1
                if -1 in y.values():
                    print("No. of Chess pieces of a single type exceeds!!!")
                    break
            else:
                print("It is a Valid Chess Board")
        else:
            print("The Chess Piece doesn't exist!!!")
    else:
        print("Chess Board Space Invalid!!!")
VCB(x)

```

##### Fantasy Game Inventory
``` bash
x=eval(input("Enter inventory:"))
def dI(i):
    print("Inventory:")
    y=sum(i.values())
    for k,v in i.items():
        print(v,k)
    print("Total number of items:",y)

dI(x)

```

##### List To Dictionary function for Fantasy Game Inventory
``` bash
def dI(i):
    print("Inventory:")
    y=sum(i.values())
    for k,v in i.items():
        print(v,k)
    print("Total number of items:",y)

def atI(n,m):
    for d in m:
        n[d]=n.get(d,0)+1
    return n
            
inv=eval(input("Enter inventory:"))
dragon_loot=eval(input("Enter dragon loot:"))
inv=atI(inv,dragon_loot)
dI(inv)

```
