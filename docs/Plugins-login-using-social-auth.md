# How to login using Social Auth (Facebook, Google, Twitter ...)


## How to enable Google login

1.  Open in a new window the  **[Google Developers Console](https://cloud.google.com/console#/project)**.
2.  Select a  **Project**  on the top and choose  **New  project**.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login1.png)

  
1.  Choose a Project name and press  **Create**.  
2.  Go to APIs overview then choose  **Credentials**, on the left menu.  
3.  Choose  **Create Credentials**  ->  **OAuth client ID**  and then click on  **Configure consent screen**.  
4.  Now you need to enter a  **Product name**  and you can fill any of the other optional fields you want. Click  **Save**.  
5.  After that, you will be redirected to create client ID.

-   Application type: Web application.
-   Authorized Javascript origins: Your site URL here. ex: https://yclas.com/
-   Authorized redirect URI: ex: https://yclas.com/social/login/1?hauth.done=Google.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login2.png)

10. Click  **Create**.  
11. Now you have to verify (register) your domain name. Go to  **Google Console Developers**  ->  **Credentials**, choose the last tab,  **Domain verification**  and follow the steps there.  
12. Go to https://yourdomain.com/oc-panel/addons/sociallogin
13. Set  **Google = TRUE**  
14. Fill  **ID = Client ID**  as appears at Google page  
15. Fill  **Secret = Client secret**  as in Google  
16. Click  **Update**  in the bottom of the page  
17. Logout.
18. Go to login, Google should appear there.  
19. You can now test it. 

  

## How to enable Facebook login

Since March 2018 it’s required to get an SSL certificate for your domain in order to use Facebook Login. If your website is hosted on yclas.com follow  [this guide](https://yclas.com/faq/ssl-encryption.html)  to get an SSL certificate. If you are using Yclas Self-Hosted read more about it  [here](https://docs.yclas.com/move-classifieds-site-http-https/).

This social login  **might change depending on Facebook**.

1. Go to  [Facebook for developers](https://developers.facebook.com/apps/).
2. Click  **Add a New App**.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login3.png)

3. Fill the fields  **Display Name**  and  **Contact Email**.
4. Press  **Create App ID**.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login4.png)

5. Choose  **Set Up Facebook Login**  on Add Product page.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login5.png)

6. Choose  **Other**  on the Quickstart page.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login6.png)

7. Choose  **Facebook Login -> Settings**  on the left menu.
8. Enable  **Client OAuth Login**  and  **Web OAuth Login**  and fill the fields:  

**Valid OAuth redirect URIs**:  
https://yourdomain.com/social/login/1?hauth_done=Facebook
or  
https://yourdomain.com/social/login/1?hauth_done=Facebook

**Deauthorize Callback URL**:  _https://yourdomain.com

7. Click  **Save Changes**.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login7.png)

8. Choose  **Settings -> Advanced**  and enable  **Social Discovery**  and  **Allow API Access to App Settings**.
9. On the header switch  **OFF**  to  **ON**.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login8.png)

10. Choose a category and click  **Confirm**.
11. Choose  **Settings -> Basic**  and copy your App ID and App Secret.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login9.png)

12. Go to https://yourdomain.com/oc-panel/addons/sociallogin
13. Set  **Facebook =**  **TRUE**.
14. Fill  **ID = App ID**  as appears at FB page.
15. Fill  **Secret = App secret**  as in FB.
16. Click  **Update**  in the bottom of the page.  
17. Logout.  
18. Go to login, Facebook should appear there.  
19. Now you can try it out.


Since our latest release, it’s really easy to login using a  **social network account**  like  **Twitter, Facebook, Google Sign-In , LinkedIn etc.** 

For doing that we use a third party open source project called **[HybridAuth](https://hybridauth.github.io/hybridauth/)**  (awesome project!).

To activate any of these social logins, you need first to purchase a premium theme from our  **[market](https://selfhosted.yclas.com/)**.


