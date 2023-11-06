# Weather-app

`Weather-app` lets users type in any location and get the current weather and also a forecast for the upcoming 4 days
![App Screenshot](https://github.com/ictee7/Webstack-Portfolio_Project/blob/main/weather-app/images/webapp.png)

# Table Of Content

 * [Usage](#usage)
 * [Configuration](#configuration)

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
2. Go to [API Key](https://home.openweathermap.org/api_keys) to get the key.
3. In your projects folder navigate to `src/components` and edit the DaysWeather.vue file and paste your unique apiKey
4. In your projects folder navigate to `src/components` and edit the Weather.vue file and paste your unique apiKey