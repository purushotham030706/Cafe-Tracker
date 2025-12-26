Café Tracker with Map

Café Tracker is a client-side web application that helps users keep track of cafés they have visited.
It allows users to log café names, mark visits, add notes and dates, save their current location, and visualize visited cafés on an interactive map.

The project focuses on frontend logic, browser storage, and geolocation-based features, and serves as a foundation for a future full-stack implementation.

Features
  Add and manage a list of cafés
  Mark cafés as visited
  Mark cafés as favorites
  Add visit dates and personal notes
  Save current location using browser geolocation
  View saved café locations on an interactive map
  View café locations in Google Maps
  Persistent storage using localStorage
  Real-time statistics (visited count, total cafés, favorites)
  Responsive and clean UI
  Map & Location Support
  Uses Leaflet.js for interactive map rendering
  OpenStreetMap tiles for map data
  Allows users to save their current GPS location for a café
  Displays all saved café locations as markers on the map
  Default map location centered on Mysuru

Tech Stack
  Frontend
  HTML
  CSS
  JavaScript (Vanilla)
  Libraries & APIs
  Leaflet.js (maps)
  OpenStreetMap tiles
  Browser Geolocation API
  Browser localStorage

Project Structure:
    cafe-tracker/
    ├── index.html
    └── README.md
(All styling and logic are handled directly within the HTML file for simplicity.)

How Data Is Stored
    Café data is stored locally in the browser using localStorage
    Each café entry contains:
      Name
      Visit date
      Notes
      Favorite status
      Visited status
      Optional GPS location (latitude & longitude)
      No backend or database is currently used.

How to Run
    Clone the repository
    Open index.html in any modern web browser
    Allow location access when prompted (optional, for map features)
    No additional setup or dependencies required.

Planned Improvements
  Convert the project into a full MERN stack application
  Add backend API for persistent data storage
  User authentication and profiles
  Cloud database integration
  Better map filtering and clustering
  Improved UI/UX and accessibility
  Deployment with backend support

Contact
Email: purushothambm2006@gmail.com
GitHub: https://github.com/purushotham030706

📝 Note

This project is part of my learning journey as a Computer Science Engineering student and is actively being improved as I work toward full-stack development.
