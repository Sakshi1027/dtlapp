Care Connect - Real-Time Healthcare Assistance System
Overview
Care Connect is a real-time healthcare assistance system designed to provide emergency support to users. It locates the nearest hospital using geolocation, displays an optimized route, and allows ambulance dispatch with a simulated movement animation. The system also includes a hospital dashboard for real-time updates on patient data, staff availability, and ambulance status.
Features

Emergency Assistance: Locate the nearest hospital and display an optimized route on a click.
Ambulance Dispatch: Request an ambulance with a simulated movement animation to the user's location.
Hospital Dashboard: Real-time updates including patient search, bed availability (ICU, General Ward, Emergency), staff availability (Doctors, Nurses, Technicians), ambulance status, triaging levels, and OT status.
Interactive Map: Powered by Leaflet and OpenStreetMap for route visualization and hospital location.
User Interface: Mobile-like design with intuitive navigation, buttons, and a dropdown menu.
Additional Pages: Emergency contacts, health profiles, and assistance request sections (under development).

Technologies Used

HTML/CSS/JavaScript: For frontend development.
Leaflet.js and Routing Machine: For map rendering and route calculation.
OpenStreetMap: Provides map data.
Firebase: Included for potential real-time data integration (in progress).
LocalStorage: For storing user location, hospital details, and dispatch messages.

Installation

Clone the repository:git clone https://github.com/Sakshi1027/dtlapp.git


Navigate to the project directory:cd dtlapp


Open index.html in a web browser to start the app locally.

Usage

Welcome Page (index.html): Click "Get Started" to access the map interface or use the menu for other sections.
Map Interface (maps.html): Click "Emergency Help" to find the nearest hospital and route, then use "Request for Ambulance Service" or "Call Ambulance Driver" to dispatch assistance.
Hospital Dashboard (hd.html): View real-time hospital data, search patients, and monitor ambulance dispatch history and live traffic.
Allow geolocation access when prompted for accurate location services.

Deployment
This project can be deployed on Vercel:

Install Vercel CLI: npm install -g vercel.
Run vercel in the project directory and link to the GitHub repository.
Access the deployed app via the provided URL (e.g., https://care-connect.vercel.app).

Visuals
![Welcome Screen](./screenshots/index.png)
![Map Interface](./screenshots/maps.png)
![Hospital Dashboard](./screenshots/dashboard.png)

Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue to discuss.
Future Improvements

Integrate Firebase for real-time data updates.
Enhance ambulance tracking with actual GPS data.
Complete emergency.html, health.html, request.html, and about.html with full functionality.
Add user authentication and data persistence.

License
MIT License (or specify your preferred license).
Contact
For questions, reach out to Sakshi at your-email@example.com.
