# Health-Monitoring-System

Health Monitoring system - Undergraduation minor project

Sensors are interfaced to the embedded world which constantly records data and the data is fetched through server and analysed through graphical representation. 
The attached sensors on patient’s body form a wireless body sensor network which measures heart rate, ECG and body temperature. 
The project can detect the abnormal conditions, issue an alarm to the patient and present a graphical view to the physician.


## Main Components used in the project

LM35 Temperature sensor

AD8232 ECG Module

Digital Heartrate sensor - BPM

## Note
Internally , 12 Bit ADC is used for conversion of values from analog to digital.
Therefore , while calcuating temperature , the formula that is implemented is = 3.3 * 1000 /4095 (Where 3.3 V is the Internal Compartor voltage to ADC)

## Overview

IoT based patient health monitoring system is a generic term given to any medical equipment that has internet capability and can measure one or more health data of a patient who is connected to the device such as heartbeat, body temperature, blood pressure, ECG, steps etc. The equipment can record, transmit and alert if there is any abrupt change in the patient’s health.

By this definition, it includes devices such as smart-watches, fitness trackers, smart-phones to expensive hospital equipment which can connect to internet.

IoT based health monitoring system is used where the patient and heath expert(s) are at different locations. For example, a patient can stay at home and continue his/her routine life and a doctor can monitor patient’s heath. Based on the received data the heath expert can prescribe a best treatment or take an immediate action in case of an emergency.

An IoT based health monitoring system using is a project that involves integrating various sensors and devices to gather and analyze health data of an individual. ThingSpeak is an open-source IoT platform that provides an easy-to-use interface to collect, analyze, and visualize data from IoT devices.

The system can be designed to monitor various health parameters such as heart rate, blood pressure, body temperature, oxygen level, and many others. The data collected from the sensors can be transmitted to a ThingSpeak channel using a Wi-Fi module such as ESP8266 or ESP32. The data can be then analyzed using MATLAB or other programming languages supported by ThingSpeak.

The system can be designed to send alerts or notifications to the individual or caregiver in case of abnormal readings or health issues. For instance, if the blood pressure reading goes beyond a certain threshold level, the system can send a notification to the individual and also to the healthcare provider for immediate attention.

Moreover, the system can also be integrated with wearable devices such as smartwatches or fitness trackers to monitor the physical activity of an individual. This can help in analyzing the overall health of an individual and provide personalized recommendations for improvement.

It also provides visualization tools to create charts, graphs, and other visual representations of the health data. This can help in tracking the progress of an individual and providing insights into their health patterns.

Overall, an IoT based health monitoring system can provide a comprehensive approach to monitor and manage an individual's health. It can enable early detection of health issues and provide timely intervention, thus improving the overall quality of life.


