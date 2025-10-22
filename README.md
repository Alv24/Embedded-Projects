# Embedded-Projects 
# MPU6050 Data Logger using STM32

This project demonstrates an embedded system application using an STM32 microcontroller for reading accelerometer data from an MPU6050 sensor over I2C and logging it via UART to a serial terminal.

## Features
- MPU6050 initialization and data acquisition
- UART data logging for Ax, Ay, and Az values
- Modular C structure following CMSIS conventions

## Hardware Setup
- STM32F4xx board (e.g., STM32F411RE)
- MPU6050 connected via I2C1
- Serial monitor via USART2 (115200 baud rate)

## Tools Used
- STM32CubeIDE
- HAL libraries
- C programming

## How to Run
1. Connect MPU6050 to the STM32 board via I2C.
2. Flash the program.
3. Open a serial terminal at 115200 baud to view live accelerometer logs.

