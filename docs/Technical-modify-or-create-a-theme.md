
# How to modify or create a Theme?

Content:
-   [I bought a Kamaleon premium theme and I want to modify it.]

*This guide is only for Yclas Self-hosted!*

 *This is the second part of our guide on  [Understanding Yclas Themes](Technical-understanding-yclas-themes.md).* 
 
For the sake of understanding this guide better, I will go through the steps one by one.

### I bought a Kamaleon premium theme and I want to modify it.

This is quite normal, and I guess you  **don’t want to lose your changes**  every time we release a new version.

**So what you need to do is:**

1.  Copy your theme folder ex: /themes/kamaleon/ to /themes/mysite/
2.  Open the file /themes/mysite/init.php
3.  Search in this file for * Theme Name: Kamaleon
4.  Change the name and save the file
5.  Go to  **Panel**  >  **Appearance**  >  **Themes**
6.  There you will see your new theme with the name you gave to it
7.  Click  **Activate**
8.  **Disable CDN**  just in case you want to modify any CSS or JS

Once you do all that, you have your own custom theme and you can modify any file you want.

Finally, just a quick reminder:

-   /themes/THEMENAME/views/ contains the php files with most of the HTML
-   Not all the views are in all the themes, if one is not present in your theme you can copy it from /themes/default/views/
-   /themes/THEMENAME/css/ and /themes/THEMENAME/js/ contains the CSS/JS styles of the site.

We hope that you find this information useful!

Kind regards,
Yclas team
