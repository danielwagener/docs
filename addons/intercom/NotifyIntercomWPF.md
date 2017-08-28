# Workflow Post Function: Notify Intercom Conversations

If your process requires to notify and re-open linked Intercom conversations on 
specific JIRA issue transitions the workflow post function *Notify Intercom 
Conversations* is for you.

This page walks you through all the steps to configure such a post function.

> **[info] Prerequisites**
>
> * Active Intercom subscription or trial
> * JIRA Project is connected to Intercom
> * Conversation linking is enabled

## Add Workflow Post Function

1. Click the **Cog icon** in the left navigation panel and select **Issues**.
1. In the sidebar, under **Workflows**, click on **Workflow schemes**.
1. Choose the project you'd like to customize, and click the associated **Workflow**.
   ![Select Workflow](/assets/addons/intercom/SelectWorkflow.png)
1. Click the **Edit** button to create a workflow draft or resume editing a draft.
   > **[warning] Warning**
   >
   > You may be in Diagram view at first. Proceed to change to Text view if so.
1. Then, choose a **Step Name**, and click on its **Transition**.
   ![Select Transition](/assets/addons/intercom/SelectTransition.png)
1. On the next screen, click on the **Post Functions** tab.
1. Click **Add Post Function**.
1. Choose **Notify Intercom Conversations**, then click **Add**.
   ![Select Workflow Post Function](/assets/addons/intercom/SelectWorkflowPostFunction.png)
1. On the next screen, choose if you like to re-open closed conversations on this transition.
   Then click **Add**.
   ![Configure Workflow Post Function](/assets/addons/intercom/ConfigureWorkflowPostFunction.png)
1. Remember to publish the draft.
   ![Publish Workflow Draft](/assets/addons/intercom/PublishWorkflowDraft.png)
   
## Edit Workflow Post Function

Once you added the workflow post function you can change its configuration at
any time. To do so

1. Open the post function in edit mode as described above in 
   *Add Workflow Post Function* (steps 1-6)
1. Find *Notify Intercom conversations* post function in the list of configured
   post functions, hover over it, and click on the **Pen icon**.
   ![Edit Workflow Post Function](/assets/addons/intercom/EditWorkflowPostFunction.png)
1. Update the configuration and click *Update*.
   ![Update Workflow Configuration](/assets/addons/intercom/UpdateWPFConfiguration.png)
1. Remember to publish the workflow draft.
   ![Publish Workflow Draft](/assets/addons/intercom/PublishWorkflowDraft.png)

## Troubleshooting

If your Workflow Post Function is not working please ensure that

1. You have a active Intercom subscription or trial
2. The JIRA project is connected to Intercom
3. [Conversation linking is enabled](ConversationLinkingConfiguration.md#enabledisable-conversation-linking) in the connection configuration