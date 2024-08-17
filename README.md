# Weather App

This is a simple Weather Application built using HTML, CSS, and JavaScript. The app fetches real-time weather data from the OpenWeatherMap API based on the city entered by the user.

## Features

- Fetches current weather data for any city using the OpenWeatherMap API.
- Displays temperature, weather description, and additional details like "Feels like," humidity, and wind speed.
- Shows a weather icon corresponding to the current weather conditions.
- Handles errors gracefully and provides user feedback.

## Project Structure

- `index.html`: The main HTML file that contains the structure of the weather app.
- `style.css`: The CSS file that styles the weather app.
- `index.js`: The JavaScript file that handles the logic for fetching and displaying weather data.
- `README.md`: This file, providing an overview of the project.

## Getting Started

### Prerequisites

- You will need a modern web browser to run this project.
- An API key from [OpenWeatherMap](https://openweathermap.org/) to fetch the weather data.

### Setup

1. **Clone the repository** (if applicable):

    ```bash
    git clone https://github.com/Thamizh-mkce/weather-app.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd weather-app
    ```

3. **Replace the API key**:

    Open the `index.js` file and replace the `const apikey = "e7ab12968358ecf387dc7f0c96c98660";` line with your own OpenWeatherMap API key.

    ```javascript
    const apikey = "your_api_key_here";
    ```

4. **Open the `index.html` file** in your web browser:

    You can double-click on the `index.html` file, or open it using the following command in your terminal:

    ```bash
    open index.html
    ```

## Usage

- Enter the name of a city in the input field and click "Submit" to view the current weather data for that city.
- The app will display the temperature, weather description, an icon representing the current weather, and additional details such as "Feels like" temperature, humidity, and wind speed.
- If an error occurs (e.g., if the city is not found), an error message will be displayed.

## Customization

- **Styling**: Modify the `style.css` file to change the appearance of the app.
- **Additional Features**: Enhance the app by adding more weather details or implementing a search history.

## License

This project is open-source and available under the MIT License. You are free to use, modify, and distribute the code.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- Inspired by various weather app tutorials and projects found online.
