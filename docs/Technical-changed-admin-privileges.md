# I accidentally changed my admin privilege, how can I fix that?

*This guide is only for Yclas Self-hosted*

“I was playing around with the user roles and accidentally changed the admin role to “1” instead of “10” on my admin account. Now I can’t do anything as I don’t have any admin permissions at all.”

**If that happened to you, here is how to fix it:**

1.  Login to your  **cPanel**  at your hosting.
2.  Go to  **phpMyAdmin**.
3.  Select your  **Yclas database**.
4.  Go to table  **oc3_users**.
5.  Search for your user and change the  **id_role**  to “**10**”.



What is more, if you forget your password and somehow the “  **Forgot my password**  “ function isn’t working, you can fix that by registering a new user and following the above mentioned steps to make the  **new user admin**.

Let us know what guide do you want next and we will create it for you and include it in our FAQ section. You just need to post a comment in the section below.


*This guide is only for Yclas Self-hosted*
