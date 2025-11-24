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
Flowcharts + Architecture diagrams
<img width="1756" height="794" alt="image" src="https://github.com/user-attachments/assets/8ba4b340-22f9-421e-846e-505a8792f296" />

#📽️ Demo Video

>>User Module Demo – Dashboard, Predictions & Past Alerts
https://github.com/user-attachments/assets/ee29b669-88f1-48ea-bf59-0ab0d9ced0b5

>>Admin Panel Demo – Map View & Hazard Zones
https://github.com/user-attachments/assets/75391ed5-67cf-449b-9206-988d1960a4be

#🖼️ Screenshots
--Dashboard home
<img width="1837" height="976" alt="Screenshot 2025-11-24 210914" src="https://github.com/user-attachments/assets/641b9787-0529-4be6-8f53-2a1205270deb" />

--Past Alerts
<img width="981" height="832" alt="Screenshot 2025-11-24 211122" src="https://github.com/user-attachments/assets/c7061315-e112-44cc-abc2-a275b92ad01f" />

--Hazard zone indicator
<img width="1825" height="1017" alt="Screenshot 2025-11-24 211050" src="https://github.com/user-attachments/assets/6518ef32-4093-4b41-9f97-1874d43577ca" />

--Admin mock UI
<img width="1820" height="1028" alt="Screenshot 2025-11-24 211226" src="https://github.com/user-attachments/assets/7db08365-e8f3-4ca6-be07-dda89450f748" />


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
