

# > General Settings ⚙️
Dear Yclas user, 

In this section, you'll find all of the general settings configuration that you have in your Yclas website. You can learn how to maintain your website with easy by following just a few simple steps. 
Good luck! [  ](https://emojipedia.org/four-leaf-clover/)🍀
**

## Content

 - Maintenance Mode
 - Bots & Crawlers
 - Change your site name and description
 - Ads moderation
 - Cookie consent 
 - Landing Page
 - Activate Access Terms Alert 
 - Add text in Contacts page 
 - Allowed Email domains
 - Private site 
 - Add tracking codes 
 - Avoid spam on your site 
 - HTML in headelement 
 - HTML in footer 
 - Currency format 
 - Change date format 
 - Change time zone 
 - Two step SMS authentication 
 - Two step Authentication
 - Set up reCaptcha
 - Notification System
 - Algolia Search
 - Multilingual Mode
 
## Maintenance Mode

**If you'd like to activate Maintenance Mode you have to follow these steps:**

1.  Go to  **Admin Panel**
2.  Select  **Settings**  ->  **General**
3.  Set  **Maintenance Mode**  option to  **ON**
4.  Click  **Save**  button

While Maintenance Mode is being activated, anyone who tries to access your website will see following page:  

> **Only administrator can access**

  They'll be able to see the whole website only by logging in.
![maintenance-mode](https://user-images.githubusercontent.com/55290441/80502873-d244e500-8979-11ea-8d54-f009e83a23b3.png)

Setting moderation: Allows you to change how to publish ads. You can read more [here](api-documentation.md) 

# Bots & Crawlers


## **What is web bot 🤖?**

A web bot is a computer program that systematically browses websites and creates indexes for them, by tracking the keywords entered on the internet. 

These bots can have a difference purpose but they operate more or less in the same manner.  [Yclas](http://yclas.com/)  allows you to prevent those bots from accessing your classifieds website or give them back their access with a single switch.

The process of collecting information from online web documents helps to reveal a website’s structure and purpose. 

Therefore, the web bots/crawlers return these results to their respective search engines whenever the keywords match the search – for example, Bing, Google or Yahoo.

## Why would I want to block the bots?

There are many reasons why webmasters and developers might want to block robots from indexing on their sites, and these include (but are not limited to):

-   The fact that, not all bots are good – some are bad and can crash your system.
-   The fact that, granting bots access can generally leave a site exposed and vulnerable.
-   Privacy, copyrights and legal issues.

However, allowing bots/crawlers to navigate your website has its advantages; particularly with regards to a great SEO (Search Engine Optimization) campaign. 

So you shouldn’t block all bots because some are ‘good’ 😇 !

## How to allow/disallow Bots and Crawlers:
Let's learn how to allow/disallow these 🤖
 Follow the steps **successively**.
1.  Go to your  **website**.
2.  Login to the  **Admin Panel**.
3.  Select  **Settings -> General**.
4.  Toggle the  **Disallows (blocks) Bots and Crawlers on this website**  option ON (to  **disallow**  the bots)  
    _OR_  
    Toggle the  **Disallows (blocks) Bots and Crawlers on this website**  option OFF (to  **allow**  the bots).
    
5.  Click the  **Save**  button.

✔ **The change is successful – general configuration updated.**

Now go to your Admin Panel and continue customizing your classifieds website so that it truly serves its purpose.  

# How to Change your Site's Name and Description
![how-to-change-site-name-description](https://user-images.githubusercontent.com/55290441/80503187-32d42200-897a-11ea-8a25-fab6a2eca882.png) 

When you  [create a classifieds website with Yclas](http://yclas.com/)  you can change your site's name and description very easily.

Both terms are pretty straight forward and self-explanatory. 

The site name carries the identity of your whole website and it is complimented by the description, which details your website’s purpose. 

**Whenever you are editing these fields, make sure to:**

-   Check that the site name is the correct title of your website – this will be publicly displayed online.
-   Check that your description matches your website’s content and purpose.
-   Take care and avoid grammatical errors, misleading/irrelevant input, plagiarism, etc.
-   Keep the length of the description field under the max (indicated by the tool tip – 160 characters).
-   Add a few keywords in the description – this could affect your SEO (Search Engine Optimization) analytics.

### How to change them step-by-step:

1.  Go to your  **website**.
2.  Login to the  **Admin Panel**.
3.  Select  **Settings -> General**.
4.  Enter the site name into the input box labeled  **Site name**.
5.  Enter the description into the input box labeled  **Site description**.
6.  Click the  **Save**  button.

✔ **The change is successful – general configuration updated.**

Although the site's name and description are important elements in your website content, remember that you can always **add more content** to your site with the following tools  🛠️:

-   [Text widget](https://docs.yclas.com/overview-of-widgets)
-   [Creating a blog](https://docs.yclas.com/how-to-create-a-blog)
-   [Add an FAQ section](https://docs.yclas.com/create-frequent-asked-questions-faq)
-   [Add a forums section](https://docs.yclas.com/add-forums-section/)

We recommend using these tools but there's plenty of fish in the sea! :)

# Ads Moderation

## Ways to publish an ad

Ads moderation is a very important feature when you want to control the amount of ads, their content or to manually avoid spammers. 
There are a few ways to moderte your ads and we are going to go through all of them:

 - Post Directly
 - Moderation On
 - Paymenet On
 - Email Confirmation On
 - Email Confirmation with Moderation On
 - Payment with Moderation

 
To configure Ads aoderation you need to go to your **Admin panel -> Settings -> General -> Moderation**

### Post directly

Post directly is a way to allow users to post new advertisements without any validation later. This means that the administrator of the page will not have obligation to activate incoming ads.

_EMAIL:_ After a user has created an advertisement, an email is sent to him. This email contains two links: one is to redirect him to his newly created ad; while the second one is to report if there’s an issue with his account.

### Moderation on

This option introduces limitation on publishing. Every new advertisement created is sent to moderation to be activated manually by administrator. This advertisement will be published with a date of activation. Until then it can be found in admin panel under moderation.

_EMAIL:_ One email is sent to user, notifying him of creation. But, in this case, he has a link that redirects him to advertisement edit. He can modify this ad, but it won’t be published until the admin activates it.

### Payment on

When the payment is active, the user is redirected to a payment gateway. But not every case. This happens only in cases in which the user have set fixed an amount of money that’s considered to be valid. Other ones are dealt like a case of “Post directly”. Example: the category “Rent a cat” have fixedan amount of 10 USD. After a user has set all the necessary fields and have clicked on button to post, he will be redirected to “Paypal”. Than he makes payment and, after this payment has been validated by “Paypal” and our back-office, his advertisement is published with the current date and time. But if the category “Rent a car” doesn’t have an amount (amount of money = 0 ), the user’s advertisement will get published with a current date and time and set on top of the list.

_EMAIL:_ One email is sent, that confirms that this advertisement is now active. Same as in “Post directly”.

### Email confirmation on

This advertisement is set to “UNCONFIRMED”. With this option every advertisement needs to be confirmed by the USER. It’s a standard way of confirming by email. The user receives an email, clicks on link that is provided and then this advertisement is validated and published. It will stay in moderation until then.

_EMAIL:_ An email is sent to the user with a link that will activate his new advertisement. NOTE: In case that this user has created advertisement while he was logged-out, after clicking the link, he will be signed up automatically.

### Email confirmation with moderation

This advertisement is set to “UNCONFIRMED”. Here, the user needs to do the email activation and then the ad is sent to moderation to be validated by the admin. This advertisement will be published with a date of activation. Until then, it can be found in admin panel under moderation.

_EMAIL:_ One email is sent to the user with a link that will activate his new advertisement and then it will be placed in moderation until the admin activates it.

### Payment with Moderation

As in the case of “payment on”, the user is redirected to payment gateway only if the product has a fixed amount. Besides, this advertisement is also processed as a “Moderation on” case. In other words, if the payment is successful, the advertisement will be sent to moderation to be once again activated by the admin. But if the posting poroess wasn’t handled with a payment, this advertisement will be set in moderation and will be waiting for the admin to activate it.

_EMAIL:_ One email is sent to user notifying him of the creation of a new ad. But, in this case, he has a link that redirects him to advertisement to edit it. He can modify this ad, but it won’t be published until the admin activates it.


# Cookie consent 🍪

1. Why to use it
2. How to use it

Let's start with **why you need a cookie consent** on your website.
Cookie consent alert is something that you have seen many times at the top or the bottom of websites. 
The reason that you should use it it’s because, since 2011, every website that is based in the EU should display that alert to let users know if they are using cookies.

## How to use it

With Yclas, we give you the option to enable the Cookie Consent alert. It will be displayed once for each visitor to let them know that your site uses cookies. 
You can acitvate it in a few simple steps:
1.  Go to  **Settings**  ->  **General**
2.  Find and enable  **Cookie Consent**
3.  Press  **Save**

# Landing page

How to change your website's landing page. You can add "Home", "Listings" or "Users" as a first page that your users will visit after typing your address. 

*New function included in **2.0.6** version makes it possible to choose what will be displayed in your **landing page** - first site that will be visible for your visitors after typing your address.

The **Home**  page (with slider and selection of categories),  **Listing**  page (with newest ads from all categories) or browse  **Users**  profile are all available in a few simple steps:

1.  Go to  **admin panel**
2.  Choose  **settings > general**
3.  In the second field select  **Home**,  **Listing**  or  **Users**
4.  Click  **save**
5.  That's it!
![landing-page](https://user-images.githubusercontent.com/55290441/80503424-80e92580-897a-11ea-9739-dd4eb60fc951.png) 


# Activate access terms alert
* [If you need to generate your terms of service or privacy policy click here.](https://www.shareasale.com/r.cfm?b=854385&u=1782794&m=65338)

This feature creates window of  **Access Terms**  to allow or deny user’s access to webpage. Unless the admin approves it, access to website is denied and the user will be redirected outside of the website.

1. To activate this feature go to  **Admin Panel**, and create new page. 
2. By clicking on  **Content**  >  **Page**  option, then a blue button  **New**. 
![activate-time-alerat1](https://user-images.githubusercontent.com/55290441/80504580-f6092a80-897b-11ea-9ca6-4e197a5e16aa.png)

3. After you created new page, go to  **Settings > General**, and find the option  **Accept Terms Alert**. Then in one of the following options should be your new page. Select it, and click on  **Save**  button.

![access-terms2](https://user-images.githubusercontent.com/55290441/80504585-f9041b00-897b-11ea-9bdc-b6a2f142d066.png)

5. That’s it, you activated the  **Access Terms Alert**. Now refresh your home page and you'll see it displayed like this:
![accept_alert_settings_3](https://user-images.githubusercontent.com/55290441/80504595-fdc8cf00-897b-11ea-8c5f-3d3fd5a1e844.png)

Once it’s accepted, terms won't appear again unless you  **clean your cookies**.

# How to add text in contact page

**This feature is available on our 2.5.0 release.*

Instead of having a plain contact form on your website’s contact page, now you can choose your own welcome message to be displayed above contact form!

To do this, just  **follow these simple steps:**

-   **Create a new Page**. In the  _description_  field, add the content you want to display on the contact page. If you don’t know how to create a new page, check our documentation on "How to add new pages".
-   On  **Settings**  ->  **General**,  **Contact page content**, choose this page.
![contact-page](https://user-images.githubusercontent.com/55290441/80504885-48e2e200-897c-11ea-8d37-e04c4009b6fb.png)
- **Save** the changes, and you are ready!

![contact-page2](https://user-images.githubusercontent.com/55290441/80504895-4bddd280-897c-11ea-913f-e74137046803.png)

# Allowed email domains


This feature gives you the option to allow the registration of users that use a **specific domain** for their email address. 
For example, you can allow the registration of students using their university email address or users using an email address of an organization or company.

To enable this feature you need to go to  **Settings**  ->  **General**  and there you need to write your email domains. 
*Keep in mind that you need to push enter after each email domain name so that it's saved.

If you want to allow **all the email domains** to be able to register on your site, just leave the field empty.

![allowed-email-domains](https://user-images.githubusercontent.com/55290441/80505012-76c82680-897c-11ea-9880-5e0d56d96f74.png)


# Private Site
*This feature is available with our 2.8.0 release and for all of the sites hosted with Yclas.com

The “Private site” option could be useful in cases you want to share your website with only a few people. 
If you enable this option, then only registered users can access your website and only the administrator of the website can register new users!

Follow the steps above to make your site private:

1.  **Login**  to your panel
2.  Go to  **Settings**  ->  **General**.
3.  **Enable Private Site**.
4.  Click  **Save**.

Now, if you logout, and try to visit your site,  a message will pop out stating that this website is private and you need to log in in order to see its content. This is what should be displayed:
![private-site1](https://user-images.githubusercontent.com/55290441/80505243-bee74900-897c-11ea-9076-d7175e7deec0.png)

-   Registered users can login using the login form on the bottom of the page.
    
-   Unregister users can request access to your site by clicking  **Request Access**  and filling the form with their Name and Email. An email with this information will be sent to the administrator in order to use it and create a new user (**Panel -> Users -> Users -> New**).

![private-site2](https://user-images.githubusercontent.com/55290441/80505265-c3abfd00-897c-11ea-828c-809ee2382524.png)

The content of the page that is displayed to unregistered users is editable. 
*You can **create a new page** through your panel. Go to **Settings -> General**, choose this page on **Private Site landing page content** and click **Save**

![private-site3](https://user-images.githubusercontent.com/55290441/80505273-c60e5700-897c-11ea-8b8a-ec1a299878bf.png)


# How to add tracking codes

-   Why you should use Google Analytics
-   Adding the Analytics Tracking ID
    -   Quick method
    -   Manual method

## Why you should use Google Analytics

It’s useful to use  [Google Analytics](https://www.google.com/analytics/)  (GA) on your website for several reasons.

First of all, GA is the best because it’s free and it’s giving you much more data (who and when visits your site, etc) than any other free analytics software.

Secondly, GA makes it easy for anyone managing a site to track and analyze these data. Its custom reports allow you to see your data the way you need to see it, whenever you need it.

Lastly, everybody trusts Google Analytics data. Currently it’s in the use of around 55% of the 10,000 most popular websites and 49.95% of the top 1,000,000 websites.

## Adding the Analytics Tracking ID

### Quick method

1.  Go to  **Panel**, choose  **Settings > General**  on the left sidebar.
2.  Add your **Google Analytics Tracking ID** into the **Analytics Tracking ID field.**
3.  Press **SAVE**.

![google-analytics1](https://user-images.githubusercontent.com/55290441/80505525-1c7b9580-897d-11ea-9610-0d335fa2406d.png)


You can change the content of the Analytics Tracking ID field whenever you want by following the same process.

### Manual method

This will work if you need to add any other tracking code, but if you have a code from your provider just use this method.

1.  Go to  **Panel**,choose  **Settings**  >  **General**  on the left sidebar.
2.  Paste your tracking code into the **HTML in HEAD element field** or into the **HTML in footer field**.
3.  Press **SAVE**

![google-analytics2](https://user-images.githubusercontent.com/55290441/80505540-200f1c80-897d-11ea-8f1e-7dd8981df1a5.png)
![google-analytics3](https://user-images.githubusercontent.com/55290441/80505548-22717680-897d-11ea-9cde-e6e5a01622b8.png)


## How to avoid spam in my site

Are you tired of getting all types of spam on your website? We have the solution you're seeking! Read on  ⬇️

-   Moderate Ads
-   Black List
-   Akismet
-   Captcha
![hate-spam](https://user-images.githubusercontent.com/55290441/80505840-8b58ee80-897d-11ea-9daa-788967714fa1.png)

**$ Spammers Wanted - Disconnected and Alive $**

Do you own a classifieds site and you are tired of getting ads like..

-   African Witches Spell Caster, Magic Healer
-   Best Love Spell Caster, Black Magic Spells
-   World class traditional healer, witchcraft charms and spells
-   Work while studying
![spammers-wanted2](https://user-images.githubusercontent.com/55290441/80505887-990e7400-897d-11ea-961b-b1ed273bd5a8.png)

And lot of other annoying stuff….

Spam is a serious issue, that’s why at Yclas we have developed a set of tools to help/prevent getting these ads and making your site look unprofessional.

## WE HAVE THE SOLUTION!

### Moderate Ads

The best option is to moderate the ads. With this, you make sure you don’t get spam or duplicated ads.

Go to the control panel and navigate to  **Settings > General**  > General site Settings. Set the Moderation option in “Moderation On”

![spammers3](https://user-images.githubusercontent.com/55290441/80505896-9ad83780-897d-11ea-99c4-bb46ae588e19.png)

**Black List**

Next step is to activate the “Black List”. There's a guide on how to do that in our documentation.



**Akismet**


You can also activate Akismet entering your Akismet key

![spammers4](https://user-images.githubusercontent.com/55290441/80505903-9dd32800-897d-11ea-9d32-9b9fe9f3ce63.png)

  
You can find more information about Akismet and how obtain an Akismet key following this link:  [https://akismet.com/](https://akismet.com/)  It’s free to use but be aware of false positives.

### Captcha

Now move to  **Settings > Advertisement > Publish Options**  set Captcha “ON”

![spammers3 5](https://user-images.githubusercontent.com/55290441/80505919-a0ce1880-897d-11ea-9909-2c8122e8b1fc.png)

No more spam!

# HTML in HEAD element

Head element is the place where most of the instructions for the browser are located and where you can store meta information about the document.

Yclas allows you to add HTML in HEAD element. You can use this feature to include your custom HTML code (validation metadata, reference to JS/CSS files, etc.) in the HEAD element of the rendered page. Also, you can use it to add a banner on the top of your website.

**Follow these steps to include your custom code in HEAD element:**

1.  **Login**  to your  **Panel**.
2.  Go on  **Settings**  ->  **General**.
3.  On General Configuration section, find the field  **HTML in HEAD element**  and insert your HTML code there.
4.  Click  **SAVE**  at the bottom of the page

![html-head](https://user-images.githubusercontent.com/55290441/80508062-3cf91f00-8980-11ea-80c0-5ae269fa9d3a.png)

# HTML in FOOTER

A footer element typically contains information about its containing element, like contact information, back to top links, copyright information, related documents, advertising banners, etc. If you are using Yclas, you can include your custom HTML code in the footer by  **following these steps**:

1.  **Login**  to your  **Panel**.
2.  Go on  **Settings**  ->  **General**.
3.  In the “General Configuration” section, find the field  **HTML in FOOTER**  and insert your HTML code there.
4.  Click  **SAVE**  at the bottom of the page.

![html-footer](https://user-images.githubusercontent.com/55290441/80508117-4d10fe80-8980-11ea-95b5-433453ae6093.png)
# How to set the currency format?

-   How to do it
-   List of currency formats


One of the most commonly asked question by our users is how to deal with the  **currency in which prices are displayed**. Apparently, it has caused a lot of problems and misunderstandings. This is why, with a new release (2.0.5), we decided to make some improvements in order to make it less confusing. 

 We use PHP function  **[money_format](https://php.net/manual/en/function.money-format.php)**  to solve all problems in a very easy way.

## How to do it

You can go to  **Settings**  >  **General**  >  **Regional**  and select your preferred currency. Once you press  **Save**, then the currency will show next to each amount.

![currency-format](https://user-images.githubusercontent.com/55290441/80508281-877a9b80-8980-11ea-80e9-d24d1bd8e83a.png)

## List of currency formats

If a currency you want to use is not listed below, feel free to contact our support team let them know!

-   **US Dollar**  
    
-   **Pound Sterling**  
    
-   **Euro**  
    
-   **Swiss Franc**  
    
-   **Japan, Yen**  
    
-   **Canadian Dollar**  
    
-   **Australian Dollar**  
    
-   **Euro in spanish format**  
    
-   **Norwegian Krone**  
    
-   **Algerian Dinar**  
    
-   **Argentine Peso**  
    
-   **Armenian Dram**  
    
-   **Aruban Guilder**  
    
-   **Bahamian Dollar**  
    
-   **Bahraini Dinar**  
    
-   **Bangladesh, Taka**  
    
-   **Belize Dollar**  
    
-   **Bermudian Dollar**  
    
-   **Bolivia, Boliviano**  
    
-   **Bosnia and Herzegovina, Convertible Marks**  
    
-   **Botswana, Pula**  
    
-   **Brazilian Real**  
    
-   **Brunei Dollar**  
    
-   **Bitcoin**  
    
-   **Cayman Islands Dollar**  
    
-   **Chilean Peso**  
    
-   **China Yuan Renminbi**  
    
-   **Colombian Peso**  
    
-   **Costa Rican Colon**  
    
-   **Croatian Kuna**  
    
-   **Cuban Convertible Peso**  
    
-   **Cuban Peso**  
    
-   **Cyprus Pound**  
    
-   **Czech Koruna**  
    
-   **XPF CFP franc**  
    
-   **Danish Krone**  
    
-   **Dominican Peso**  
    
-   **East Caribbean Dollar**  
    
-   **Egyptian Pound**  
    
-   **El Salvador Colon**  
    
-   **Ethiopean Birr**  
    
-   **Old Ghana, Cedi**  
    
-   **Ghana, Cedi**  
    
-   **Gibraltar Pound**  
    
-   **Guatemala, Quetzal**  
    
-   **Honduras, Lempira**  
    
-   **Hong Kong Dollar**  
    
-   **Hungary, Forint**  
    
-   **Iceland Krona**  
    
-   **Indian Rupee ₹**  
    
-   **Indonesia, Rupiah**  
    
-   **Iranian Rial**  
    
-   **Jamaican Dollar**  
    
-   **Jordanian Dinar**  
    
-   **Kazakhstani Tenge**  
    
-   **Kenyan Shilling**  
    
-   **Kuwaiti Dinar**  
    
-   **Latvian Lats**  
    
-   **Sri Lankan Rupee**  
    
-   **Lebanese Pound**  
    
-   **Lithuanian Litas**  
    
-   **Moroccan Dirham**  
    
-   **Macedonia, Denar**  
    
-   **Malaysian Ringgit**  
    
-   **Maltese Lira**  
    
-   **Mauritius Rupee**  
    
-   **Mexican Peso**  
    
-   **Mozambique Metical**  
    
-   **Nepalese Rupee**  
    
-   **Nigerian Naira**  
    
-   **Netherlands Antillian Guilder**  
    
-   **New Israeli Shekel ₪**  
    
-   **New Turkish Lira**  
    
-   **New Zealand Dollar**  
    
-   **Pakistan Rupee**  
    
-   **Paraguay Guarani**  
    
-   **Peru, Nuevo Sol**  
    
-   **Peso Uruguayo**  
    
-   **Philippine Peso**  
    
-   **Poland, Zloty**  
    
-   **Rial Omani**  
    
-   **Romania, New Leu**  
    
-   **Romania, Old Leu**  
    
-   **Russian Ruble**  
    
-   **Saudi Riyal**  
    
-   **Singapore Dollar**  
    
-   **Slovak Koruna**  
    
-   **Slovenia, Tolar**  
    
-   **South Africa, Rand**  
    
-   **South Korea, Won ₩**  
    
-   **Swaziland, Lilangeni**  
    
-   **Swedish Krona**  
    
-   **Tanzanian Shilling**  
    
-   **Thailand, Baht ฿**  
    
-   **Tonga, Paanga**  
    
-   **UAE Dirham**  
    
-   **Ukraine, Hryvnia**  
    
-   **Ugandan Shilling**  
    
-   **Vanuatu, Vatu**  
    
-   **Venezuela Bolivares Fuertes**  
    
-   **Venezuela, Bolivar**  
    
-   **Viet Nam, Dong ₫**  
    
-   **West African CFA Franc**  
    
-   **Zambian Kwacha**  
    
-   **Zimbabwe Dollar**  
    
-   **Default**  To use your chosen locale currency_  
    
-   **Without currency sign**  
    
-   **One decimal digit**  
    
-   **Two decimal digits**  
    
-   **Three decimal digits**  
    
-   **Four decimal digits**

# How to change date format?

**Date format**  differs from country to another and Yclas gives you the option  **to change that format according to your preferences**. This change will have an effect on all of your ads. If your website is functioning in more than one country, you will need to have different domains for each country and have separate management for each site.

**To change the date format,**  simply follow those steps:

1.  Log in to your  **Admin Panel**
2.  Go to  **Settings**  >  **General > Regional Settings**
3.  Change the field  **Date format**
4.  Press  **Update**

In case you change it to an invalid form and you want to go back to default, our default given date format is:  **d-m-y.**

If you would like to  **add hours/minutes/seconds**, you can use  **d-m-y H-i-s**. For more options about it, you can refer to  **[PHP Date/Time format](https://php.net/manual/en/function.date.php)**.

![date-format](https://user-images.githubusercontent.com/55290441/80508288-89445f00-8980-11ea-8457-e52bc8a55432.png)

# How to change Time Zone


It’s important to have your Time Zone correctly set up. For example, ads, orders, reviews, topics and replies on forum, blog posts etc, will not display the date or time you expect to if you don’t have the correct timezone set in your website.

To change the Time Zone, follow these steps:

1.  Go to Panel,  **Settings**  ->  **General**
2.  In the  _Regional Settings_  section,  **Time Zone**  field, select your city or the city with the same timezone as yours.
3.  Press  **Save**

![timezone](https://user-images.githubusercontent.com/55290441/80508298-8c3f4f80-8980-11ea-8e08-8c6f8dd55cfc.png)

# Two-step SMS authentication

-   How to enable and configure Two-step SMS Authentication:
-   Set an inital country
-   How it works:
-   Register and login with phone number
    -   Register
    -   Login


Keep your users secure with the two-step SMS authentication. Two-step authentication is a mechanism to double check that your identity is legitimate.

## How to enable and configure Two-step SMS authentication:

1.  Register at  [Clickatell](https://www.clickatell.com/)
2.  On Clickatell dasboard, choose  **SMS integrations**
3.  Click  **Activate Now**  and setup Billing Details. You can calculate the pricing  [here](https://www.clickatell.com/pricing-and-coverage/message-pricing/#step-1)
4.  Now that the integration is activated, choose SMS integrations again and copy the  **API key**
5.  In your website admin panel,  **Settings -> General**, enable  **2 Step SMS Authentication**  and paste the API key into the  **Clickatell**  field
6.  If your Clickatell integration is a two-way messaging type, paste your Two-way phone number into the  **Clickatell Phone Number**  field
7.  Press  **Save**

![2-step-sms1](https://user-images.githubusercontent.com/55290441/80508572-e0e2ca80-8980-11ea-8094-b96ef9d498e4.png)


## Set an inital country

This option will make it easier for your customers to login or register to your site. Select the country your website is targeted to. This way, the country’s code will be the default country code in the phone field in the register, login and publish a new page.

Go to  **Settings**  ->  **General**  ->  **Regional**  ->  **Country**  and select the country your website is targeted to.

## How it works:

1.  An user registers on your website or posts an ad.
2.  An user account is created and the user goes to Edit Profile page and enters his phone number.
3.  After updating the profile details, the user will get a verification code by message on his mobile phone, which he will need to enter in the next page.
4.  Now the user is authenticated and the Two-step SMS authentication is enabled on his account
![2-step-sms-2](https://user-images.githubusercontent.com/55290441/80508580-e3452480-8980-11ea-8f79-69d952754cac.png)

## Register and login with phone number

### Register:

Users can choose to register with their email and password, or to choose to register with their phone number.

1.  A user visits your site and choose to register.
2.  We send them an SMS with a code.
3.  They enter the code, if it’s valid.
4.  We ask them for name and email.
5.  User is successfully registered!

### Login:

1.  Registered user visits your site and wants to login.
2.  He/She chooses to login with a phone number and enters his/her number.
3.  If the number is valid and a profile account with that phone number is found, we send them a code.
4.  The user enters the code.
5.  If the code is valid, the user is successfully logged in!

# Two-Step Authentication

-   How to configure two-step authentication
-   How to enable the two-step authentication on your profile
-   How to use it

**This feature is available with our 2.8.0 release and on all sites hosted at  [Yclas.com](https://yclas.com/)*

This feature gives you and your users two-factor authentication. You can protect your account with both your password and your phone.

## How to configure 2 step authentication:

1.  Login to your  **Admin Panel**.
2.  Go to  **Settings -> General**.
3.  Activate  **2 Step Authentication**.
4.  Press  **Save**

![2step1](https://user-images.githubusercontent.com/55290441/80509170-b5141480-8981-11ea-9f1e-afe8f77bd1fc.png)

## How to enable the 2 Step Authentication on your profile:

1.  **Login**  to your website.
2.  Go to  **[Edit Profile](https://docs.yclas.com/how-to-edit-your-profile/)**.
3.  If you don’t have  **Google Authenticator**  app installed on your mobile phone, you can choose  **Android**  or  **iOS**  below to get one.
4.  Run the app on your mobile phone, click  **Set up account**  from the options and  **scan the QR code**.
5.  In the “2 Step Authentication” section, scan the QR code. 

![2step-auth-enable2](https://user-images.githubusercontent.com/55290441/80509188-bb09f580-8981-11ea-8b19-79bf1fdb0490.png)

6. Once the QR code is scanned, you will see the account created with a verification code. (There’s no need to write down or memorize the verification code because it changes every 30 seconds.)
7. Now you will be redirected to enter the verification code and press “Send”. If the code is valid 2 Step Authentication will be enabled, otherwise you will have to scan QR code and enter the verification code again.
![2step3](https://user-images.githubusercontent.com/55290441/80509193-be04e600-8981-11ea-82fe-69ca403bf4bc.png)

## How to use it:

1.  Go to your website and choose to log in.
2.  Enter your  **Email**  and  **Password**  and click  **Login**.
3.  Now you will be redirected to  **enter the Verification Code**  (Run the Google Authenticator app to find the verification code.)
4.  Click  **Send**.
5.  Now you are logged into your website!
![2step4](https://user-images.githubusercontent.com/55290441/80509206-c0ffd680-8981-11ea-8717-0de4b26f5fcd.png)


# Add reCAPTCHA to your website

So you’ve registered your site with Google and now you want to see it in action, just follow these simple instructions:

1.  Go to your  **website**.
2.  Login to the  **Admin Panel**.
3.  Select  **Settings -> General -> reCaptcha**.
4.  Toggle the  **Enable reCAPTCHA as a CAPTCHA provider**  option ON.
5.  Place your website’s ‘Site Key’ in the  **reCAPTCHA Site Key**  input box. v2 of recaptcha
6.  Place your website’s ‘Secret Key’ in the  **reCAPTCHA Secret Key**  input box. v2 of recaptcha
7.  Click the  **Save**  button.

![recaptcha2](https://user-images.githubusercontent.com/55290441/80510488-75e6c300-8983-11ea-97a8-8aeadeefc435.png)


![recaptcha3](https://user-images.githubusercontent.com/55290441/80510750-d2e27900-8983-11ea-9a13-3eca197471c9.png)

✔ **The change is successful – general configuration updated.**

# Notification System

-   [How to enable the Notification System](https://docs.yclas.com/notification-system/#how-to-enable-the-notification-system)
-   [Showcase](https://docs.yclas.com/notification-system/#showcase)

By using the Notification System, you can notify your website users that an email was sent to them from your website. That email could be sent after they perform a certain action like register, post an ad, request to change their password or when they get contacted from other users.
![NS1](https://user-images.githubusercontent.com/55290441/80630267-9fbfe880-8a5c-11ea-923a-52b43f310cc8.png)


### How to enable the Notification system

1. Register on  [pusher.com](https://dashboard.pusher.com/accounts/sign_up)  
2. After the registeration, you will be asked to enter your app details as displayed below:

![NS2](https://user-images.githubusercontent.com/55290441/80630266-9f275200-8a5c-11ea-8bf7-56401f84687c.png)


**Name your app:**  Enter your website name or leave the default name.  
**Select a cluster**  
**What’s your front-end tech?:**  Select “JQuery”  
**What’s your back-end tech?:**  Select “PHP”  

You can leave the other fields empty and click  **Create your app**.

3. The next page you will see is the dashboard, select  **App keys**  on the top menu. Go to  **Settings -> General -> Notifications**, enter the App ID, Key and Secret and select the Cluster you chose when you created the app. Enable notifications and click  **Save**.

4. Now, when users are logged in and they receive emails from your website, they will get notified so they can go check their email.

### Showcase

A user contacts the admin through his profile page.

# Algolia Search

-   [Configuration](https://docs.yclas.com/algolia-search/#configuration)
-   [Re-indexing](https://docs.yclas.com/algolia-search/#re-indexing)
-   [Video](https://docs.yclas.com/algolia-search/#video)

With Algolia search you can bring instant and relevant search to your classfieds website and make content browsing more intuitive for your visitors.

## Configuration

Follow the steps below to use Algolia search in your website:

1. Create a free account on  [Algolia.com](https://www.algolia.com/)  
2. Complete the required fields on the registration page. In the “Select your region” field select Europe (France) or Europe (Germany) and press “Let’s Get Started”.  
3. The account is created and you will be directed to a tutorial. You can click “Continue” or “Skip tutorial” on the right top.  
4. Press “Go to your Dashboard” to find the required keys.  
5. Select  **API keys**  on the left sidebar.  

![algolia1](https://user-images.githubusercontent.com/55290441/80630311-aea69b00-8a5c-11ea-9b2f-b10bda82c4c4.png)

6. Copy the  **Application ID**,  **Admin API Key**  and  **Search-Only API Key**  and paste them into your website admin panel,  **Settings**  ->  **General**  ->  **Algolia Search**.

![algolia2](https://user-images.githubusercontent.com/55290441/80630301-ad756e00-8a5c-11ea-8695-7201112924e3.png)


7. Enable  **Algolia Search**  and press  **Save**.  
8. Now the search forms in your website are using Algolia search!

## Re-indexing

Yclas automatically reindex the records of your site every hour. However we have created an option in the panel so you can manually reindex the records and keep Algolia up to date with your website.

To reindex the records go to  **Extra**  ->  **Tools**  ->  **Algolia Search**.

![algolia3](https://user-images.githubusercontent.com/55290441/80630307-ae0e0480-8a5c-11ea-983d-f135970b0a6e.png)


# How to activate multilingual mode?

A new feature is included in the 3.5 version that makes it possible for you to set your website in multilingual.

**To activate multilingual mode:**

1.  Go to  **Admin Panel**
2.  Select  **Settings**  ->  **Regional**
3.  Set  **Multilingual**  option to  **ON**
4.  Set your  **website languages**  (a language must correspond to the ones listed on  **Settings**  ->  **Translations**). Keep in mind that you need to push enter after each language.
5.  Click  **Save**  button

Once enabled you will see on your website a language selector.

![multilingual-configuration1](https://user-images.githubusercontent.com/55290441/80630351-be25e400-8a5c-11ea-9372-267a8c37df1d.png)


![multilingual-2](https://user-images.githubusercontent.com/55290441/80630362-c120d480-8a5c-11ea-9d00-5901e5e25a27.png)

**Translate categories and locations:**

Once the multilingual mode is enabled you can update your categories and locations to translate their names and descriptions.
![multilingual3](https://user-images.githubusercontent.com/55290441/80630368-c41bc500-8a5c-11ea-9fd6-12bbe3c4537c.png)
