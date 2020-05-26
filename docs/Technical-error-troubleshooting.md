# Error troubleshooting - Wow this seems to be an error...

*This guide is only for Yclas Self-hosted!*

**Have you seen this page?**

![](https://raw.githubusercontent.com/yclas/guides/master/images/1.png)


Don’t worry,  it is not as complicated as it may seems!

**How to see what’s the error about?**

You need to log in at your  **Panel**  >  **Tools**  >  **Logs**, then you will see something like:

![](https://raw.githubusercontent.com/yclas/guides/master/images/internal-server-error-1.png)

Here are the error logs that happened in the application and a bit of explanation of what’s going on.

-   If you can’t access to your panel, probably your MySQL server is gone. Contact your hosting provider.
-   If you can’t access to your site, contact your hosting provider as well.

  
**If you can’t access your error log**  follow these steps:

-   Open in your editor  **/oc/bootstrap.php**  (accessed from file manager or FTP)
-   Search for  **=== ‘reoc.lo’**  and replace it with  **!== ‘reoc.lo’**
-   Now you should see the error with some debug information in the footer
-   Revert the changes on the bootstrap.php file

**If you still don’t see any error at your logs**, you can check the error log at your hosting.

In your  **cPanel**  it’s located at  **Home**  >  **Logs**  >  **Error Log.**  If you are the admin of your server, you can type:

`sudo tail -f /var/log/apache2/error.log`  or something similar to see all the errors
