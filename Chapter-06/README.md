### Practice Questions Answers

1.
 ``` bash 
An escape character lets us use characters that are otherwise impossible to put into a string.
\n, \t, \', \", \\ are escape characters.
```

2 . \n represents new line and \t represents tab.

3 . \\ puts a backslash character in a string.

4 . "Howl's Moving Castle" is a valid string as a single quote character can be used in double quotes 
and python will consider it as a single quote not as the beginning of a string.

5 . If we want newlines in a string without using \n we can use multiline string with triple quotes.

6 . 
``` bash
 'Hello, world!'[1] gives 'e'
 'Hello, world!'[0:5] gives 'Hello'
 'Hello, world!'[:5] gives 'Hello'
 'Hello, world!'[3:] gives 'lo, world'
```

7 . 
``` bash
'Hello'.upper() gives 'HELLO'.
'Hello'.upper().isupper() gives True.
'Hello'.upper().lower() gives 'hello'.
```

8 . 
``` bash
'Remember, remember, the fifth of November.'.split() gives ['Remember,','remember,','the','fifth','of','November.'].
'-'.join('There can be only one.'.split()) gives 'There-can-be-only-one.'
```

9 . to right-justify, left-justify, adn center a string .rjust(),.ljust() and .center() are used respectively.

10 . To trim whitespace characters of a string from the beginning we use .lstrip() and from the end we use .rstrip().
