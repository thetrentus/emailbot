# Email Spambot Script Version 1.0

### Instructions
- Setup
- Configuration
- Manual
- How to use

### Setup
- Rename "Setup.txt" to "Setup.bat".
- Run "Setup.bat"
- Enable "Less secure apps" for your gmail account. (The site that was opened by your browser.)


### Configuration
- Open "EmailSpam.vbs" with your preffered text editor (Don't double click it)
- In line 7, replace [Your Email] with your gmail address. (Example: User = "example@gmail.com" )
- In line 8, replace [password] with your gmail account's password. (Example:  Pass = "StrongPassword15" )
  - Note: The password is case sensitive and will NOT be send with the email. 
- In line 9, replace [Your name] with your name. (Example: Name = "Peter Clark" )
  - Note: Don't use your actual name. Use a nickname!
- In line 10, replace [Opponent Email] with the email you want to spam. (Example: Input = "example.mail@gmail.com" )
- In line 11, replace [Title] with the title of the spam email. (Example: Input2 = "This is Spam" )
- In line 12, replace [Body] with what the email should include. (Example: Input3 = "Spam Spam Spam Spam Spam" )
  - Note: Do NOT use HTML to  write the email's body. The body is only for plain text.
- Save the file.

### Manual
- If the configuration failed, run "Manual.vbs" instead.
- You will not be able to automatically send emails if the server rejects your requests.

### How to use
- In order to use this Spambot, you have to configure the "EmailSpam.vbs" file (see "Configuration" above).
- After the configuration is done, you can now run the "SpamStart.bat" file.

### SpamStart.bat
- The batch file will start a new commandpromt window (cmd.exe) and start to send emails to your opponents email address.
- Approximately every second one emails will be sent. It will take about a minute until the gmail server blocks your request.
- The batch file will automatically wait for 5 minutes until the server is open again.
  - Note: You can only send about 2.000 emails per day. After you reached the cap, the Spambot will be useless for 24 hours.
