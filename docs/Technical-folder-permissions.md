# How to change folder permissions

*This guide is only for Yclas Self-hosted!*

Yclas Self Hosted requires some folders to be writable.

This is useful if you are getting an error of folder not writable. It works too in case you can’t upload pictures, or cache corrupted, etc.

Please, make sure that at least these folders have correct permissions and ownership:

-   /oc/cache
-   /oc/logs
-   /images

Example on how to do it:

```
sudo chmod -R 755 /var/www/yclas/oc/cache
sudo chown -R www-data:www-data  /var/www/yclas/oc/cache

```

We recommend giving permissions and correct ownership to the entire folder 755 

Clean your cache if there’s an error:

```
sudo rm -f /var/www/yclas/oc/cache
```
