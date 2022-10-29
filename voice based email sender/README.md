
# Voice Controlled Email

The project is a python-based voice controlled email application for visually impaired persons using speech to text voice response, thus enabling everyone to control their mail accounts using their voice only.


## Features

- Create and send mails to multiple users.
- Get mailbox status (Mail count from different folders).
- Search mail by Subject or Sender Email (Across different folders).
- Get Latest mails (Across different folders). Defaults to 3 Inbox mails unless specified.
- Voice feedback at most of the steps.
- Gives option to read the full mail body or skip it. 
- Also downloads attachment including a HTML copy of mail in respective folders named after the subject of the mail.
  
## Environment Variables

To run this project, you will need to add the following environment variables to your `CONSTANTS.py` file.

`EMAIL_ID` : *Your Email ID*

`PASSWORD` : *Your Email Password*

**Important :** Also enable `Allow less secure apps` in your Google Account.

**Help Link** : https://support.google.com/accounts/answer/6010255