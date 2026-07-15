## DC Motor Interfacing using STM32

## Overview
This project demostrates DC motor interfacing with an STM32 microcontrollor using the L293D motor driver.
The motor direction is controlled through GPIO pins, while the speed is controlled using PWM genereted by a timer.

## Features
- DC motor interfacing with L293D
- Forward and reverse motor control
- PWM-based speed control
- GPIO-based direction control
- STM32CubeIED project

## Hardware usesd
- STM32F407G Discovery Board
- L293D Motor Driver IC
- External Power Supply
- Connectiong Wires

## Software Used
- STM32CubeIDE
- STM32F103C6T6
- STM32 HAL Library
- Proteus

## Working 
The STM32 microcontroller sends directin and PWM control signals to the L293D motor driver.
the L293D receives power from an external supply and drives the DC motor according to the commands from the microcontrollers.

## Core
- Inc main.c
- Src main.c

## Future Improvement
- Speed control using potentiometer (ADC)
- Button-based motor control
- UART command-based motor control
  
