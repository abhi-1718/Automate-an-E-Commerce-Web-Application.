Description:

Flipkart is an e-commerce platform, and they have launched a new feature to search for a product in a particular category. Once the product is searched, Flipkart displays it as a list of product items. To enhance the performance of the application, Flipkart has implemented lazy loading. It displays only a few products that can come on the screen.

To display or load more products, the user must scroll down.

As a Test Engineer, you are expected to test this feature end-to-end.

 

Detailed Scenario:

-Navigate to the Flipkart homepage (https://www.flipkart.com/)
-Determine a page load time with a performance test
-Search for a product, say, “iPhone 13” under the “Mobile” category
-Check if the images are loaded and visible till the screen height only
-Check if the page has a scroll feature
-Check the frequency at which the content will be refreshed while scrolling
-Verify that the image is downloaded just before the user scrolls to its position and gets displayed in time
-Verify that it navigates to the bottom of the page
-Check whether different browsers and screen resolutions render it the same way
 

Tools Required:

-Selenium Library
-Eclipse IDE
-TestNG Library
-Maven
