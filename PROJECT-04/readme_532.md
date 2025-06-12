# Weather App Project

## Project Overview
A dynamic weather application that displays current weather information and forecasts. The app uses modern web technologies to provide real-time weather data with a clean and intuitive user interface.

## Features
- Real-time weather information
- Weather forecast display
- Dynamic weather icons
- Temperature conversion
- Location-based weather
- Responsive design

## Technical Stack
- HTML5 for structure
- CSS3 for styling
  - Flexbox layout
  - Custom animations
  - Responsive design
- JavaScript for functionality
  - API integration
  - Dynamic content updates
  - Event handling

## Project Structure
```
PROJECT-04/
├── index.html           # Main application page
├── style.css           # Main stylesheet
├── script.js           # Main JavaScript file
├── cloudy.png          # Weather icons
└── image.png           # Additional assets
```

## Key Features
1. **Weather Display**
   - Current temperature
   - Weather conditions
   - Humidity levels
   - Wind speed
   - Weather icons

2. **User Interface**
   - Clean, modern design
   - Responsive layout
   - Interactive elements
   - Weather animations

3. **Functionality**
   - Location detection
   - Weather data fetching
   - Temperature conversion
   - Forecast updates

## Code Examples
```javascript
// Weather data fetching
async function getWeatherData(location) {
    try {
        const response = await fetch(`weather-api-url/${location}`);
        const data = await response.json();
        updateWeatherDisplay(data);
    } catch (error) {
        console.error('Error fetching weather:', error);
    }
}

// Weather display update
function updateWeatherDisplay(data) {
    document.getElementById('temperature').textContent = data.temperature;
    document.getElementById('condition').textContent = data.condition;
    updateWeatherIcon(data.condition);
}
```

## Setup and Running
1. Clone the repository
2. Open `index.html` in a web browser
3. Allow location access for local weather
4. View weather information

## Learning Objectives
- API integration
- Asynchronous JavaScript
- DOM manipulation
- Event handling
- Responsive design
- Error handling

## Screenshots
![Screenshot 2025-06-11 143556](https://github.com/user-attachments/assets/f34e1b9c-5436-46ce-98ab-cbcb5318c525)
![Screenshot 2025-06-11 143522](https://github.com/user-attachments/assets/485bbebd-1227-4875-b0dd-ba976a2d1a30)

## Future Improvements
- Add 5-day forecast
- Implement weather alerts
- Add more weather details
- Include weather maps
- Add user preferences
- Implement caching
