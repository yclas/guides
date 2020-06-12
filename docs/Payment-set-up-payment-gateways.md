# How to Setup Payment Gateways
Content:
-   Payment methods
    -   Alternative payment
    -   Stripe
    -   Escrow
    -   Paypal
    -   2checkout
    -   Authorize.net
    -   Paymill
    -   Alipay
    -   Bitpay
    -   Omise
    -   Paytabs
    -   PayFast
    -   Mercadopago
    -   Zenith GlobalPAY
    -   Payline
  

**Heads Up!**  Authorize, Stripe, Paymill, 2checkout, Paysbuy, SecurePay, Robokassa, Paguelofacil and Bitpay are only available with premium themes and on all sites hosted at  [Yclas.com](https://yclas.com/)!

  
Let’s first go through the payment settings we have here, of course you can access payment settings by logging into your admin panel  then go to  **Settings**  >  **Payments**  :

-   **Payment Currency:**  Pick the currency you want to get paid with. Make sure that your chosen Payment Gateway supports that currency!
-   **Featured ads:**  Turn On or Off the option to feature ad.
-   **Featured Plans:**  This feature allows you to give users the option to select between different length of the featured of their ad and pay according to your plans. Follow  [this guide](Payment-featured-plans.md)  for more.
-   **Bring to top Ad:**  Turn On or Off the option to bring an ad to top of the list.
-   **To top price:**  The amount you charge for bringing an ad to top.
-   **Stock control:**  [When users limit their stock enable this option](Payment-pay-directly-from-the-ad-option.md).

## Payment methods:

### Alternative payment:

Here you can choose a page that you created to pop up when a client clicks on alternative payment, we added this in case you needed to charge clients in another way so you can create a page with the instructions and it will pop up.

----------

### Stripe

Follow  [this guide](Payment-set-up-marketplace-with-srtipe-connect.md)  for more information.

To get paid via credit card you can also use a Stripe account, It’s also  [free to register](https://stripe.com/)  and they charge 2.95% on any transaction.

**Stripe private key**  and  **Stripe public key**  can be obtained from your  [Stripe account](https://dashboard.stripe.com/account/apikeys). Enter the value of  _Secret_  into the “Stripe private key” and  _Publishable_  into “Stripe public key”.

**Requires address to pay for extra security:**  Users will be asked for their address for more secure payments when using a credit card.

----------

### Escrow

With escrow the money gets on hold until the buyer receives the item. To configure Escrow follow  [this guide](Payment-marketplace-with-escrow.md)

----------

### Paypal

To accept Paypal payments you need to  **set up a Paypal account**,  **enable Instant payment notifications**  in your PayPal account (Seller Preferences -> Instant payment notifications), enter your website URL (http://example.com) into the Notification URL field and then input the paypal e-mail in its designated box in your website admin panel:

**Paypal account:**  Input here your Paypal email  
**Sandbox:**  Enable testing mode  

----------

### 2checkout

**Sandbox:**  Enable testing mode  
**Account Number**  and  **Secret Word**  can be obtained from your account info at  [2checkout](https://www.2checkout.com/)

You can find more information about 2checkout configuration  [here](Payment-2checkout-configuration.md)

----------

### Authorize.net:

To accept credit card payments you need to set up an account with authorize.net and you will also need an SSL certificate. Take a look at their [payment types](https://www.authorize.net/our-features/payment-types.html). You need to register at [here](https://support.authorize.net/s/article/How-can-I-sign-up-for-Visa-Checkout). This is their [price list](https://www.authorize.net/sign-up/pricing.html) and a [full guide](https://support.authorize.net/s/article/Authorize-Net-Getting-Started-Guide) of the services they offer. If you want to check if Autorize.net supports certain payment processors in your country [click here](https://support.authorize.net/s/article/As-a-merchant-located-outside-the-United-States-can-I-use-Authorize-Net-as-my-payment-gateway)

**Sandbox:**  Enable this for testing mode  **Authorize API login**  and  **Authorize transaction key**  can be obtained from your account info at authorize.net

----------

### Paymill

To get paid via credit card you need a Paymill account, it’s  [free to register](https://app.paymill.com/user/register)  and they charge 2.95% on any transaction.

**Paymill private key**  and  **Paymill public key**  can be obtained from your Paymill account after registration.

----------

### Alipay

**Accept Alipay payments:**  Merchants using Stripe will be able to instantly enable Alipay acceptance.

----------

### Bitpay

Accept Bitcoins using Bitpay, you can  [register for free](https://bitpay.com/)  and start accepting Bitcoins.

**Bitpay api key:**  Input your Bitpay api key here after you finished your registration.

----------

### Omise

Free registration [here!](https://www.omise.co/)

**Omise account:**  Enter your Omise account email here. **Sandbox:**  Enable this for testing mode

----------

### Paytabs

Free registration [here](https://www.paytabs.com/en/)

**Merchant email:**  Your Paytabs account email.  **Secret Key:**  Secret key available on the merchant dashboard, under the menu “Ecommerce Plugins and API”.

----------

### PayFast

In order to receive online payments with  **PayFast**, you need to  [go to their site and register](https://www.payfast.co.za/user/register/full).

Your  **Merchant ID**  and  **Merchant Key**  can be found by logging into your PayFast account and clicking on the Settings page. They are listed under “Merchant Identifiers”. Enable  **Sandbox**  for testing mode.

----------

### Mercadopago

To setup  **Mercadopago**  for your classifieds sites, please follow the steps:

1.  Register  in [Mercadopago](https://www.mercadopago.com.ar/registration-mp?confirmation_url=https%3A%2F%2Fwww.mercadopago.com.ar%2F) 
2.  Get you  **Client-id**  and  **Client-Secret**.
3.  Go to your admin panel ->  **Settings**  ->  **Payments**  ->  **MercadoPago**  and paste the Client-id and Client-Secret.

----------

### Zenith GlobalPAY

https://www.globalpay.com.ng/Payments.aspx

### Payline

https://paylinedata.com/


----------

Of course you can enable as many payment gateways as you want simultaneously without any restrictions. When they’re enabled the user will be redirected to a checkout page to select his preferred payment method.

  

Note: Only paypal works with the free Yclas self-hosted version [premium themes!](https://selfhosted.yclas.com/).  Upgrade your Yclas site to activate this feature.

  
**Related posts:**

-   [2checkout Configuration](Payment-2checkout-configuration.md)
-   [Stripe Connect](Payment-set-up-marketplace-with-srtipe-connect.md)
