# Weather Dashboard

A React-based weather dashboard application that displays current and historical weather information using OpenWeatherMap API and Chart.js for data visualization.

## Features

- Real-time weather data display
- Historical weather information visualization
- Interactive charts and graphs
- Responsive design
- City-based weather search

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- A modern web browser

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd weather-dashboard
```

2. Install dependencies:
```bash
npm install
```

3. Create an account on [OpenWeatherMap](https://api.openweathermap.org) and get your API key

4. Create a `.env` file in the root directory and add your API key:
```
REACT_APP_WEATHER_API_KEY=your_api_key_here
```

## Project Structure

```
weather-dashboard/
├── src/
│   ├── components/
│   │   └── WeatherChart.js    # Chart component for weather visualization
│   ├── pages/
│   │   └── WeatherDashboard.js # Main dashboard page
│   ├── services/
│   │   └── weatherServices.js  # API service for weather data
│   ├── App.js
│   └── index.js
├── public/
│   └── index.html
└── package.json
```

## Dependencies

- `axios`: For making HTTP requests
- `chart.js`: For creating charts and graphs
- `react-chartjs-2`: React wrapper for Chart.js
- `react`: Frontend framework
- `react-dom`: React rendering for web

## Running the Application

1. Start the development server:
```bash
npm start
```

2. Open your browser and visit:
```
http://localhost:3000
```

## Usage

1. Enter a city name in the search bar
2. View current weather information
3. Explore historical weather data through interactive charts
4. Toggle between different weather metrics (temperature, humidity, etc.)

## API Integration

The application uses the OpenWeatherMap API to fetch:
- Current weather data
- 5-day weather forecast
- Historical weather data

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ScreenShots
![Screenshot 2025-06-11 201337](https://github.com/user-attachments/assets/3516991b-cc7f-4ae8-8f3e-1ca980e15255)
![Screenshot 2025-06-11 201319](https://github.com/user-attachments/assets/0ef81763-77ec-4649-8a9c-a5f4935779e2)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenWeatherMap for providing the weather API
- Chart.js for the visualization library
- React team for the amazing framework
