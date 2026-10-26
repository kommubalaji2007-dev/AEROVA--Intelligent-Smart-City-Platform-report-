# AEROVA - Intelligent Smart City Platform

## About the Project

AEROVA is a front-end prototype of a smart city control center. The idea is to bring important city services into one place so that users can view their status through a single dashboard instead of switching between separate screens.

The interface brings together traffic, energy, water, waste collection, public transport, and safety information. It also includes a simulated city map, analytics, notifications, settings, and an AI-style assistant.

**Please note:** This is currently a demonstration prototype. The city information, sensor readings, map indicators, predictions, and assistant responses are simulated in JavaScript. It is not connected to real city infrastructure, live sensors, or emergency services.

## Main Features

* **City Dashboard:** View a quick summary of selected city indicators.
* **Digital City Map:** Explore a simulated map with service markers and status information.
* **Traffic Management:** View sample congestion information and simulated predictions.
* **Energy Management:** See sample energy-demand, solar-generation, and grid-health indicators.
* **Water Management:** View sample reservoir levels and simulated leak alerts.
* **Waste Management:** Explore sample waste-bin capacity and collection-route concepts.
* **Transport Management:** View sample bus availability, passenger loads, and fleet details.
* **Safety Center:** Review illustrative incident information, safety scores, and alerts. It does not contact emergency services.
* **AI Center:** Try a chat-style assistant and view sample predictions based on predefined or simulated logic.
* **Analytics:** View visual summaries of the displayed sample information.
* **Notifications and Settings:** Use the available interface controls and messages.
* **Desktop-style Controls:** Collapse the sidebar and move supported windows around the screen.
* **Text Report Export:** Export a text summary of the information available in the application.

## Technologies Used

* **HTML5** - Builds the page structure.
* **CSS3** - Handles the layout, styling, and responsive appearance.
* **JavaScript** - Controls navigation, user interactions, simulated data, notifications, and report export.

The project uses plain HTML, CSS, and JavaScript and does not require an external JavaScript library.

## Project Structure

```text
AEROVA/
├── index.html    # Main page and interface structure
├── style.css     # Styles and layout
├── script.js     # Interactions and simulated city data
└── README.md     # Project information and launch instructions
```

Your folder may contain additional files depending on the version you received.

## How to Run the Project

### Option 1: Open it directly

1. Download or extract the AEROVA project folder.
2. Open the folder and locate `index.html`.
3. Double-click `index.html` to open it in a modern web browser.
4. Use the login screen and explore the dashboard and the modules in the sidebar.

### Option 2: Run it in Visual Studio Code

1. Open Visual Studio Code.
2. Select **File > Open Folder** and choose the AEROVA project folder - the folder that contains `index.html`.
3. If you have the **Live Server** extension installed, right-click `index.html` and select **Open with Live Server**.
4. Your browser should open the application. You can now test the dashboard, sidebar links, module windows, notifications, and report export.

No `npm install` or backend server is required for this front-end prototype.

## Demo Login

The project report lists these demonstration credentials:

* **Email:** `admin@aerova.city`
* **Password:** `aerova123`

These credentials are only for trying the prototype. They are not secure production credentials and must not be used for a real service. If the login screen in your copy is configured differently, follow the instructions shown on that screen.

## How to Use AEROVA

1. Open the application in your browser.
2. Submit the demo login form.
3. Start from the City Home dashboard to get an overview of the sample indicators.
4. Use the sidebar to open Traffic, Energy, Water, Waste, Transport, Safety, the AI Center, Analytics, or other available sections.
5. Explore the map markers, sample values, assistant responses, notifications, and settings.
6. Try moving a supported window or collapsing the sidebar.
7. Use the report export option if you need a text summary.

## Testing Checklist

Before presenting or submitting the project, check the following:

* The login screen opens correctly.
* Submitting the demo form opens the control center.
* Each sidebar section opens and displays its content.
* Dashboard values and simulated map markers are visible.
* The AI-style assistant and prediction displays respond as expected.
* Notifications and toast messages work where supported.
* The sidebar can collapse and supported windows can be moved.
* The text report exports and contains the expected information.
* The interface remains usable when the browser window is resized.
* The browser console does not show unexpected JavaScript errors during normal use.

Record the actual result of each test rather than marking it as passed without checking.

## Current Limitations

AEROVA demonstrates the interface and workflow of a smart city control center, but it is not yet a live smart city system. In the current version:

* City data and sensor readings are simulated.
* The map is illustrative and is not connected to a live GIS service.
* The AI Center uses predefined or simulated behavior, not a verified trained machine-learning model.
* There is no production backend or persistent database described in this version.
* The login is for demonstration only and is not production-grade authentication.
* The application does not control traffic signals, utilities, vehicles, or emergency systems.

Because of these limitations, the displayed values should not be used to make real-world operational decisions.

## Future Improvements

Possible next steps for a more complete version include:

* Add a backend API and database with suitable access controls.
* Connect to authorized, secure city-service and sensor data sources.
* Replace the simulated map with an appropriate GIS service.
* Implement secure authentication, session handling, and audit logs.
* Add properly trained and evaluated prediction models, with documented datasets and performance measures.
* Improve accessibility, automated testing, error handling, and deployment practices.
* Provide separate views for operators, analysts, and administrators.

## Project Team

* G. Thilak Masthan
* K. Balaji

**Department:** Computer Science and Engineering
**Institution:** SRM Institute of Science and Technology, Ramapuram, Chennai
**Academic Year:** 2026-27

## Final Note

AEROVA is a student project created to demonstrate how different urban-service dashboards could be presented through one browser-based interface. Its current purpose is to show the design, modules, and user workflow. Live data integration, verified AI predictions, and production-level security would need to be developed and tested separately.
