## Release Notes

> **[success] Latest Release**
>
> ### 1.1.3 (Marketplace Version: **1.2.6-AC** )
>
> Release Date: **2017-09-15**
>
> **New Features**  
>  * New visible field [configuration to add Intercom custom attributes](IntercomIssuePanelConfiguration.md#custom-attributes)
>    to Intercom Issue Panel.

## Past Releases

### 1.1.2 (Marketplace Version: **1.2.5-AC** )

Release Date: **2017-09-11**

**Bug Fixes**  
 * Fix an issue where conversation URLs copied from Intercom Respond fail to
   be parsed properly.

---

### 1.1.1 (Marketplace Version: **1.2.5-AC** )

Release Date: **2017-09-11**

**New Features**  
 * Intercom issue panel can now **show Intercom contacts extracted from linked
   Intercom conversations**.
 * New **contact source configuration** that allows to control whether Intercom
   issue panel shows Intercom contacts based on linked conversations or based
   on issue reporter's email address.

**Removals**
 * Create Intercom User or Lead when there is no Intercom contact matching
   a issue reporter's email has been removed. If anyone needs this feature
   we will look into ways to add it back.


> **[info] Note**
>
> Existing users who have Intercom issue panel enabled might see the 
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
 * Fix a problem causes contact matching to fail and hinders Intercom panel
   from rendering
   
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