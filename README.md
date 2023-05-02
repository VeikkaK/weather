This is my simple web application built using React that allows users to check the local weather. It utilizes an API key to fetch weather data and displays it in a user-friendly format. With this app, users can stay informed about the current weather conditions in their area.

- Display of current weather information
- Dynamic updating of weather data based on user's location
- User-friendly interface with clear and concise weather details

To install and run the Weather App locally, please follow these steps:

1. Clone the repository to your local machine:
git clone https://github.com/VeikkaK/weather.git

2. Navigate to the project's root directory:
cd weather

3. Install the dependencies using npm:
npm install

4. Obtain an API key from a weather data provider (e.g., OpenWeatherMap, AccuWeather). Make sure to sign up and get an API key following their documentation.

5. Create a `.env` file in the project's root directory and add the following line, replacing `<YOUR_API_KEY>` with your actual API key:
REACT_APP_API_KEY=<YOUR_API_KEY>

6. Start the development server:
npm start

7. Open your browser and navigate to `http://localhost:3000` to view the Weather App.
