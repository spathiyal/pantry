# Pantry


## Summary: 
##### The pantry app is a web-based application built using React for the frontend, Node.js with Express for the backend, and PostgreSQL as the database. It allows users to manage their pantry items, including adding, editing, and removing items. Additionally, users can select items from their pantry to find recipes based on the available ingredients.

### Add/Edit/Remove Items: 
##### Users can easily add new items to their pantry, edit existing items to update details such as quantity or expiration date, and remove items they no longer have. This functionality ensures that the pantry inventory is always up-to-date and accurate.

### Select Items to Find Recipes: 
##### Users can select items from their pantry to find recipes that they can make using the available ingredients. The app leverages this feature to suggest recipes based on what items the user currently has in their pantry. This helps users make use of ingredients they already have and reduces food waste.

##### This pantry app provides a convenient way for users to manage their pantry inventory, ensure nothing goes to waste, and discover new recipes based on the ingredients they already have at home.

##### API:
Edamam's Recipe Search API lets you integrate a recipe database and faceted recipe search into your websites or mobile applications.

The Edamam B2B API is accessed by sending HTTPS requests on specific URLs as described below. The base URL is https://api.edamam.com, and obtain the full URL by appending request’s path to the base URL, for example, https://api.edamam.com/api/recipes/v2.
Recipe Search API allows us to search through millions of web recipes and integrate this information into our mobile or web applications.


https://api.edamam.com/search?q=${search_query}&app_id=${APP_ID}&app_key=${APP_KEY}`


search_ query – It is a selection of pantry items selected by the user to the search bar. 


APP_ID and APP_Key are personal info, and they will be stored in environmental variables.


##### Stack used:
React
Node.js
Express.js
PostgreSQL


