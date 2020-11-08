# How to develop on local

Content:
-   Requirements
-   Vhost
-   Install Yclas Self Hosted and use your premium theme


If you want to develop your theme on local, you can do it by using reoc.lo as a hostname. By doing that, you will not be required an extra license to develop your theme locally.

*This guide provides the information that you need in order to do this*

## Requirements

First, you have to check the requirements for running Yclas Self Hosted:

-   A computer that has a working internet connection
-   An internet browser
-   A web hosting that supports:
    -   Apache 2+
    -   PHP 7.4+
    -   Short Tags
    -   GD support
    -   mod_rewrite
    -   Gettext
    -   Curl
    -   MySQL 5+

## Vhost

Secondly, create a vhost called ‘reoc.lo’; this will enable debug/profiler tools, disable cache and disable minify.

To create this vhost open the /etc/hosts file with a text editor:

```
sudo vim /etc/hosts

```

and add this line below:  _127.0.0.1 localhost_:

```
127.0.0.1   reoc.lo

```

Next, a file called reoc.lo.conf into /etc/apache2/sites-available/:

```
sudo vim /etc/apache2/sites-available/reoc.lo.conf

```

You can use the following:

```
<VirtualHost *:80>
    ServerAdmin webmaster@localhost
    ServerName reoc.lo
    ServerAlias www.reoc.lo
    DocumentRoot /var/www/yclas
    <Directory "/var/www/yclas">
        AllowOverride All
    </Directory>

    ErrorLog ${APACHE_LOG_DIR}/error.log
    CustomLog ${APACHE_LOG_DIR}/access.log combined
</VirtualHost>

```

Save it and enable the site:

```
sudo a2ensite reoc.lo
sudo service apache2 reload

```

## Install Yclas Self Hosted and use your premium theme

Now you have reoc.lo activated! The last step is to install Yclas Self-hosted following  [this guide](Yclas-self-hosted-installation-insatallation.md).  
Note that if you used the above reoc.lo.conf file, you have to install Yclas Self-hosted into /var/www/yclas.

To use your premium theme, go to your **Admin Panel** -> **Appearance** -> **Theme**, choose to activate your theme and enter a valid or invalid license number.

You can now develop your theme on local.

  
**Related guides:**

* [Vagrant configuration for Yclas Self-hosted](Development-vagrant-configuration.md)
* [Docker configuration for Yclas Self-hosted](Development-docker-configuration.md)

