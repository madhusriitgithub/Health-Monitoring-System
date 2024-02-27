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


