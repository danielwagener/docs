# Getting Started

## Installation

1. Log into your JIRA instance as an admin.
1. Click the admin dropdown and choose **Add-ons**.
   The Find new add-ons screen loads.
1. Locate **Intercom for JIRA**.
1. Click **Free trial** to download and install your add-on.

You're all set!

Proceed with the setup of your Intercom connection.

## Setup a Connection to Intercom

Before you can see any Intercom data you will have to set up a connection to your 
Intercom app.

1. Click the admin dropdown and choose **Projects**.

1. Click the project for which you would like to set up an Intercom connection.

1. In the left sidebar, click on **Intercom integration**.

1. Then click the button **Connect with Intercom**.

   ![Local Image](/assets/addons/intercom/ConnectToIntercom.png)
   
   This will redirect you to the Intercom OAuth page, where you will be asked to
   log into Intercom (if you haven't done so already) and then for permission to 
   link JIRA to Intercom.
   
   > **[info] Note**
   >
   > The Intercom user you use to authenticate the connection will be shared by all
   > JIRA users of this project. Every interactions with 
   > Intercom happens on behalf of this particular Intercom user.
   > 
   > If you do not want to use your personal Intercom account, consider setting 
   > up a Intercom user specifically for this add-on.
   >
   > See [Intercom Documentation](https://docs.intercom.com/faqs-and-troubleshooting/your-team-inbox/how-do-i-add-or-delete-a-teammate) on how to add a new teammate.
   
1. On the top right of the OAuth page select the Intercom app you would like
   to connect to. 
   
   ![Local Image](/assets/addons/intercom/IntercomOAuthPage.png)
   
1. Click **Connect** to continue. The OAuth page closes automatically and the 
   Intercom connection status changes to _Connected_.
   
   ![Local Image](/assets/addons/intercom/IntercomConnected.png)
   
   When connected the connection details show which Intercom app you are 
   connected to and which user has been used to authorize the connection. 
   Clicking on the app or user name brings you straight to the respective 
   Intercom page.

## What's next?
 
* [Conversation Linking](ConversationLinking.md)
* [Contact Matching](ContactMatching.md)