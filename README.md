* Weather Forecast Web App *
----------------------------
A simple and interactive web application that displays weather forecasts using the 7Timer! API, built with HTML, CSS, JavaScript, and PapaParse for dynamic CSV parsing.

---

# Features

* 🌍 Select cities from a dropdown (populated from a CSV file).
* 📍 Enter custom latitude and longitude coordinates.
* ☁️ Fetch real-time weather forecasts using the **7Timer! API**.
* 🔄 Handle asynchronous data loading and display.
* 📄 Built-in CSV parsing with **PapaParse**.

---

# Technologies Used

* HTML5 & CSS3 – UI structure and styling
* JavaScript (ES6) – DOM manipulation and async API handling
* PapaParse.js – For parsing and loading city data from a CSV file
* 7Timer! API – For retrieving civil weather forecast data
* Live Server – For local development and testing

---

# Project Structure

```
weather-forecast-app/
├── index.html
├── css/
│   └── master.css
├── js/
│   └── main.js
├── city_coordinates.csv
└── README.md
```

---

# Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-forecast-app.git
   cd weather-forecast-app
   ```

2. Open the project in VS Code and run with Live Server:

   * Install [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
   * Right-click on `index.html` → "Open with Live Server"

3. Or run with Python (optional):

   ```bash
   python -m http.server
   ```

4. View in browser:
   Visit `http://localhost:5500` (or whatever port your server runs on).

---

## 🧪 Sample CSV Format

```csv
name,latitude,longitude
New York,40.7128,-74.0060
London,51.5074,-0.1278
Tokyo,35.6895,139.6917
```

---

## 🧐 What I Learned

* Integrating public APIs into web apps
* Working with CSV data using PapaParse
* Handling asynchronous JavaScript operations
* Debugging file load issues and MIME type errors

---

