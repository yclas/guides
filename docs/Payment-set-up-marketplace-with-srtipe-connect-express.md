# Marketplace with Stripe Connect Express

With [Stripe Connect](https://stripe.com/connect) you will be able to charge your customers an application fee (percentage) based on the sale they make by using your platform.

### Example

You (site owner) set your site to get a 3% commission for each sale made via your website. Your customer (publisher) posts an advertisement selling his services for the value of $100. Once this customer sells his product to a customer (product buyer), your customer (publisher) will receive $97 and you (site owner) will get immediately $3 on sale commission in your stripe account.

### Prerequisites

- Configure your site to user Stripe Connect, see below for more details.

### Site configuration

1. The site owner needs a free **Stripe account**.
2. [Go to your Stripe Connect settings page](https://dashboard.stripe.com/account/applications/settings) to customize the visual appearance of the form with your brand’s name, color, and icon. Stripe Connect Onboarding requires this information.
4. Go to your **panel -> Integrations -> Stripe**.
5. **Activate Stripe Connect Express**.
6. Set a **Stripe client ID** that you got here https://dashboard.stripe.com/account/applications/settings.
7. Set the percentage fee if you want to charge your customers, using the field called **Application Fee** in your website panel.
8. Click **Save**.

### User configuration

1. Your customers will need to have a Stripe account to receive the items.
2. With stripe connect active it’s mandatory to be registered before posting an ad, this is controlled by the application.
3. The publisher will be redirected to his profile to connect with Stripe.
4. Once connected he will be able to sell items on your site.

### Payment flow

1. The buyer pays for a product listed on your site.
2. Stripe receives the money.
3. Your customer (publisher) receives the amount in his Stripe account.
4. You (site owner) will get from his Stripe account the fee you set in your Stripe account.
5. 2 orders are created, 1 with the amount paid by the buyer and another with the fee paid by the publisher to you as an application fee.
6. Buyer and seller get an email with the transaction details.

## Stripe Escrow

### Example

Your customer (publisher) posts an advertisement selling his products. Once this customer sells his product to a customer (product buyer), the publisher ships package and changes the order status to “shipped”. The product buyer receives the package and changes the order status to "received". When the status is changed to “received”, the publisher gets paid out.

### Escrow flow

1. The buyer pays for a product listed on your site.
2. Stripe receives the money.
3. Your customer (publisher) ships the sold product and marks the order as “shipped” on the "My Sales" page.
4. The product buyer receives the product and marks the order as “received” on the "My Orders" page.
5. Your customer (publisher) receives the payout.
6. You (site owner) will get from his stripe account the fee you set in your Stripe account.
7. 2 orders are created, 1 with the amount paid by the buyer and another with the fee paid by the publisher to you as an application fee.

### Cancellations flow

1. Your customer (publisher) and product buyer can cancel an order if is not yet marked as “shipped”.
2. An email is sent to your customer (publisher) and product buyer about the order cancellation.
3. You (site owner), refund the order from your order's panel.
4. The product buyer receives the money back.

You (site owner) can cancel an order in the panel even if it's shipped but hasn't paid out to your customer (publisher).

If the order is not marked as "Shipped" after a certain number of days, configured in the panel, the
order is automatically canceled, and your customer (publisher) and product buyer are informed by email.

**Related posts:**

-  [Buyer Instructions](Custom-fields-buyer-instructions.md)
-  [How to Setup Payment Gateways](Payment-set-up-payment-gateways.md)
