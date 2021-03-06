# Release Notes

> **[success] Latest Release**
>
> ### 1.2.1 (Marketplace Version: **1.2.8-AC** )
>
> Release Date: **2018-01-05**
>
> **New Features**  
>  * Simplified configuration for [visible fields:](ConversationPanelConfiguration.md#configure-visible-fields) 
>    Custom and standard attributes can now be configured through the same select box and get fetched
>   directly from your Intercom app. 
>

## Past Releases

### 1.2.0 (Marketplace Version: **1.2.8-AC** )

Release Date: **2018-01-03**

**New Features**  
 * Intercom Issue Panel is now [Conversation Panel](ConversationPanel.md). The panel now
   shows linked conversations and their respective Intercom user.

**Bug Fixes**  
 * Fix a problem where lead name is not rendered when there is only a pseudonym available.
   
---


### 1.1.5 (Marketplace Version: **1.2.7-AC** )

Release Date: **2017-12-07**

**Bug Fixes**  
 * Fix a problem where conversation actions fail because of inconsistent data format.

---

### 1.1.4 (Marketplace Version: **1.2.7-AC** )

Release Date: **2017-12-06**

**New Features**  
 * New [conversation actions](ConversationActions.md) to create and link Jira issues
   directly from Intercom conversations.

**Improvements**  
 * Show a pop-up message to inform users to reload the Jira page if connection to 
   add-on server has expired.
 * Change Intercom configuration page to a Tab layout instead of a single page to make
   it easier to navigate different feature configurations. 

**Bug Fixes**  
 * Fix a problem where Intercom feature toggles did not actually reflect the correct on/off
   state.


---

### 1.1.3 (Marketplace Version: **1.2.6-AC** )

Release Date: **2017-09-15**

**New Features**  
 * New visible field [configuration to add Intercom custom attributes](ConversationPanelConfiguration.md#custom-attributes)
   to Conversation Panel.

---

### 1.1.2 (Marketplace Version: **1.2.5-AC** )

Release Date: **2017-09-11**

**Bug Fixes**  
 * Fix an issue where conversation URLs copied from Intercom Respond fail to
   be parsed properly.

---

### 1.1.1 (Marketplace Version: **1.2.5-AC** )

Release Date: **2017-09-11**

**New Features**  
 * Conversation panel can now **show Intercom contacts extracted from linked
   Intercom conversations**.
 * New **contact source configuration** that allows to control whether Intercom
   conversation panel shows Intercom contacts based on linked conversations or based
   on issue reporter's email address.

**Removals**
 * Create Intercom User or Lead when there is no Intercom contact matching
   a issue reporter's email has been removed. If anyone needs this feature
   we will look into ways to add it back.


> **[info] Note**
>
> Existing users who have Conversation panel enabled might see the 
> panel disappear after the update. To fix this simply go to to the 
> Intercom configuration page and toggle the feature switch to *off* and 
> then *on* again.
   
---

### 1.1.0

Release Date: **2017-08-28**

**New Features**  
 * New configuration to **enable/disable Contact Matching** feature.
 * New **Workflow Post Function to notify Intercom conversation** on issue
   transition and optionally re-open conversation.
 * New **notification trigger configuration** that allows more fine-grained
   configuration of when to notify Intercom conversations. 

**Removals**
 * Removed global re-open conversation configuration. We replaced the global
   re-open switch with a much more fine-grained configuration that is more
   versatile and adaptable to different use cases. The use case of a global
   re-open feature is fully covered by the new configuration.

Marketplace Version: **1.2.4-AC**  

---

### 1.0.5
Release Date: **2017-08-17**

**Bug Fixes**  
 * Fix a problem that caused contact matching to fail and resulted in Intercom panel
   not rendering.
   
Marketplace Version: **1.2.1-AC**  

---

### 1.0.4

Release Date: **2017-08-11**

**Improvements**  
 * Fix UI spacing on connection configuration page

Marketplace Version: **1.2.1-AC**  

---

### 1.0.3

Release Date: **2017-08-10**
 
**New Features**
 * Conversation Linking

**Improvements**  
 * Render *Browser* field with decoded browser and OS information

Marketplace Version: **1.2.1-AC**  

---
 
### 1.0.2

Release Date: **2017-08-01**

** New Features**
 * Contact matching
 * Configurable visible Intercom fields
 * Create Intercom User or Lead if no match found
 
Marketplace Version: **1.2.0-AC**  