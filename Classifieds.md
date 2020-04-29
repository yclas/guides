
Guides for yclas.com
# How to manage advertisements?

As your website advertisements amount increases, it can be a challenge to manage them. This guide will explain how to manage, edit, delete filter ads and more!

To access the ads management page, go to your ** Admin Panel**, choose  **Classifieds**  and then  **Advertisements**  from the left sidebar. You will see a list of  **all advertisements**  that are published on your site. The newest are on the top. Only 10 ads will be displayed. To go to older ones, navigate among the pages of the list.

![manage-ads](https://user-images.githubusercontent.com/55290441/80600680-7049b580-8a35-11ea-9e38-cbd9f90bbea3.png)

On the list you see the  **name**,  **category,**  **location**  (where the ad was published),  **hits**,  **status**,  **published**,  **created**. What is more, you have the possibility of searching for the adequate ads by using a field:  **Search**. On the right side you have buttons representing different available actions. Just click the one that you need and confirm when the system asks if you’re sure. The following options are available:

-   **Update:**  You can update the ad details.
-   **Spam:**  Mark the ad as spam if you think that it is! The publisher of the ad will automatically be added to the **blacklist**  if it’s enabled and he will not be available to post new ads.
-   **Sold:**  If the product is not available anymore, you can mark the ad as sold. This action will make the ad inactive.
-   **Desactivate:**  Desactivate the ad without deleting it. Use this option in case you don’t need an ad to be published but you don’t want to delete it permanently.
-   **Delete:**  Simply delete an ad that you don’t need anymore to be displayed on your website. This action cannot be undone!
-   **Featured:**  Manually make an ad featured. This option appears only when  [Featured Ads](https://docs.yclas.com/how-to-create-featured-plan/)  is enabled and it redirects you to the checkout page.
-   **Go to Top:**  Manually renew the ad. This action redirects you to the checkout page.
-   **Stats:**  Display the stats of the ad.

At the top of the page, you have some tabs that let you filter or sort the ads:

![manage-ads2](https://user-images.githubusercontent.com/55290441/80600691-73dd3c80-8a35-11ea-9437-56f98ff932cf.png)

-   **All Ads:**  Display all the ads, active and expired ones.
-   **Spam:**  Display only spam ads.
-   **Unavailable:**  Display inactive and sold ads.
-   **Unconfirmed:**  Ads that are published but do not have the publisher´s confirmation via email.
-   **Expired Ads:**  This tab appears only if  **Ad expiration date**  on Settings -> Advertisement is greater than zero. It only shows expired ads.
-   **Not Expired Ads:**  This tab appears only if  **Ad expiration date**  on Settings -> Advertisement is greater than zero. It only displays ads that are not expired
-   **Featured Ads:**  Display only featured ads.
-   **Sort:**  You can sort ads by title, id, published date, created date, category, location and status. By default the latest ads will be displayed first.

# Flag ads as inappropriate

*Since our 2.6.0 release, users can report an ad as inappropriate.*

Below each ad, users will find this button:
![flag-inappropriate](https://user-images.githubusercontent.com/55290441/80600813-9e2efa00-8a35-11ea-853f-58f77bf2d098.png)


By clicking on this button, they will be redirected to the contact page, where Subject and Message are already filled with the necessary text.

![flag-inappropriate2](https://user-images.githubusercontent.com/55290441/80600826-a0915400-8a35-11ea-9db6-d8c9e396dbe7.png)


An email will be send to the administrator of the website in order to review the reported ad.
  
 # How to add categories and manage them?
Content:
-   How to add new categories
    -   Quick method
    -   Manual method
    -   Import Categories
-   How to manage categories
    -   Move/Change order
    -   Edit
    -   Delete
-   Categories widget

One of the most frequently asked questions are  **how to add categories**  and  **how to** **manage them**.  In this documentation you’ll find an answer to this question and a step-by-step manual.

***Warning:**  We do not recommend adding more than 100 categories if you use a shared hosting. Otherwise, your website will work very slow.*

## How to add new categories

### Quick method

In the quick category creator, add the name of the category, hit  **enter**  on your keyboard and when you are done, press the ‘**Send’** button as explained in the following screenshot.
![quick-category1](https://user-images.githubusercontent.com/55290441/80600954-cdde0200-8a35-11ea-8dda-819f833df45e.png)


### Manual method

1. Go to  **Panel**  - choose  **Classifieds**  >  **Categories**

2. Press ‘**New category**’ button

3.  **Fill in the fields:**

-   **Name:**  Choose a name for the category that will be displayed in a listing, e.g. “Jobs”, “Apartments”. Basically, this field is the most important, the rest are kind of optional.
-   **Order:**  You can choose the order in which the subcategories will be displayed within a parent category. It’s not obligatory - later you can just use “drag & drop” to change the order.
-   **Parent:**  Here you can choose and create main and sub categories. If you choose “Home Category”, that category will become the main one. If a category is choosen as “Parent”, everything within that category is a subcategory.
-   **Seoname:**  A seoname will be auto-generated based on the name of category, but you can change it if you want it to be different.
-   **Description:**  You can add a few words about what is available in this category.
-   **Price:**  If you want people to pay for posting in this category, set your price here. Leave blank if it’s free to post.

4. Press  **SUBMIT**

![new-category2](https://user-images.githubusercontent.com/55290441/80600968-d1718900-8a35-11ea-811e-916c4765948f.png)


After submitting, you should receive a message stating:

*“_Success. Item created. Please, to see the changes, delete the cache”_.*

Continue creating new categories if necessary, but remember to always  **delete cache**  after finishing to see the changes. To delete cache, go to:  **Tools**  >  **Cache**  on the left sidebar and press ‘**Delete all**’. You can visit the site to see the changes you’ve made.

While adding categories, you should remember that only 2 levels of categories will be displayed in the theme and be accessible to view from the main page. If you want to add deeper categories, its recommended to use the “Categories” widget (watch how below).

### Import Categories

Go to  **Panel**  ->  **Classifieds**  ->  **Categories**, select “Import” and choose your csv file ([example](https://docs.google.com/uc?id=0B60e9iwQucDwTm1NRGlqcEZwdGM&export=download)). More information  [here](https://docs.yclas.com/use-import-tool-categories-locations/#import-categories).

## How to manage categories

Managing categories is very easy. Go to  **Panel**, choose  **Classifieds** -> **Categories**  on the left sidebar.

### Move/Change order

If you want to move categories and change their order you just need to drag and drop the selected category to the place you have chosen.

### Edit

To change something, e.g. the name or description of the category, you can use the  **Edit**  button.

### Delete

To delete a category, press the red button with a trash bin. Note that when you delete the parent category, subcategories within it will be moved a level up - to become the parent of the deleted category.

## Categories widget

The category widget gives you additional options. To activate it go to  **Panel**  and choose  **Appearance >** **Widgets**  on the left sidebar. Choose  **‘Categories’ widget** from the list and click  **Create**. Give a name to the widget’s title and choose if you want to display it in a sidebar or in the footer. You may also keep it  **Inactive**. Thanks to this widget, navigation between categories is easier. A list of categories will be displayed at all times at the side or at the bottom of the page.


# Hide Categories from homepage

*'Hide categories from homepage' feature is currently available only on all sites hosted at  [Yclas.com](https://yclas.com/)*

This feature offers the option to choose which categories you want to hide from the homepage of your site without deleting them!

**Steps to follow:**

1.  Login to your panel.
2.  Go to  **Classifieds**  ->  **Categories**.
3.  Press  **Hide Categories**.
4.  Choose the categories you want to hide.
5.  Press  **Save**.
6.  Go to your homepage and see the results!

Keep in mind that choosing to hide a parent category will affect all the subcategories of that category!

![hide-categories1](https://user-images.githubusercontent.com/55290441/80601210-2f9e6c00-8a36-11ea-8a1d-24e4e485852e.png)
![hide-categories2](https://user-images.githubusercontent.com/55290441/80601227-3331f300-8a36-11ea-9545-d226af31b1df.png)

![hide-categories3](https://user-images.githubusercontent.com/55290441/80601231-33ca8980-8a36-11ea-8adf-38dfe556a8ab.png)

![hide-categories4](https://user-images.githubusercontent.com/55290441/80601233-33ca8980-8a36-11ea-8aa0-d8c5816d9bf2.png)


# How to add icons to categories?
Content
-   How to do it
    -   Image icon
    -   Font icon

To make your categories recognisable, it is possible to add an icon to every category you have on your site. This option is available only in the  **[premium themes](https://selfhosted.yclas.com/)**. The uploaded logo appears in the  **home page**, next to the category description as shown below.
![categories-icons1](https://user-images.githubusercontent.com/55290441/80601510-9885e400-8a36-11ea-8473-29b3c1a9445f.png)


_Random icon uploaded to the Housing category at Home Page_

## How to do it

Adding icons to your categories is super easy! First of all, you have to create a category. If you are not sure how to do it,  [check out our useful tips](https://docs.yclas.com/how-to-add-categories).

### Image icon

1.  If you’ve already created the categories, you need to go to  **Admin Panel > Categories**. There you can find a list of the categories you have created.
2.  Click the button:  **Edit**  on the category you wish to update
3.  Find the field:  **Upload Category Icon**
4.  Upload your icon (note: get your icon file ready in your preferred format with the recommended dimensions of 250px by 40px)
5.  Press  **Submit**

![category-icon2](https://user-images.githubusercontent.com/55290441/80601518-9a4fa780-8a36-11ea-985d-e3c96fb068fe.png)

By doing this, you will have the image inserted next to the category, at the slider small box and the full sized image after clicking on the category.

If you decide to change or delete your image, the steps are very easy as well. The red button :  **Delete icon**  will apprear under the uploaded icon. Just press a button, accept the operation and impose the changes.

### Font icon

1.  Go to  **Admin Panel > Categories**  and create or edit a category.
2.  Find the field  **Icon Font**
3.  Select an icon from the library
4.  Press  **Submit**

<img width="502" alt="category-icon-font3" src="https://user-images.githubusercontent.com/55290441/80601536-9f145b80-8a36-11ea-9402-f9b89e093f4a.png">

  

By doing this, you will have the icon inserted next to the category on your site.

# How to add locations?

-   How to add locations
    -   Geonames
    -   Quick Creator
    -   Manual method
    -   Import Locations
-   How to add sub-locations
-   How to manage locations
-   Locations widget
- 
**Locations**  makes it possible to segregate ads by place or city. Thanks to this users can narrow their search ads within their geographical territory.

***Warning:**  We do not recommend adding more than 1000 locations if you use shared hosting. Otherwise, your website will work very slow.*

![add-locations1](https://user-images.githubusercontent.com/55290441/80601834-003c2f00-8a37-11ea-95af-a63e7cebce2e.png)


## How to add locations

### Geonames

**Steps:**

1.  Login to your admin panel.
2.  Choose  **Classifieds**  ->  **Locations**.
3.  Select  **Import Geonames Locations**.

![add-location2](https://user-images.githubusercontent.com/55290441/80601840-03cfb600-8a37-11ea-88d1-572f0a3e9490.png)


![add-location3](https://user-images.githubusercontent.com/55290441/80601856-092d0080-8a37-11ea-9ca6-285abb59ce34.png)

This is probably the easiest and fastest way to add multiple locations.  You have to do choose a location (Continent, Country, State/Province, County/Region or City) and press  **Import**  to import its sub-locations.  
For example, if you choose:  
Continent = Europe  
Country = Spain  
State/Province = Catalonia  
and then click Import, it will add Barcelona, Girona, Lleidia and Tarragona to your locations.

Then, you can add the sub-locations of a location.  
If you have added Barcelona in your locations, click  **Browse**  on the right of this location.  
Then choose:  
Continent = Europe  
Country = Spain  
State/Province = Catalonia  
County/Region = Barcelona  
and click “Import” to add all the sub-locations of Barcelona.

# How to use import tool for categories and locations?
Content:
-   Import Categories
-   Import Locations

You are building a large scale  **classifieds website**  with lots of categories and locations, but you’re having a problem with adding them all in without spending so much time typing each one out.

We have the solution for you! You can use an easy import tool to add all of your locations and categories with a press of a button. You simple need to follow those steps:

**Warning:** We do not recommend adding more than 100 categories or 1000 locations if you use shared hosting. Otherwise, your website will work very slow.

### Import Categories

1.  Log into your  **Admin Panel**.
2.  Go to  **Classifieds**  >  **Categories**.
3.  Click  **Import**.
4.  Upload CSV files for your categories.

![import-categories](https://user-images.githubusercontent.com/55290441/80602306-9cfecc80-8a37-11ea-8ece-92e190720a76.png)

  
You can find  [here](https://docs.google.com/uc?id=0B60e9iwQucDwTm1NRGlqcEZwdGM&export=download)  the example of the correct CSV format.

![import-locations](https://user-images.githubusercontent.com/55290441/80602317-9f612680-8a37-11ea-8d29-2354d237b8ce.png)

# How to manage orders

Yclas gives you the option to  _view_  and  _edit_  the orders made in your website.

When orders placed by users, they will appear on  **Panel**,  **Classifieds**  ->  **Orders**.  _Note that only the administrator of the website has access to that area!_
![orders1](https://user-images.githubusercontent.com/55290441/80602524-ea7b3980-8a37-11ea-9672-1183b299acbf.png)



Here you can view the orders made in your website as well as their details:  _Status_,  _Product_,  _Amount_,  _User_  (who placed this order, username - email),  _Ad_,  _Date_  (date created),  _Date Paid_.

You can also edit these details by clicking the button under  _Actions_  on the right of the order.

![orders2](https://user-images.githubusercontent.com/55290441/80602522-e9e2a300-8a37-11ea-96de-50ab8ebc65d1.png)

![orders3](https://user-images.githubusercontent.com/55290441/80602545-f0711a80-8a37-11ea-94ef-907cb39e6afb.png)

-   **Id Product:**
    1.  _Post in paid category_
    2.  _Top up ad_
    3.  _Feature ad_
    4.  _Buy product_
-   **Paymethod:**  You can change the payment method of this order.
-   **Pay Date:**  In this field you can edit the date user paid.
-   **Currency:**  Which currency is used for this order.
-   **Amount:**  The amount of this order.
-   **Status:**
    -   0 = not paid
    -   1 = paid
    -   5 = refused payment
    -   99 = refunded
-   **Description:**  You can add a desctription about this order
-   **Txn Id:**  The transaction id of the payment gateway.

# How to use Coupon System
Content:
-   How to create coupons
    -   Create single coupon
    -   Bulk creation
    -   Import coupons
-   Edit Coupons
-   How to use coupons
    -   On the checkout page
    -   From widget coupons
    -   Add Coupon Name in any URL
-   Export coupons

**Note that Coupon System is available only on Premium Themes. When you are ready to have a Premium Theme, go to our  [market](https://selfhosted.yclas.com/).*

*This feature is available on our 2.5.0 release.*

This new tool allows you to give special discounts to customers to post on paid categories, top up or upgrade their ads to feature.

## How to create coupons

There are three ways to offer coupons: Create single coupon, bulk creation of unique coupons and import coupons by uploading a CSV file.

### Create single coupon

Login to your Panel, go on  **Classifieds**  ->  **Coupons**  and click  **New**.

[![new coupon](https://docs.yclas.com/images/coupons-new.png)](https://docs.yclas.com/images/coupons-new.png)

Fill the fields and press  **Submit**.

[![new coupon 1](https://docs.yclas.com/images/coupons-new1.png)](https://docs.yclas.com/images/coupons-new1.png)

-   **Name:**  It must be unique, cannot be repeated.
-   **Id Product:**  Any means will work for any product. If you choose a product, then the coupon will work only for that product.
-   **Discount Amount:**  (If Fixed discount is selected) Fixed amount to be discounted, ex. 3 (will discount 3$ from the total).
-   **Discount Percentage:**  (If Percentage discount is selected) Percentage of discount, ex. 50 (will remove 3$ from a $6 order).
-   **Number Coupons:**  Number of times that unique coupon can be used.

-   **Valid until:**  Until when you can use that coupon.

[![new coupon 2](https://docs.yclas.com/images/coupons-new2.png)](https://docs.yclas.com/images/coupons-new2.png)

[![new coupon 3](https://docs.yclas.com/images/coupons-new3.png)](https://docs.yclas.com/images/coupons-new3.png)

### Bulk creation

Login to your Panel, go on  **Classifieds**  ->  **Coupons**  and click  **Bulk**.

[![bulk coupon](https://docs.yclas.com/images/coupons-bulk0.png)](https://docs.yclas.com/images/coupons-bulk0.png)

Fill the fields and press  **Submit**.

[![bulk coupon](https://docs.yclas.com/images/coupons-bulk2.png)](https://docs.yclas.com/images/coupons-bulk2.png)

Unique coupon names will be created automatically.

[![bulk coupon](https://docs.yclas.com/images/coupons-bulk3.png)](https://docs.yclas.com/images/coupons-bulk3.png)

### Import coupons

Login to your Panel, go on  **Classifieds**  ->  **Coupons**, click  **Import**, choose your CSV file and click  **Upload**.

[![import coupon](https://docs.yclas.com/images/coupon-import.png)](https://docs.yclas.com/images/coupon-import.png)

You can use this tool for example if your provider sends you the coupons.  [Here’s a sample CSV file](https://cdn.rawgit.com/yclas/yclas/master/install/samples/import/coupons.csv).

## Edit Coupons

If you made a mistake or you want to update a coupon, you can simply go on  **Classifieds**  ->  **Coupons**  and click to edit the coupon.

[![edit coupon](https://docs.yclas.com/images/coupons-edit.png)](https://docs.yclas.com/images/coupons-edit.png)

You can edit all the fields except from the name of the coupon.

## How to use coupons

At first, give the  **coupon name**  to the beneficiary. After that, there are three ways for the beneficiary to use the coupon:

### On the checkout page

Add the coupon name in the field on the right bottom of the checkout form.

[![checkout](https://docs.yclas.com/images/coupons-checkout.png)](https://docs.yclas.com/images/coupons-checkout.png)

[![checkout1](https://docs.yclas.com/images/coupons-checkout1.png)](https://docs.yclas.com/images/coupons-checkout1.png)

### From widget coupons

Users can enter the name of the coupon, click add and if the coupon exists and it’s valid, then it’s automatically added on the checkout page. Before that, you need to create a coupon widget. If you don’t know how to create a widget, please follow  [this guide](https://docs.yclas.com/overview-of-widgets)

[![widget](https://docs.yclas.com/images/coupon-widget.png)](https://docs.yclas.com/images/coupon-widget.png)

[![widget1](https://docs.yclas.com/images/coupon-widget1.png)](https://docs.yclas.com/images/coupon-widget1.png)

### Add Coupon Name in any URL

If the name of the coupon is “FEATURE20%”, then users can add this in any URL of your website

```
?coupon=FEATURE20%

```

## Export coupons

Last but not least, you can export coupons from your panel to CSV file. This will be useful for example to send those coupons to your provider.


# How to mark image as primary

-  How it works
**This feature is available on our 2.5.1 release.*

With it, users have the option to change the **primary image** of their ad. If a user publishes an ad with five images, he can choose which image will be displayed as primary by editing the ad.

## How it works

Let’s say you have published an ad with two images. This is how it’s displayed on the Listing page:

![primary-image](https://docs.yclas.com/images/primary-image.png)

If you want to change the primary image, you have to click “Edit” on the ad and then click “Primary Image” under the image you want to mark as primary.

![primary-image1](https://docs.yclas.com/images/primary-image1.png)

This is the result!

![primary-image2](https://docs.yclas.com/images/primary-image2.png)

Notice that you can change the primary image as many times as you'd want!

