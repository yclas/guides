# How to update your website?

Your website should be always up-to-date :)

You can find a guide for an **Automatic update** or **Manual update** below. We offer an **update service** as well.

Follow these simple steps and update to the newest version available.

**Requirments for updates**



 - 4.x version requires **PHP 7.3** as a minimal version.
 - Make sure that you have a **PHP 7** before updating. You can ask your hosting provider for it. This is necessary because you need to have a decent updated version of **PHP** installed for your hosting.
 - If you have Yclas Self-hosted Pro, be sure your susbscription is active so you get latest Pro version. [Please buy here](https://yclas.com/self-hosted.html)




### Automatic Update

You just have to follow the normal automatic update steps listed below:

1. Make a backup  of all your **files and DB.**
2. Log in  to your **admin panel.**
3. Go to  **Panel -> Settings -> Updates** and click **Update**.

> **Please, if your current version is `4.2.0` replace the following files before proceeding to step 3.**
> 1. `oc/classes/controller/panel/update.php` with [yclas/yclas/oc/classes/controller/panel/update.php](https://raw.githubusercontent.com/yclas/yclas/69d2d91b4ac93d26b0b1225053610d0117a9d7a4/oc/classes/controller/panel/update.php)
> 2. `themes/default/views/oc-panel/pages/update/confirm.php` with [yclas/yclas/themes/default/views/oc-panel/pages/update/confirm.php](https://raw.githubusercontent.com/yclas/yclas/c00bb1d929b69fb47f5725455752157dfd4785a5/themes/default/views/oc-panel/pages/update/confirm.php)

### Manual Update

**Please follow these instructions**  to prevent any errors.

1.  Make a backup  of all your **files and DB.**

2.  Log in  to your **admin panel.**

3.  **Activate the default theme / atlantic**  if you had a premium theme.

4.  **[Download the latest version](https://yclas.com/selfhosted/latest)**  and extract the files in its folder.

5.  **Enable maintenance mode.**

6.  **Open your FTP**  or your website file manager.

7. Delete all files in your website folder  **except**  the following:

-   robots.txt
-   /oc/config/auth.php
-   /oc/config/database.php
-   .htaccess
-   /images/
-   /themes/default/css/web-custom.css if you have custom CSS
-   and check in /themes/ if you have a custom them do not delete it

8.  **Now upload to your folder all the files**  we extracted earlier, except for the files we mentioned in the previous step and the “/install” folder.

9.  **Run in your browser** [http://yourdomain.com/oc-panel/update/database?from_version=**2.9.0**](http://yourdomain.com/oc-panel/update/database?from_version=2.9.0) (put your current version here )

Note: We don't take fault for fail updates and we can't assist you in fixing any occurring issues during that time. If you are not certain how to do the updates we offer an update service for $150 if you have a version 2.x or latest. Please, contact us before getting the update service, [contact us](https://yclas.com/contact/).
