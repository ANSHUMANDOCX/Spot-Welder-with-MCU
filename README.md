# Spot Welder with MCU
## Description
- This is a Mosfet Based Spot welder made using IRFB7430 mosfet paired with a OLED display, rotary encoder and ATMEGA328P IC. This is a projet inspired by [This Project](https://www.instructables.com/DIY-Arduino-Battery-Spot-Welder/) 
- This is a two PCB Design and made such that one can order the PCB as a whole and has to separate the PCBs by Cutting manually to save cost.
- It has two Aluminum parts that attach to the PCB since the circuit will be dealing high current of about 400A in a single pulse
- The pulse timing can be adjusted using the rotary encode and is very simple to use.
- It has a onboard programmer for the ease of programming the board 
## Parts used 
- IRFB7430 Mosfet
- Atmega328p as the MCU 
- 0.96 128x64 oled display
- ABR-PR-12APBTX90 Amaron 12v 9Ah Battey for high short pulse current
- 6AWG wire to handle the high current
- 4010 fan 
## PCB Schematic and CAD 
<img width="1174" height="813" alt="Screenshot 2026-03-18 173154" src="https://github.com/user-attachments/assets/cbb075f6-b4ce-46c3-a354-a777d824c654" />
<img width="717" height="483" alt="Screenshot 2026-03-18 182859" src="https://github.com/user-attachments/assets/6668426d-fe12-4133-ae64-42253d59d1c6" />
<img width="979" height="615" alt="Screenshot 2026-03-18 183110" src="https://github.com/user-attachments/assets/f49a7147-a671-4f9d-8206-8e8168321385" />
<img width="780" height="577" alt="Screenshot 2026-03-19 000905" src="https://github.com/user-attachments/assets/836cb685-8498-4be3-ab65-ca320c1a61ed" />
<img width="921" height="719" alt="Screenshot 2026-03-19 000851" src="https://github.com/user-attachments/assets/17319b98-9443-44a0-8daa-a78deff73315" />
<img width="617" height="627" alt="Screenshot 2026-03-18 234639" src="https://github.com/user-attachments/assets/1ee67ee1-f378-4aaa-aea5-054328b444e9" />

## BOM 
| Name                      | Purpose                         | Cost Per Item (USD) | Quantity | Total (USD) | Link | Distributor     |
|---------------------------|---------------------------------|---------------------|----------|-------------|------|-----------------|
| SHIPPING JLC+LCSC         | SHIPPING                        | 10.00               | 1        | 10.00       | [LINK](https://lcsc.com) | LCSC, JLC       |
| Aluminum parts+ PCB       | PCB + Aluminum Block            | 6.00                | 1        | 6.00        | [LINK](https://jlccnc.com) | JLCCNC, JLCPCB  |
| FAN                       | to disspate heat                | 0.70                | 1        | 0.70        | [LINK](https://makerbazar.in/products/generic-axial-dc-cooling-fan-blowers?variant=46306240004336) | Maker Bazar     |
| Passive Component         | Resistor diodes and Capacitor   | 6.06                | 1        | 6.06        | [LINK](https://lcsc.com) | LCSC            |
| 6AWG wire                 | Heavy duty wires                | 4.73                | 1        | 4.73        | [LINK](https://makerbazar.in/products/flexible-silicon-wire?variant=45564209725680&country=IN&currency=INR&gad_campaignid=17426677322) | Maker Bazar     |
| Battery 9ah               | the battery                     | 18.25               | 1        | 18.25       | [LINK](https://www.flipkart.com/amaron-abr-pr-12apbtx90-9-ah-battery-bike/p/itmd23986a4bee47?pid=VEBGSMF6ZHXYFG7V&lid=LSTVEBGSMF6ZHXYFG7VQWILCD&marketplace=FLIPKART&cmpid=content_vehicle-battery_22371611432_x_8965229628_gmc_pla&tgi=sem,1,G,11214002,x,,,,,,,c,,,,,,,&entryMethod=22371611432&&cmpid=content_22371611432_gmc_pla&gad_campaignid=22371673895) | Flipkart        |
| MCP1407-E/SN              | gate driver                     | 1.75                | 1        | 1.75        | [LINK](https://www.lcsc.com/product-detail/C52138.html) | LCSC            |
| 5.0SMDJ13A                | diode                           | 0.42                | 4        | 1.70        | [LINK](https://www.lcsc.com/product-detail/C5295091.html) | LCSC            |
| IRFB7430PBF(UMW)          | Mosfets                         | 0.44                | 10       | 4.43        | [LINK](https://www.lcsc.com/product-detail/C19100591.html) | LCSC            |
| CH340K                    | USB UART                        | 0.62                | 1        | 0.62        | [LINK](https://www.lcsc.com/product-detail/C968586.html) | LCSC            |
| Oled                      | to show the timer               | 2.17                | 1        | 2.17        | [LINK](https://www.lcsc.com/product-detail/C5248080.html) | LCSC            |
| Rotary encoder            | to set the timer                | 1.42                | 1        | 1.42        | [LINK](https://www.lcsc.com/product-detail/C19712528.html) | LCSC            |
| 3.3uH 20mΩ Inductor       | Inductor                        | 0.71                | 1        | 0.71        | [LINK](https://www.lcsc.com/product-detail/C7588932.html) | LCSC            |
| TPS563201DDCT             | Regulator                       | 0.46                | 1        | 0.46        | [LINK](https://www.lcsc.com/product-detail/C2070819.html) | LCSC            |
| ATMEGA328P-AU             | MCU                             | 2.17                | 1        | 2.17        | [LINK](https://www.lcsc.com/product-detail/C14877.html) | LCSC            |
| **Grand Total**           |                                 |                     |          | **63.17**   |      |                 |
