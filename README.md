# Weather_Data_Pipeline
# 🌤 Weather Data Collection & Storage with Python & MySQL

This project fetches real-time weather data for multiple cities using the [OpenWeatherMap API](https://openweathermap.org/api), processes it using Python, and stores it in a MySQL database for further analysis or dashboarding.

---

## 📌 Project Features

- Fetches weather data (temperature, humidity, and description) for a list of cities.
- Uses Python's `requests` and `datetime` modules for API handling and timestamping.
- Inserts structured data into a MySQL database for analysis and reporting.
- Logs successful and failed API calls.
- Easy to expand for scheduling (e.g., cron jobs or Python schedulers).

---

## 🛠 Tech Stack

- **Language:** Python  
- **API:** OpenWeatherMap API  
- **Database:** MySQL  
- **Libraries Used:** `requests`, `mysql.connector`, `datetime`

---

## 🏗 Database Schema

Table: `weatherdata`

| Column       | Type          |
|--------------|---------------|
| city         | VARCHAR       |
| temperature  | FLOAT         |
| humidity     | INT           |
| description  | VARCHAR       |
| timestamp    | DATETIME      |

---

## 🚀 How to Run

 **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/weather-data-python-mysql.git
   cd weather-data-python-mysql

🌍 Cities Included
   #Frankfurt
   #Berlin
   #Munich
   #Sargodha
   #Schmitten
   #Wurzburg
   #Steinbach
   #Lancaster

You can easily edit the city list in the script to include your desired locations.



