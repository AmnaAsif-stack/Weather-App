Weather and Chatbot App
This project is a weather application with the OpenWeather API to fetch information on questions related to the weather and the Gemini API for other questions. It will include weather data, filter functions for different conditions of the weather, and a chat interface to answer questions about the weather and other topics.

Features
Weather Forecast: It retrieves the current weather and 5-day forecast for a given city or based on the user's locale.
The open-ended chatbot performs the OpenWeather API-based weather-related queries along with Gemini API-based non-weather-related queries.
Modern, User-Friendly Interactive UI: The application comes integrated with background animation and weather-based color transitions.
The user can filter the weather data as per rainy days or highest temperatures and sort the temperatures in ascending or descending order.
Application Fully Responsive: This application is fully responsive and adjusts according to the size of the screen.
Technologies Used
HTML/CSS: Used to style and structure the application, including a video background with themes dependent on weather conditions.
JavaScript: Handling the interactions with APIs; chatbot functionality and filtering of information.
OpenWeather API: Retrieves the data regarding the weather of locations.
Gemini API: Used for the processing of non-weather-related query of the chatbot.
Project Files
FrontedLayout.html: This is the main HTML file which contains the structure for the chatbot, displaying weather, and UIs.
script.js: The associated JavaScript file responsible for handling calls with APIs, handling chatbots logic, and rendering the data for weather.
style.css: Defines the visual appearance of the application, which embeds it with backgrounds, animations, and transitions.
Setup Instructions
To run this application locally, follow these instructions.

1. Prerequisites
Install the following on your computer:

A modern web browser (Chrome, Firefox, Safari, etc.)
A text editor or IDE (VSCode, Sublime, etc.)
2. OpenWeather API Key
Go to OpenWeather.
Obtain your API key from the dashboard.
Replace the placeholder in script.js using your OpenWeather API key:
javascript
Copy code
const apiKey = 'your-openweather-api-key'; // OpenWeather API key
3. Gemini API Key
Get an API key from Gemini by following the instructions.
Replace the placeholder in script.js with your Gemini API key:
javascript
Copy code
const geminiApiKey = 'your-gemini-api-key'; // Gemini API key
4. Running the App
Download all the project files (FrontedLayout.html, script.js, style.css).
Open the FrontedLayout.html file in your web browser.
5. Using the App
Weather Queries: Write queries like "What is going to happen in London?" or "Is it raining in Paris?"
General Queries: You can write queries that are not weather-related like "What is the capital of France?"
Troubleshooting
Have you put the API keys correctly in script.js?
If the weather data or chatbot responses aren't working, inspect the browser console for error logs
Make sure your internet works before making an API request.
Future Improvements
Add more conversational features to the chatbot.
Make the design even more interactive to an immersive user experience.