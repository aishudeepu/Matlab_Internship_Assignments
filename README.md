# Weather App 🌦️

A simple Python application that fetches and displays real-time weather information for any city using a weather API.

## Features

- Search weather by city name
- Displays temperature, humidity, and weather conditions
- User-friendly command-line interface
- Real-time weather updates

## Technologies Used

- Python 3
- Requests Library
- OpenWeatherMap API

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/weather-app.git
```

2. Navigate to the project folder:

```bash
cd weather-app
```

3. Install dependencies:

```bash
pip install requests
```

## Configuration

Create a file named `config.py` and add your API key:

```python
API_KEY = "your_api_key_here"
```

## Usage

Run the application:

```bash
python weather.py
```

Example:

```text
Enter city name: London

Weather in London
Temperature: 18°C
Humidity: 72%
Condition: Cloudy
```

## Project Structure

```text
weather-app/
│
├── weather.py
├── config.py
├── requirements.txt
└── README.md
```

## Future Improvements

- 7-day weather forecast
- Graphical user interface (GUI)
- Weather alerts and notifications

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Author

Your Name
GitHub: @yourusername
