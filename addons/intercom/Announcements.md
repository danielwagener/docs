# Announcements

On this page we will publish important notices related to Intercom for Jira. Please subscribe to 
future updates by leaving your email address below or come back once in a while to check on the 
latest updates.

<div id="mc_embed_signup">
    <form action="https://toolsplus.us16.list-manage.com/subscribe/post?u=86259383cdca3014501f79098&amp;id=4fabaa3a90" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll">
            <div class="mc-field-group">
                <label for="mce-EMAIL">Email Address </label>
                <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
            </div>
            <div id="mce-responses" class="clear">
                <div class="response" id="mce-error-response" style="display:none"></div>
                <div class="response" id="mce-success-response" style="display:none"></div>
            </div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
            <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_86259383cdca3014501f79098_4fabaa3a90" tabindex="-1" value=""></div>
            <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
        </div>
    </form>
</div>

<br>

## Removal: *issue reporter email* contact source for Intercom Issue Panel

12 December 2017 

In the Intercom Issue Panel settings you are able to choose whether Intercom contacts 
should be shown based on linked conversations or the issue reporter's email. We believe 
that Intercom contacts on the Intercom Issue Panel are almost exclusively shown based on 
linked conversations (which is the default configuration for new installations). To our 
knowledge there is no use case for rendering contacts based on the issue reporter's email 
address.

![Issue Reporter Email Contact Source](/assets/addons/intercom/RemovalIssueReporterEmail.png)

### Planned change
Remove *issue reporter email* as a contact source from Intercom settings.

### How does this change affect you?
* If you are using *linked conversations* as contact source for your Intercom Issue Panel 
(this is the default) you won't be affected by this change.
* If you are using *issue reporter's email* as contact source the add-on will automatically 
fallback to linked conversations setting.

### When does this change take effect?
This change is planned to be completed by end of December or early January 2018.

Please get in touch if you are using this feature or you think removal of it might be problem 
for you.