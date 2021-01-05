### Practice Questions Answers

1. PyInputPlus is not a part of the Python Standard Library.

2. PyInputPlus is commonly imported with import pyinputplus as pyip to save us from typing pyinputplus 
each time we want to call a PyInputPlus function instead we can type pyip which is a shorter name.

3. inputInt() and inputFloat() return int and float value respectively.

4. pyip.inputNum('Enter num:',min=0,max=99) can ensure that the user enters a whole number betweeen 0 and 99.

5. The input values which can be allowed are passe through allowRegexes keyword argument 
and the input values that are not allowed or invalid are passed through blockRegexes keyword argument.

6. If blank input is entered three times then inputStr(limit=3) returns RetryLimitException.

7. If blank input is entered three times then inputStr(limit=3,default='hello') returns default value instead of an exception.
