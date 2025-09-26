### Guide to Setting Up Stremio with Real Debrid ###
Follow the steps below to integrate Real Debrid with Stremio for enhanced streaming experience.

Step 1: Create a Stremio Account
Go to Stremio's Official Website
Click on "Sign Up" and follow the process to create your account.

Step 2: Create a Real-Debrid Account
Visit Real Debrid's Website
Sign up for an account.
Note: A Real Debrid subscription costs €4 for 30 days or €16 for 180 days. You can choose from a variety of payment methods available on Real Debrid.

Step 3: Access Stremio Account Bootstrapper
Visit to Stremio Account Bootstrapper

Step 4: Input Stremio Account Information
Option 1: Using Email & Password
Enter the email and password used to create your Stremio account.
Option 2: Using Auth Key
Alternatively, you can retrieve your Stremio Auth Key using the developer console in your browser.
Open the developer tools (usually with F12 or Ctrl+Shift+I), go to the Console tab, and enter the following JavaScript command:
JSON.parse(localStorage.getItem("profile")).auth.key

Step 5: Get Your Real Debrid API Token
Go to Real Debrid API Token Page
Log in with your Real Debrid account if you haven't already.
Copy your API private token.

Step 6: Configure Settings on Bootstrapper
In the Stremio Account Bootstrapper, you will have an option to select settings.
Choose the following options to ensure everything is set up correctly:
Enable Real Debrid integration.
Set any additional preferences you need for your account.

Step 7: Load Preset and Sync to Stremio
After configuring the settings, click on Load Preset.
Confirm that the preset matches the settings provided.
Once confirmed, click on Sync to Stremio to apply the settings.

Step 8: Log into Stremio
Go back to the Stremio app or website
Log in using the account details.
You’re All Set!
