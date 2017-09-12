# Conversation Linking Configuration

Intercom conversation linking allows you to get notifications on Intercom conversations 
whenever associated Jira issues change. This page will walk you through the
configuration options and show you how to tweak the feature to your needs.

> **[info] Prerequisites**
>
> * [Authorized Intercom Connection](GettingStarted.md)
> * [Jira _Administer projects_ Permission](https://confluence.atlassian.com/adminjiracloud/managing-project-permissions-776636362.html)


## Open Conversation Linking Configuration

The conversation linking configuration is available on the Intercom connection
page. To open it

1. Click the admin dropdown and choose **Projects**.
1. Click the project you would like to configure.
1. In the left sidebar, click on **Intercom integration**.

The following screenshot shows the Conversation Linking configuration with all
features enabled. See below on how the individual settings work.

![Linked Conversation Configuration](/assets/addons/intercom/ConversationLinkingConfiguration.png)

## Enable/Disable Conversation Linking
                                                             
By enabling/disabling the toggle button next to the Conversation Linking title
you can enable/disable the whole conversation linking feature.

This is useful if you don't want the add-on to post to your conversations even
if you happen to past conversation links to issue descriptions or comments. Or,
if you do not have a active Intercom trial or subscription (Conversation Linking
with Intercom trail or subscription).

## Configure when to notify linked Intercom conversations

Check the Jira issue events for which you would like Intercom
for Jira to post notifications. You can choose one or more of the following events: 

* issue created
* issue assignee changed
* issue status changed
* issue commented

For each of these events you can decide whether you would like to re-open closed 
Intercom conversations or not.

> **[info] Workflow Post Function: Notify Intercom Conversations**
>
> If you would like to send notifications on issue transition and have fine-grained
> control over when notifications are sent and when conversations are re-opened,
> consider using a **Workflow Post Function** to notify Intercom conversations.
>
> See the [Workflow Post Function page](NotifyIntercomWPF.md) for detailed 
> description and how to configure it.