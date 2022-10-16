# SE762-IS300-Project

## Email Attachment Automation

Our proposed RPA bot will generate a personalised PDF featuring relevant information for each sponsor company in the provided excel spreadsheet. The bot will then proceed to email the industry sponsor with the attached PDF.

# Instructions for use

## SETUP

### Requirements
 - Windows
 - Google Account with Gmail
 - UiPath Studio (>= 2021.10.7)

### Add your email as the sender. 
To do this:
- Open 'Email-Sending-Template' file
- Inside the 'Use Gmail' sequence, 
- Beside the Gmail logo, under Account, click Add new account
- Use default values in the popup, and click OK.

	This opens a google sign in form
	Log in to the email account you wish to send emails from
	Accept permission for "Read, compose, send and permanently delete all your email from Gmail."
	Click continue.

### Optional: Add a recipient email
Open the excel spreadsheet containing the data.
Enter the desired email into each contact persons' email address.

This will be the email address that is sent the PDF email.

## Run Main file
#### Run file - Do not run via debug  
 - On running, the user will be prompted with input dialogs.  
 - Input the requested information:
 	- Names of the coordinators;  
 	- The various deadlines of the event;    
 	- Links to be inserted into the final pdf.

#### After the variables have been input,  You will be prompted to select file locations,  
- Select the excel sheet containing company information.  
- Select the word template to fill out.  
- Select the a folder to store the generated PDF files

After all inputs have been entered, the bot will generate the PDFs.

Once the PDFs have been generated, the bot will pause to allow for you to check the PDFs are correct.  
If you are happy, click OK.

On clicking OK, the bot will open Google sign in.  
Sign in with the email you wish to send out the emails from.  
Now, the bot will begin sending out the emails to the intended recipient.

## Contributors
By Group 5:
John Jia, Michelle Lu, Aria Li, Maya de Souza, Alex Qin, Leo Wood, Xueyuan Ye
