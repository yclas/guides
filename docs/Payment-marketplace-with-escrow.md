# Marketplace with Escrow Pay

### Prerequisites

+ Configure your site to use Escrow Pay, see below
+ Your customer (publisher) needs to have a different Escrow account to receive payments.

### Payment flow

1. Buyer pays for a product listed on your site
2. Escrow receives the money
3. Your customer (publisher) ships the item that they sold
4. Buyer receives and accepts the item
5. Your customer (publisher) receives the amount in his Escrow account

### Site configuration

1. Go to your **panel -> Settings -> Payments**
2. **Enable Escrow Connect**
3. Enable Sandbox mode for testing purposes only


### User configuration

1. Your customers (the publisher) will need to have an Escrow account to receive the payments
2. With Escrow pay enabled it's mandatory to be registered before posting an ad, this is controlled by the application.
3. The publisher will be redirected to his profile to connect with Escrow.
4. Once connected he will be able to sell items on your site.

### Buying Process
1. A user buys an item
2. The Buyer goes to the checkout page and pays with Escrow
3. The buyer is redirected to Escrow checkout to create an account or login with an existent account
4. The buyer makes a payment
5. The buyer can mark an order as **paid** if pays with wire transfer and Escrow has secured the payment
6.  Now, the seller ships the item and marks the order as **shipped**
7. Then, the buyer receives the item and marks the order as **received**
8. The buyer can mark an order as **accepted** if is satisfied with the order received.
9. Finally, the seller receives their payment.


**Related posts:**

+ [Buyer Instructions](Custom-fields-buyer-instructions.md)
+ [How to Setup Payment Gateways](Payment-set-up-payment-gateways.md)
+ [2checkout Configuration](Payment-2checkout-configuration.md)
