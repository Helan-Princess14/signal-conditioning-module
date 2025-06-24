# 📈 Signal Conditioning Module for Sensor Interface

This project involves the design and implementation of a signal conditioning module used for interfacing analog sensors to microcontroller ADC inputs.

## 🧠 Purpose

To convert and filter raw sensor signals into a suitable range and quality for ADC sampling on C2000 microcontroller.

## ⚙ Features

- ⚡ Level shifting and amplification using Op-Amps (LM358)
- 🔄 Precision voltage reference for ADC scaling
- 🧲 Tested with Function generator
- 💾 Designed and developed in KiCAD

## 🛠 Components Used (Through hole)

- LM358 Op-Amp
- Voltage Divider Circuit using resistors
- RC Filter using capacitors
- Varistors
- Inductors
- Diodes
- Power supplies(+3V,+5V)

## 📊 Results

- Reduced noise and ripple by ~70%
- Output scaled to 0-3.3V for C2000 ADC
- Improved ADC accuracy from ±200mV to ±20mV

