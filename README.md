# Bluetooth Remote Controlled Forklift

## Introduction

The project represents a four-wheeled RC forklift that is being controlled via Bluetooth, which has moving forks. The carriage's movement is being detected by sensors and signaled through a specific sound and blinking light.

The idea started from my passion for forklifts, that i enjoyed watching growing up, and RC cars, which were a total mystery to me. Also, tinkering is something that i have been doing for my whole life. With that being said, this project harmoniously combines many of my passions and interests.

## General Description

The RC forklift has a sliding carriage with attached forks, the movement of which is detected by sensors. They, not only signal to the buzzer and the LED that the carriage is still moving so those can play the set sound and blinking light, but have the role of detecting the ends of the sliding carriage. Two motors connected to the front wheels ensure the movement, as well as the steering of the forklift. This whole project revolves around the ESP32 as the main microcontroller.

## Hardware Design

### Components
- 1x ESP32
- 2x Motors
- 1x Buzzer
- 1x RGB LED
- 1x Resistor (220 Ohm)
- Jumper Wires

| # | Name | Quantity | Useful Links |
|1   |  [ESP32 DevKit V1](https://www.sigmanortec.ro/placa-dezvoltare-esp32-cu-wifi-si-bluetooth) | 1  |  [link](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32d_esp32-wroom-32u_datasheet_en.pdf)  |
| 2  |  [Dual H-Bridge Motor Driver L298N](https://www.sigmanortec.ro/Punte-H-Dubla-L298N-p125423236) | 1  | [link](https://www.st.com/resource/en/datasheet/l298.pdf)  |
| 3  |  [TT Gear Motor with Wheels [1:48 Gear Ratio]](https://www.sigmanortec.ro/Kit-Motor-reductor-Roata-plastic-cu-cauciuc-p134585625) | 4   |  N/A  |
| 4  |  [Li-Ion 18650 Battery, 3.7V, 2200mAh](https://www.dedeman.ro/ro/acumulator-li-ion-well-18650-3-7v-2200-mah/p/1050265) | 2   |    N/A |
| 5  |  [Li-Ion 18650 Battery Case with On/Off Switch](https://www.sigmanortec.ro/Suport-baterie-18650-2S-cu-capac-si-intrerupator-p192040353) | 1   |    N/A |
| 6  |  GP2Y0A21YK0F Infrared Distance Sensor | 1   | [link](https://global.sharp/products/device/lineup/data/pdf/datasheet/gp2y0a21yk_e.pdf)  | 
| 7  |  [MicroSD Module](https://www.sigmanortec.ro/Modul-MicroSD-p126079625) | 1      | N/A|
| 8  |  Mini Audio Amplifier PAM8403 | 1  |  [link](https://www.mouser.com/datasheet/2/115/PAM8403-247318.pdf?srsltid=AfmBOoqdyrw5H8aEVmHnLDsAMdP0bwbvcuJrRvT6vCjeOBP84tMt8KNv) |
| 9  |  2.5W, 4 Ohm Speaker | 1  | N/A |
| 10  |  Red LED | 2   | N/A |
| 11  |  Clear Blue LED | 2  | N/A |
| 12  |  220 Ohm Resistor | 4  | N/A |

### Circuit diagram

TODO

## Software Design

For this project I will be using Arduino IDE.

## Results

## Conclusions

## Resources
