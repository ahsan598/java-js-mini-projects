# 🌦️ Weather Web-App – JavaScript + OpenWeatherMap API


### 📌 Project Overview

This browser-based **Weather Application** allows users to search for any city and view its current weather information. It integrates the **OpenWeatherMap API** to display live **temperature, humidity, and wind speed**. The UI dynamically changes its background to reflect the current weather conditions, making the experience visually engaging and interactive. Built as part of a JavaScript mini-project series to practice **real-world API consumption and client-side updates**.

---

### 🎯 Objective

- Learn how to fetch and display data from third-party APIs using `fetch()`
- Practice working with JSON data and dynamic DOM updates
- Enhance UI design using condition-based styling
- Understand basic frontend app structure for real-time data applications


### 🧱 Architecture

- **HTML**: Base layout and input/search field
- **CSS**: Responsive styling and dynamic background changes
- **JavaScript**:
  - API integration via `fetch`
  - Parses and displays weather details
  - Updates DOM and background based on weather type

![weather-webapp](https://github.com/ahsan598/js-mini-projects/blob/master/JavaScript/weather-webapp/screenshots/weather-webapp.png)


### 📂 Project Structure

```sh
weather-webapp/
├── images/             # Images used in the game
├── app.html          # Main HTML structure
├── app.css           # Styling and background logic
├── app.js            # API logic and UI interaction
├── screenshots/
│   └──weather-webapp.png
└── README.md
```


### 🛠️ Technologies Used

| Technology       | Purpose                        |
|------------------|--------------------------------|
| HTML5            | Structure                      |
| CSS3             | Styling and layout             |
| JavaScript       | Logic, interactivity, API calls|
| OpenWeatherMap   | Weather data source            |
| VS Code          | Development                    |
| Browser Console  | Debugging                      |


### 🚀 Execution Steps

1. **Clone or Download** this repository
2. **Navigate to the folder** in your local machine
3. Replace the placeholder **API key in `app.js`** with your own from OpenWeatherMap:
   ```sh
   const apiKey = "YOUR_API_KEY_HERE";
   ```
4. **Open `app.html`** in any modern browser

```bash
open app.html   # macOS
start app.html  # Windows
```


### 📚 Key Concepts Explored

- API integration using `fetch()`
- JSON parsing and dynamic rendering
- Conditional DOM manipulation based on API data
- Responsive design with CSS
- Error handling for invalid input or network issues


### 🧠 Learnings

- Understood the flow of fetching and displaying real-time external data
- Learned how to handle asynchronous operations and loading states
- Faced minor layout responsiveness issues, resolved with media queries
- Debugged API rate limits and error handling for empty/invalid inputs


### 📝 Summary

This project showcases how simple web technologies can be used to build meaningful, real-world applications. The weather app not only strengthens JavaScript fundamentals but also introduces learners to REST APIs, async programming, and UI feedback design — all essential skills for frontend developers.
