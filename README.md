# Potentiometer-controlled-head-massager
## Overview
This project is a simple massage machine circuit. The circuit uses a 9V battery, a potentiometer, an NPN transistor, and multiple DC motors. The potentiometer allows adjustment of the motor speed/intensity by controlling the transistor, which acts as a switch and current amplifier.

## Components Used

| Component | Quantity |
|------------|----------|
| 9V Battery | 1 |
| 25 kΩ Potentiometer | 1 |
| NPN Transistor | 1 |
| 100 Ω Resistor | 1 |
| DC Motors | 3 |
| Connecting Wires | As required |

## Circuit Description

- The **9V battery** provides power to the circuit.
- The **25 kΩ potentiometer** adjusts the base current supplied to the transistor.
- The **NPN transistor** controls the amount of current flowing through the motors.
- The **100 Ω resistor** limits current and helps protect the transistor.
- Three **DC motors** are connected in the output stage to generate vibrations.

By rotating the potentiometer, the transistor receives different base currents, which changes the current delivered to the motors and therefore their rpm

## Features

- Adjustable motor speed for confortable relief
- Simple analog control system
- Low component count
- Easy to prototype and modify
- Begginer friendly

## How It Works

1. Power is supplied by the 9V battery.
2. The potentiometer varies the voltage/current reaching the transistor base.
3. The transistor regulates current flowing through the motors.
4. Motor speed and vibration strength change according to the potentiometer setting.

## Applications

- Basic massage devices
- Motor control experiments
- Electronics learning projects

## Challenges Faced

- I struggled with finding a suitable resistor value as I only used 330 ohm resistors from the beggining but due to the need to protect the transistor and have precise control over the motors. Due to a lack of part number on my dc motors I had to rely on trial and error to find the resistor value as I couldn't use OHM's Law.
- At first I was trying to connect the potentiometer directly to the motors which didn't work as only a small amount of current was let through causing the motor's rpm to decrease.

## Lessons Learned

- How to use a tranistor as a signal amplifier
- How to use pre-existing data to make educated guesses (finding the correct resistor value)
