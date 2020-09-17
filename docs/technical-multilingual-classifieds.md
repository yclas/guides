# How to have a Multilingual Classifieds

Yclas Self-hosted allows you to have more than 1 language active at the same time.

This means that you can  **easily change the site translation**  to any language you have in the site. Then simply add links in your sidebar or header using our widgets or the menu generator to link languages.

## Languages Widget

The languages widget let users choose in which language your website will be translated to them. To create this widget, login to your **Admin Panel** ->  **Appearance**  ->  **Widgets**  and click to create the **Languages Widget**.

After that, a list with your selected languages will appear in your website so users can choose their prefered language. For more information about it, check out  [this guide](http://docs.yclas.com/languages-widget/).

## Different languages - the same installation

This is an an example of our demo in different languages:  [English](http://demo.yclas.com/?language=en_EN), [Bengali](http://demo.yclas.com/?language=bn_BD), [Catalan](http://demo.yclas.com/?language=ca_ES). This has some benefits and some negative things too.

**Pros**:

-   Easy to activate.
-   Share the same users and ads database.
-   The same domain.
-   The same theme license.

**Cons:**

-   Ads don’t have language attribute, this means you can not filter by language.
-   Categories and locations are not by language either, so once you write a category name it would be the same for all languages.

**I don’t like this option at all**. As a better alternatives and also better for SEO, we recommend the  **3 other options**. How to configure:

1.  Go to http://yourdomain.com/oc-panel/config/update/allow_query_language.
2.  Set Config Value to 1.
3.  Save.
4.  Now to link to a language simply : http://domain.com/?language=ca_ES.

  

## Domain per language

This is probably the best option, imagine you have: MyDomain.com, and you want to add *Spanish* and *Italian* translations, you will buy the domains MyDomain.es and MyDomain.it and you will have the separate sites per language. It’s more expensive, but it allows you to use a local name in the domain name and for google to crawl it better.

**Pros**:

-   Better SEO per domain language, THIS MAKES A HUGE difference.
-   You can use the same design.
-   Users are not confused nor lost between languages.
-   If you want, you can add a localized server for the domain extension, so the domain is in the language of the country.

**Cons:**

-   You need a license for each domain for your premium theme.
-   You need different domain names (money expenses).
-   Separate administration of the site, software updates and moderation.
-   Probably more expenses on hosting.


*This guide is only for Yclas Self-hosted*
