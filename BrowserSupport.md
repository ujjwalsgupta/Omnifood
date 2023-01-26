<!--! Texts & Optimization  -->

<!--todo: 1. Browser Support -->
<!--? Browser Support means, how different browser supports different CSS properties. -->

<!--* Go to https://caniuse.com to see which browsers can support the modern css properties & how much percentages of people use it. -->

<!--* Prefix-ing: It is a method in which a prefix is added before the css-property, so that the browser that merely supports that property can also support it. The prefix is usually always given on the browser description on https://caniuse.com. -->

<!--? Example: -->
<!--* backdrop filter is a css property which is used to blur the content of any component which is beside the opened content.
  <!--* We can see on https://caniuse.com that safari only supports this css property if we include the prefix -webkit-.
  <!--* Don't forget to check the css-properties on https://caniuse.com. If any main browser is not supporting it (even there's no prefix) then, try setting the values which all browsers can support. -->

/\***\*\*\*\*\*\*\***\*\*\***\*\*\*\*\*\*\***\*\*\*\*\***\*\*\*\*\*\*\***\*\*\***\*\*\*\*\*\*\***/

<!--todo: 2. Lighthouse Test -->
<!--? Lighthouse test is done to check how much accessible, performance oriented, seo oriented, best practices are used in your website. -->

<!--* Always check Lighthouse after building your website to ensure best practices.
<!--* The results before hosting (local host) & after hosting the website to the internet are often different. So, check if there's any bad practices used in website in all four terms, -->

1. Performance Oriented
2. Accessibility
3. Search Engine Optimization
4. Best Practices

/\***\*\*\*\*\*\*\***\*\*\***\*\*\*\*\*\*\***\*\*\*\*\***\*\*\*\*\*\*\***\*\*\***\*\*\*\*\*\*\***/

<!--todo: 2. Image Optimization -->

STEP 1. <!--? The actual image size should always be double the size that will actually going to be displayed on our webpage.-->

<!--* On hovering on image inside developer tools,
<!--* We can get the actual size of the image (Intrinsic size)
<!--* Also the displayed size of the image on the webpage size (Rendered size) -->

<!-- As per STEP 1, make sure that
! Rendered Size = Intrinsic Size / 2  -->

STEP 2. <!--? To reduce file/image size, so that images can render faster on the web, we will use https://squoosh.app. -->

<!--* Firstly, go to Network tab inside developer tools, reload the page & chech-out for MBs of resources. Currently in omnifood project, its 3.7 MB which is too slow to render. -->
<!--* Now, go to squoosh, note, we only want pngs & webp extension images for our websites.
<!--* Convert to Oxipng for pngs & convert to webP for .webp images. -->
<!--* Always try to decrease the percentage sizes as much as possible. Look for the essential differences in the original & modified image & try to minimize it.-->

<!--! webP is the best image format to use for website images because they take low storage, faster time to reload, high performing. -->
<!--? We can see that in https://caniuse.com, the webp extention does not quite work on below 14 - 15.6 version of safari. -->
