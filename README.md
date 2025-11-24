# ElectroShield-Hazard-Detection-Prototype
Python + ML prototype that simulates electrical hazard detection using simulated sensor data. UI demo, docs, and video included.

#⚡ ElectroShield – Electrical Hazard Detection (Python ML Prototype)

ElectroShield is a small software prototype I made using Python + basic Machine Learning to simulate how an IoT-based system could detect electrical hazards in advance and alert nearby users.

This version focuses mainly on the logic, prediction model (using simulated sensor values) and a UI preview of how an admin/public dashboard might look.

Note: My original implementation code was lost during a system reset, so I’m rebuilding the full version. This repo contains the documentation, demo video, screenshots and all the architecture.

#🎯 Project Overview
ElectroShield uses ML predictions on simulated values like:
-Voltage
-Temperature
-Leakage current
-Wire health indicators

#Based on the prediction, the system identifies:
🔴 High-risk zones
🟡 Medium-risk zones
🟢 Safe zones

#The prototype also demonstrates:
-A simple dashboard
-Mock SMS-style public alerts
-Admin map-style hazard indicators
-Hazard history

#🧠 Tech Stack
*Python: pandas, sklearn (ML model)
*Simulated dataset (self-generated)
*HTML / CSS / JS for prototype UI
*Flowcharts + Architecture diagrams

#📽️ Demo Video

#🖼️ Screenshots
<img width="1756" height="794" alt="image" src="https://github.com/user-attachments/assets/8ba4b340-22f9-421e-846e-505a8792f296" />

#🔧 How the Model Works
>Preprocessed simulated sensor data
>Trained a simple classification model
>Output used to visualize hazard levels
>Mapped to colour-coded risk zones
This prototype demonstrates concept validation before the hardware phase.

#📌 Future Work
-Rebuilding Python source code (lost)
-Integrating actual sensor hardware
-Real geo-mapping
-Automatic SMS gateway alerts

#🙌 Author
Built by your DivyaMahibalan as part of an early-stage IoT + ML exploration project.
