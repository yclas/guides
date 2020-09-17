# How to redirect www to non www


Users have asked us many times this question - *'How to redirect my website from **www** to **non www.** ? '*

 In order to redirect all of the requests for  _www.example.com_  to  _example.com_  you should set the appropriate **rewrite rule.**

## Should I use WWW. for my site?

**Short answer:**  Only if you want to. It's not obligatory.

Since the beginning of the Internet we've always had websites with the famous WWW. in front of all the domain names.

`Ex: www.yclas.com`

That’s something some companies still use, but almost none of the new websites are using the WWW.

**What should I do?**  Redirect all the request from www.yclas.com to yclas.com, it's that’s easy. You can do this from almost all the hosting panels in a simple and timely manner.

**Why not the WWW?**  The WWW. is actually another subdomain in your server and your clients need to type the WWW to enter your site. So always have a redirect, just in case, they don’t type it.

**What happens if I am using the WWW?**  Really it doesn’t matter what you do, just stick to the domain you choose to avoid future problems and remember to have the correct redirects.

**A bit of more info about WWW.**

World Wide Web:  
n. Abbr. WWW

1) The complete set of documents residing on all Internet servers that use the HTTP protocol, accessible to users via a simple point-and-click system.

2) n : a collection of internet sites that offer text and graphics and sound and animation resources through the hypertext transfer protocol.

## How to do it

You can do this by adding the following lines on the top of your .htaccesss file:

```
RewriteEngine On
RewriteBase /
RewriteCond %{HTTP_HOST} ^www.(.)$ [NC]
RewriteRule ^(.)$ http://%1/$1 [R=301,L]

```

Save your changes and check your site. Try different www and non-www combinations of your domain to see if the redirect is working as expected.


*This guide is only for Yclas Self-hosted*
