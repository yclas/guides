# Sell digital goods
Content:
-   How it works
-   Prerequisites
-   Create the File field
-   Dropbox
-   Google Picker

Now sellers can upload files to their ads from Dropbox or Google Picker and sell them. With this feature it’s possible to sell digital goods in your website.

## How it works

-   Seller uploads a file from Dropbox or Google Picker while posting his ad.
-   Buyer clicks the Buy Now button and buys the product.
-   The confirmation email is sent to the buyer, which includes the Order ID, Product ID and the link to download the uploaded file.

## Prerequisites

-   Dropbox  or  Google Picker app is created and configured.
-   [Buyer instructions custom field](Custom-fields-buyer-instructions.md)  is created.
-   Seller fills the “Buyer instructions” custom field while posting the ad.
-   File download custom field  is created.
-   Seller selects the file while posting the ad.

## Create the File field

1.  Create a Custom Field on  **COnfigure** -> **Settings** -> **Custom Fields** -> **New**.
2.  The custom field  _Name_  must be  **file_download**  and  _Type_  must be  **File Dropbox**  or  **File Google Drive**.
3.  The custom field values are comma separated allowed file extensions.
4.  Now you need to configure one of the methods described below.



## Dropbox

1.  Create a new app on the  [Dropbox Platform].(https://www.dropbox.com/developers/apps/create)
2.  While you create the app, add your website URL to  **Chooser/Saver domains**.
3.  Copy the  **App key**  from your app and paste it in your website panel,  **Configure -> Integrations -> Dropbox -> App key**.

If this feature is properly configured, the result should be this:

![](https://github.com/yclas/guides/blob/master/images/newcustomfield2.png)


## Google Picker

1. Go to  [Google Developers Console].(https://console.developers.google.com/)
2. Press  **My Projects**  ->  **Create Project**.
![](https://github.com/yclas/guides/blob/master/images/newcustomfield3.png)

3. Choose  **Credentials**  on the left sidebar and click  **Create Credentials**  ->  **API key**.
![](https://github.com/yclas/guides/blob/master/images/newcustomfield4.png)

4. Copy your  **API key**  and paste it to your website admin panel ->  **Configure**  ->  **Integrations**  ->  **Google Picker**  ->  **Google Picker API Key** .[](https://github.com/yclas/guides/blob/master/images/ncs5.png)
![Google picker](https://raw.githubusercontent.com/yclas/guides/master/images/google%20picker.png)

5. Choose  **Credentials**  on the left sidebar and click  **Create Credentials**  ->  **OAuth Client ID**.
6. Click  **Configure consent screen**.


7. Choose your Email address, enter the  **Product name**,  **Privacy Policy URL**  and click  **Save**.
![](https://github.com/yclas/guides/blob/master/images/ncf9.png)

8. The next step requires to create the client ID. Choose  **Application Type - Web Application**, enter your website name into the  **Name**  field, your website URL into the field  **Authorized JavaScript origins**  and press  **Create**.
![](https://github.com/yclas/guides/blob/master/images/ncf10.png)
![](https://github.com/yclas/guides/blob/master/images/ncf12.png)

11. Copy the Client ID and paste it to your website admin panel -> **Configure**  ->  **Integrations**  ->  **Google Picker**  ->  **Google Picker Client ID**  and click   **Save**.


10. Go to  **Libary**, find and enable  **Google Picker API**.
![](https://github.com/yclas/guides/blob/master/images/ncf14.png)
![](https://github.com/yclas/guides/blob/master/images/ncf15.png)

11. Done. You can now go to the  _Publish new_  page to see the result.
![](https://github.com/yclas/guides/blob/master/images/ncf16.png)

**This feature is available on all sites hosted at  [Yclas.com](https://yclas.com/)**

