# SE762-IS300-Project

## Email attachment automation

Our proposed RPA bot will generate a personalised PDF featuring relevant information for each sponsor company in the provided excel spreadsheet. The bot will then proceed to email the industry sponsor with the attached PDF.


# Instructions for use

## SETUP

### Add your email as the sender. 
To do this:
Open 'Email-Sending-Template' file
Inside the 'Use Gmail' sequence, 
Beside the Gmail logo, under Account, click Add new account
Use default values in the popup, and click OK.

	This opens a google sign in form
	Log in to the email account you wish to send emails from
	Accept permission for "Read, compose, send and permanently delete all your email from Gmail."
	click continue.

### Optional: Add a recipient email
Open the excel spreadsheet containing the data.
Enter the desired email into each contact persons' email address.

This will be the email address that is sent the PDF email.

## Run Main file

On running, the user will be prompted with input dialogs.  Please input the asked information.
the names of the coordinators;  the various deadlines of the event;  and links to be inserted into the final pdf.

After the variables have been input,  
setup information will be prompted,  
Select the excel sheet containing company information.  
Please select the word template to fill out.  
Please select the a folder to store the generated PDF files

Once the PDFs have been generated, the bot will pause to allow for you to check the PDFs are correct.  
If you are happy, click OK.

On clicking OK, the bot will open Google sign in.  
Sign in with the email you wish to send out the emails from.


By Group 5:
John Jia, Michelle Lu, Aria Li, Maya de Souza, Alex Qin, Leo Wood, Xueyuan Ye