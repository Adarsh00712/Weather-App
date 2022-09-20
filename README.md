# React Weather App 

## Task
***
Creating a Weather App using React JS which shows the weather update by calling an weather api using axios library . 
## Skills Required
***
Good Knowledge of React.js, Node.js, HTML & CSS. 
## Technologies
***
* [Visual Studio Code](https://code.visualstudio.com/Download) :Version 1.69
* [Node.js](https://nodejs.org/en/download/) Version 16.16.0 (includes npm 8.11.0).
* [Github](https://github.com/) Version 5.10.3 
* [Weather API](https://openweathermap.org/).

## Installation
***
Steps to install Visual Studio code:

* Click on [Visual Studio Code](https://code.visualstudio.com/Download) and install according to your operating system.
* Also install [Github Desktop](https://desktop.github.com/).
***
Steps to install Node.js:

* Click on [Node.js](https://nodejs.org/en/download/) and install according to your operating system.

***
Packages:

* Open Terminal of VS Code type `npx create-react-app weather-app` to install all folders and json files.
* After adding all the files and folders type `npm start` into the terminal to start your server.
* Now install axios by using `npm i axios` into the terminal and then import in App.js file to make a request to an API and return data     from an API.
***
Dependencies:

* Following dependencies will be added to package.json file by writing to terminal 'npm install express nodemon body-parser dotenv mongoose'.
```bash
 "dependencies": {
     "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "axios": "^0.27.2",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4"
  }
```
***
### Creating a Weather App Project using React Js, AXIOS and Weather API.
***
* Folder -> weather-app(src).
* Files -> 
#### "index.js": This is the file that will be called once we will run the project to render.
#### "App.js": Use for building our webpage and imporing the weather api.
#### "index.css": For designing our webpage using Css.
* Finish

## Execution
***
* Start building our webpage in App.js file in function App using JSX format. 
* In container class we make our top and bottom of our webpage.
* Using useState hook for getting data and location.
* Getting our API link from openweathermap website and using in our url by getting using axios.
* To connect with API make a search function with 'searchLocation' function and set location.
```bash
 <div className="search">
        <input
          value={location}
          onChange={event => setLocation(event.target.value)}
          onKeyPress={searchLocation}
          placeholder='Enter Location'
          type="text" />
      </div>
```
* Now getting values from API by targeting data items by using weather.json file.


## Result
***
* The calling of weather api is successful into our webpage using axios.

![Weather App](https://github.com/Adarsh00712/Weather-App/blob/main/Screenshots/1.png)

***
![Weather Appps://github.com/Adarsh00712/Weather-App/blob/main/Screenshots/2.png)

***
![W] ts://github.com/Adarsh00712/Weather-App/blob/main/Screenshots/3.png)

***
![REST API](https://github.com/Adarsh00712/Weather-App/blob/main/Screenshots/4.png)

***
![REST API](https://github.com/Adarsh00712/Weather-App/blob/main/Screenshots/6.png)

## Support
***
For Support email at adarshdwivedi2@gmail.com

