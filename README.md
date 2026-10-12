# Learning_Firmware
A portfolio recording my learning and progress in firmware using a Microcontroller (TM4C123G Tiva C LaunchPad)

My goal is to develop a strong understanding of how firmware interacts with hardware, how microcontroller peripherals are configured and controlled, and how to design, debug, and test reliable low-level software.

# Learning Roadmap

**text** 1. Embedded C and Low-Level Programming

Build a strong foundation in C programming for resource-constrained microcontrollers.

Variables, data types, functions, arrays, and structures

Pointers, memory addresses, and pointer dereferencing

Bitwise operations, bit masks, and register manipulation

Memory-mapped I/O and hardware registers

The purpose of volatile when accessing hardware registers

Understanding how source code is compiled, assembled, linked, and loaded onto a microcontroller

Using compiler warnings and errors to diagnose build issues

**text** 2. GPIO and Digital I/O

Learn how firmware controls physical hardware through general-purpose input/output (GPIO) pins.

Configuring GPIO pins as inputs and outputs

Controlling LEDs and reading push buttons

Understanding active-high and active-low signals

Configuring pull-up and pull-down resistors

Using bit masks to modify individual register bits without affecting others

Understanding switch debouncing and reliable digital input handling

Planned project: RGB LED Controller using the TM4C123G LaunchPad.

**text** 3. Hardware Timers and Interrupts

Move beyond simple polling loops and learn how firmware responds to events and performs time-dependent tasks.

Configuring hardware timers

Generating periodic events and delays

Understanding polling versus interrupt-driven programming

Writing interrupt service routines (ISRs)

Understanding interrupt flags, priorities, and timing

Learning about shared data between interrupt handlers and the main program

Planned project: Timer-driven reaction-time game using button inputs and LED feedback.

**text** 4. UART and Serial Communication

Learn how microcontrollers exchange information with a computer or another device.

Configuring a UART peripheral

Understanding baud rates, transmit, and receive operations

Sending diagnostic messages over a serial terminal

Receiving and parsing serial commands

Using serial output to assist with debugging

Handling input and communication errors

Planned project: UART Serial Command Interface for controlling the microcontroller through a terminal.

**text** 5. ADC, PWM, and Hardware Control

Explore how firmware interacts with analog signals and controls hardware outputs.

Understanding analog-to-digital conversion (ADC)

Reading analog sensor values

Understanding pulse-width modulation (PWM)

Controlling LED brightness or other suitable outputs

Mapping sensor readings to control behavior

Learning about sampling, resolution, and timing considerations

Planned project: ADC and PWM-Based Controller.

**text** 6. Peripheral Communication: I2C and SPI

Learn the fundamentals of communication between a microcontroller and external peripherals.

Understanding serial communication protocols

Comparing I2C and SPI

Learning about buses, clock signals, addressing, and data transfers

Reading data from external sensors or peripheral devices

Structuring communication code into reusable functions or drivers

Handling communication failures and unexpected responses

Planned project: Sensor Monitor using an external sensor and an appropriate communication interface.

**text** 7. State Machines and Modular Firmware Architecture

Progress from small demonstrations toward firmware that is easier to maintain, test, and extend.

Designing finite state machines (FSMs)

Separating hardware initialization, peripheral drivers, application logic, and utility functions

Organizing code into reusable C source and header files

Defining clear interfaces between software modules

Managing state transitions and error conditions

Improving readability, maintainability, and testability

Goal: Apply these concepts across the projects above rather than treating each program as a standalone demonstration.

**text** 8. Debugging, Testing, and Development Tools

Develop the habits needed to investigate firmware issues systematically.

Using Code Composer Studio (CCS) to build, flash, and debug firmware

Setting breakpoints and stepping through code

Inspecting variables, memory, and hardware registers

Diagnosing compiler, linker, and runtime issues

Using datasheets and technical reference manuals to understand hardware behavior

Testing normal operation, edge cases, and unexpected inputs

Using Git and GitHub to track changes and document progress

**text** 9. Capstone: Embedded Monitoring System

Combine the concepts from earlier projects into a more complete microcontroller-based system.

The intended system will use one or more peripherals or sensors to collect data, process inputs, and report or respond to system conditions.

Potential features include:

Periodic sampling using hardware timers

Interrupt-driven event handling

Sensor communication through I2C or SPI

Data reporting through UART

A state machine for application behavior

Modular drivers and application code

Error handling and documented testing

The exact scope will evolve as I gain experience and identify opportunities to apply what I have learned.
