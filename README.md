# downloadgmailattachments
This Python script uses imaplib and email libraries to allow the user to download email attachments from specific email addresses. The user must enter their Gmail account credentials, including their email address and password, into the code. The user can also specify labels such as "Inbox," "Trash," or "Archive" to search within messages, as well as the email addresses and subject (using the 'ALL' keyword to download all attachment files) to search for. Once the search parameters are set, the script loops through each email message that meets the criteria and saves attachments that meet the specified criteria to a folder called attachments in the directory where the script is run. 

Steps to run the code:

  Edit the code to include your Gmail account credentials, email addresses, and subject lines.
  Run the script in your Python environment (Python 2.7/3.6 compatible).
  The code will create a folder called attachments to store the downloaded files, if the folder does not already exist.
  The script searches the email messages based on the set parameters.
  The script saves attachments that meet the criteria to the attachments folder.
