# Conversation Panel Configuration

Once you have an authorized Intercom Connection you have a bunch of configuration
options available to tailor-fit the add-on's behaviour and features to your needs.

> **[info] Prerequisites**
>
> * [Authorized Intercom Connection](GettingStarted.md)
> * [Jira _Administer projects_ Permission](https://confluence.atlassian.com/adminjiracloud/managing-project-permissions-776636362.html)

## Enable/Disable Conversation Panel
                                                             
By enabling/disabling the toggle button *Enable Conversation Panel* you can 
enable/disable the whole feature.

This is useful if you don't want the add-on to render the Conversation panel on your
Jira issue page.

## Configure Visible Fields

This setting allows you to configure visible fields for different Intercom entities, e.g.
when rendering users in the [Conversation Panel](ConversationPanel.md). In addition to 
Intercom standard attributes you can also configure [custom attributes](https://docs.intercom.com/configure-intercom-for-your-product-or-site/customize-intercom-to-be-about-your-users/send-custom-user-attributes-to-intercom).

* [Add Field to Visible Fields](#add-field-to-visible-fields)
* [Reorder Visible Fields](#reorder-visible-fields)
* [Remove Field from Visible Fields](#remove-field-from-visible-fields)

> **[warning] Warning**
>
> This feature is designed for configurability of the user interface. It is not 
> designed to securely remove information visible to Jira users.
> If a field is not visible, it does not mean that the data is not available to 
> Jira users.


![Visible Fields](/assets/addons/intercom/VisibleFields.png)

### Add Field to Visible Fields

1. Select the entity (**User**, **Lead**) that you would like to configure.
1. Click the select box reading **Choose a field** below the list of visible fields.
1. Type to search or scroll to browse until you have found the field.
1. Click **Add Field**.
1. Your field will be added to the list of visible fields and the configuration
   change will be saved automatically.
   
### Reorder Visible Fields

1. Select the entity (**User**, **Lead**) that you would like to configure.
1. Hover over the field you would like to reorder.
1. Click and drag it to the desired position.
1. The configuration change will be saved automatically.
   
### Remove Field from Visible Fields

1. Select the entity (**User**, **Lead**) that you would like to configure.
1. Browse the list of visible fields until you have found the field you would like
   to remove.
1. Click the **trash bin** button at the right side of the field entry.
1. Your field will be removed from the list of visible fields and the configuration
   change will be saved automatically.