# Configure Intercom Connection

Once you have an authorized Intercom Connection you have a couple of configuration
options available to tailor-fit the add-on's behaviour to your needs.

> **[info] Prerequisites**
>
> * [Authorized Intercom Connection](GettingStarted.md)
> * [JIRA _Administer projects_ Permission](https://confluence.atlassian.com/adminjiracloud/managing-project-permissions-776636362.html)

## Configure Visible Fields

This setting allows you to configure visible fields for Intercom Users and Leads.
Visible fields will show up on the [Intercom Panel](IntercomIssuePanel.md) in the order defined.

The configuration allows you to 

* [Reorder Visible Fields](#reorder-visible-fields)
* [Add Field to Visible Fields](#add-field-to-visible-fields)
* [Remove Field from Visible Fields](#remove-field-from-visible-fields)

> **[warning] Warning**
>
> This feature is designed for configurability of the user interface. It is not 
> designed to securely remove information visible to JIRA users.
> If a field is not configured to be visible, it does not mean that the data is  not
> available to JIRA users.


![Visible Fields](/assets/addons/intercom/VisibleFields.png)

### Reorder Visible Fields

1. Select **User** or **Lead** depending on which entity you would like to configure.
1. Hover over the field you would like to reorder.
1. Click and drag it to the desired position.
1. The configuration change will be saved automatically.

### Add Field to Visible Fields

1. Select **User** or **Lead** depending on which entity you would like to configure.
1. Click the select box reading **Choose a field** below the list of visible fields.
1. Type to search or scroll to browse until you have found the field.
1. Click **Add**.
1. Your field will be added to the list of visible fields and the configuration
   change will be saved automatically.
   
### Remove Field from Visible Fields

1. Select **User** or **Lead** depending on which entity you would like to configure.
1. Browse the list of visible fields until you have found the field you would like
   to remove.
1. Click the **trash bin** button at the right side of the field entry.
1. Your field will be removed from the list of visible fields and the configuration
   change will be saved automatically.
   
## Configure Conversation Linking


Intercom conversation linking allows you to get updates to a Intercom conversations 
whenever the associated JIRA issue changes.

> **[info] Conversation Linking Feature**
>
> See the [Conversation Linking page](ConversationLinking.md) for detailed feature 
> description and how to use it.

The following screenshot shows the Conversation Linking configuration with all
features enabled. See below on how the individual settings work.

![Linked Conversation Configuration](/assets/addons/intercom/ConversationLinkingConfiguration.png)

### Enable/Disable Conversation Linking
                                                             
By enabling/disabling the toggle button next to the Conversation Linking title
you can enable/disable the whole conversation linking feature.

This is useful if you don't want the add-on to post to your conversations even
if you happen to past conversation links to issue descriptions or comments. Or,
if you do not have a active Intercom trial or subscription (Conversation Linking
with Intercom trail or subscription). 
   
### Enable/Disable re-open closed conversations

By enabling this option closed Intercom conversations are re-opened automatically
once a JIRA issue update is posted to the conversation.

If don't want the add-on to touch conversation states disable this option. 


## What's next?

* [Using Conversation Linking](ConversationLinking.md)
* [Using the Intercom Issue Panel](IntercomIssuePanel.md)