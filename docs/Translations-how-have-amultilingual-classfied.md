# How to have a Multilingual Classifieds

This means that you can  **easily change the site translation**  to any language you have in the site. Then simply add links in your sidebar or header using our widgets or the menu generator to link languages.

## Languages Widget

The languages widget let users choose in which language your website will be translated to them. To create this widget, login to your **Admin Panel** -> **Appearance**  ->  **Widgets**  and click to create the Languages Widget.

After that, a list with your selected languages will appear in your website so users can choose their prefered language. For more information, check out  [this guide](Widget-language-widget.md).

## Different languages - the same installation


**Pros**:

-   Easy to activate.
-   Share the same users and ads database.
-   The same domain.
-   The same theme license.

**Cons:**

-   Ads don’t have language attribute, this means you can not filter by language.
-   Categories and locations are not filter by language either, so once you write a category name it would be the same for all languages.

**I don’t like this option at all**. As a better alternatives and also better for SEO, we recommend the  **3 other options**.
How to configure:

1.  Go to http://yourdomain.com/oc-panel/config/update/allow_query_language.
2.  Set Config Value to 1.
3.  Click Save.
4.  Now to link to a language simply : http://domain.com/?language=ca_ES.

  

## Domain per language

This is probably the best option, imagine you have: MyDomain.com, and you want to add Spanish and Italian translations for your content, you will buy the domains MyDomain.es and MyDomain.it and you will have the separate sites per language. It’s more expensive, but it allows you to use a local name in the domain name and for google to crawl it better.

**Pros**:

-   Better SEO per domain language, MAKES A HUGE difference.
-   You can use the same design.
-   Users are not confused or lost between languages.
-   If you want, you can add a localized server for the domain extension, so the domain is in the language of the country.

**Cons:**

-   You need a license for each domain for your premium theme.
-   You need different domain names (that cost money).
-   Separate administration of the site, software updates and moderation.
-   Maybe more expenses on hosting.

  

## Sub-Domain per language

If you don’t want to have many domains and you want to save some money then this would be the better option. Imagine you have: MyDomain.com, and you also want to add Spanish and Italian translations, you will create sub domains like es.MyDomain.com and it.MyDomain.com and you will have separate sites per language.

**Pros**:

-   It’s better SEO per domain language.
-   You can use the same design.
-   The user will not be confused nor lost between the two different languages.
-   Same domain / hosting.
-   If you want, you can add a localized server for the sub-domain, so the sub-domain is in the language of the country.
-   1 license works on as many subdomains as you want.

**Cons:**

-   Separate administration of the site, software updates and moderation

  

## Folder per language

If you don’t want to have many domains/sub domain and save some money maybe this is the option for you. I don’t prefer this option, but it will work better than the first one. Example: you have MyDomain.com, and you also want to add an Spanish and an Italian translations, you will create folders like MyDomain.com/es and MyDomain.com/it and you will have different OC installations per language.

**Pros**:

-   You can use the same design, theme and license.
-   The same domain / hosting.
-   The same license.

**Cons:**

-   Separate administration of the site, software updates and moderation.

**How to configure:**

-   You simply do a  [new installation](Yclas-self-hosted-installation-insatallation.md) in a new folder within your website, follow the screenshot below to see how to do it using Softaculous.
![](https://raw.githubusercontent.com/yclas/guides/master/images/multilingual.png)
  
  *This guide is applicable only for Yclas Self-hosted*

