# Automatic emails sent to users 📧
Content:
-   Available templates of emails
-   Set Email from

When a user of your classified site does certain actions, e.g. register, post an ad or request to change the password, he receives an  **automatic email for confirmation**. 

To see and manage those emails, please loginto  **Admin Panel**  ->  **Settings**  > **Email**.

*Note: You need to [add your SMTP configuration](Email-settings-SMTP-configuration.md) before activating this feaure.*

Email templates are already created and translated to multiple languages. You can  **Edit**  them according to your needs by clicking blue button next to the template.
![](https://github.com/yclas/guides/blob/master/images/editemail.png)

  Be sure to set  **locale**  that you are currently using for your site  You can edit  **title**  of the email, its  **body**  and the senders  **email**  displayed. For everything to work properly you need to remember to choose the  **type: email**  and click on  **status**  check box to make it  **active**.

## Available templates of emails

- _Change Password (_**_auth-remember_**_):_  
Sent to user for confirmation after request to change password.

  
- _Welcome to [SITE.NAME]! (_**_auth-register_**_):_  
Welcoming email sent to user after completing registration, reminding data for logging it.

  
- _Hello [USER.NAME]! (_**_user-contact_**_):_  
Mail informing that user have been contacted regarding his advertisement, quoting the message.

  
- _Hello [USER.NAME]!(_**_user-profile-contact_**_):_  
Message sent to user to notify when another user is contacting them directly via their profile.

  
- _[EMAIL.SENDER] wants to contact you! (_**_contact-admin_**_):_  
Message sent to admin when a visitor uses a contact form.

  
- _Your advertisement at [SITE.NAME], has been activated! (_**_ads-activated_**_):_  
Message sent to user when his ad was activated after the moderation by the admin.

  
- _Success! Your advertisement is created on [SITE.NAME]! (_**_ads-notify_**_):_  
Message notifying that the message was created and informing how to edit it and that it still have to be validated by administrator.

  
- _Advertisement is created on [SITE.NAME]! (_**_ads-user-check_**_):_  
Message sent to registered user when the advertisement was created using their account to inform about creating the ad and confirm that they are responsible for posting it.

  
- _Advertisement [AD.TITLE] is created on [SITE.NAME]!_  (**_ads-subscribers_**):  
Message sent to registered user to recommend the related ads.

  
- _Advertisement [AD.TITLE] is created on [SITE.NAME]!_  (**_ads-to-admin_**):  
Message sent to admin with an included link which is worth to visit.

  
- _Advertisement [AD.TITLE] is sold on [SITE.NAME]!_  (**_ads-sold_**):  
Message sent to user to confirm a sale of an advertisement and to provide the information concerning the ID of order and sold product.

  
- _Advertisement [AD.TITLE] is out of stock on [SITE.NAME]!_  _(**out-of-stock**):_  
Message sent to inform about an inactive and invisible advertisement for users and to provide a link which enable admin to activate and increase stocks.

  
- _Advertisement [AD.TITLE] is purchased on [SITE.NAME]!_  _(**ads-purchased**):_  
Message sent to user to confirm a purchase of an advertisement and to provide the confirmation of a purchase (Order ID / Product ID).

  
- _Receipt for [ORDER.DESC] #[ORDER.ID]_  _(**order-new**):_  
Message sent to inform user about an order and to complete the payment (Checkout URL).

  
- _Success! Your advertisement is created on [SITE.NAME]! (_**_ads-confirm_**_)_:  
Message sent to users after creating advertisement with a confirmation link.

  
- _Your ad [AD.NAME] has expired (_**_ad-expired_**_)_:  
Message sent to inform user that his/her ad has expired. It sends that message one day after the expiration.

  
- _Your ad [AD.NAME] is going to expire (_**_ad-to-expire_**_)_:  
Message sent to inform user that his/her ad is going to expire. It sends that message two days before the expiration.

  
- _[FROM.NAME] sent you a direct message (_**_messaging-user-contact_**_)_:  
Message sent to inform user that he/she has a direct message. It includes the name of the sender, the content of the message and the link to this message.

  
- _Hello [TO.NAME]! (_**_messaging-ad-contact_**_)_:  
Message sent to inform user that he/she has been contacted regarding an advertisement. It includes the name of the sender, the ad he/she is interested in, the content of the message and the link to this message.

  
- _New review for [AD.TITLE] [RATE] (_**_ad-review_**_)_:  
Message sent to inform user about a new review on an ad.

  
- _There is a new reply on the forum (_**_new-forum-answer_**_)_:  
Message sent to inform admin about a new reply on the forum. Users that participated to the topic will get informed as well.

  
- _Your plan [PLAN.NAME] has expired (_**_plan-expired_**_)_:  
Email sent to user with a link to pay and renew his subscription.

## Set Email from

This feature is currently available only on all sites hosted at  [Yclas.com](https://yclas.com/)

**Tip:** Previously, when you wanted to replace the Email From field from all the email templates, you had to go to **Content** -> **Email** and edit all the templates one by one. Now there’s an option that allows you to change that field from all email templates directly.*

Follow these steps to set an email form: 
Go to  **Content**  ->  **Email** ->  **Set Email From**, set a new  _From Email_  and click  **Send**.

