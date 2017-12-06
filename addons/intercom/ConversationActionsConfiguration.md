# Conversation Actions Configuration

This page will walk you through the configuration options for [Conversation Actions](ConversationActions.md) 
and show you how to choose the right configuration for this feature.

> **[info] Prerequisites**
>
> * [Authorized Intercom Connection](GettingStarted.md)
> * [Jira _Administer projects_ Permission](https://confluence.atlassian.com/adminjiracloud/managing-project-permissions-776636362.html)


## Open Conversation Actions Configuration

The conversation actions configuration is available on the Intercom configuration
page. To open it

1. Click the admin drop-down and choose **Projects**.
1. Click the project you would like to configure.
1. In the left sidebar, click on **Intercom integration**.
1. On the page switch to the **Conversation Actions** tab.

![Conversation Actions Configuration](/assets/addons/intercom/ConversationActionsConfiguration.png)

## Enable/Disable Conversation Actions
                                                             
By enabling/disabling the checkbox for the feature you can enable/disable the conversation actions 
feature for the Jira project.

The feature is disabled by default, so make sure you enable it before you start using conversation 
actions. Please take note of the additional step below if you used Intercom for Jira before 
December 6, 2017.

> **[warning] If you used Intercom for Jira before December 6, 2017**
>
> If you used Intercom for Jira before December 6, 2017 enabling Conversation actions on Jira projects 
> that have already been connected to Intercom may fail (the checkbox does not check).
>
> This is because your existing Intercom connections do not have permission to create the required 
> Intercom webhook. To fix this please revoke and re-authorize the Intercom connection on your Jira 
> projects as described in [Setup a Connection to Intercom](GettingStarted.md#setup-a-connection-to-intercom).

## Configure Create Jira Issue from Intercom

At this time you can choose a default issue type that is used for all issues created via conversation
actions.

### Choose Default Issue Type
Choose your preferred issue type from the select box. Your choice will be saved automatically.

## Configure Link Jira Issue from Intercom

This feature has no configuration options. The configuration page provides an example on how to use
this feature.