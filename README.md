# Smart-Medicine-Dispenser--Iot

# Smart Medicine Dispenser (IoT Project)

## 📌 Overview
Developed an IoT-based smart medicine dispenser to improve medication adherence for elderly users through automated dispensing, real-time verification, and cloud-based monitoring.

## 🚀 Features
- Automated pill dispensing using ESP32
- Multi-modal reminders (LED, buzzer, display)
- Medication intake verification using IR sensor
- Real-time alerts for missed doses
- Cloud data logging using Firebase

## 🛠 Tech Stack
- ESP32 (Microcontroller)
- Firebase (Cloud Database)
- Embedded C / Arduino IDE
- Sensors: IR Sensor, Motor, LED, Buzzer

## ⚙️ System Architecture
- User sets medication schedule via web/app
- ESP32 fetches schedule via Wi-Fi
- Device triggers alerts at scheduled time
- Sensor verifies medication intake
- Data uploaded to Firebase for monitoring

## 📂 Project Structure
- firmware/ → ESP32 code
- hardware/ → circuit components
- cloud/ → Firebase setup
- docs/ → project report

## 🧠 Key Outcomes
- Improved medication adherence tracking
- Real-time monitoring for caregivers
- Scalable and low-cost IoT solution

## 📎 Future Improvements
- Mobile app integration
- AI-based adherence prediction
- Enhanced sensor accuracy
