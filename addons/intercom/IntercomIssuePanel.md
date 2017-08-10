# Intercom Issue Panel

Some of your customers might use JIRA Service Desk to report issues. At the same
time this same customer contacted you previously via the Intercom messenger on
your homepage.

The Intercom Issue Panel allows you to display Intercom Contacts next to your JIRA
issue by auto-matching the issue reporter's email address against your Intercom
Users and Leads. Matching contacts show up automatically and give you useful Intercom
information about the issue reporter.

If on the other hand no matching contact could be found you can easily create a
Intercom User or Lead from the JIRA issue reporter.

> **[info] Prerequisites**
>
> * [Authorized Intercom Connection](GettingStarted.md)

## Contact Matching

As soon as the issue page loads, Intercom for JIRA will try to match the issue
reporter's email address against any Intercom User or Lead email addresses.
 
* If there is only _one match_ you will see the Intercom user directly showing on
  the Intercom panel.
  
  ![Local Image](/assets/addons/intercom/IntercomPanel.png)

* If there is _more then one match_ a list of Users and Leads will be shown with
  a button to see each [Contact's](Glossary.md#def-contacts) details.
  
  ![Local Image](/assets/addons/intercom/IntercomPanelMultiContacts.png)
  
### Open Intercom with current Context

For any matched contact in the Intercom panel you can jump to the respective 
Intercom contact with a single click. Use the link button to load Intercom in a 
new tab or simply click the Contact's name.

![Local Image](/assets/addons/intercom/IntercomPanelOpenLink.png)

### Create Intercom User or Lead from Issue reporter

If Intercom for JIRA could not find a matching Intercom User or Contact you will 
be given the option to create a User or Lead from the issue reporter.

Simply click **Create** and select **User** or **Lead** depending on which one 
you would like to create. As soon as creation is complete the Intercom panel
reloads and the created contact is shown.

![Local Image](/assets/addons/intercom/IntercomPanelNoMatch.png)

## What's next?

* [Using Conversation Linking](ConversationLinking.md)