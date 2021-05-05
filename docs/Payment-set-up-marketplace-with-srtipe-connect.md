# Marketplace with Stripe Connect Express

With  [Stripe Connect](https://stripe.com/connect)  you will be able to charge your customers an application fee (percentage) based on the sale they make by using your platform.

### Example

You (site owner) set your site to get 3% commission for each sale made via your website. Your customer (publisher) posts an advertisement selling his services for the value of $100. Once this customer sells his product to a customer (product buyer), your customer (publisher) will receive $97 and you (site owner) will get immediately $3 on sale commission in your stripe account.

### Prerequisites

-   Configure your site to user Stripe Connect, see below for more details.

### Site configuration

1.  The site owner needs a  **Stripe account**  which is free.
2.  **Create an application  [here](https://dashboard.stripe.com/account/applications/settings)**.
4.  Go to your  **panel -> Integrations -> Stripe**.
5.  **Activate Stripe Connect Express**.
6.  Set a  **Stripe client ID**  that you got here https://dashboard.stripe.com/account/applications/settings.
7.  Set the percentage fee if you want to charge your customers, using the field called  **Application Fee**  in your website panel.
8.  Click  **Save**.

### User configuration

1.  Your customers will need to have a Stripe account to receive the items.
2.  With stripe connect active it’s mandatory to be registered before posting an ad, this is controlled by the application.
3.  The publisher will be redirected to his profile to connect with Stripe.
4.  Once connected he will be able to sell items on your site.

### Payment flow

1.  Buyer pays for a product listed on your site.
2.  Stripe receives the money.
3.  Your customer (publisher) receives the amount in his Stripe account.
4.  You (site owner) will get from his stripe account the fee you set in your stripe account.
5.  2 orders are created, 1 with the amount paid by the buyer and another with the fee paid by the publisher to you as application fee.
6.  Buyer and seller get an email with the transaction details.

## Stripe Escrow

**Related posts:**

-   [Buyer Instructions](Custom-fields-buyer-instructions.md)
-   [How to Setup Payment Gateways](Payment-set-up-payment-gateways.md)
