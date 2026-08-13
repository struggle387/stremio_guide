## Guide to Setting Up Stremio with Tor Box
Follow the steps below to integrate TorBox with Stremio.


#### Step 1: Create a Stremio Account
Go to [Stremio's Official Website](https://www.stremio.com/)
Click on "Sign Up" and follow the process to create your account.


#### Step 2: Create a TorBox Account
Visit [TorBox's](https://www.torbox.app/) Website.
Sign up for an account.


#### Step 3: Access Stremio Account Bootstrapper
Visit the [Stremio Account Bootstrapper](https://stremio-account-bootstrapper.vercel.app/) website.


#### Step 4: Input Stremio Account Information
Option 1: Using Email & Password.

Enter the email and password used to create your Stremio account.
<img width="909" height="406" alt="Screenshot From 2025-09-26 12-27-37" src="https://github.com/user-attachments/assets/101149c8-10b0-4d92-9230-a8378521cc21" />

Option 2: Using Auth Key

Alternatively, you can retrieve your Stremio Auth Key from [stremio](https://www.stremio.com/) using the developer console in your browser.
Open the developer tools (usually with F12 or Ctrl+Shift+I), go to the Console tab, and enter the following JavaScript command:
``JSON.parse(localStorage.getItem("profile")).auth.key``


#### Step 5: Get Your Debrid API Token
Go to [TorBox API Token Page](https://torbox.app/settings?section=account),
Log in with your TorBox account if you haven't already.
Copy your API private token. Do not share this API private token with others.
<img width="881" height="166" alt="image" src="https://github.com/user-attachments/assets/bb00e272-e87f-4c75-b2d0-2851d9fb10e1" />



#### Step 6: Configure Settings on Bootstrapper
In the Stremio Account Bootstrapper, you will have an option to select settings.
Paste your API private token into the TorBox API key box. 
Set any additional preferences you need for your account.
Choose the following options to ensure everything is set up correctly:

 !!! MAKE SURE TO SELECT Cached-only (debrid) !!!
<img width="1003" height="1082" alt="Screenshot From 2025-09-26 12-28-35" src="https://github.com/user-attachments/assets/101f7f14-f6cb-4362-8cdf-9856fdaf436f" />


#### Step 7: Load Preset and Sync to Stremio
After configuring the settings, click on Load Preset.
Confirm that the preset matches the settings provided.
Once confirmed, click on Sync to Stremio to apply the settings.
<img width="949" height="818" alt="Screenshot From 2025-09-26 13-14-12" src="https://github.com/user-attachments/assets/ef5ddffb-80b3-47df-a876-3367917adb18" />


#### Step 8: Log into Stremio
Go back to the Stremio app or website.
Log in using the account details.
You’re All Set!
