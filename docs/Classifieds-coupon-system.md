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

This new tool allows you to give special discounts to customers to post on paid categories, top up or upgrade their ads to feature.

## How to create coupons

There are three ways to offer coupons: Create single coupon, bulk creation of unique coupons and import coupons by uploading a CSV file.

### Create single coupon

Login to your **Admin Panel**, go on  **Settings**  ->  **Coupons**  and click  **New**.

![](https://raw.githubusercontent.com/yclas/guides/master/images/Coupon%20create.jpg)


Fill the fields and click  **Submit**.

![coupons2](https://user-images.githubusercontent.com/55290441/80603249-d6840780-8a38-11ea-9800-e25af3934b54.png)


-   **Name->**  It must be unique, cannot be repeated.
-   **Id Product->**  Any means will work for any product. If you choose a product, then the coupon will work only for that product.
-   **Discount Amount->**  (If Fixed discount is selected) Fixed amount to be discounted, ex. 3 (will discount 3$ from the total).
-   **Discount Percentage->**  (If Percentage discount is selected) Percentage of discount, ex. 50 (will remove 3$ from a $6 order).
-   **Number Coupons->**  Number of times that unique coupon can be used.

-   **Valid until->**  Until when can you use that coupon.

![coupons3](https://user-images.githubusercontent.com/55290441/80603252-d71c9e00-8a38-11ea-8902-b46ac219162b.png)
![coupons4](https://user-images.githubusercontent.com/55290441/80603254-d71c9e00-8a38-11ea-9ef5-5ac5eebcea3b.png)



### Import coupons

Login into your **Admin Panel**, go to  **Settings**  ->  **Coupons**, click on **Import**, choose your CSV file and click  **Upload**.

![coupon8](https://user-images.githubusercontent.com/55290441/80603323-eb609b00-8a38-11ea-953d-05415bf4a713.png)


You can use this tool for example if your provider sends you the coupons.  [Here’s a sample CSV file](https://raw.githubusercontent.com/yclas/guides/master/samples/import_coupons_example.csv).

## Edit Coupons

If you made a mistake or you want to update a coupon, you can simply go on  **Settings**  ->  **Coupons**  and click to edit the coupon.

![coupons9](https://user-images.githubusercontent.com/55290441/80603259-d84dcb00-8a38-11ea-81bf-16bd3748acfc.png)

You can edit all the fields except from the name of the coupon.

## How to use coupons

Given that you have already provided the **coupon code** to the beneficiary, they can be used in either way as stated below : n:

### On the checkout page

Add the coupon name in the field on the right bottom of the checkout form.

![coupons10](https://user-images.githubusercontent.com/55290441/80603244-d552da80-8a38-11ea-9989-abb227c90a35.png)
![coupons11](https://user-images.githubusercontent.com/55290441/80603246-d5eb7100-8a38-11ea-92d2-59fc810ab711.png)


### From widget coupons

Users can enter the name of the coupon, click add and if the coupon exists and it’s valid, then it’s automatically added on the checkout page. Before that, you need to create a coupon widget. If you don’t know how to create a widget, please find the needed information on our documentation.

![coupon12](https://user-images.githubusercontent.com/55290441/80603335-f0254f00-8a38-11ea-81da-40087cc2f611.png)

![coupon13](https://user-images.githubusercontent.com/55290441/80628862-ad746e80-8a5a-11ea-9b0d-fdfe39854a04.png)
### Add Coupon Name in any URL

If the name of the coupon is “FEATURE20%”, then users can add this in any URL of your website

```
?coupon=FEATURE20%

```

## Export coupons

Last but not least, you can export coupons from your panel to CSV file. This will be useful for example to send those coupons to your provider.


**Note that Coupon System is available only on Premium Themes. When you are ready to have a Premium Theme, go to our  [market](https://selfhosted.yclas.com/).*


<iframe width="100%" height="400px" src="https://www.youtube.com/embed/gFTDgz6NWTU" title="Yclas video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
