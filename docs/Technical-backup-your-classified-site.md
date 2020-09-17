# How to backup your classified site?
Content:
-   Manual Backup
    -   1. Files
    -   2. Database
-   Restoring Backup
      - 1. Restoring Files
      - 2. Restoring Database
-   cPanel Backups
-   Plesk Backups


 **UPDATE:  [Automatic daily backups](Technical-automatic-daily-backup.md)


**This is a bit advanced “How To”**

Normally, your hosting has their own backup tools. But if your hosting doesn’t have those or you just want to create your own backup for your website built with Yclas, follow this guide:

  

**How to Backup a Classifieds Site:**

We need to backup 2 different things:

-   **Files**, like your images, theme, etc.
-   **Database**, where the actual data is stored, like ads, users, categories, etc.

## Manual Backup

### 1. Files

Access your FTP or file manager or the tool your hosting provides and go to your site root. In many cases it is like a public_html or www.

Depending on the tool, you need to select all the files and compress them, or if it’s via FTP download them to your computer and compress them.

You don’t need to download everything. These are the unique files for your installation that you will need later for restoring:

-   robots.txt
-   .htaccess
-   images/
-   oc/config/auth.php
-   oc/config/database.php
-   And /themes if you customized your themes

**NEVER LOSE THESE FILES.**

### 2. Database

This is probably the most important part of the process: always have backups of your DB.

**Using phpmyadmin:**

-   Login to your phpmyadmin from your hosting panel.
-   Select the database where Yclas is installed.
-   Go to export
-   Export method Custom
-   Select all the tables (normally they start with oc3_)
-   Compression zip
-   Go to the bottom of the page, click Go.

**Manually:**

In the console of your hosting, replace your values with:

```
mysql -u USER -pPASSWORD DATABASENAME > file_name.sql 

```

## Restoring Backup

It really depends on the way you have backed up your data. If it was done in the panel of you hosting, check with them on how to restore it.

NOTE: Be sure you have a functional backup before restoring.

### 1. Restoring Files

Unless there is an easier way at your hosting then I recommend the next to restore files:

-   Delete all the files except fir the the /images/ folder
-   Download [install-yclas.php](https://raw.githubusercontent.com/yclas/yclas/master/install-yclas.php)
-   Upload and execute at your browser: yourdomain/install-yclas.php
-   Download it and you will get redirected to the isntallation process but do not install
-   Delete from the downloaded files from the folder /install/
-   Replace them from your backup to the site of these files
    -   robots.txt
    -   .htaccess
    -   oc/config/auth.php
    -   oc/config/database.php
    -   And if you have any custom theme

### 2. Restoring Database

**Using phpmyadmin:**

-   Login to your phpmyadmin from your hosting panel.
-   Select the database where Yclas is installed.
-   If theres data select all the tables and delete them, since the data will be wrong if you are restoring…
-   Go to import
-   Select your zipped file

**Manually:**

In the console of your hosting, replace everything and use your values:

```
mysql -u USER -pPASSWORD DATABASENAME < file_name.sql 

```

## cPanel Backups

[![How to backup your website in cPanel](https://img.youtube.com/vi/Xxvn5D7QTFc/0.jpg)](https://www.youtube.com/watch?v=Xxvn5D7QTFc)

  

## Plesk Backups

[![How Do I Backup my Website Using Plesk Control Panel?](https://img.youtube.com/vi/2FKQY1Lmyuk/0.jpg)](https://www.youtube.com/watch?v=2FKQY1Lmyuk)

This guide is only for Yclas Self-hosted.
