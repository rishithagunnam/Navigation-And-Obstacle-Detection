## Navigation-And-Obstacle-Detection
The Location-Based Navigation and Obstacle Detection System with Voice Alerts for Visually Impaired is an Arduino-powered smart assistive device designed to enhance mobility for visually impaired individuals. The system integrates ultrasonic sensors for obstacle detection, GPS for real-time location tracking, and GSM for emergency communication. When an obstacle is detected, the device triggers audio alerts to notify the user via a speaker or headphones. It can also send the current GPS coordinates to a predefined contact using GSM messaging. The device is built around an Arduino microcontroller, making it cost-effective and easy to customize. Voice modules are used to provide real-time feedback to the user about obstacles and location. The system aims to reduce dependency on others by enabling independent navigation. It includes a buzzer for short-range alerts and water sensors for wet surface detection. The stick-based design ensures minimal training and is portable for daily use. This project empowers visually impaired individuals to navigate safely and confidently.

## 🛠️Technologies Used
- **Arduino Uno** – Microcontroller used for processing and control.
- **Ultrasonic Sensor** – For obstacle detection in the range of ~2 cm to 450 cm.
- **Water Sensor** – To detect water on the path.
- **GPS Module** – To get real-time location coordinates of the user.
- **GSM Module** – To send SMS with location details to predefined contacts.
- **Voice Playback Module (Audio Recorder)** – For real-time voice alerts and location announcements.
- **Buzzer** – For close-range obstacle alerts via sound.
- **Power Supply Unit** – Regulated 5V and 12V supply (using transformer, rectifier, filter, and voltage regulators like 7805/7812).
- **ThingSpeak (IoT Platform)** – For uploading and visualizing sensor/location data online.
- **AVR/Embedded C** – Programming for microcontroller logic (via Arduino IDE).
- **GSM and GPS Communication Protocols** – For location sharing and message transmission.
