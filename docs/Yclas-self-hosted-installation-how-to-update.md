# How to update your website?

Your website should be always up-to-date! :)

You can find a guide for an **Automatic update** or **Manual update** below. We offer an **update service** as well!

Follow these simple steps and update to the newest version available. 

**Requirments for updates**

 

 - 4.x version requires **PHP 7.2** as a minimal version. 
 - Make sure that you have a **PHP 7** before updating. You can ask your hosting provider for it. This is necessary because you need to have a decent updated version of **PHP** installed for your hosting.




### Automatic Update

You just have to follow the normal automatic update steps listed below:

-   **Make a backup**  of all your files and DB.
-   **Log in**  to your admin panel.
-   Go to  **Panel > Updates**  and click  **Update**.
-   That's all!

### Manual Update

**Please follow these instructions**  to prevent any errors.

1.  **Make a backup**  of all your files and DB.  

2.  **Log in**  at your panel.  

3.  **Activate the default theme**  if you had a premium theme.  

4.  **[Download the latest version](https://github.com/yclas/yclas/releases/latest)**  and extract the files in its folder.  

5.  **Enable maintenance mode.**  

6.  **Open your FTP**  or your website file manager  

7. Delete all files in your website folder  **except**  the following:  

-   robots.txt
-   /oc/config/auth.php
-   /oc/config/database.php
-   .htaccess
-   /images/
-   and /themes/ if you had a custom theme.

8.  **Now upload to your folder all the files**  we extracted earlier, except for the files we mentioned in the previous step and the “/install” folder.  

9.  **Run in your browser**  http://yourdomain.com/oc-panel/update/database?from_version=**2.9.0** ( put your current version here )  

10.  **That's all!**

Note: We don't take fault for fail updates and we can't assist you in fixing any occurring issues during that time. If you are not certain how to do the updates we offer an update service for $150 if you have a version 2.x or latest. Please, contact us before getting the update service, [contact us](https://yclas.com/contact/).
