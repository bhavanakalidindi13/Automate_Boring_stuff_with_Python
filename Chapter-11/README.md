### Practice Questions Answers

1. assert spam>=10

2. assert eggs.lower() != bacon.lower will trigger an AssertionError.

3. assert False will always trigger an AssertionError.

4.
  ``` bash
   import logging
   logging.basicConfig(filename='myProgramLog.txt', level=logging.DEBUG, format='%(asctime)s -  %(levelname)s -  %(message)s')
   These two lines are necessary to be able to call logging.debug().
  ```
5 .  
 ``` bash
 import logging
 logging.basicConfig(filename='programLog.txt', level=logging.DEBUG,format=' %(asctime)s -  %(levelname)s -  %(message)s')
These two lines are necessary to have in order to have logging.debug() send a logging message to a file named programLog.txt.
 ```

6 . The five logging levels are DEBUG,INFO,WARNING,ERROR and CRITICAL.

7 . To disable all logging messages we use logging.disable(logging.CRITICAL).

8 . In logging messages we can disable the messages by simply writing a function logging.disable(logging.CRITICAL) whereas if we use print() then we should remove each command manually.

9 . 
   ``` bash
 Step In will cause the debugger to execute the next line of code as well as to step into the function if existed.
 Step Over will cause the debugger to execute the next line of code but steps over the function if existed.
 Step Out will cause the debugger to execute lines of code at full speed until it returns from the current function.
   ```

10 . After clicking Continue button the program will execute normally until it terminates or reaches a breakpoint.

11 . A breakpoint is a specific line of code that forces the debugger to pause whenever the program execution reaches that line.

12 . To set a breakpoint, click the line number in the file editor to cause a red dot to appear, marking the breakpoint.