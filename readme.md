# Explaination of test

## requirements
-  Multiple stores (tables)

-  A few stores (tables) with several thousand records, statistics related to other stores (tables).

-  Loading the list in a page, opening an item in that list to a new page that can collect other data and display data.

-  Anything that can also show – add/removal/updates to a store (table). Similar to a directory. Showing how they can add a name/phone number. Update the record if the phone number changes etc.

-  Be mindful of style. We would like to see something as a finished product.

The basic principle of the assignment is to test adds/inserts/deletes, paging through data, and updating it with some basic UI thought process. Beyond that, you have creative control.

# Final Product
There are two stores created when page first load in browser - products and orders
In products store there is reference object with orders store ids with other values like name and description 
In orders store have values like name and description

Products list table shows product values with three action button - add order to product, update product description and remove product
Orders list table shows order values with two action - update order and remove order

There is Add button in both pages with products list table and orders list table to add new product or new order respectively.
In orders list page, product information also available to show users about orders related to which products.

# Languages and technology used
- HTML, jQuery, Bootstrap, Javascript, CSS, IndexedDB

# Conclusion
This test is done by lots of research on indexedDB as i didn't have any knowledge about it and then passing through many errors and solving them one by one and finally have finished product as it looks.

There is endless opportunity to optimize the code and adding new features in it but I tried whatever possible from my side in few hours to complete test.
