# Smart Plant Disease Detection System

End-to-end IoT system for real-time plant disease detection using machine learning and multi-sensor monitoring. Built for SIT210 Embedded Systems Development — Deakin University (T1 2026).

## ML Model

- **Architecture:** MobileNetV2 (fine-tuned)
- **Dataset:** PlantVillage — 54,000+ images, 38 classes
- **Validation accuracy:** 97%
- **Format:** TensorFlow Lite (INT8 quantized) — ~4MB, ~650ms inference on Raspberry Pi 3B+

## Hardware

- Raspberry Pi 3B+ (main controller)
- Arduino Nano 33 IoT (sensor hub)
- Sensors: DHT11, BH1750, capacitive soil moisture, DS18B20, Pi Camera v2
- Actuators: relay + water pump, LCD 16x2, buzzer

## Status

Project in progress — ML model complete, hardware integration ongoing.

## Author

Kyle (Nguyen Anh Khoa Vo) — Deakin University
