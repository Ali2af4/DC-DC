# Dimmable LED Driver using TPS54331D

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is a high-efficiency DC-to-DC buck converter designed to power and control the brightness (dimming) of an LED. It is ideal for applications requiring precise and efficient LED current control.

## Key Features

* **High Efficiency:** Achieved by using the `TPS54331D` switching regulator.
* **Adjustable Output:** Allows for precise brightness control via a potentiometer.
* **Wide Input Voltage Range:** Capable of operating from a wide range of input voltages (typically 3.5V to 28V).
* **Compact Design:** Designed for a small footprint on the Printed Circuit Board (PCB).

## Circuit Schematic

The complete circuit schematic is shown below:

<img src="./Screenshot%202025-06-08%20223356.png" alt="PCB Layout of the Dimmable LED Driver" width="600">

## Key Components

* **Regulator IC:** `TPS54331D` (Texas Instruments)
* **Schottky Diode:** `SS34`
* **Inductor:** `10uH`
* **Potentiometer:** `5kΩ` (for dimming control)

## How It Works

The circuit utilizes the `TPS54331D` IC to step down an input voltage (which can be supplied via USB) to a lower, regulated output voltage. By adjusting the potentiometer in the feedback loop, the reference voltage is altered, which in turn controls the output voltage and the current flowing through the LED. This process allows for smooth dimming of the LED's brightness.

## Tools Used

* **Schematic & PCB Design:** Altium Designer (or Cadence / Proteus)
