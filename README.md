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


### Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

##### Available Scripts

In the project directory, you can run:

###### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

###### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

###### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

###### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

##### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

###### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

###### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

###### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

###### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

###### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

###### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)



