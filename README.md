# Asynchronous-JavaScript-RESTful-APIs

# 🌤 Real-Time Weather Dashboard

## 📌 Project Overview

The Real-Time Weather Dashboard is a responsive web application developed using HTML, CSS, and JavaScript. This project fetches live weather information from a public REST API and dynamically displays weather details based on the city entered by the user.

The application uses modern asynchronous JavaScript concepts such as Fetch API and async/await to retrieve and process JSON data in real time.

This project was developed as part of an internship task focused on asynchronous JavaScript and RESTful API integration.

---

# 🚀 Features

* Fetches real-time weather data using Fetch API
* Uses asynchronous JavaScript with async/await
* Displays live weather metrics dynamically
* Search weather by city name
* Handles invalid city and network errors
* Responsive modern UI design
* Loading state implementation
* Dynamic weather icons
* Keyboard support using Enter key
* Mobile-friendly dashboard

---

# 🛠 Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Fetch API
* Async/Await
* REST API
* OpenWeatherMap API

---

# 📂 Project Structure

```bash
weather-dashboard/
│
├── index.html
├── style.css
└── script.js
```

---

# ⚙️ How the Project Works

## 1. User Input

The user enters a city name in the search input field.

## 2. API Request

The application sends a request to the OpenWeatherMap REST API using the Fetch API.

```javascript
const response = await fetch(url);
```

## 3. JSON Data Processing

The JSON response received from the API is parsed dynamically to extract weather information such as:

* Temperature
* Humidity
* Wind Speed
* Pressure
* Weather Description

Example:

```javascript
data.main.temp
data.wind.speed
data.weather[0].description
```

## 4. Dynamic Rendering

The weather information is displayed dynamically on the dashboard using JavaScript DOM manipulation.

## 5. Error Handling

The project implements proper error handling using:

```javascript
try
catch
finally
```

It handles:

* Invalid city names
* Empty search input
* Failed network requests

---

# 🌐 REST API Used

## OpenWeatherMap API

The project uses the OpenWeatherMap API to fetch live weather data.

API Endpoint Used:

```bash
https://api.openweathermap.org/data/2.5/weather
```

---

# 📱 Responsive Design

The dashboard is fully responsive and works properly on:

* Desktop
* Tablet
* Mobile Devices

---

# 📸 Screenshots

##  Main Dashboard

<img width="1710" height="988" alt="Screenshot 2026-05-29 at 9 46 44 AM" src="https://github.com/user-attachments/assets/503158d1-1ad2-45d8-a570-a911edf3318d" />

---

##  Weather Search Result

<img width="1707" height="987" alt="Screenshot 2026-05-29 at 9 45 44 AM" src="https://github.com/user-attachments/assets/1f9ae6f0-6b0c-4ede-b6d8-0784e5433e93" />

---

##  Invalid City Error Handling

<img width="1699" height="983" alt="Screenshot 2026-05-29 at 9 46 00 AM" src="https://github.com/user-attachments/assets/46ae9c65-ca60-49a1-9f61-4fc0923f1658" />

---

##  Empty Search Error Handling

<img width="1710" height="983" alt="Screenshot 2026-05-29 at 9 47 01 AM" src="https://github.com/user-attachments/assets/b1debaf7-2002-4478-bf4e-4983a5cb5968" />

---

# 📚 Learning Outcomes

Through this project, the following concepts were learned and implemented:

* Asynchronous JavaScript
* Fetch API
* Async/Await
* REST API Integration
* JSON Parsing
* Error Handling
* DOM Manipulation
* Responsive Web Design

---

# ▶️ How to Run the Project

1. Download or clone the repository
2. Open the project folder in VS Code
3. Add your OpenWeatherMap API key in `script.js`
4. Open `index.html` using Live Server

---

# 👨‍💻 Author

Developed as part of Internship Task Submission.
