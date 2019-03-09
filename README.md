# Unmanned-Aerial-Robots


### Flight Controller

#### I/O
• 6 + 8 PWM I/O can remap as input or output for RC/CPPM/Motors/Servos. Supports varying update rates (50Hz - 32kHz). Direct-drive brushed motors also supported with additional hardware (FETs).
• 8 channel standard PWM RC input
• CPPM (up to 12 channels) RC input
• Second UART accessible for Spektrum Satellite RX or GPS
• MicroUSB connector for firmware updating, configuration and telemetry
• Max 5.5V power via servo connector (rev0-4, rev5acro), Max 16V power via servo connector (rev5)
• Built in FrSky Telemetry converter (rev5)
• Battery voltage monitoring and low-voltage alarm through telemetry/OSD/buzzer
• External buzzer for alarm/user notification
• 2 programmable status LEDs, 1 constant power LED
• One 3.3V and one 5V-tolerant GPIO (rev5)

#### Hardware
• 36x36mm 2 layer pcb, 30.5mm mounting pattern
• STM32F103CxT6 CPU (32bit ARM Cortex M3, 72MHz, 64K/128K flash)
• Invensense MPU6050 3-axis gyro (from rev4 onwards)
• Honeywell HMC5883L digital compass
• MEAS-SPEC MS5611-01BA03 pressure sensor (from rev4 onwards)
• 16Mbit SPI flash memory (rev5)

#### Looptime/Frequency
3500 = 286HZ
3000 = 333HZ
2500 = 400HZ
2000 = 500HZ
1500 = 600HZ
