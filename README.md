# EE313 Term Project: Micro-Air Conditioner

## 🎯 Project Goals
- Build an analog-controlled micro air conditioner for small spaces
- Maintain user-set temperature using heater and fan
- Display temperature using an RGB LED with continuous color mapping
- Apply analog design principles without microcontrollers

## 🧊 Project Overview
A modular analog air conditioning system built using discrete components. The circuit includes temperature sensing, setpoint input, heating/cooling control, and RGB-based visual feedback.

Developed for **EE313 - Analog Electronics Lab (2023-2024 Fall Term)** at METU.

## 🔧 System Components
- **Control Unit**: Activates heater or cooler based on temp comparison
- **Heating**: Power resistor
- **Cooling**: DC fan (5V or 12V)
- **Sensor**: LM35 or RTD
- **Display**: RGB LED for ambient/set temp (toggle switch)
- **Setpoint**: Adjustable via potentiometer

## ✅ Design Requirements
- Temperature range: 24°C to 40°C
- RGB LED shows continuous color spectrum
- Heater/cooler never run simultaneously
- Deadband ±1°C; autonomous switching
- ≥3W power, max 15W, ±12V supply
- Must reach target temp at ≥5°C/min
