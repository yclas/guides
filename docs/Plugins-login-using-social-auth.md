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
_http://yourdomain.com/social/login/1?hauth_done=Facebook_  
or  
_https://yourdomain.com/social/login/1?hauth_done=Facebook_  

**Deauthorize Callback URL**:  _https://yourdomain.com_

7. Click  **Save Changes**.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login7.png)

8. Choose  **Settings -> Advanced**  and enable  **Social Discovery**  and  **Allow API Access to App Settings**.
9. On the header switch  **OFF**  to  **ON**.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login8.png)

10. Choose a category and click  **Confirm**.
11. Choose  **Settings -> Basic**  and copy your App ID and App Secret.

![](https://raw.githubusercontent.com/yclas/guides/master/images/login9.png)

12. Go to https://akosibadak.tk/oc-panel/addons/sociallogin
13. Set  **Facebook =**  **TRUE**.
14. Fill  **ID = App ID**  as appears at FB page.
15. Fill  **Secret = App secret**  as in FB.
16. Click  **Update**  in the bottom of the page.  
17. Logout.  
18. Go to login, Facebook should appear there.  
19. Now you can try it out.

## How to enable AOL login

1.  Go to https://akosibadak.tk/oc-panel/addons/sociallogin
2.  Set  **AOL = TRUE**.
3.  Click  **Update**  in the bottom of the page.
4.  Logout.
5.  Go to login, AOL should appear there.
6.  Now you can try it out.

## How to enable Open ID (yahoo) login

With this option users will be able to login using an Open ID account. In Yclas we use Yahoo as Open ID provider since it’s really easy to implement.

1.  Go to https://akosibadak.tk/oc-panel/addons/sociallogin
2.  Set  **Open ID = TRUE**.
3.  Click  **Update**  in the bottom of the page.
4.  Logout.
5.  Go to login, Open ID should appear there.
6. Now you can try it out.

## How to enable Yahoo login

1.  Go to  [https://developer.yahoo.com/apps/create/](https://developer.yahoo.com/apps/create/)  and create a new application.
2.  Fill out any required fields such as the  **Application Name**  and the  **Description**  one.
3.  In the  **Redirect URI(s)**  field enter: http://yourdomain.com/social/login/1
4.  Set  **Application Type**  to  _Web Application_.
5.  Choose  **API Permissions**  ->  **OpenID Connect Permissions**


[](https://raw.githubusercontent.com/yclas/guides/master/images/login10.png)

6. Go to your panel,  **Settings -> Plugins**, enable  **Social Auth**, click  **Save**  and then go to  **Settings**  ->  **Social Auth**  or https://akosibadak.tk/oc-panel/addons/sociallogin 
7. Set  **Yahoo = TRUE** .
8. Fill  **ID**  = Client ID as appears at Yahoo.
9. Fill  **Secret**  = Client secret as in Yahoo.
10. Click  **Update**  in the bottom of the page.
11. Logout.
12. Go to login, Yahoo should appear there.  
13. Now test it.

## How to enable Twitter login

1.  Go to  [https://apps.twitter.com/](https://apps.twitter.com/)  and press  **Create new app**
2.  Fill the fields Name, Description and Website.
3.  In the  **Callback URL**  field enter: http://yourdomain.com/social/login/1?hauth_done=Twitter
4.  Press  **Create your Twitter application**
5.  Go to the “Keys and Access Tokens” tab.
6.  Copy the  **Consumer Key**  and  **Consumer Secret**  and paste in your website admin panel. Settings -> Social Auth -> Twitter Key and Secret.
7.  Back in your Twitter app, go to the Permissions tab and make sure the Access is set to “Read and Write”.
8.  You're all set.

Since our latest release, it’s really easy to login using a  **social network account**  like  **Twitter, Facebook, Google Sign-In , LinkedIn etc.** 

For doing that we use a third party open source project called **[HybridAuth](https://hybridauth.github.io/hybridauth/)**  (awesome project!).

To activate any of these social logins, you need first to purchase a premium theme from our  **[market](https://selfhosted.yclas.com/)**.



## Other social login

From documentation Hybrid Auth, follow similar procedure.
1.  [Twitter](https://hybridauth.github.io/hybridauth//userguide/IDProvider_info_Twitter.html)
2.  [Yahoo](https://hybridauth.github.io/hybridauth//userguide/IDProvider_info_Yahoo.html) (deep integration, but check better Open ID)
3.  [MySpace](https://hybridauth.github.io/hybridauth//userguide/IDProvider_info_MySpace.html)
4.  [Windows Live](https://hybridauth.github.io/hybridauth//userguide/IDProvider_info_Live.html)
5.  [LinkedIn](https://hybridauth.github.io/hybridauth//userguide/IDProvider_info_LinkedIn.html)
6.  [Foursquare](https://hybridauth.github.io/hybridauth//userguide/IDProvider_info_Foursquare.html)
