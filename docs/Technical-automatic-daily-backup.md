# Automatic daily backups

_This guide is only for  [Yclas Self-hosted](https://yclas.com/)!_


  From the many support tickets I have covered and issues that were reported by our users I noticed that having automatic backups is of huge importance as we have mentioned before, doing a backup before any update can save you LOTS of time!

We have a guide on [how to do backups](Technical-backup-site), but it’s a tiring manual process...

Not pleasant to deal with and the best scenario is that you don’t forget to do the backup or pray that all will work fine while restoring it…

In my  [personal time an script](http://garridodiaz.com/ftp-backup-for-mysql-and-files/)  I have automated this process, but that requires an external FTP to upload backups, good enough, but remember every few and then to download the backup, and lastly, but really important, to verify the backup!

Since now 1 month ago I am using  [CodeGuard](https://mbsy.co/CodeGuard/17761100)  to backup  [Yclas](https://yclas.com/)  servers from any problem may happen.

**Things I love so far**

-   Was really easy to setup
-   They do a daily backup
-   Notification every time there’s a modification on the files (get an email)
-   MySQL backups for 1 DB
-   Restore your website from any point. WOW!
-   Great support

**Whats' not that great**

-   If your website is huge will be a bit expensive, but if it’s huge you are making money right?
-   You need to pay by card and in USD, with paypal a bit more complex
-   $5 for each extra site

Luckily I have not tried the restore option, but looks awesome!

My recommendation is to take the  [ninja plan for $5 month](https://mbsy.co/CodeGuard/17761100)  and exclude the “media” files such as images or css from the backup if you already do monthly backups.  You get 5GB, use it wisely!

![](https://raw.githubusercontent.com/yclas/guides/master/images/hosting.png)
