
# How to set login attempts to 0


Sometimes you either forget or mistype your password. Almost all of the web services that require a login have a specified number of consecutive invalid login attempts allowed. After that, you are restricted from further login attempts for a certain time period.

![](https://raw.githubusercontent.com/yclas/guides/master/images/error.png)


If your website is made with the Yclas Self-hosted script, then it works as stated below:

**-   After 3 Failed Login attempts:**  _Login has been temporarily disabled due to too many unsuccessful login attempts. Please try again in a minute._
    
-   **After 5 Failed Login attempts:**  _Login has been temporarily disabled due to too many unsuccessful login attempts. Please try again in 24 hours._
    

If you have access to phpmyadmin, there is nothing to worry about!  **Follow these steps to set login attempts to 0:**

1.  Go to phpmyadmin from the cPanel of your hosting.
2.  On the database of your website, choose the table named ‘oc3_users’.
3.  Find the user you want and change the value of the field ‘failed_attempts’ to ‘0’ (zero).

![](https://raw.githubusercontent.com/yclas/guides/master/images/loginattempts.png)

Now you will be are able to login into your website!

*This guide is only for Yclas Self-hosted!*
  
**Related posts:**

-   [How do I create a MySQL database?](Useful-artciles-how-to-use-MySQLi.md)
