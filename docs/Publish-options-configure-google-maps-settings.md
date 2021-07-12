## Configure Google Maps

Currently you get free $200 per month for maps usage , please see [Google Maps Pricing](https://cloud.google.com/maps-platform/pricing)

**Steps:**

1.  Login to  **Admin Panel** -> **Integrations**  ->  **Google Maps**.
2.  Fill the fields.
3.  Click  **SAVE**.


-   **Google Maps API Key** (step-by-step below ⤵️)
-   **Google map style**: Custom Google Maps styling.
-   **Google map zoom level**: Google map default zoom level. It will be applied on the map in the Publish New page and Ad page.
-   **Map latitude coordinates**: Google map default latitude coordinates. It affects the map in the Publish New page. (You can get lat and long here https://www.latlong.net/)
-   **Map longitude coordinates**: Google map default longitude coordinates. It affects the map in the Publish New page.
-   **Auto locate distance**: Sets maximum distance of closest suggested locations to the visitor.

## Get your API Key

1.  Go to  [Google developer’s console](https://console.developers.google.com/)  page to get your API Key.
2.  Choose  **Create a Project**  and click  **Continue**.
3.  Enter a  **Name**  for the API and on  **Accept requests from these HTTP referrers (web sites)**  enter  _yourdomain.com/*_  and click  **Create**.
4.  Copy the API Key into your admin panel,  **Settings**  ->  **Advertisement**  ->  **Google Maps**  and click  **Save**.
5.  Then back to the APIs Console, click  **Library**  on the left menu, under  **Google Maps APIs**  find and enable:

-   [Maps Static API](https://console.cloud.google.com/apis/library/static-maps-backend.googleapis.com)
-   [Geocoding API](https://console.cloud.google.com/apis/library/geocoding-backend.googleapis.com)
-   [Maps JavaScript API](https://console.cloud.google.com/apis/library/maps-backend.googleapis.com)
-   [Directions API](https://console.cloud.google.com/apis/library/directions-backend.googleapis.com)
-   [Geolocation API](https://console.cloud.google.com/apis/library/geolocation.googleapis.com)
-   [Places API ](https://console.cloud.google.com/apis/library/places-backend.googleapis.com)
-   [Distance Matrix API](https://console.cloud.google.com/apis/library/distance-matrix-backend.googleapis.com)

If you want to use Google Maps in your iOS app please also enable [Maps SDK for iOS](https://console.cloud.google.com/marketplace/product/google/maps-ios-backend.googleapis.com)




![](https://raw.githubusercontent.com/yclas/guides/master/images/googlemapssettings2.png)


<iframe width="100%" height="400px" src="https://www.youtube.com/embed/HkgirwUTl74" title="Yclas video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 
 **Related posts:**

-   [How to create a map widget?](Widgets-map-widget.md)
-   [How to add an Interactive Map?](Content-create-an-interactive-map.md)
-   [Search ads by distance](Search-ads-by-distance.md)

