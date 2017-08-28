# Conversation Linking

Intercom conversation linking allows your team to associate Intercom conversations with
JIRA issues. Linked conversations get updates from associated JIRA issues posted 
as a [Note](https://docs.intercom.com/responding-to-users-and-visitors/work-as-a-team/loop-teammates-into-conversations).

This allows your team to easily stay on top of replying to all your customers impacted
by a certain issue in a scalable way. Simply link all conversations to the
respective issue. Additionally, linked issues can automatically be re-opened on 
updates. Initially, you link and close conversations. Once there is progress on 
the JIRA ticket, linked conversations are automatically re-opened and show up at 
the top of your inbox.

> **[info] Prerequisites**
>
> * Active Intercom subscription or trial
>
> This feature is only available if the Intercom App you are connected to has a 
> trial or active subscription.

![Linked Conversation](/assets/addons/intercom/LinkedConversation.png)

 
Notifications can be posted for the following JIRA issue events:

* issue created
* issue assignee changed
* issue status changed
* issue commented

Which of these notifications should be posted and when conversations are re-opened
is fully configurable. See the [here](ConversationLinkingConfiguration.md) on how 
to tweak it.

### Link Intercom Conversation to JIRA Issue
                                                             
A link between an JIRA issue and an Intercom conversation can be established 
simply by pasting a conversation URL into the issue description or comments.

1. Open the Intercom conversation you would like to link.
1. Copy the URL from the browser's address bar.
   ![Copy Conversatio URL](/assets/addons/intercom/CopyConversationUrl.png)
1. Open the JIRA issue you would like to link or create a new one.
1. Paste the URL into an issue comment, or add it to the issue description.
1. Your conversation is now linked and you can find a Note 
   with the issue reference posted to the Intercom conversation.
   
### Unlink Intercom Conversation from JIRA Issue

You can unlink an Intercom conversation by removing the conversation URL from 
the respective JIRA issue comment or description.
After that no more updates will we sent to that conversation.

## Feature limitation

> **[info]** Conversation linking is only available if the Intercom App you are connected to
has a trial or active subscription. 

This condition is imposed by the Intercom API and cannot be changed.

If you are solely using Intercom Platform (free), we recommended that you 
disable conversation linking all together. Follow the instructions on how to [configure
Conversation Linking](ConfigureConnection.html#enabledisable-conversation-linking).


## What's next?

* [Configure Conversation Linking](ConversationLinkingConfiguration.md)
* [Workflow Post Function: Notify Intercom Conversations](NotifyIntercomWPF.md)