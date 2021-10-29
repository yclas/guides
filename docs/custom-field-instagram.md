# Instagram feed

Allow users to include an Instagram feed for an ad.

This guide explains how to give publishers the option to show an Instagram feed in their ads:

Please follow steps "**1: Create a Facebook App**" and "**2: Configure Instagram Basic Display**" from instagram guide: https://developers.facebook.com/docs/instagram-basic-display-api/getting-started#step-1--create-a-facebook-app.

You will get an **App ID**, and a **App Secret** codes. Please enter those on the Instagram page at https://yourdomain.com/oc-panel/integrations/instagram.

When asked for a Valid OAuth Redirect URIs, please enter `https://yourdomain.com/instagram/auth/now`, and when asked for a Deauthorize Callback URL, please enter `https://yourdomain.com/instagram/auth/now` too.

You will also need to follow the [App Review process](https://developers.facebook.com/docs/development/release).

Login to your **Admin Panel**-> **Configure -> Integrations -> Social** and click on **Instagram** and fill your **App ID** and **App Secret** details.

Once completed, an "Instagram Connect" section will appear on edit profile page.
