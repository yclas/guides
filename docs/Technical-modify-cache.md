# How to modify cache time?

Content:
-   How it works?
-   Where is it implemented?
-   How can I change the duration?
-   How can I disable it?
-   Enable real time
-   Use other cache

*This guide is only for Yclas Self-hosted!*

***Before you read:**  This post is a bit more technical, but I will try to keep it as simple as possible.*

Thanks to the  **Cache**, we are able to  **serve more hits in your web without scaling your system**. That means you get a  **cheaper hosting**, a lot  **more of page views**  and  **faster page loading**  !

### How it works?

Every time your web server needs some dynamic information, we send a query to the database server. It then does a search in all its data and returns the values to the web server.

This is normally  **the most expensive operation**  that an application will do, so why repeating the same query many times when we already know the results?

The cache will store these results in a place that’s it’s easy to find so we can use it later.

**An example:**  just think that you go to a huge library and they tell you to find all the books written between 1923 and 1984 that contain the word “advertisement”.

That will take you a lot of time, right?

But you will write down in a paper every match and next time someone asks you for that information you wont need to go to the library and you will have the results in seconds.

That’s exactly what the cache does!

### Where is it implemented?

**Yclas** is  **highly cached optimized** - all the queries to the data base are cached during a period of time, we even have parts of HTML generated (fragments) so that it will load much faster. That’s why we ask you so many times to clean the cache. I know we are quite annoying, but it’s necessary.

### How can I change the duration?

You need to edit the file  **/oc/config/cache.php**  and where it says `‘default_expire’ => 3600, replace the number with any other value in seconds. By default, we set it to one hour duration, but you can easily increase it. It may work better in some cases than others.

### How can I disable it?

You can, but we do not recommend this. Just set the duration to  **“o”.**

### Enable real time

Do not set it to “o”, please! Just put 10 seconds at least, that means that 6 times per minute the server will actually get a hit.

###  Use other cache

As you can see, in that file we have a default value:  `'default' => 'file',`

This means that the cache is stored in the HD of your hosting. This has some advantages and disadvantages. Be careful not to run out of space at your hosting. HD normally are really slow (although now with SSD disks it’s getting better), so the best option would be to store it in the memory.

If your hosting has APC cache, just replace the previous line with:  `'default' => 'apc',`

This will work immediately and you will see that everything is faster. APC works in the memory of the server, which makes it lightning fast!

If you need to check other configurations like memcache, please check this guide of  [Kohana](http://kohanaframework.org/3.2/guide/api/Cache).

