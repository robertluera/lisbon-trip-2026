Portugal 2026 Trip Details Site
Purpose
A lightweight, single-page web application designed to centralize logistics for the May 2026 wedding and coastal trip to Lisbon and Ericeira. It serves as a high-leverage reference point for friends to access flight times, lodging addresses, and wedding credentials.

Core Functional Components
Live Countdown Engine: A JavaScript-driven timer synchronized to the departure flight (May 23, 2026, 4:40 PM LAX).

Logistics Modules:

Flight Logistics: Displays directional data for TAP Air Portugal transit.

Accommodation Registry: Lists Airbnb locations with integrated Google Maps API deep links for mobile navigation.

Event Sync: Contains venue specifics and the password-protected gateway for the primary wedding website.

Visual Framework: CSS-in-JS style architecture utilizing a responsive, mobile-first design with a specific focus on scannability via "date-badges" and bolded key-value pairs.

Technical Specifications
Frontend: HTML5, CSS3.

Logic: Vanilla JavaScript (ES6+).

Hosting: Optimized for deployment via GitHub Pages or local browser execution.

Dependencies: Zero external libraries; self-contained for maximum performance and offline reliability once cached.

Configuration
To modify the departure target or location data, update the following variables within the source:

Takeoff: takeoffDate constant in the <script> block.

Links: href attributes within the .trip-section containers.
