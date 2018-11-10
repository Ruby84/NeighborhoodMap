# Neighborhood Map (React)



## Short description about your project: 

This is the neighborhood map project for Udacity's React course.Built a single map application using a React and the Google Maps API. The goal of this Project is Using CSS, HTML markup, React code, Nodejs,create-react-app, Bootstrap. This App serves as a neighborhood map that provides features like a search function that searches the map to find a specific restuarant. In addition, integrates a third-party data API and makes the app accessible and usable offline. Focus is appropriately managed allowing users to noticeably tab through each of the important elements of the page. Modal or interstitial windows appropriately lock focus.All content-related images include appropriate alternate text that clearly describes the content of the image.


## How to open/run the map: 
1. Please download/clone the repository [here!](https://github.com/Ruby84/NeighborhoodMap). 
2. open index.html in browser and you can run the map:
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](#running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](#deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## The required steps to use the app:

1.location filter: Includes a text input field that filters the map markers and list items to locations matching the text input.
2.List view:
A list-view of location names is provided which displays all locations by default, and displays the filtered subset of locations when a filter is applied.Clicking a location on the list displays unique information about the location, and animates its associated map marker ,bouncing
3.Map and Markers: Map displays all location markers by default, and displays the filtered subset of location markers when a filter is applied.Clicking a marker displays unique information about a location with image of that location on the page.

 
## how to cache the service worker in the production mood.

When available in the browser, the site uses a service worker to cache responses to requests for site assets. Visited pages are rendered when there is no network access.


## APIs used :

Application utilizes the Google Maps API and Foursquare API to get a info and image of particular location .All the  data requests are retrieved in an asynchronous manner using either the Fetch API.



