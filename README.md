# Weather-app

`Weather-app` lets users type in any location and get the current weather and also a forecast for the upcoming 4 days
![App Screenshot](https://github.com/ictee7/Webstack-Portfolio_Project/blob/main/weather-app/images/webapp.png)

# Table Of Contents

 * [Usage](#usage)
 * [Configuration](#configuration)
 * [Project Demo](#project-demo)
 * [Known Issues](#known-issues)
 * [Acknowledgements](#acknowledgements)

 ## Usage

 To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

 ```bash
# Clone this repository
$ git clone https://github.com/ictee7/Webstack-Portfolio_Project.git

# Go into the repository
$ cd Webstack-Portfolio_Project/weather-app

# Install dependencies
$ npm install

# Run the app
$ npm run serve
```

## Configuration

For the backend this app uses a weather API called [OpenWeatherMap](https://openweathermap.org/) . For the app to be fully functional follow these steps:

1. Create an account at [OpenWeatherMap](https://openweathermap.org/) for free.
2. Go to [API Key](https://home.openweathermap.org/api_keys) page to get the key.
3. In your projects folder navigate to `src/components` and edit the DaysWeather.vue file and paste your unique apiKey.
4. In your projects folder navigate to `src/components` and edit the Weather.vue file and paste your unique apiKey.

## Project Demo

To try out and see the app in action got to this site [WeatherApp](http://alx.appsols.tech)

## Known Issues

For those wanting to contribute, this app has the following issues:

1. The app is not responsive, that is if you open it on mobile browser it comes out distorted.
2. Fix button issue to automaticaly submit the search button once 'Enter' key is pressed.

## Acknowledgements

Thanks to [CodeWithSK](https://codewsk.com/) for the amazing [Tutorial](https://www.youtube.com/watch?v=YqsmqL8wHT8) on how to create this app