### Practice Questions Answers

1 . 
   ``` bash
   webbrowser module launches a web browser to a specific URL.
   requests module downloads files/ pages from the Web.
   BeautifulSoup module parses HTML.
   selenium module launches and controls a browser.
   ```
2 . requests.get() returns a response object. It as a text attribute that contains the downloaded content as a string value.

3 . raise_for_status() method checks whether the download worker or not.

4 . To get HTTP status code of a requests response we use status_code attribute.

5 . 
``` bash
s= open('file.html','wb')
for chunk in res.iter_content(chunk_size):
    s.write(chunk)

# we should specify chunk_size before the for loop
```

6 . 
``` bash
In chrome and internet explorer for windows , the developer tools are appeared on pressing F12, in macOS pressing option-I will open Chrome's Developer Tools(for me option-J worked).
In firefox, CTRL-SHIFT-C on windows and linux or by pressing option-C on macOS.
```

7 . We can view the HTML of a specific element on a web page by right-clicking the element in the page and selecting Inspect Element.

8 . The CSS selector string that would find the element with an id attribute of main is '#main'.

9 . The CSS selector string that would find the elements with a CSS class of highlight is '.highlight'.

10 . The CSS selector string that would find all the <div> elements inside another <div> element is 'div div'.

11 . The CSS selector string that would find the <button> element with a value attribute set to favorite is 'button[value="favorite"]'.

12 . To get a string from that Tag object stored in te variable spam we use spam.getText().

13 . To store all the attributes of a Beautiful Soup Tag object in a variable named linkElem we use linkElem.attrs

14 . To import selenium module we use - from selenium import webdriver.

15 . The find_element_* method gives the first matching element whereas find_elements_* method gives a list of all matching elements.

16 . For simulating mouse clicks and keyboard keys, Selenium's WebElements have click() and send_keys() methods respectively.

17 . An easier way to submit a form with selenium is by using submit() method.

18 . To simulate clicking a browser's Forward,Back and Refresh buttons with selenium we use forward(), back() and refresh() WebDriver object methods respectively.
