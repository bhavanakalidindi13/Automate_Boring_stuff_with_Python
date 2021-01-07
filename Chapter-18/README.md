### Practice Questions Answers

1. Protocol for sending email is SMTP and for checking and receiving email IMAP.

2. To log in to an SMTP server the following four smtplib functions/methods are called-
   ``` bash
    smtplib.SMTP()
    smtpObj.ehlo()
    smtpObj.starttls()
    smtpObj.login()
   ```

3. To log in to IMAP server the following two imapclient functions/methods are called-
   ``` bash
    imapclient.IMAPClient()
    imapObj.login()
   ```

4. The argument to IMAP's search() is a list of strings, each formatted to the IMAP's search keys.

5. If we get an error message that says got more than 10000 bytes we will have to disconnect and reconnect to the IMAP server and try again 
or change the size limit from 10000 bytes to 10000000 bytes by running the following code:
   ``` bash
    import imaplib
    imaplib._MAXLINE=10000000
   ```

6. pyzmail module handles reading the emails that imapclient collects.

7. The credentials.json file contains the Client ID and Client Secret information.
The tokens.json gives our Python scripts access to the given Gmail account.

8. GmailThread represents conversation threads whereas GmailMessage represents individual emails that makeup a thread.

9. We can enter 'has:attachment' in the search() function for searching emails with file attachments.

10. We need Twilio account SID number, authentication token number and our Twilio phone number before we can send text messages from Twilio.
