# Unmanned-Aerial-Robots


### Flight Controller (1 PC)

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


### Electrical Speed Controllers ESCs (4 PCS)
ESCs are a quality speed controller
![ESCs and Brushless DC Motors](./images/An%20ESC%20wired%20with%20a%20Brushless%20DC%20Motor.jpg)

#### Details: 
• Smooth and linear throttle control 
• Fast response to throttle input 
• Atmel MCU
• Stalled motor protection 
• Throttle signal lose protection 
• Safe power-on (throttle lockout) 
• Support 480Hz+ high refresh rates (up to 499hz) 
• Compatible with programming card
![ESC on the Oscilloscope](./images/ESC%20signal%20on%20Oscilloscope.jpg)

#### Specs:
Constant Current: 30A
Input Voltage: 2-6 cells Lipoly
Frequency: 20-500Hz
BEC: Yes (Switching) [Remove middle wire to disable]
BEC Output: 5V/4APWM: 8 KHz
Max RPM: 240,000rpm for 2 Poles Brushless Motor
PCB Size: 41mm x 24mm
Discharge Plugs: Male 3.5mm Bullet Connector
Motor Plugs: Female 3.5mm Bullet Connector
Weight: 35g
#### [Where to buy](https://hobbyking.com/en_us/turnigy-multistar-30-amp-blheli-multi-rotor-brushless-esc-2-6s-v2-0.html)


### Fight Controller Software
We depends on an Open-Source flight controller software which designed for modern flight boards

![flight controller software](./images/cleanflight-anim.gif)
