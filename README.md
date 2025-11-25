ElectroShield – Electrical Hazard Detection Prototype (Python + ML)

Project Overview

ElectroShield is a Python-based prototype that simulates electrical hazard detection using machine learning on simulated sensor data. The system predicts hazard-prone areas and provides visual insights through user and admin dashboards, offering a conceptual solution for safer electrical environments.

This version focuses on the logic, prediction model, and UI prototype. Full Python implementation is being rebuilt due to system reset, but this repository includes documentation, architecture, screenshots, and demo videos.

ElectroShield predicts hazard risks using simulated parameters such as:
-Voltage
-Temperature
-Leakage current
-Wire-health indicators

Outputs:
High-risk / Medium-risk / Safe zone

#This prototype demonstrates:
*User dashboard (live prediction + past alerts)
*Admin hazard-map visualization
*Mock SMS-style public alerts
*Hazard history and zone indicators

Features

-ML-based risk classification
-Synthetic dataset generation
-Real-time prediction demo (UI simulated)
-Interactive dashboards (User + Admin)
-Hazard history and logging
-Visual hazard indicators (map, charts, icons)

Installation

The full Python implementation is being rebuilt.
This section will be updated with setup instructions soon.
Current repo includes:
>Model explanation
>Architecture diagrams
>UI demo (HTML/CSS/JS prototype)
>Screenshots
>Documentation

Tech Stack

*Python: pandas, scikit-learn
*Machine Learning: Basic classification on simulated dataset
*UI Prototype: HTML, CSS, JavaScript
Architecture diagrams + flowcharts

<img width="1756" height="794" alt="image" src="https://github.com/user-attachments/assets/8ba4b340-22f9-421e-846e-505a8792f296" />

How the Model Works

>Preprocessed simulated sensor data
>Trained a simple classification model
>Output used to visualize hazard levels
>Mapped to colour-coded risk zones
This prototype demonstrates concept validation before the hardware phase.

Demo Videos

User Module Demo
>>Dashboard • Live Predictions • Past Alerts
https://github.com/user-attachments/assets/ee29b669-88f1-48ea-bf59-0ab0d9ced0b5

Admin Panel Demo
>>Map View • Hazard Zones
https://github.com/user-attachments/assets/75391ed5-67cf-449b-9206-988d1960a4be

Screenshots

Dashboard

<img width="1837" height="976" alt="Screenshot 2025-11-24 210914" src="https://github.com/user-attachments/assets/641b9787-0529-4be6-8f53-2a1205270deb" />

Past Alerts

<img width="981" height="832" alt="Screenshot 2025-11-24 211122" src="https://github.com/user-attachments/assets/c7061315-e112-44cc-abc2-a275b92ad01f" />

Hazard zone indicator

<img width="1825" height="1017" alt="Screenshot 2025-11-24 211050" src="https://github.com/user-attachments/assets/6518ef32-4093-4b41-9f97-1874d43577ca" />

Admin mock UI

<img width="1820" height="1028" alt="Screenshot 2025-11-24 211226" src="https://github.com/user-attachments/assets/7db08365-e8f3-4ca6-be07-dda89450f748" />

Viewing Outputs

To view outputs, see the included screenshots and demo video.
Code can be run locally if Python and required libraries are installed.

Results / Insights

Successfully identifies hazard-prone areas with simulated data.
Provides visual insights for quick decision-making.
Modular design allows easy addition of new sensors or ML models.

Use Cases

--Home electrical safety systems
--Industrial hazard monitoring
--Smart grid predictive diagnostics
--Workplace safety automation
--Predictive maintenance for electrical units
--IoT-based early warning systems

Future Work

>Rebuilding complete Python source code
>ntegrating real sensors (temperature, voltage, leakage current)
>ESP32 / Raspberry Pi hardware interfacing
>Real-time geo-mapping
>SMS / app-based hazard alerts
>Cloud storage + analytics

Key Learning / Takeaways

Practical experience in Python, ML, and data visualization.
Designing user/admin dashboards for actionable insights.
Structuring a project for portfolio and internship showcase.

Rebuild Notice

The original Python implementation was lost during a system reset. This repository currently contains the UI demo, architecture diagrams, documentation, and concept workflow. Full Python implementation is under reconstruction.

Author

Divya Mahibalan – early-stage IoT + ML exploration project
