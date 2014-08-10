### Balua_AIO_Tracker_V1.0 - Board with finished schematic but with open layout and still to be tested...

#### Updated version of the original tracker found in the Balua_tracker repository with extra features and small corrections


#### Features:

#####Microprocessor
- ATMEGA 328p smd package

#####Power
- Step up Boost Converters from 2 AA Batteries to 3.3V and 5V

#####Communication
- Radiometrix HX1 - VHF Narrow Band FM High Power (300mW) Transmitter with SMA Antenna
- RFM22B ISM Transceiver Module with SMA Antenna

#####GPS
- Ublox Max 7 GPS with Quad V GPS antenna with jumpers in the RX/TX line and in the I2C for hardware selectable communication mode

#####Sensors
- SMD Onewire temperature sensor - DS18B20
- Battery Voltage sensing
- 0-15psi Pressure Sensor SMT mount - HSCSANN015PA2A3
- 9-axis Motion Tracking MEMS (3-axis gyroscope, 3-axis accelerometer and magnetometer) - MPU-9150 

#####Storage
- MicroSD Socket

#####Programming
- SMD AVR SPI Programming pins available

#####External pins
- I2c Pins with pull-up for expansion available
- 2 pins for Software Serial
- 2 pins for Hardware Serial
- Power Pins (VBatt, 5V, 3.3V and GND)
- Power pins for Cutoff system

#####Other
- On Board AA battery holder
- 5V boost converter with enable controllable
- UBlox GPS Power ON Controllable
- RFM22B Radio enable pin Controllable
- On board LED
- Cutoff System implemented
