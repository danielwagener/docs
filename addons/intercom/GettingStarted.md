# Getting Started

## Installation

1. Log into your JIRA Cloud instance.
2. Click the admin dropdown and choose **Add-ons**.
   The Find new add-ons screen loads.
3. Search for **Intercom for JIRA**.
4. Click **Free trial** to install your add-on.

That's it.

From here proceed with the setup of your Intercom connection.

## Setup a Connection to Intercom

Before you can see any Intercom data you will have to set up a connection to your 
Intercom app.

1. Click the admin dropdown and choose **Projects**.

2. Click the project for which you would like to set up an Intercom connection.

3. In the left sidebar, click on **Intercom integration**.

4. Then click the button **Connect with Intercom**.
   
   This will redirect you to the Intercom OAuth page, where you will be asked for
   permission to link JIRA to Intercom.
   
   > **[info] Note**
   >
   > The Intercom user used to authenticate the connection will be usable by all
   > JIRA users of this project. This means, every interactions with 
   > Intercom happens on behalf of this particular Intercom user.
   > 
   > If you do not want to use your personal Intercom account, consider setting 
   > up a Intercom user specifically for this add-on.
   
5. Click **Connect** to continue. The OAuth page closes automatically and the 
   Intercom connection status changes to _Connected_.

## What's next?

* [Using the Intercom Issue Panel](IntercomIssuePanel.md)