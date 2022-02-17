# How to configure SMTP 
Content:
-   Zoho
-   Mailgun
-   SendPulse
-   Amazon Simple Email Service
-   Gmail
-   Outlook
-   Yahoo

For efficient email delivery, we highly recommend using a specialized SMTP service like  **Zoho**,  **Mailgun**,  **SendPulse**  or  **Amazon SES**.

To have a good deliverabilty of your emails you need to use your own email domain such as info@YOURDOMAIN.com and not something like mywebsite@gmail.com. Using free SMTP serivces like Gmail, Outlook or Yahoo it’s a bad idea since there’s lot of limitations on the amount of emails you can send. Please do not use them.

You can easily use you own domain to send emails by using [Zoho for free](Email-settings-host-email-with-custom-domain.md) 

It’s now mandatory to have your site working using SMTP or  [Elasticemail](Email-settings-elasticemail.md). This guide explains how to set up the SMTP configuration of your website.

Go to  **Settings**  ->  **Email** and scroll down to **SMTP** to specify or enable:

-   **Smtp host**
-   **Smtp port**
-   **Smtp Secure**: Enable if the SMTP connection needs to occur over ssl
-   **Smtp auth**: If SMTPAuth should be used 
-   **Smtp username**
-   **Smtp password**



When you finish with this configurations, click  **SAVE**

## Zoho

1. Create an account on  [Zoho.com](https://www.zoho.com/signup.html)  
2.  [Follow the instructions](Email-settings-host-email-with-custom-domain.md)  to verify your domain, add users (email accounts) and create groups.  
3. On the step  **Configure Email Delivery**, you need to login to your domain name provider panel and add the following DNS records:

-   Type:  **MX**
-   Host Name:  **@**
-   Address:  **mx.zoho.com**
-   Priority:  **10**

and

-   Type:  **MX**
-   Host Name:  **@**
-   Address:  **mx2.zoho.com**
-   Priority:  **20**

4. Proceed to  **Mail Client Configuration**  ->  **Outgoing/SMTP**  to find the configuration for your website SMTP:

Using SSL:

-   **Smtp active**: ON
-   **Smtp Secure**: SSL
-   **Smtp host**: smtp.zoho.com
-   **Smtp port**: 465
-   **Smtp auth**: ON
-   **Smtp username**:  _(example@zoho.com, or your own domain’s email address)_
-   **Smtp password**:  _SMTP APP PASSWORD_ (Please refer to the steps below on how you can generate SMTP APP PASSWORD)

Using TLS:

-   **Smtp active**: ON
-   **Smtp Secure**: TLS
-   **Smtp host**: smtp.zoho.com
-   **Smtp port**: 587
-   **Smtp auth**: ON
-   **Smtp username**:  _(example@zoho.com, or your own domain’s email address)_
-   **Smtp password**:  _SMTP APP PASSWORD_ (Please refer to the steps below on how you can generate SMTP APP PASSWORD)


**Generating SMTP APP PASSWORD WITH ZOHO**: 

1. Login to your Zoho account 
2.  Go to Security 
3. Go to Application specific password 
4. Enter the Application name (Yclas)
5. Then click Generate Password.  Copy the password and use this to set up  your email.  

## Mailgun

1. Create an account on  [Mailgun.com](https://www.mailgun.com/smtp)  
2. Obtain your SMTP credentials on your  [domains tab](https://app.mailgun.com/app/domains).  
3. Verify your domain by following  [this guide](https://documentation.mailgun.com/en/latest/quickstart-sending.html#verify-your-domain).  
4. Proceed to  **Mail Client Configuration**  ->  **Outgoing/SMTP**  to find the configuration for your website SMTP:

-   **Smtp active**: ON
-   **Smtp Secure**: SSL
-   **Smtp host**: smtp.mailgun.org
-   **Smtp port**: 465
-   **Smtp auth**: ON
-   **Smtp username**:  _[your Default SMTP Login](https://app.mailgun.com/app/domains)_
-   **Smtp password**:  _password_

## SendPulse

1. Create an account on  [SendPulse.com](https://sendpulse.com/prices/smtp)  
2. Obtaining your SMTP credentials on your SMTP settings.    
3. Proceed to  **Mail Client Configuration**  ->  **Outgoing/SMTP**  to find the configuration for your website SMTP:

-   **Smtp active**: ON
-   **Smtp Secure**: SSL
-   **Smtp host**: smtp-pulse.net
-   **Smtp port**: 465
-   **Smtp auth**: ON
-   **Smtp username**:  _mail@domain.com_
-   **Smtp password**:  _password_

## Amazon Simple Email Service

1. Create an account on  [AWS](https://aws.amazon.com/ses/)  
2. Obtain your SMTP credentials by following  [this guide](https://docs.aws.amazon.com/ses/latest/DeveloperGuide/smtp-credentials.html).  
3. Proceed to  **Mail Client Configuration**  ->  **Outgoing/SMTP**  to find the configuration for your website SMTP:

-   **Smtp active**: ON
-   **Smtp Secure**: TLS
-   **Smtp host**:  _Enter the SMTP endpoint for the AWS Region in which you use Amazon SES. For a list of endpoints, see  [Amazon SES Endpoints](https://docs.aws.amazon.com/ses/latest/DeveloperGuide/regions.html#region-endpoints)._
-   **Smtp port**: 587
-   **Smtp auth**: ON
-   **Smtp username**:  _SMTP user name_
-   **Smtp password**:  _SMTP password_

## Gmail

If you are using a Gmail account use the information provided below.

In order to get Gmail to work with SMPT you have to enable Gmail to allow less secure apps to use it's service.

If your website is using SSL (https://):

-   **Smtp active**: ON
-   **Smtp Secure**: SSL
-   **Smtp host**: smtp.gmail.com
-   **Smtp port**: 465
-   **Smtp auth**: ON
-   **Smtp username**:  _email address (example@gmail.com)_
-   **Smtp password**:  _gmail account password_

If your website is using TLS (http://):

-   **Smtp active**: ON
-   **Smtp Secure**: TLS
-   **Smtp host**: smtp.gmail.com
-   **Smtp port**: 587
-   **Smtp auth**: ON
-   **Smtp username**:  _email address (example@gmail.com)_
-   **Smtp password**:  _gmail account password_

## Outlook

-   **Smtp active**: ON
-   **Smtp Secure**: TLS
-   **Smtp host**: smtp-mail.outlook.com
-   **Smtp port**: 587
-   **Smtp auth**: ON
-   **Smtp username**:  _email address (example@outlook.com)_
-   **Smtp password**:  _password_

**Important! Settings -> Email settings -> Notify Email must match your SMTP user**

## Yahoo

-   **Smtp active**: ON
-   **Smtp Secure**: TLS
-   **Smtp host**: smtp.mail.yahoo.com
-   **Smtp port**: 587
-   **Smtp auth**: ON
-   **Smtp username**:  _email address (example@yahoo.com)_
-   **Smtp password**:  _password_

  
**Related posts:**

-   [Host your email with your custom domain using Zoho Mail](Email-settings-host-email-with-custom-domain.md)
-   [How to Configure ElasticEmail on Yclas](Email-settings-elasticemail.md)
-   [Troubleshooting Email errors](Email-settings-troubleshooting-email-errors.md)



<iframe width="100%" height="400px" src="https://www.youtube.com/embed/_0efWYoB3BQ" title="Yclas video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
