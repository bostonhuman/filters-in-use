# Filters In Use

This example selects all list items and then uses different filters to select a subset of the items from the list to work with. The example used both the filtering methods as well as the CSS style pseudo selector :not(). Once the filters have selected a subset of the list items, other jQuery methods are used to update them.
 
# Components that make the app run

* The .filter() method finds the last list item with a class attribute whose value is hot. It then removes that value from the class attribute.
* The :not() selector is used within the jQuery selector to find li elements without a value of hot in their class attribute and adds a value of cool.
