### Practice Questions Answers

1. We pass a file object to the fuction PyPDF2.PdfFileReader().

2. File objects for PdfFileReader() and PdfFileWriter() need to be opened in 'rb' and 'wb' respectively.

3. getPage(4) will give page object for page 5 from a PdfFileReader as Page 0 is considered the first page.

4. numPages variable stores the number of pages in the PDf document.

5. before obtaining page object we use decrypt('swordfish')

6. To rotate a page we use rotateClockwise() and rotateCounterClockwise() methods.

7. To get a document object for a file named demo.docx we use docx.Document('demo.docx')

8. A paragraph begins on a new line and contains multiple runs whereas runs are continuous groups of characters within a paragraph.

9. To get a list of paragraph objects for a document object that's stored in a variable named doc we use doc.paragraphs.

10. Run object has bold,underline, italic, strike, and outline variables.

11. Setting variable bold to True will always make the run object bold and setting it to False will always make the run object unbold regardless of the style given.
 Setting it to None will make the run object use the setting given in style.
 
12. To create a document object for a new word document we use docx.document()

13. To add a paragraph with the text 'Hello,there!' to a document object stored in a variable named doc we use doc.add_paragraph('Hello,there!')

14. Integers that represent the levels of headings available in word documents are 0,1,2,3 and 4.
    