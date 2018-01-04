# Conversation Panel

Once you start using [Conversation Linking](ConversationLinking.md) you might
want to see more details on linked conversations and would like to see Intercom 
Users or Leads associated with these conversations. 
That's why we created a Conversation Panel that extracts Intercom conversations and
contacts from linked conversations and displays them next to your Jira issue.

> **[info] Prerequisites**
>
> * [Authorized Intercom Connection](GettingStarted.md)
> * Conversation Panel enabled

As soon as the issue page loads, Intercom for Jira will load all linked Intercom 
conversations and display them as cards in the Conversation Panel.
 
<img class="max-width-50 centered" src="/assets/addons/intercom/ConversationPanel.png"/>

Clicking the user icon on any conversation card will show details for the user associated 
with this conversation.

Conversations for which no details could be resolved (last card in example above) are displayed 
with their id. These conversations might be obsolete and can be removed by 
deleting the respective conversation link in the issue description or comments.

### Open Intercom with conversation

For any conversation in the Conversation panel you can jump to the respective 
Intercom conversation, simply by clicking on the word "Conversation". 
  
### Open Intercom with user/lead

For any conversation in the Conversation Panel you can jump to the respective 
Intercom contact with a single click, simply by clicking on the contact's name.

## What's next?

* [Configure Conversation Panel](ConversationPanelConfiguration.md)