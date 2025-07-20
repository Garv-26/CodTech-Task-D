NAME: GARV PUROHIT INTERNSHIP @ CODETECH IT SOLUTIONS DOMAIN: ANDROID DEVELOPMENT DURATION: 20th June 2025 to 20th July 2025 
Overview of the Projects:
# Fitness Tracker App
Overview
This project is a Fitness Tracker Android app built as part of the CODTECH Internship Task 4. The app tracks steps, distance, and calories burned using Android’s built-in sensors. It also includes real-time updates and data visualization of user activity using charts.

# Features
Real-time step counting using Android's Step Counter Sensor
Live distance tracking (based on average stride length)
Calorie estimation based on number of steps
Graphs showing past activity data using MPAndroidChart
Simple and clean user interface

# Tech Stack
Language: Kotlin
Platform: Android (API Level 21+)
Sensor: Step Counter Sensor (TYPE_STEP_COUNTER)
Data Visualization: MPAndroidChart Library
IDE: Android Studio

# Screens
Home screen displaying:
Step count
Distance walked
Calories burned
Chart showing step count over past days

# Installation
Clone the repository:
git clone https://github.com/your-username/fitness-tracker-app.git
Open in Android Studio.

Build and run on a real device (sensor support required).

# Permissions
No runtime permissions required as the step counter is sensor-based and does not use GPS or storage.

# Libraries Used
MPAndroidChart – for line chart visualization
Distance and Calories Formula
Distance (m) = Steps × 0.78 (average stride length)
Calories (kcal) = Steps × 0.04 (approximate value)

# Notes
The app does not use GPS, so it consumes less battery.
Best tested on physical devices with hardware step sensors.
Data is reset on device restart unless saved using local storage.

# Future Improvements
Add daily history with Room Database
Allow user profile input (weight, height) for accurate calculations
Add progress notifications and reminders
