# Welcome to my github projects

## 1. Website with native web-elments
I built a website for a food delivery service called **Omnifood**.

**_Technologies used_**:  
- Native web elements: `HTML`, `CSS`, `JavaScript`.
- Standard CSS Transitions are used for the hover effects.
- Used SVG icons and customized them using CSS styles.
- Utilized high quality images and appropriate content for a professional look.

[Github Source Code](https://github.com/rv-web-app-dev/omnifood)  
[Try it out here!!](https://vynpzyo12y.codesandbox.io)

## 2. Redux-Thunk examples
I created two example API integration usecases for demonstrating the usage of Redux thunk middleware in a React application. This can now be used as a boilerplate for making any API calls using Redux Thunk.
1. Real time weather data is obtained via [OpenWeather API](http://api.openweathermap.org/data/2.5/weather)
2. Random images from [UnSplash API](https://api.unsplash.com/)

**_Technologies used_**:  
- The application is bootstrapped with [Create React App](https://github.com/facebook/create-react-app) 
- `axios` is being used for making the API calls.
- `redux-thunk` as middleware.

[Github Source Code](https://github.com/rv-web-app-dev/redux-thunk-examples)  
[Try it out here!!](https://lp5lq7mzyl.codesandbox.io/images)

## 3. A Reusable ListWebView react component:
**Problem:** One of the most important usecase in most of the web applications is to render a list of items on the screen by reading from a data source (a file, an API call, etc..) The primary challenge we face is with the performance of the page as it needs to pull all the data at once and display that on the screen. We can use third party libraries to add pagination. However, is there a better way to solve this?   
**Solution:** By using the ListView component available in this project, the rendering of the data on the screen can be customized to show only certain sections of the data that can fit into the viewable area of the screen (termed as WebView). 
In this project I am using a mock flat file for the data, however this can be changed to fetch data from any data source (for ex, an API) 

**_Technologies used_**:  
- The application is bootstrapped with [Create React App](https://github.com/facebook/create-react-app) 
- Native javascript event hanlders for identifying the webview.
- Standard React lifecycle methods for mounting and demounting of components in web view.

[Github Source Code](https://github.com/rv-web-app-dev/ListWebView)  
