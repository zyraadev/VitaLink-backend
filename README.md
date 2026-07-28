# VitaLink Backend

An AI-powered IoT Health & Activity Monitoring System developed as a **Computer Engineering Capstone Project**. This backend provides real-time data collection, storage, and intelligent analysis of students' vital signs and physical activity using IoT sensors and machine learning.

---

##  Project Overview

The **IoT Health & Activity Dashboard for Students** is a web-based monitoring system designed to help assess students' health and wellness through real-time physiological and activity data.

The system collects heart rate and motion information from wearable sensors connected to an ESP32 microcontroller. An **Isolation Forest** machine learning model analyzes incoming data to identify abnormal patterns that may indicate stress, fatigue, or unusual physical activity.

The dashboard presents both live and historical health data, allowing users to monitor trends and receive alerts when abnormal readings are detected.

---

##  Project Objectives

### General Objective

Develop a smart dashboard for student health monitoring with AI integration.

### Specific Objectives

- Capture real-time heart rate and motion/activity data.
- Transmit sensor data from the ESP32 to the backend server.
- Store collected sensor data in a database.
- Apply an Isolation Forest AI model to detect abnormal stress or activity patterns.
- Display live and historical health information through a web-based dashboard.
- Generate alerts for abnormal readings to support student health and wellness.

##  Features

-  Real-time heart rate monitoring
-  Motion and activity tracking
-  AI-based anomaly detection using Isolation Forest
-  Live dashboard visualization
-  Historical data analysis
-  Health alert notifications
-  IoT integration with ESP32

---

##  Technologies Used

### Hardware

- ESP32
- MAX30102 Heart Rate Sensor
- MPU6050 Motion Sensor

### Backend

- Python
- Flask / FastAPI
- REST API

- ### Database

- MySQL
- SQLite

### Artificial Intelligence

- Scikit-learn
- Isolation Forest Algorithm

- ### Development Tools

- Git
- GitHub
- Postman
