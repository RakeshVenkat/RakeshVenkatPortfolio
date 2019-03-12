# Welcome to my GitHub projects overview :)

## 1. An employee dashboard, for a firm interested in their employee records.
I built a single page dashboard for representing the employees of a company.

**_Technologies used_**:  
- Native web elements: `HTML`, `CSS`, `JavaScript`.
- Project was bootstrapped with the `create-react-app` boilerplate.
- Used data source from a flat file with employee records displayed in the form of a Grid.
- Created a modal for displaying extra user info, added Search and Sort by features.
- Application is responsive and hence can be used on mobility device resolutions.

[GitHub Source Code](https://github.com/rv-web-app-dev/employee-dashboard)  
[Try it out here!!](https://5wpnr48o2k.codesandbox.io/)

## 2. A Country search application.
I built a single page country search application with details about the country fetched from a back-end API.

**_Technologies used_**:  
- Project was bootstrapped with the `create-react-app` boilerplate.
- Used `BootStrap` for styling and responsive behaviour.
- Application supports only a Search bar. 
- Type any country name slowly to get the results.

[GitHub Source Code](https://github.com/rv-web-app-dev/CountrySearch)  
[Try it out here!!](https://n5lmnw9zvm.codesandbox.io/)

## 3. Website with native web-elments
I built a website for a food delivery service called **Omnifood**.

**_Technologies used_**:  
- Native web elements: `HTML`, `CSS`, `JavaScript`.
- Standard CSS Transitions are used for the hover effects.
- Used SVG icons and customized them using CSS styles.
- Utilized high quality images and appropriate content for a professional look.

[GitHub Source Code](https://github.com/rv-web-app-dev/omnifood)  
[Try it out here!!](https://vynpzyo12y.codesandbox.io)

## 4. Redux-Thunk examples
I created two example API integration usecases for demonstrating the usage of Redux thunk middleware in a React application. This can now be used as a boilerplate for making any API calls using Redux Thunk.
1. Real time weather data is obtained via [OpenWeather API](http://api.openweathermap.org/data/2.5/weather)
2. Random images from [UnSplash API](https://api.unsplash.com/)

**_Technologies used_**:  
- The application is bootstrapped with [Create React App](https://github.com/facebook/create-react-app) 
- `axios` is being used for making the API calls.
- `redux-thunk` as middleware.

[GitHub Source Code](https://github.com/rv-web-app-dev/redux-thunk-examples)  
[Try it out here!!](https://lp5lq7mzyl.codesandbox.io/images)

## 5. A Reusable ListWebView react component:
**Problem:** One of the most important usecase in most of the web applications is to render a list of items on the screen by reading from a data source (a file, an API call, etc..) The primary challenge we face is with the performance of the page as it needs to pull all the data at once and display that on the screen. We can use third party libraries to add pagination. However, is there a better way to solve this?   
**Solution:** By using the ListView component available in this project, the rendering of the data on the screen can be customized to show only certain sections of the data that can fit into the viewable area of the screen (termed as WebView). 
In this project I am using a mock flat file for the data, however this can be changed to fetch data from any data source (for ex, an API) 

**_Technologies used_**:  
- The application is bootstrapped with [Create React App](https://github.com/facebook/create-react-app) 
- Native javascript event hanlders for identifying the webview.
- Standard React lifecycle methods for mounting and demounting of components in web view.

[GitHub Source Code](https://github.com/rv-web-app-dev/ListWebView)  
