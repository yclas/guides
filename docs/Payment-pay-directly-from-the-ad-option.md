# Pay directly from the ad option

Content:
-   How to activate Buy Now button
-   Limiting stock amount

Did you know that sellers posting ads of their products in your classified site are allowed to get  **direct payments**  through PayPal for the goods they’re offering? Thanks to this feature, customers and sellers can  **complete the transaction**  on your site, which makes your site a kind of a selling platform.

### How to activate Buy Now button

It works under  **4 conditions**:

1.  As an admin, you have to activate the option. In  **Admin Panel**  ->  **Integrations -> PayPal**. In the last field  **Buy Now Button**  set  **Enabled**.
2.  Email submitted by the user while registration has to be the  **paypal email address**  connected with the sellers account. If you want users to be able to use a different email for their PayPal account, follow  [this guide](Custom-fields-PayPal-email-for-users.md).
3.  A seller, while posting an ad, has to set the  **price**  in the ‘Price’ field.
4.  If  **Stock Amount**  is enabled, the stock amount of the product has to be more than zero.
    
**Note**:  That is only possible if the  **‘PRICE’**  field is active - to choose which fields are visible in the **‘Publish new advertisement’** form, go in Panel to  **Settings > Advertisement**. Make sure there is  **ON**  selected next to the  **Price**  field.

If all conditions are met, an option will appear next to the published advertisement to pay for a product immediately. Payment can be done through  **Paypal account or with a credit card**.


### Limiting stock amount

Let’s say a user has a limited stock amount of the product he’s selling, and he doesn’t want to get more payments than the number of products that he has.

To enable that you need to have every condition met in the above section, and you need to have one more option enabled:

1.  Log in to your  **Admin Panel**.
2.  Go to  **Settings**  >  **Payment**  >  **General**.
3.  Set  **Stock Control**  to  **ON**.
4.  Click  **Save**.

Once you do this, your users will have the option to set a counter on their products. This counter goes down on each Paypal payment they receive. And once the counter is “0” their ad will be deactivated.
