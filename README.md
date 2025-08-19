# ⚡ Mini-Automation Projects

This repository contains a collection of small **Python automation projects** that use APIs, automation scripts, and browser interaction tools like **Selenium** to simplify everyday tasks.  
Each project demonstrates how Python can integrate with real-world services to fetch, process, and act on data automatically.

---

## 📂 Repository Structure

### 🔹 API-Automation
This folder contains projects that integrate with external APIs to fetch, process, and act on real-world data:

#### 🌧️ Rain Notifier
- **APIs Used:** [OpenWeather API](https://openweathermap.org/api), [Twilio API](https://www.twilio.com/).  
- Checks weather forecasts and sends an **SMS alert** if rain is predicted.  
- Example: "It might rain today ☔, don’t forget your umbrella!"  

#### 📈 Stock Notifier
- **APIs Used:** [Alpha Vantage API](https://www.alphavantage.co/), [NewsAPI](https://newsapi.org/), [Twilio API](https://www.twilio.com/).  
- Fetches stock data for Tesla (TSLA) and calculates daily price changes.  
- If change is significant, fetches related news and sends it via SMS.  

#### 📊 Habit Tracker
- **API Used:** [Pixela API](https://pixe.la/).  
- Tracks daily progress (e.g., DSA questions solved).  
- Records, updates, or deletes entries on a graph for visual tracking.  

#### 🏋️ Workout Tracker
- **APIs Used:** [Nutritionix API](https://www.nutritionix.com/business/api), [Sheety API](https://sheety.co/).  
- Logs workout details based on natural language input.  
- Stores exercise data (name, duration, calories burned) into a Google Sheet.  

#### 📧 Monday Quote Mail Sender
- **Tools Used:** Python `smtplib`, Gmail SMTP server.  
- Sends a **motivational quote every Monday** by email.  
- Picks a random quote from `quotes.txt` and delivers it to the recipient’s inbox.  

---

### 🔹 Automatic Job Applier
This standalone project automates job applications on **LinkedIn** using **Selenium WebDriver**.  

#### ✨ Features
- Logs into LinkedIn using stored credentials.  
- Navigates job listings from a predefined search URL.  
- Automatically fills in phone number and submits applications.  
- Skips complex, multi-step applications.  
- Keeps the browser open if the script crashes for debugging.  

#### 🛠️ Tech & Tools
- **Python 3.x**  
- **Selenium** (for browser automation)  
- Google Chrome & Chrome WebDriver  
- LinkedIn account  

#### 🚀 Usage
1. Install Selenium:
   ```bash
   pip install selenium
