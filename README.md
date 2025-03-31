# MyWeatherApp-JSP

## 🌦️ About the Project
MyWeatherApp-JSP is a web application that provides real-time weather updates using the OpenWeather API. Built using JSP, Servlets, HTML, CSS, and JavaScript, this project helps users get accurate weather information for any location.

## 🚀 Features
- 🌍 Get real-time weather details for any city
- 📌 Search location-based weather updates
- 🌡️ Display temperature, humidity, wind speed, and weather conditions
- 🎨 Responsive UI with CSS for a better user experience
- 🔗 Integrated OpenWeather API

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Java (JSP & Servlets)
- **Database:** Not required (API-based data fetching)
- **API Used:** OpenWeather API

## 📂 Project Structure
```
MyWeatherApp-JSP/
│── .idea/
│── src/main/
│── images/
│── WEB-INF/
│── build/classes/MyPackage/
│── index.html
│── index.jsp
│── method.java
│── myScript.js
│── style.css
│── weather-logo.png
│── README.md
```

## ⚙️ Installation Guide
### Prerequisites
- Install **JDK 8+**
- Install **Apache Tomcat 9+**
- Setup an IDE like **Eclipse** or **IntelliJ IDEA**

### Steps to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/abhishekparmal/MyWeatherApp-JSP.git
   ```
2. Open the project in your IDE.
3. Configure Apache Tomcat in the IDE.
4. Deploy and run the application on the server.
5. Open `http://localhost:8080/MyWeatherApp-JSP/index.jsp` in your browser.

## 📜 API Configuration
1. Register on **OpenWeather** and get an API key.
2. Replace `<YOUR_API_KEY>` in the `myScript.js` file:
   ```js
   const apiKey = "<68e398aebfd3b1b1f3891c14c2340431>";
   ```

## 📷 Screenshots
_Add some screenshots here_

## 📌 Future Enhancements
- 🌍 Add geolocation-based weather detection
- 📊 Show weekly and hourly forecasts
- 🎨 Improve UI with animations

## 📝 License
This project is **open-source** and free to use.

---
🚀 Developed by **Abhishek Parmal**
