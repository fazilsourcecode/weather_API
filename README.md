# Weather API Application

This Java application fetches weather data using the Open Meteo API. It allows users to input a city name and retrieves the current weather conditions for that city. The application provides functionalities to display the current temperature, relative humidity, and wind speed.

## Prerequisites

Ensure you have the following installed:

- Java Development Kit (JDK) version 8 or higher
- Internet connection to fetch data from the Open Meteo API

## How to Use

1. Clone the repository or download the source code.
2. Compile the Java source file `weather_API.java`.
   ```bash
   javac weather_API.java
   ```
3. Run the compiled program.
   ```bash
   java weather_API
   ```
4. Follow the prompts to enter a city name. Type "No" to quit.
5. View the displayed weather data for the entered city.

## Features

- Fetches weather data using the Open Meteo API.
- Retrieves current temperature, relative humidity, and wind speed.
- Allows users to input multiple cities to check their weather.

## Dependencies

- [org.json.simple](https://code.google.com/archive/p/json-simple/): A simple Java toolkit for JSON processing.

## Usage Notes

- Ensure proper network connectivity to fetch data from the Open Meteo API.
- City names should be entered accurately to retrieve correct weather information.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Open Meteo for providing the weather data API.
- JSON Simple for JSON parsing capabilities.

---

Feel free to customize this README according to your project's needs. If you have any questions or suggestions, please [open an issue](https://github.com/your_username/your_repository/issues). Enjoy exploring the weather data!
