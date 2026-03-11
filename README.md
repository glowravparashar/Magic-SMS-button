# Magic SMS Button (IoT Alert System)

This project is an IoT-based alert device that sends an SMS when a physical button is pressed.

## Hardware
- ESP32 FeatherS2 Development Board
- Breadboard
- Push Button
- Jumper Wires
- Resistor (400–1000Ω)

## Software
- CircuitPython
- Mu Editor
- Twilio SMS API

## How It Works
1. Device connects to WiFi.
2. System waits for button input.
3. Button press triggers API request.
4. Twilio sends SMS to predefined phone number.

## Applications
- Emergency alert button
- Smart doorbell notification
- Assistance request system
