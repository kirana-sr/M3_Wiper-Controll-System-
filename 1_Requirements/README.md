# Requirement

#Case Study:Wiper Control System

-Blue,Green, Orange ,LEDs

-Come on and OFF alternately for set frequency

- State A,RED led will be ON

Scenario:Wiper Control System

1.ignition Key Position at ACC:The RED LED is ON.if user button is pressed and held for 2 sec

2.Wiper ON:Wiper is OFF: On press of user input,Blue,Green and Orange LEDs come On at a time with the set frequency.The frequency changes on every alternate key 
  press, 3 frequency level with 1,4 and 8 hz
  
3.Wiper OFF:Wiper is ON:The LED glow pattern stops on the 4th press:the wiper action starts next press onwords as mentioned in step 2

4.ignition Key Position at ACC:The RED LED is .if user button is pressed and held for 2 sec


# INTRODUCTION

The operational speed of a wiper is controlled by a wiper speed control system in accordance with frequencies. The pulse signal is digitally processed to provide a control signal. A wiper driver circuit receives the control signal and adjusts the operational speed or timing in line with it.

# SOFTWARE REQUIREMENTS
STM32 CUBE IDE
COMPONENTS
STM32F4O7VG MICROCONTROLLER BOARD

# DESCRIPTION
STM32F407VG
The STM32F407 Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.

# FEATURES OF STM32F407VG MICROCONTROLLER
In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
USB ST-LINK with three separate interfaces and re-enumeration capability.
Virtual Com port Debug port (with new order code only)
Large-scale storage (with new order code only)
Board power is supplied through USB or an external 5 V supply source.
3 V and 5 V external application power supply

# USES

This Microcontroller is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems.
This module can be found in a variety of household products.

#WORKING PRINCIPLE

Assume that the automobile is the microcontroller. If the button is hit, the first led (red) will turn on, Clicking again  the wiper will start, and the second led (blue) will turn on for a desired rate. If the button is pressed again, the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange), and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.

# 4 W'S
# WHAT IS WIPER SYSTEM
Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.

# WHY WIPER SYSTEM 

To keep the windscreen clean enough to give adequate view at all times.

# WHEN SHOULD USE WIPER SYSTEM

The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.

# WHO DISCOVERED WIPER SYSTEM

Mark Anderson invented on 1902
 
