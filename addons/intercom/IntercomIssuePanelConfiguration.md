# Intercom Issue Panel Configuration

Once you have an authorized Intercom Connection you have a bunch of configuration
options available to tailor-fit the add-on's behaviour and features to your needs.

> **[info] Prerequisites**
>
> * [Authorized Intercom Connection](GettingStarted.md)
> * [Jira _Administer projects_ Permission](https://confluence.atlassian.com/adminjiracloud/managing-project-permissions-776636362.html)

## Enable/Disable Intercom Issue Panel
                                                             
By enabling/disabling the toggle button next to the Intercom Issue Panel title
you can enable/disable the whole feature.

This is useful if you don't want the add-on to render the Intercom panel on your
Jira issue page.

## Configure Contact Source

You can specify how Intercom for Jira fetches Contacts. Choose between 
**Linked conversations** or **Issue reporter's email**.

With **Linked conversations** selected, Intercom for Jira will search your issue
for conversation URLs ([Linked Conversations](ConversationLinking.md)) and
extract the associated Intercom Users/Leads from those. The resulting Intercom
Contacts will be shown on the panel.

If you select **Issue reporter's email** the issue reporter's email address will
be matched against Intercom Users and Leads. Matching Intercom Contacts will
be shown on the panel. 

## Configure Visible Fields

This setting allows you to configure visible fields for Intercom Users and Leads.
Visible fields will show up on the [Intercom Panel](IntercomIssuePanel.md) in 
the order defined. In addition to *Intercom standard fields* you can also 
configure [custom attributes](#custom-attributes).

* [Add Field to Visible Fields](#add-field-to-visible-fields)
* [Reorder Visible Fields](#reorder-visible-fields)
* [Remove Field from Visible Fields](#remove-field-from-visible-fields)
* [Add Custom Attribute to Visible Fields](#add-custom-attribute-to-visible-fields)

> **[warning] Warning**
>
> This feature is designed for configurability of the user interface. It is not 
> designed to securely remove information visible to Jira users.
> If a field is not visible, it does not mean that the data is not available to 
> Jira users.


![Visible Fields](/assets/addons/intercom/VisibleFields.png)

### Add Field to Visible Fields

1. Select **User** or **Lead** depending on which entity you would like to configure.
1. Click the select box reading **Choose a field** below the list of visible fields.
1. Type to search or scroll to browse until you have found the field.
1. Click **Add Field**.
1. Your field will be added to the list of visible fields and the configuration
   change will be saved automatically.
   
### Reorder Visible Fields

1. Select **User** or **Lead** depending on which entity you would like to configure.
1. Hover over the field you would like to reorder.
1. Click and drag it to the desired position.
1. The configuration change will be saved automatically.
   
### Remove Field from Visible Fields

1. Select **User** or **Lead** depending on which entity you would like to configure.
1. Browse the list of visible fields until you have found the field you would like
   to remove.
1. Click the **trash bin** button at the right side of the field entry.
1. Your field will be removed from the list of visible fields and the configuration
   change will be saved automatically.
   
### Custom Attributes

Custom attributes are Intercom's way of adding your own fields to your Intercom 
apps. Follow the [instructions in the Intercom documentation](https://docs.intercom.com/configure-intercom-for-your-product-or-site/customize-intercom-to-be-about-your-users/send-custom-user-attributes-to-intercom) 
on how to configure custom attributes. Make sure you follow Intercom's recommended
practices for naming custom attributes, in particular make sure that keys of
attributes of type **Date** end with `_at`, e.g. `last_order_at`. Custom attributes
that end in `_at` are detected as timestamps and rendered in a human readable 
fashion. 

### Add Custom Attribute to Visible Fields

1. Select **User** or **Lead** depending on which entity you would like to configure.
1. Paste the custom attribute name into the input field reading **Custom attribute name** 
   below the list of visible fields. 
   
   > **[info] Note**
   > 
   > The custom attribute name is **case sensitive** and has to match exactly the 
   > name you choose when you configured the field, including _ and spaces.
   >
   > If you need to look up the exact name hover over the custom attribute icon
   > on the User/Lead page and copy it from there.
   >
   > ![Copy Custom Field Name](/assets/addons/intercom/CopyCustomFieldName.png)
   
1. Click **Add Custom Attribute**.
1. Your custom attribute will be added to the list of visible fields and marked 
   with a "Custom Attribute" label. The configuration change will be saved 
   automatically.