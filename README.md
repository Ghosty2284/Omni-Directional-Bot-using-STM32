# Omni-Directional-Bot-using-STM32
This repository contains the complete firmware and hardware documentation for an Omnidirectional Obstacle Avoidance Robot based on the STM32F401CCU6 microcontroller. The robot uses three DC motors for omnidirectional movement, three ultrasonic sensors for obstacle detection, and optional servo motors for sensor scanning.

# Features

=> Omnidirectional Movement: Three independently controlled motors allow the robot to move in any direction.
=> Obstacle Avoidance: Uses three ultrasonic sensors (front, left, right) to detect and avoid obstacles in real time.
=> Servo Scanning (Optional): Supports up to three servo motors for dynamic sensor positioning.
=> PWM Motor Control: Smooth speed control using hardware PWM via IRF540 MOSFET drivers.
=> Modular Code: Easily adaptable for additional sensors or actuators.
=> STM32 HAL Library: Written using STM32 HAL for portability and maintainability
