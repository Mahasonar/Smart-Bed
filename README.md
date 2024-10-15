# Smart Bed Approach for Personalized Health Management

This repository contains the project files for the **Smart Bed Approach for Personalized Health Management**, developed by Kaushalya K.T.S., Kapiladewa M.N.G., and Kahandawa Arachchi K.A.M.N. at the University of Moratuwa, Sri Lanka. This system integrates advanced sensors, data analytics, and machine learning algorithms to monitor and optimize sleep conditions and health.

## Features

- **Real-time Health Monitoring**:
  - Continuous monitoring of **heart rate**, **body temperature**, and **blood pressure** using wearable sensors and a custom smart bed system.
  
- **Sensor Integration**:
  - **ECG sensor** and **temperature sensor** for health data acquisition.
  - **MAX30100 Pulse Oximeter** for oxygen level and heart rate monitoring.
  - **MPX5050DP Blood Pressure Sensor** for blood pressure measurement.

- **Real-time Data Visualization**:
  - Integration with **MATLAB** for signal processing and real-time data visualization.
  - A user-friendly interface provides graphical representations of health parameters such as heart rate, body temperature, and blood pressure.

- **Noise Filtering**:
  - A **Low-Pass Filter** designed using **MATLAB** to filter out noise from the ECG signals, ensuring more accurate health monitoring.

- **Alerts and Notifications**:
  - The system triggers alerts for critical conditions, such as irregular heart rate, high body temperature, or abnormal blood pressure, enabling timely interventions.

## System Workflow

1. The smart bed system continuously monitors physiological parameters using ECG, temperature, and blood pressure sensors.
2. Data from these sensors are transmitted to **Arduino** microcontrollers (Mega and Uno) for signal processing.
3. The processed data is displayed in real-time using **MATLAB** with graphical interfaces showing heart rate, body temperature, and blood pressure levels.
4. MATLAB also generates alerts when abnormal health conditions are detected.

## Technologies Used

- **Sensors**: ECG Sensor, DS18B20 Temperature Sensor, MAX30100 Pulse Oximeter, MPX5050DP Blood Pressure Sensor.
- **Microcontrollers**: Arduino Mega and Uno.
- **Software**: MATLAB, Simulink.
- **Signal Processing**: Butterworth filter for ECG noise reduction, MATLAB-based plotting of real-time data.
