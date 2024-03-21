# Weather Data API

The Weather Data API project provides a RESTful API for accessing weather-related information. It retrieves weather forecasts, current weather conditions, and historical weather data for specified locations. This API serves as a useful tool for developers to integrate weather data into their applications.

## Features

- **Weather Forecasts**: Retrieve forecasts for future weather conditions.
- **Current Weather Conditions**: Access real-time weather data for specified locations.
- **Historical Weather Data**: Retrieve historical weather data for past dates and locations.
- **Location-based Queries**: Get weather data for specific locations by providing latitude and longitude coordinates or city names.
- **Flexible Integration**: Easily integrate the Weather Data API into your applications using HTTP requests.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/rky5231/weather-data-api.git
    ```

2. Navigate into the project directory:

    ```bash
    cd weather-data-api
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables for API keys and configurations as specified in the `.env.example` file.

5. Run the Flask application:

    ```bash
    python app.py
    ```

6. Access the API endpoints using a tool like cURL, Postman, or by making HTTP requests from your application.

## Usage

1. Send HTTP GET requests to the API endpoints to retrieve weather-related information.
2. Use the provided endpoints `/forecast`, `/current`, and `/historical` to access different types of weather data.
3. Customize and extend the API as needed to suit your application's requirements.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests to suggest improvements, report bugs, or add new features.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/rky5231/weather-data-api/blob/main/LICENSE) file for details.
