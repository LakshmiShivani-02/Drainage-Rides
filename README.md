# Drainage-Rides
An IoT Project
# Obstacle Avoiding Robot Code Readme

## Overview

This Arduino code is for a simple obstacle-avoiding robot that uses an HC-SR04 ultrasonic sensor to measure distance and a servo motor to scan. The robot moves forward until it detects an obstacle, at which point it stops, scans its surroundings, moves backwards, turns left, and resumes forward movement.

## Hardware Requirements

*   Arduino board
*   HC-SR04 ultrasonic sensor
*   Servo motor
*   Two DC motors with a motor driver circuit
*   Jumper wires
*   Power source

## Connections

*   **HC-SR04 Ultrasonic Sensor:**
    *   `VCC` to 5V
    *   `GND` to GND
    *   `Trig` to Arduino digital pin 9
    *   `Echo` to Arduino digital pin 8
*   **Servo Motor:**
    *   `Signal` to Arduino digital pin 10
    *   `VCC` to 5V
    *   `GND` to GND
*   **DC Motors (via Motor Driver):**
    *   Left Motor:
        *   `MLa` to Arduino digital pin 4
        *   `MLb` to Arduino digital pin 5
    *   Right Motor:
        *   `MRa` to Arduino digital pin 6
        *   `MRb` to Arduino digital pin 7

## Code Explanation

### Includes and Definitions
