# Intercom Issue Panel

Once you start using [Conversation Linking](ConversationLinking.md) you might
want to know which Intercom Users or Leads are associated with linked 
conversations and display that information in your Jira issue. 
That's why we created Intercom Issue Panel that extracts Intercom Contacts from
linked conversations and displays them next to your Jira issue.

> **[info] Prerequisites**
>
> * [Authorized Intercom Connection](GettingStarted.md)
> * Intercom Issue Panel enabled

As soon as the issue page loads, Intercom for Jira will extract Intercom 
Users or Leads for all linked Intercom conversations and display the result
in the Intercom Issue Panel.
 
* If there is only _one match_ you will see the Intercom user directly showing on
  the Intercom panel.
  
  ![Local Image](/assets/addons/intercom/IntercomPanel.png)

* If there is _more then one match_ a list of Users and Leads will be shown with
  a button to see each customer's details.
  
  ![Local Image](/assets/addons/intercom/IntercomPanelMultiContacts.png)
  
### Open Intercom with current User/Lead

For any contact in the Intercom panel you can jump to the respective 
Intercom contact with a single click. Use the link button to load Intercom in a 
new tab or simply click the Contact's name.

![Local Image](/assets/addons/intercom/IntercomPanelOpenLink.png)

## Alternative use case

If some of your Intercom Contacts use Jira Service Desk to report issues you can
configure the Intercom Panel to display Intercom Contacts next to your Jira
issue by auto-matching the issue reporter's email address against your Intercom
Users and Leads. Matching contacts show up automatically and give you customizable
Intercom information about the issue reporter.

To enable this mode see [Configure Intercom Issue Panel](IntercomIssuePanelConfiguration.md) 
to change the contact source configuration to *Issue reporter's email*.

## What's next?

* [Configure Intercom Issue Panel](IntercomIssuePanelConfiguration.md)