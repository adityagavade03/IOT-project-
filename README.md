# IOT-project

Smart Water Quality Monitoring System with Multi-Level Usability and Waterborne Disease Risk Prediction

Abstract

Water contamination is a major concern that affects human health and can lead to various waterborne diseases. This project presents a Smart Water Quality Monitoring System using IoT and machine learning techniques for real-time water quality analysis. The system uses a turbidity sensor and ESP32 microcontroller to monitor water quality and classify it into drinkable, usable, and dangerous categories. It also predicts possible waterborne disease risks based on contamination levels. The proposed system provides a low-cost, efficient, and real-time solution for water quality monitoring.

Methodology

The proposed system collects water quality data using a turbidity sensor connected to an ESP32 microcontroller. A machine learning model is trained using a water quality dataset and converted into lightweight decision logic for embedded implementation. During operation, the sensor continuously measures turbidity levels and sends the readings to the ESP32. The collected data is processed to classify water into drinkable, usable, and dangerous categories. Based on the classification result, the system predicts possible waterborne disease risks and displays the output through the Arduino IDE Serial Monitor.

Block Diagram
Water Sample
      ↓
Turbidity Sensor
      ↓
ESP32 Microcontroller
      ↓
Data Processing
      ↓
ML Classification
      ↓
Disease Risk Prediction
      ↓
Serial Monitor Output
Result

The system successfully monitored water quality in real time and classified water into different usability levels based on turbidity readings. The machine learning model provided accurate classification results and predicted possible disease risks associated with contaminated water. The output was displayed through the Arduino IDE Serial Monitor, enabling easy observation and analysis of water quality conditions.

Conclusion

The proposed Smart Water Quality Monitoring System provides an effective and low-cost solution for real-time water quality assessment. By combining IoT and machine learning techniques, the system classifies water into multiple usability levels and predicts potential disease risks. The results demonstrate that the system can improve traditional water monitoring methods and enhance awareness regarding water safety and public health.
