# mini-ems-arduino
Mini DC Microgrid Energy Management System using Arduino UNO
# Mini Energy Management System (EMS) – Arduino

## Objective
Design and simulate a small-scale Energy Management System (EMS) that monitors
voltage, current, power, and temperature from a DC microgrid and controls loads
based on priority and power thresholds.

## System Overview
- Power Source: 12V DC Adapter / Battery
- Controller: Arduino UNO (ATmega328P)
- Sensors:
  - INA219 (Voltage, Current, Power)
  - ACS712 (Load Current)
  - DHT11 (Temperature)
- Actuators:
  - 2-Channel Relay Module
- Display:
  - 16x2 LCD (I2C)

## Load Priority
1. Fan (Critical)
2. LED (Moderate)
3. DC Motor (Optional)

## EMS Logic
1. Read voltage, current, temperature
2. Compute power: P = V × I
3. Compare with threshold
4. Switch loads using relays
5. Log data via serial interface

## Hardware Components
- Arduino UNO R3
- INA219 Power Monitor
- ACS712 Current Sensor
- DHT11 Temperature Sensor
- 2-Channel Relay Module
- 16x2 I2C LCD
- 12V DC Adapter
- DC Fan, LED, Motor

## Status
- [x] Components procured
- [x] Initial sensor testing
- [ ] Full assembly
- [ ] Data logging
- [ ] Final demo
