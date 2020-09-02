# Troubleshooting Email errors

Sometimes when someone registers to your website, posts an ad or contacts you through the contact page they may get an error message. The *error* could be caused by user, for example an invalid input, but it could also be related to the mail function.

We have listed the most common error messages you may get. If there’s an error related to the email configuration an explanation will follow and a tip about what to do. Please refer to the examples below : 

-   [Mailer Error: SMTP connect failed](https://github.com/PHPMailer/PHPMailer/wiki/Troubleshooting)  
    It means that we cannot connect to your SMTP server, probably because email settings are not configured.  [This guide](Email-settings-SMTP-configuration.md)  explains how to configure Email Settings.
    
-   **Mailer Error: The following From address failed: some@email.com : Called MAIL FROM without being connected**  
    Email Settings are not properly configured. You need to review  **SMTP user**  and  **SMTP password**  on Settings -> Email Settings.
    
-   **Mailer Error: stream_socket_enable_crypto(): SSL operation failed with code 1. OpenSSL Error messages: error:14090086:SSL routines:ssl3_get_server_certificate:certificate verify failed**  
    On Settings -> Email, switch  **SMTP secure**  from SSL to TLS and  **SMTP port**  from 465 to 587.
    
You may also be interested in:

-   [How to configure SMTP](Email-settings-SMTP-configuration.md)
-   [How to Configure ElasticEmail on Yclas](Email-settings-elasticemail.md)
