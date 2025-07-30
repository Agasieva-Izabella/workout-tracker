# workout-tracker
Mapty is a geolocation-based web app that allows users to log and visualize their running and cycling workouts on an interactive map using the Leaflet.js library.

A map-based workout logging app built with JavaScript and Leaflet.js. Users can track their running and cycling workouts by clicking on the map, filling in workout details, and viewing their workout history.
What the App Does:

- Detects your current location using the Geolocation API
- Displays a Leaflet.js map centered on your location
- Lets you log running or cycling workouts by clicking anywhere on the map
- Stores workout data including:
  - Type (running or cycling)
  - Distance
  - Duration
  - Cadence (for running)
  - Elevation gain (for cycling)
- Automatically calculates and displays:
  - **Pace** for running
  - **Speed** for cycling
- Shows workouts in a sidebar and as markers on the map
- Saves all workouts to localStorage (persists after page reloads)


How to Use It

1. Open the app in your browser
2. Allow location access when prompted
3. Click anywhere on the map to log a new workout
4. Select the type of workout: `Running` or `Cycling`
5. Enter the workout details (distance, duration, etc.)
6. View your workout data in the list and on the map
7. Refresh the page — your workouts are still there thanks to localStorage!

---

Technologies Used

- JavaScript (ES6+)
  - Classes & Inheritance
  - Private class fields
  - DOM Manipulation
- Leaflet.js for interactive maps
- HTML5 + CSS3
- Geolocation API to get user’s current position
- localStorage API for saving data

