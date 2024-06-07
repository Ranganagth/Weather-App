# Weather App

This project is a simple weather application that fetches and displays weather information for a specified city using the OpenWeatherMap API. The app is built with HTML, CSS, and JavaScript, and includes jQuery for a gradient background animation.


## Features

- User can input the name of a city to get the current weather details.
- Displays temperature, humidity, pressure, and wind speed.
- Shows an icon representing the current weather condition.
- Animated background gradient using jQuery.

### Live Deom: [Weather-App](https://weather-app.xtgem.com/)

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- An API key from [OpenWeatherMap](https://openweathermap.org/).

## Setup

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/Ranganagth/Weather-App.git
   cd Weather-App
   ```

2. **Open the Project:**

   Open the `index.html` file in your favorite web browser.

## Configuration

1. **Get an API Key:**

   Sign up on [OpenWeatherMap](https://openweathermap.org/) and obtain an API key.

2. **Add the API Key:**

   In the `index.html` file, locate the following line and replace `YOUR_API_KEY` with your actual API key:

   ```javascript
   const apiSecret = "YOUR_API_KEY";
   ```

## Usage

1. **Enter City Name:**

   Type the name of the city in the input field.

2. **Fetch Weather Details:**

   Click on the search button to fetch and display the weather details.

## File Structure

```plaintext
weather-app/
│
├── images/
│   ├── humidity.png
│   ├── pressure.png
│   ├── search.png
│   ├── weather.png
│   ├── wind.png
│
├── index.html
├── style.css
```

### `index.html`

This file contains the HTML structure of the web app. It includes:
- A search field for the user to input the city name.
- Elements to display the weather details (temperature, city name, humidity, pressure, wind speed).
- A script for fetching data from the OpenWeatherMap API and updating the DOM with the fetched data.
- A script for animating the background gradient.

### `style.css`

This file contains the CSS for styling the web app. It includes styles for:
- General layout and design.
- Search field and button.
- Weather details display.
- Background gradient animation.

### `icons by:`
-  <a href="https://www.flaticon.com/free-icons/weather" title="weather icons">Weather icons created by GOWI - Flaticon</a>
-  <a href="https://icons8.com/" title="icons8">icons8</a>

## License

This project is open-source and available under the [MIT License](LICENSE).

---
