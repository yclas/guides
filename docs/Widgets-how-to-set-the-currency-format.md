# Currency Converter Widget

Content:
-   Get an API Key
-   Create Currency Converter Widget
-   Currencies to display
    -   Major Currencies
    -   European Currencies
    -   Skandi Currencies
    -   Asian Currencies
    -   American Currencies
-   More currencies
-   Examples

If you want your website users and visitors to be able to convert currencies then this is the widget for you. As the title says, this is the widget which users can use to choose between your selected currencies and have ads prices converted to their chosen currency.

## Get an API Key

This is a mandatory step to follow in order to have the currency converter widget work. What you need to do is to go to  [https://fixer.io/product](https://fixer.io/product)  and choose a plan. Once you choose the plan you will be redirected to create an account and you will find the API key  [here](https://fixer.io/dashboard).

If your website uses SSL, please note that  **SSL encryption**  is only allowed for  **Fixer**  paid plans.

![](https://raw.githubusercontent.com/yclas/guides/master/images/currency.jpg)

## Create Currency Converter Widget

It’s really simple to create and use this widget:

1.  Login to your admin panel.
2.  Go to  **Design**  ->  **Widgets**.
3.  Find the Currency Converter Widget and press  **Create**.
4.  Choose  **where do you want the widget displayed**  and  **the name of the widget**  that will be displayed in your website.
5.  Type the  **Currencies to display**, comma separated, or leave it empty to display all the currencies.
6.  Enter the currency of your site on  **Choose the default currency**  field. Use this field ONLY in case you are using a different currency than your local one and make sure that the prices of the ads have the same currency.
7.  Click  **Save Changes**.

## Currencies to display


In this field you can type the currencies you want to be available on your site.
**Please note that you have to enter the three-character currency codes in order to work.** An example of input would be:

```
EUR,USD,CAD,AUD

```

Using this example you will have Euros, USA Dollars, Canadian Dollars and Australian Dollars available.

Additionally we have created  **groups of currencies**  to make it easier for you.

### Major Currencies

If you include the word  **major**  in the currencies to display, it will add USD, EUR, GBP, JPY, CAD, CHF, AUD and ZAR.

### European Currencies

Including the word  **european**, will add ALL, BGN, BYR, CZK, DKK, EUR, GBP, HRK, HUF, ISK, NOK, RON, RUB, SEK and UAH.

### Skandi Currencies

For Scandinavian currencies, include the word  **skandi**. It will add DKK, SEK and NOK.

### Asian Currencies

Asian currencies can be added by typing  **asian**  into the currencies field. JPY, HKD, SGD, TWD, KRW, PHP, IDR, INR, CNY, MYR and THB are available for convertion.

### American Currencies

Include the word  **american**  to have USD, CAD, MXN, BRL, ARS, CRC, COP and CLP.

## More currencies

Here are all the available currencies:

AED, ALL, BDT, BGN, CAD, CNY, CZK, DKK, EUR, GBP, INR, HRK, HUF, IDR, JPY, NOK, PHP, PKR, PLN, RON, RSD, RUB, SEK, TRY, USD, VND, XAG, MOP, MDL, VEF, GEL, ISK, THB, MXV, TND, JMD, BWP, MUR, AZN, MGA, LBP, XDR, IEP, AUD, MMK, LYD, ZAR, IQD, XPF, TJS, CUP, UGX, PGK, TOP, KES, TMT, CRC, MZN, BYN, SYP, ANG, ZMW, BRL, BSD, NIO, GNF, BMD, SLL, MKD, BIF, LAK, BHD, SHP, SGD, TTD, SCR, BBD, SBD, MAD, GTQ, MWK, ITL, PEN, LVL, XPD, UAH, LRD, LSL, FRF, XOF, COP, CDF, TZS, NPR, GHS, ZWL, SOS, DZD, LKR, FKP, CHF, KYD, CLP, IRR, AFN, DJF, SVC, PYG, ERN, ETB, ILS, TWD, KPW, GIP, SIT, BND, HNL, BZD, DEM, JOD, RWF, LTL, WST, PAB, NAD, DOP, HTG, KMF, AMD, MRO, ECS, CYP, KWD, XCD, XCP, CNH, SDG, CLF, KZT, NZD, FJD, BAM, BTN, STD, VUV, MVR, AOA, EGP, QAR, OMR, CVE, KGS, MXN, MYR, GYD, SZL, YER, SAR, UYU, UZS, GMD, AWG, MNT, XAU, HKD, ARS.

## Examples

-   An example of input:
    
    ```
      european,american
    
    ```
    

Available currencies will be: ALL, BGN, BYR, CZK, DKK, EUR, GBP, HRK, HUF, ISK, NOK, RON, RUB, SEK, UAH, USD, CAD, MXN, BRL, ARS, CRC, COP and CLP.

-   For input:
    
    ```
      asian,EUR,USD
    
    ```
    

Available currencies will be: JPY, HKD, SGD, TWD, KRW, PHP, IDR, INR, CNY, MYR, THB, EUR and USD.

-   For input:
    
    ```
      EUR,CAD,CNY,NOK,PHP,USD
    
    ```
    

Available currencies will be: EUR, CAD, CNY, NOK, PHP, USD



You may also be interested in:

-   [Overview of widgets](Widgets-overview.md)
-   [How to set the currency format?](General-currency-format.md)
-   [Choose Language Widget](Widgets-langauge-widget.md)
-   [Image Widget](Widgets-image-widget.md)
-   [How to add a banner](Appearance-how-to-add-a-banner.md)
