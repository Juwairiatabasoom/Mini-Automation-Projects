# ⚡ Mini-Automation Projects

A collection of small Python projects that use **APIs** and automation to simplify daily tasks.  
This repository is designed as a learning resource for API integration, automation, and task scheduling using Python.

---

## 📂 Repository Structure

### 🔹 API-Automation
This folder contains projects that integrate with external APIs to fetch, process, and act on real-world data:

#### 🌧️ Rain Notifier
- Uses the **OpenWeather API** to check weather forecasts.  
- Sends an **SMS alert** via **Twilio API** if rain is predicted, reminding you to carry an umbrella.  

#### 📈 Stock Notifier
- Fetches stock data from the **Alpha Vantage API** for Tesla (TSLA).  
- Calculates the price difference between days and, if significant, fetches related news from **NewsAPI**.  
- Sends alerts with news headlines via **Twilio API**.  

#### 📊 Habit Tracker
- Uses the **Pixela API** to track daily progress on habits (e.g., DSA questions solved).  
- Records data in a visual graph, with options to add, update, and delete daily entries.  

#### 🏋️ Workout Tracker
- Uses the **Nutritionix API** to process workout details based on natural language input.  
- Logs workout info (exercise, duration, calories burned) into a Google Sheet via the **Sheety API**.  

#### 📧 Monday Quote Mail Sender
- Sends a **motivational quote every Monday** via Gmail’s SMTP server.  
- Randomly selects a quote from `quotes.txt` and emails it to the recipient.  

---

### 🔹 Automatic Job Applier
- Automates searching and applying for jobs online.  
- Uses scripts to filter jobs and auto-submit applications with stored user data.  

---

## 🛠️ Tech & Tools
- **Python 3.x**  
- APIs: OpenWeather, Twilio, Alpha Vantage, NewsAPI, Pixela, Nutritionix, Sheety  
- Libraries: `requests`, `datetime`, `smtplib`, `twilio`  

---
   git clone https://github.com/your-username/mini-Automation-Projects.git
   cd mini-Automation-Projects
