ARCOVA – AI Urban Disaster Evacuation System

An AI-assisted disaster risk prediction and evacuation planning system designed to support safer decision-making during urban emergencies such as floods and cyclones.

About the Project

ARCOVA aims to help people and emergency response teams understand disaster risks, identify potentially unsafe roads, explore evacuation routes, and locate available shelters through a centralized dashboard.

Key Features

- Disaster Risk Prediction: Estimates disaster risk using environmental and location-related inputs.
- Unsafe Road Detection: Identifies potentially unsafe roads based on risk conditions.
- Alternative Evacuation Routes: Helps users explore alternative paths when a route becomes unsafe.
- Shelter Information: Displays shelter information to support evacuation planning.
- Interactive Dashboard: Brings risk information, route details, and shelter data together.
- Risk Monitoring: Supports assessment of changing disaster conditions.

Technology Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Python and Flask
- Machine Learning: Scikit-learn / Random Forest
- Data Storage: CSV datasets
- Development Environment: Visual Studio Code

Project Structure

The project may include the following files:

- "app.py" – Flask application and web routes
- "predict.py" – Disaster risk prediction logic
- "requirements.txt" – Python dependencies
- "index.html" – Dashboard interface
- "static/style.css" – Styling
- "risk training.csv" – Risk model training data
- "routes.csv" – Road and route data
- "shelters.csv" – Shelter information

How to Run the Project

1. Install Python 3.

2. Download or clone this repository.

3. Extract the ZIP file if you downloaded the archive.

4. Open a terminal in the project folder.

5. Install the required packages:
   
   pip install -r requirements.txt

6. Start the Flask application:
   
   python app.py

7. Open the local address displayed in the terminal. It may be "http://127.0.0.1:5000/".

Machine Learning Note

If the model is trained using simulated or synthetic data, its predictions are intended for demonstration and educational purposes. They should not be treated as validated real-world disaster forecasts or used as the sole basis for emergency evacuation decisions.

Future Enhancements

- Integration with real-time weather and flood information.
- Road-network-based routing using verified map data.
- Live shelter capacity updates.
- Improved evacuation planning and population allocation.
- Validation using reliable historical disaster data.

Project Information

- Project Name: ARCOVA – AI Urban Disaster Evacuation System
- Event: ARTIWHIZ’26 – AI for Sustainability
- Category: Artificial Intelligence and Sustainable Smart Cities

Disclaimer

This project is a prototype intended for educational and demonstration purposes. Real emergency decisions should follow official disaster management guidance and verified local information.
