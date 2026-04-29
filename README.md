 
An automated workflow built with n8n that sends a daily weather 
update for Lahore to Gmail every morning at 8am.

 Tools Used:
n8n (workflow automation)
OpenWeatherMap API (weather data)
Gmail (notification delivery)

  How It Works:
1. Schedule Trigger fires every morning at 8am
2. HTTP Request fetches live weather from OpenWeatherMap
3. Data is formatted into a clean message
4. Gmail sends the weather report to my inbox

  How to Use:
1. Import the .json file into your n8n instance
2. Add your OpenWeatherMap API key
3. Connect your Gmail account
4. Activate the workflow!
