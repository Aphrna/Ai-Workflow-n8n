# 🌦 Weather Tracker with n8n


 What This Workflow Does
-  Runs automatically every day (or whenever you want)
-  Gets real-time weather data from **OpenWeatherMap**
-  Sends a neat, easy-to-read weather report to you
-  Fully customizable for your location and style

---

## 🛠 How It Works
1. **Schedule Trigger** – Picks the time you want the update (e.g., 8 AM).
2. **HTTP Request** – Calls the weather API to get fresh data.
3. **Data Cleanup** – Turns raw API data into something friendly.
4. **Notification Node** – Delivers it to email, Slack, or your phone.

---

## 📷 A Peek at the Workflow
![Workflow Diagram](workflow.png)

---

## 🚀 How to Set It Up
1. **Download** `weather-tracker.json` from this repo.
2. **Import into n8n**:
   - Open your n8n editor
   - Click **Import from file**
   - Select `weather-tracker.json`
3. **Get your API Key** from [OpenWeatherMap](https://openweathermap.org/api) (it’s free!).
4. Paste your API key into the HTTP Request node.
5. Set your preferred city and schedule.
6. Save & activate. That’s it. 🎉

---

## 📝 Example Daily Update
