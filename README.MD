# Workout Tracker Application
#### This is a workout tracker application built with JavaScript, HTML, and CSS. It allows users to log their running and cycling workouts, displaying them on a map and in a list format.

# Features
### Running Workouts: Users can log running workouts, including distance, duration, and cadence (steps per minute). The application calculates and displays the pace (minutes per kilometer) for each running workout.

### Cycling Workouts: Users can log cycling workouts, including distance, duration, and elevation gain. The application calculates and displays the average speed (kilometers per hour) for each cycling workout.

### Geolocation: Utilizes the Geolocation API to determine the user's current position and displays it on an interactive map using Leaflet.js.

### Map Integration: Workouts are displayed as markers on the map, allowing users to click on them to see workout details.

### Data Persistence: User data is stored locally using the browser's localStorage API, ensuring that workouts persist between sessions.

# How to Use
### Log a Workout: Fill out the form with the type of workout (running or cycling), distance, duration, and additional details (cadence for running, elevation gain for cycling). Submit the form to log the workout.

### View Workouts: Logged workouts are displayed both on the map and in a list format below the form.

### Click on Workouts: Clicking on a workout marker on the map or in the list will zoom in on the workout's location on the map.

### Reset Data: To reset all logged workouts, click the reset button. This will clear all stored workout data.

# Technologies Used
## JavaScript
## HTML
## CSS
## Leaflet.js (for map integration)