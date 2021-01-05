### Practice Questions Answers

1. re.compile() is the function that creates regex objects.

2. We often use raw strings when creating regex objects so that backslashes are considered.

3. search() method returns match object.

4. 

5. In r'(\d\d\d)-(\d\d\d-\d\d\d\d)' , group 0 gives full pattern that is (\d\d\d)-(\d\d\d-\d\d\d\d) ,
 group 1 gives the pattern (\d\d\d) and group 2 gives the pattern (\d\d\d-\d\d\d\d).
 
6. To make regex to match actual parenthesis and period characters we use backslash before them that is \(,\),\.

7. When called on a regex with no groups, such as \d\d\d-\d\d\d-\d\d\d\d, findall() gives list of strings and
 when called on a regex with groups, such as (\d\d\d)-(\d\d\d)-(\d\d\d\d), findall() gives list of tuples of strings.
 
8. The character | is used when we want to match one of many expressions.

9. The character ? is used for two different things. First, for optional matches and second,
 for non-greedy matching that is to return shortest string possible.
 
10. The * character is used to match zero or more whereas + character is used to match one or more.
    ``` bash
    for example:
    a= re.compile(r'Bat(wo)*man')
    mo=a.search("The Batman")
    gives Batman as return value
    but 
    a=re.compile(r'Bat(wo)+man')
    mo=a.search("The Batman")
    gives None as return value.
    ```
11. {3} gives patterns that repeat 3 times. {3,5} gives patterns that repeats 3,4 or 5 times.

12. Shorthand characters
    ``` bash
     \d shorthand character class represents any numeric digit from 0 to 9
     \w shorthand character class represents any letter, numeric digit or the underscore character
     \s shorthand character class represents any space, tab or newline character.
     ```
13. Shorthand characters 
    ``` bash
    \D shorthand character class represents any character that is not a numeric digit from 0 to 9.
    \W shorthand character class represents any character that is not a letter, numeric digit or the underscore character
    \S shorthand character class represents any character that is not a space, tab or newline character.
    ```
    
14. .* matches as much text as possible whereas .*? matches the smallest possible match.

15. [0-9a-z]

16. To make regular expressions case- insensitive, we use re.IGNORECASE or re.I as second argument in re.compile.

17. . character normally matches any character except newline. If re.DOTALL is passed as the second argument to re.compile it matches newline as well.

18. 'X drummers, X pipers, five rings, X hens' is returned.

19. re.VERBOSE allows us to ignore whitespaces and comments.

20. re.compile(r'^\d{1,3}(,\d{3})*$)

21. re.compile(r'[A-Z][a-z]*\Watnabe')

22. re.compile(r'(Alice|Bob|Carol)\s(eats|pets|throws)\s(apples|cats|baseballs)\.', re.IGNORECASE).
