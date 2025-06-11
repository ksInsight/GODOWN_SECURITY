📌 Overview:
This project demonstrates the implementation of a Smart Security System for a warehouse (godown) using IoT devices and Cisco Packet Tracer. By simulating real-time surveillance, controlled access, and automation, this model showcases how warehouses can be safeguarded against unauthorized access and threats using networked smart systems.

🛠️ Tools & Technologies Used
Cisco Packet Tracer 7.1

IoT Devices (Smartphone, Webcam, Fan, Door, Lamp, Motion Detector)

Wireless Home Gateway

Network Simulation & Configuration

IoT Monitoring Interface

📚 Features Implemented
✅ Smart IoT Setup
Designed a wireless home gateway setup to simulate a smart godown.

Connected multiple smart devices (fan, lamp, door, webcam, etc.) to the gateway.

Integrated a smartphone to control all IoT devices wirelessly.

✅ Real-Time Monitoring
Live video and IoT dashboard simulated using Cisco Packet Tracer's IoT monitor.

Implemented alerts and feedback for device status.

✅ Access Control & Security
Simulated door control using smartphone.

Configured sensors for unauthorized motion detection.

Switched between open/closed, on/off, dim/high states based on commands.

✅ Inventory Support
Monitored devices like fans and lamps for inventory environments.

⚙️ System Architecture
Components
Sensors & Detectors

Control Panel (Smartphone)

IP Camera System

Alarms & Notification System

Wireless Network Infrastructure

Interaction Flow
mathematica
Copy
Edit
Sensor Trigger → Signal to Control Panel → Action Execution (e.g., Alarm, Door Lock) → Feedback to Smartphone Monitor
🧪 Step-by-Step Implementation
1. Device Setup
Add Home Gateway and all IoT devices

Set SSID in Home Gateway

Connect each device via PT-IOT-NM-1W Adapter

2. Wireless Configuration
Disabled authentication for ease of simulation

Connected smartphone via SSID setup

3. IoT Monitoring
Smartphone → Desktop → IoT Monitor

Login → Control & Monitor all devices

4. Testing
Switched lamp ON/OFF

Adjusted fan speed

Opened/closed door via smartphone

Observed alert feedback in real time

🎯 Objectives
Build a secure and automated IoT environment in a warehouse using Cisco Packet Tracer

Simulate real-time security control via mobile

Enhance awareness of smart networked systems in warehousing

📈 Benefits of Smart Security in Godown
Enhanced Security – Live alerts & centralized monitoring

Inventory Management – Better control of internal devices

Access Control – Only authorized users can interact

Cost Efficiency – Reduces manual effort & theft

🧩 Scope of Future Work
Integrate AI for automated decision-making

Real-time email/SMS alert system

Cloud database logging for events

Voice command-based control via smartphone
