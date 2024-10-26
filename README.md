# WorkoutTracker-Mapty
This project is a workout tracking application that allows users to record and view workouts directly on a map. The application differentiates between two types of workouts, running and cycling, and tracks essential metrics such as distance, duration, pace, and speed. It also includes the ability to save and load workouts via local storage.

## Features

- **Workout Tracking**: Users can add running and cycling workouts with information like distance, duration, cadence (for running), and elevation gain (for cycling).
- **Map Integration**: Using the Leaflet library, the app allows users to view their location on a map, and click on the map to log workout locations.
- **Local Storage**: Workouts are saved in local storage so that data is retained across browser sessions.
- **User Interface**: Form inputs adjust based on workout type (e.g., cadence input is shown for running, elevation input for cycling).
- **Data Visualization**: Workouts appear as markers on the map, and users can view a list of their workouts below the map.

## Usage

1. Load the application and allow location access to display your current location on the map.
2. Click on the map to open the workout entry form.
3. Choose a workout type (running or cycling) and enter the required details.
4. Submit the form to log the workout, which will appear as a marker on the map and in the workout list.
5. All workout data is saved locally, so you can revisit your logged workouts anytime.

## Dependencies

- **Leaflet**: Used for map functionalities, displaying user location, and handling map interactions. Leaflet is an open-source JavaScript library for mobile-friendly interactive maps.
- **HTML/CSS**: For structuring and styling the application's interface.
- **JavaScript (ES6)**: The primary language used to implement the application logic and user interactions.

## How to Use

1. Open the application in your web browser.
2. Allow location access when prompted to get your current position.
3. Fill out the workout form with distance, duration, and specific details depending on whether you are running or cycling.
4. Click submit to log the workout, which will be displayed on the map and in the list below.
5. You can click on the workout in the list to zoom in on the workout route on the map.

## Credits

This application is developed as part of my learning journey based on the work of **[Jonas Schmedtmann](https://github.com/jonasschmedtmann)**.

## License

This project is not licensed under any specific terms but is created for educational purposes.
