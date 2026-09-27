# Smart Dual Quality Analyzer

## 🚀 Project Overview

**Smart Dual Quality Analyzer** is an IoT-based smart quality monitoring system designed for real-time analysis of quality parameters using sensor data and a digital monitoring interface.

The system provides a user-friendly platform for selecting a sample, connecting the quality-analysis device, performing a scan, viewing live readings, generating quality results, and maintaining test history.

## 🎯 Objectives

* Enable fast and easy quality analysis
* Monitor quality parameters using sensors
* Provide real-time sensor readings
* Identify possible adulteration or quality issues
* Maintain test history and generated reports
* Provide a simple and user-friendly interface

## ✨ Key Features

* 🔐 User Login and Account Creation
* 🌐 Multi-language interface
* 🔌 IoT device connection interface
* 🥛 Milk quality analysis
* 📊 Live sensor readings
* 🤖 AI-based quality assessment interface
* 📋 Quality score and risk analysis
* 💡 AI recommendations
* 📝 Test history
* 📄 Automatic report generation
* 🌓 Light and Dark mode
* 📱 Responsive web interface

## 🥛 Milk Quality Analysis

The system supports milk quality analysis for parameters such as:

* Fat
* SNF
* Water dilution
* Urea
* pH
* Possible adulteration indicators

The application describes the milk analysis workflow as selecting a sample, inserting/detecting the sample, acquiring sensor data, processing the data, and generating a quality assessment.

## 🔧 Technology Used

* HTML5
* CSS3
* JavaScript
* Tailwind CSS
* Lucide Icons
* IoT Sensors
* ESP32 / IoT Device Interface
* AI/Data Analysis Interface

The current web interface uses Tailwind CSS through its CDN and Lucide icons.

## 📂 Project Structure

```text
Smart-Dual-Quality-Analyzer/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   ├── translations.js
│   └── sensor.js
│
├── assets/
│   ├── images/
│   └── icons/
│
└── hardware/
    └── esp32/
```

> Note: Keep the structure above only if you have separated the original single HTML file into these files.

## 🔄 System Workflow

```text
User Login
    ↓
Dashboard
    ↓
Connect IoT Device
    ↓
Select Sample
    ↓
Insert / Detect Sample
    ↓
Start Scan
    ↓
Live Sensor Readings
    ↓
Data Processing
    ↓
Quality Assessment
    ↓
Risk Analysis
    ↓
AI Recommendation
    ↓
Save Test
    ↓
Generate Report
```

## 📊 Quality Assessment

The system provides:

* Quality Score
* Risk Analysis
* Quality Status
* Adulteration Detection
* AI Recommendation
* Test History

The interface includes a report table with quality-related readings and generated report information.

## 🌐 User Interface

The application includes:

* Home Dashboard
* Scan Section
* Report Section
* Bottom Navigation
* Theme Toggle
* Login / Signup
* Device Connection
* Sample Selection
* Result Dashboard

The current implementation contains Home, Scan and Report navigation and a responsive bottom navigation interface.

## 🏆 Smart India Hackathon

**Project:** Smart Dual Quality Analyzer
**Event:** Smart India Hackathon (SIH) 2026

## 👥 Project Team

Developed as an IoT-based smart quality monitoring solution for the Smart India Hackathon.

## 📌 Future Scope

* Real ESP32 hardware integration
* Cloud-based data storage
* Mobile application
* Advanced machine-learning models
* More adulterant detection
* Remote monitoring
* Automated alerts
* Historical analytics dashboard

## ⚠️ Project Status

This repository contains the prototype/source code of the Smart Dual Quality Analyzer system developed for demonstration and hackathon purposes.

---

### 📄 License

This project is developed for educational, research, and hackathon purposes.
