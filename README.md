# weather_app
Python Weather App 

A simple weather application built with Python that retrieves weather information using a weather API.

This project was developed as part of my Python learning journey, with a focus on API integration, handling HTTP requests, and working with external data.

Features:

- Retrieve weather information using a weather API.
- Display weather information returned by the API.
- Handle API requests and responses.
- Keep API credentials outside the source code.

Update this section to reflect the features actually implemented in your application.

Technologies Used:

- Python
- Weather API from OpenWeatherAPI
- Requests
- python-dotenv (if used)

Requirements

- Python 3
- A weather API key
= The dependencies listed in requirements.txt

Installation

1. Clone the repository

git clone https://github.com/YOUR_USERNAME/python-weather-app.git
cd python-weather-app

Replace YOUR_USERNAME with your GitHub username.

2. Create a virtual environment

python3 -m venv .venv

Activate it on macOS or Linux:

source .venv/bin/activate

3. Install dependencies

python -m pip install -r requirements.txt

4. Configure the API key

Create a .env file in the project root if your application uses environment variables.

Add your API key:

WEATHER_API_KEY=your_api_key_here

Never publish your actual API key.

5. Run the application

python weather.py

Replace weather.py if your main Python file has a different name.

Project Structure

python-weather-app/
├── weather.py
├── requirements.txt
├── .gitignore
├── .env.example
├── README.md
└── LICENSE

What I Learned:

- Making API requests with Python.
- Working with JSON responses.
- Handling external data.
- Managing Python dependencies.
- Using Git and GitHub to publish a project.



Author

Created by Mehdi Zermout.

