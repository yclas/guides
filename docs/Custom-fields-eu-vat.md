# VAT on checkout

Content:
-   [Configure VAT for features](Custom-fields-eu-vat.md#configure-vat-for-features)
    - EU countries
    - Non EU countries
-   Configure VAT for sellers
    - Advertisement VAT number
    - User VAT number
-   The checkout page
-   VAT on automatic emails
-   VAT for non EU countries


Yclas allows you to include VAT to the orders. When users purchase Featured Ads, To Top, Pay to Post or Membership plans the VAT will be added at checkout. You can also configure your website in a way that users can simply add their VAT number and the VAT will be added automatically at the checkout.

## Configure VAT for features

Follow the steps below to add the VAT to the features of your website,  **Featured Ads**,  **To Top**,  **Pay to Post**  and  **Membership plans**.

### EU countries

1.  Login to your **Admin Panel**.
2.  Go to  **Settings -> Payment -> General**.
3.  Enter the  **VAT country**  and  **VAT number**.
4.  Click  **Save**.

Once you click Save you should get a success message. If you get the following message it means that VAT country or number is wrong :

_Error: Invalid EU Vat Number, please verify number and country match_

### Non EU countries

1.  Login to your **Admin Panel**.
2.  Go to  **Settings -> Payment -> General**.
3.  Enter the  **VAT country**,  **VAT number**  and  **VAT rate only for Non-EU countries**.
4.  Click  **Save**.

## Configure VAT for sellers

If you don’t know how to enable the Buy Now button,  [here’s how](Payment-pay-directly-from-the-ad-option.md)

Sellers can enter their VAT number and include VAT at checkout when they are selling their products through your website. This can be done in two ways: using  [advertisement custom fields](Custom-fields-create-custom-fields.md)  or  [user custom fields](Users-create-custom-field-for-users.md).

At checkout, your website will try to calculate the VAT using the Advertisement VAT number, if it’s missing it will use the User VAT number and if that is missing too, then no VAT will be added on the amount.

### Advertisement VAT number

1.  Login to your **Admin Panel**.
2.  Go to  **Settings -> Custom Fields**.
3.  Click  **New Field**.
4.  Enter  **vatcountry**  into the field called Name. It’s important to enter  _vatcountry_  as name and choose Country as the field type in order to make the feature works. Choosing Country will automatically create dropdown menu with all the countries included.
5.  **Fill the fields**  and  **press Create**.




### User VAT number

1.  Login to your **Admin Panel**.
2.  Go to  **Settings -> User Custom Fields**.
3.  Click  **New Field**.
4.  Enter  **vatcountry**  into the field called “Name”. It’s important to enter  _vatcountry_  as name and choose Country as the field type in order to make the feature works. Choosing “Country” will automatically create dropdown menu with all the countries included.
5.  **Fill the fields**  and  **press Create**.


## The checkout page

If the VAT country and the VAT number match, the checkout page will look like this.

## VAT on automatic emails

Once you configure VAT to be added at checkout, you will be able to include it to the **[automatic emails](Content-automatic-emails-sent-to-users.md)**  _ads-sold_  and  _ads-purchased_.

The variables you can use are:

-   **[VAT.COUNTRY]**

Includes the two-letter country code.

-   **[VAT.NUMBER]**

Includes the VAT number.

-   **[VAT.PERCENTAGE]**

The VAT rate based on the seller VAT number.

## VAT for non EU countries

If your selected country is an EU member, the VAT rate is calculated automatically. The solution we have for non EU countries is for the seller to add manually the VAT rate, in his user profile details or each ad details.

To let sellers manually insert the VAT rate, you need to create a custom field or user custom field called  **vatnoneu**.

1.  Login to your **Admin Panel**.
2.  Go to  **Classifieds -> Custom Fields**  or  **Users -> User Custom Fields**.
3.  Click  **New Field**.
4.  Enter  **vatnoneu**  into the field called Name. It’s important to enter  _vatnoneu_  as name and choose Number Decimal in the field type to make this feature work.
5.  **Fill the fields**  and  click **Create**.

<iframe width="100%" height="400px" src="https://www.youtube.com/embed/iICTpQ_hqKk" title="Yclas video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 

