![Weather Dashboard Cover](weather-dashboard\f93b01f3-cbb7-4bc9-9772-23a389b31309.webp)

# Weather Dashboard

A weather dashboard that fetches real-time weather data for multiple cities using the OpenWeather API and stores the data in AWS S3 also shows the results on terminal.


## Table of Contents
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)


## Features
- Fetches weather data for multiple cities.
- Stores weather data in an AWS S3 bucket.
- Displays temperature, humidity, and weather conditions.

## Setup

### Prerequisites
- Python 3.10 or higher
- AWS account
- OpenWeather API key
- AWSCLI

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/DarFaizan18/weather-dashboard.git

2. Navigate to the project directory:
   ```bash
   cd weather-dashboard

3. Install dependencies:
   ```bash
   pip install -r src/requirements.txt

4. Configure environment variables in src/.env:
   ```bash
   OPENWEATHER_API_KEY=your_api_key
   AWS_BUCKET_NAME=your_bucket_name

## Usage
1. Run the script:
   ```bash
   python src/weather_dashboard.py

2. View the fetched weather data in your terminal.

3. Check the AWS S3 bucket for saved weather data files.

### 7. **Technologies Used**
```markdown
## Technologies Used
- Python
- Boto3 (AWS SDK for Python)
- OpenWeather API
- AWS S3

## Contributing
Feel free to contribute to this project by:
- Reporting bugs
- Suggesting features
- Submitting pull requests

For major changes, please open an issue first to discuss what you would like to change.


## License
This project is licensed under the MIT License. See `LICENSE` for details.


