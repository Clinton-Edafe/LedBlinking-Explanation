# Understanding the Code and Components in the Blinking LED Project

## Table of Contents
- [Concepts](#concepts)
- [Digital Pins on the Arduino](#digital-pins-on-the-arduino)
- [Code Breakdown](#code-breakdown)
- [Role of the Resistor](#role-of-the-resistor)

---

## Concepts

This section explains the fundamental concepts and components used in the Blinking LED project.

---

## 1. Digital Pins on the Arduino

Digital pins on the Arduino can be configured as either input or output. In this project:
- **Pin 13** is set as an output to control the LED's state (on or off).

---

## 2. Code Breakdown

Below is an explanation of the code used in the Blinking LED project:

- `pinMode(13, OUTPUT);` : Configures pin 13 as an output pin.
- `digitalWrite(13, HIGH);` : Turns the LED on by providing voltage to pin 13.
- `digitalWrite(13, LOW);` : Turns the LED off.
- `delay(1000);` : Pauses the code execution for 1000 milliseconds (1 second).

---

## 3. Role of the Resistor

The **220-ohm resistor** is used to limit the current flowing through the LED, preventing it from burning out. This helps maintain a safe current level for the LED, ensuring it operates correctly.
