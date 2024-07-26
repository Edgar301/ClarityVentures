# ClarityVentures
Repository containing Clarity Ventures project assignment for Edgar Diaz

To test this program, please unzip the folder and make the changes below.

# To test with Postman, use your 'localhost' and port number ending with the following URL structure '/api/email/send'
- Ex: https://localhost:5001/api/email/send

# Enable Multiple Startup Projects
- Select EmailSenderAPI, EmailSenderWeb, and ProjectScenarioConsole as the startup projects.

# The next step will be to sign up for a SendGrid account and generate an API Key to test this program.
- https://sendgrid.com/en-us/solutions/email-api

# Within the 'ProjectScenarioLibrary' folder, locate the EmailSender.cs class file:
- Update/change line 30 to include your email and name associated with your SendGrid account.

# Within the 'EmailSenderApi' folder, locate the Program.cs class file:
- Update/change lines 25 and 26 to your localhost port number.

# Within the 'EmailSenderApi' folder, locate the appsettings.json file:
- Update line 3 with your API Key from SendGrid.

# Now you should be able to compile the application and run the program.

# Note: File Path for DLL: ProjectScenarioLibrary\bin\Debug\net8.0\ProjectScenarioLibrary.dll

> # One Possible Error:
> ![image](https://github.com/user-attachments/assets/7222dba5-2b66-44c9-b78a-d46eee152ce7)
> 
> I was not able to fully debug this as I was running out of time, but please note that this does not affect the program! Everything works as it should, and you can send emails without issue once the initial setup is done correctly.

