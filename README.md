⚡ 5V AC to DC Converter

📌 Overview

This project demonstrates the conversion of an AC input into DC output using a bridge rectifier circuit and a filter capacitor. It is designed to demonstrate the fundamental principles of rectification, filtering, and DC power supply circuits.

The circuit uses four 1N4007 diodes arranged in a bridge rectifier configuration to convert AC into pulsating DC. A capacitor is then used to reduce ripple, while an LED indicates the presence of power.

🎯 Project Objectives

Convert AC voltage into DC voltage.

Understand the working principle of a bridge rectifier.

Reduce output voltage ripple using a filter capacitor.

Indicate power availability using an LED.

Design a circuit schematic and PCB using KiCad.

⚙️ Components Used

Component

Specification

Quantity

Diodes

1N4007

4

Capacitor

1000 µF

1

Resistor

2.2 kΩ

1

Resistor

10 kΩ

1

LED

5 mm

1

Terminal Block

2-pin

2

🔌 Circuit Design

The circuit consists of three main stages:

Bridge Rectifier: Four 1N4007 diodes convert AC input into pulsating DC.

Filtering Stage: A 1000 µF capacitor smooths the rectified output by reducing voltage ripple.

Indicator Stage: An LED with a current-limiting resistor indicates power availability.

🔄 Working Principle

1. AC Input

The AC voltage is supplied through the input terminal block.

2. Rectification

The four diodes form a full-wave bridge rectifier. Both halves of the AC waveform are converted into the same polarity at the output.

3. Filtering

The 1000 µF capacitor charges during the rectification process and discharges between peaks, helping to provide a smoother DC voltage.

4. Power Indication

The LED connected with a 2.2 kΩ resistor acts as a visual indicator of power at the circuit.

🛠️ Tools Used

KiCad – Schematic design and PCB layout.

Electronic Components – For circuit implementation and testing.

📷 Project Preview

Add your schematic, PCB layout and physical circuit photos here.

🚀 Future Improvements

Add a voltage regulator for a stable 5V DC output.

Improve filtering to reduce voltage ripple.

Perform PCB layout optimisation.

Test the circuit under different load conditions.

⚠️ Safety Note
This circuit is intended for educational purposes. AC voltage can be dangerous. Use an appropriately isolated, low-voltage AC source for testing. Do not connect the circuit directly to mains electricity.

The circuit shown does not include a voltage regulator, so the output is not guaranteed to be a regulated 5V DC supply.
This circuit is intended for educational purposes. AC voltage can be dangerous. Use an appropriately isolated, low-voltage AC source for testing. Do not connect the circuit directly to mains electricity.

The circuit shown does not include a voltage regulator, so the output is not guaranteed to be a regulated 5V DC supply.
