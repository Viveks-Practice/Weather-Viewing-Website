# Weather Viewing Website

## Table of Contents

- [Overview](#overview)
- [Website Sections](#website-sections)
  - [Top Section - Today's Weather](#top-section---todays-weather)
  - [Middle Section - 7 Day Forecast](#middle-section---7-day-forecast)
  - [Bottom Section - Hourly Weather List](#bottom-section---hourly-weather-list)
- [How to install and run the project](#how-to-install-and-run-the-project)
  - [Retrieve the project URL](#retrieve-the-project-url)
  - [Clone the project](#clone-the-project)
  - [Install the required dependencies](#install-the-required-dependencies)
  - [Launch the website](#launch-the-website)

## Overview

Check out the weather forecast in your area with this neat web app! The application will request to use the current location of your device to show the current weather, the weather for the 7-day forecast, as well as the 7-day hourly weather in a detailed list! This project was written using javascript, html, and css!

![Weather Example Image!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/weather-app-image.png)

## Website Sections

The application is split into three components:

### Top Section - Today's weather

1. The top section displays the weather for today, including:

- An icon indicating the type of weather
- The current temperature
- High and low for today
- The "Feels like" high and low for today
- Wind speeds to be expected today
- Precipitation amount expected today

![Weather Example Image!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/weather-app-first-row.png)

### Middle Section - 7 Day Forecast

2. The middle section displays the weather for the 7-day forecast in boxed icons! Details include:

- The type of weather, indicated by an icon
- The expected temperature

![Weather Example Image!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/weather-app-second-row.png)

### Bottom Section - Hourly Weather List

3. The bottom section displays the weather in hourly increments, from now, to the next 7 days (scroll down for the upcoming hours)! Details shown at each hour include:

- Date and Time
- An icon indicating the type of weather
- The expected temperature
- What the temperature will "feel like"
- Expected wind speeds
- Precipitation

![Weather Example Image!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/weather-app-third-row.png)

## How to install and run the project

### Retrieve the project URL

1. Navigate to the repo's URL (https://github.com/Viveks-Practice/Weather-Viewing-Website)
2. Click the green code icon
3. Under Clone>HTTPS copy the url provided

![Github Repo Clone Link!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/git-clone-image.png)

### Clone the project

1. Open a cmd or terminal window, and navigate to the folder you wish to install the project's files
2. Type "git clone (the url of the repo copied from previous steps)"

```
git clone https://github.com/Viveks-Practice/Weather-Viewing-Website.git
```

![Clone the project!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/git-clone-success.png)

### Install the required dependencies

1. Navigate into the newly created folder with command

```
cd Weather-Viewing-Website
```

![Change Directory!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/cd-weather-viewing-app.png)

2. Install all required dependencies with npm

```
npm install
```

![Install Dependencies!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/install-dependencies.png)

### Launch the website

1. Run the website

```
npm run dev
```

![Run the website!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/run-the-program.png)

2. Click the URL provided to open the project webpage (or type it into a web browser)

```
 http://127.0.0.1:5173/
```

![Click the provided link!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/url-provided.png)

3. Click "Allow" when the website prompts you to use your device's location

![Click Allow!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/click-allow.png)

4. You now have access to the website! Scroll down to view the hourly weather of the next 7 days!

![Done!](https://github.com/Viveks-Practice/Weather-Viewing-Website/blob/main/images/done.png)
