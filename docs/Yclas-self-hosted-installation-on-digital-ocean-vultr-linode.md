## How to install Yclas Self-hosted on Digital Ocean, VULTR or Linode


***Introduction***

Let’s start by creating the image / installing server

In this guide we will teach you how to install Yclas Self Hosted in a VPS. We will be covering, [Digital Ocean](https://www.digitalocean.com/?refcode=ebff5f6941b0), [VULTR](https://www.vultr.com/?ref=6814237) and [Linode](https://www.linode.com/). Here are some requirements that you have to cover before proceeding:

***Requirements***

 - Apache 2+



-   PHP 5.6+

-   Short Tags

-   GD support

-   mod_rewrite

-   mcrypt

-   Gettext

-   Curl

-   MySQL 5+

    *We provide guides for you in every step of the way!*

# Guides

For [Digital Ocean](https://www.digitalocean.com/?refcode=ebff5f6941b0)

-   Ubuntu 14.04 Droplet.
    
-   Create a non-root user with sudo privileges. You can follow steps 1-4 in the [Initial Server Setup with Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-14-04/) guide.
    

For [VULTR](https://www.vultr.com/?ref=6814237)

Follow  [this guide](https://www.vultr.com/docs/how-to-install-apache-mysql-and-php-on-ubuntu) to install LAMP.

[Linode](https://www.linode.com/)

Follow [this guide](https://www.linode.com/docs/websites/lamp/lamp-server-on-ubuntu-12-04-precise-pangolin) to install LAMP.

[RoseHosting.com](https://www.rosehosting.com/)

Follow  [this guide](https://www.rosehosting.com/blog/how-to-install-open-classifieds-on-a-debian-8-vps/) to install it on Debian or contact their support team and they will install it for free.

# Creating your user Database

In order to install Yclas Self-Hosted, you will need a Database and a Username.

Log in to MySQL with the root account. That’s how it will look:

> mysql -u root -p

The system will prompt you for a password. You can use your MySQL root as a password.

Now, create a database that you’ll use with Yclas. We will call it yclas in the following example.

> CREATE DATABASE yclas;

Next, create a database user and assign a password. You can replace the username ycuser and the password with your own password.

> CREATE USER ycuser@localhost IDENTIFIED BY '_password_';

Next, grant permission to access the database.

> GRANT ALL PRIVILEGES ON yclas.* TO ycuser@localhost;

Now set the new user and then reload the privileges.

> FLUSH PRIVILEGES;

Exit MySQL

> exit


## Install Yclas Self-hosted

-   Download  **[install-yclas.php](https://raw.githubusercontent.com/yclas/yclas/master/install-yclas.php)**.
-   Upload it to Apache’s document root.
-   Run  **http://yourdomain.com/install-yclas.php**.
-   Press  **Download and Install**.
-   Follow the steps.
-   Log in to your  **Admin Panel**, create some  **Categories**  and  **Locations**.
