#  Smart Medicine Dispenser

##  Objective
To design an automated medicine dispensing system that ensures timely medication for users, especially elderly individuals, and provides alerts if medication is missed.

##  Components Used
- ESP32 Microcontroller  
- Servo Motor  
- Ultrasonic Sensor  
- Buzzer  
- LEDs  
- Power Supply  

##  Working Principle
The system operates based on preset medication timings:

1. When the scheduled time is reached, the ESP32 activates the system.
2. The servo motor rotates to dispense the medicine.
3. An ultrasonic sensor detects whether the user's hand is present to collect the medicine.
4. Once the medicine is taken, a notification is sent confirming successful dispensing.

##  Alert Mechanism
- If the user's hand is **not detected within 30 seconds**:
  - The system assumes the medicine is not taken.
  - An **alert phone call** is triggered to notify the user.

##  Target Users
- Elderly people  
- Patients with strict medication schedules  
- Individuals requiring automated assistance  

##  Features
- Automated time-based dispensing  
- Real-time hand detection using ultrasonic sensor  
- Missed dose alert system  
- Remote notification via phone call  

##  Future Improvements
- Mobile app integration  
- IoT-based remote monitoring  
- Voice assistant reminders  
- Data tracking for medication history  

##  Presentation
The detailed project presentation is available in this repository.
