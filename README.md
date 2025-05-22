# slime-nano
The smallest size of Slime VR tracker

### 1.Description

To redo this project, you need certain skills and abilities to solder some very small components. 

At the same time, in order to achieve the minimum size requirement, this version sacrifices performance such as signal strength and PCB board thickness.

The actual tracking performance may not be as good as the official version. Please pay attention when using it.

### 2.Tool requirements

| No. |        Name         |                               Tips                               |
|:---:|:-------------------:|:----------------------------------------------------------------:|
|  1  |     solder iron     |                                -                                 |
|  2  |      Heat gun       |                  Used in electronic engineering                  |
|  3  |    Solder paste     | Low temperature solder paste helps reduce the chance of damaging |
|  4  |     Solder flux     |                                -                                 |
|  5  | Solder flux Remover |                                -                                 |


### 3.BOM list and links.

Please note that I reside in China, so I have used some parts that **may only** be available for sale in China.

If you have better replacement parts or substitutes, you can directly submit an ISSUE to merge or update the purchase link.

**Attention when submitting PCB orders: Please choose the thinnest possible PCB, otherwise it may not fit into the casing. In my example, I used a PCB with a thickness of 0.8mm
Manufacturers may have different quotes for different thicknesses, please choose the one that you think is suitable!**

**The quantity is FOR EACH ONE OF TRACKERS!**

| No. | Quantity |          Type          |     Spec      |                     Designator                     |              Footprint              | Manufacturer Part Number | Manufacturer | Link |
|:---:|:--------:|:----------------------:|:-------------:|:--------------------------------------------------:|:-----------------------------------:|:------------------------:|:------------:|:----:|
|  1  |    1     |        Resistor        |     600Ω      |                         B1                         |                R0603                |            -             |    muRata    |  -   |
|  2  |    4     |       Capacitor        |     10uF      |                   C1,C14,C15,C16                   |                C0603                |   CGA0603X7R104K500JT    |     HRE      |  -   |
|  3  |    3     |       Capacitor        |      1uF      |                      C2,C4,C6                      |                C0603                |   CGA0603X7R104K500JT    |     HRE      |  -   |
|  4  |    4     |       Capacitor        |     100nF     |                    C3,C7,C9,C13                    |                C0603                |   CGA0603X7R104K500JT    |     HRE      |  -   |
|  5  |    2     |       Capacitor        |     22pF      |                       C5,C8                        |                C0603                |     CL10C220JB8NNNC      |   SAMSUNG    |  -   |
|  6  |    1     |       Capacitor        |     3.3nF     |                        C11                         |                C0603                |   CGA0603X7R104K500JT    |     HRE      |  -   |
|  7  |    2     |       Capacitor        |     10uF      |                      C17,C18                       |                C0603                |   CGA0603X5R106K100JT    |     HRE      |  -   |
| 8¹  |    1     |      Contact pin       | PZ254V-11-02P |                         H1                         |                  -                  |         NOT USED         |   NOT USED   |  -   |
| 9²  |    7     |          LED           |   KT-0603W    | LED-25%,LED-50%,LED-75%,LED-100%,LED-B,LED-G,LED-R |                R0603                |         KT-0603W         |    KENTO     |  -   |
| 10  |    1     |         MOSFET         |    AO3401A    |                         Q1                         |   SOT-23_L2.9-W1.3-P1.90-LS2.4-BR   |         AO3401A          |     AOS      |      |
| 11  |    2     |       Transistor       |     S8050     |                       Q2,Q3                        |   SOT-23_L2.9-W1.3-P1.90-LS2.4-BR   |          S8050           |   Hottech    |      |
| 12  |    10    |        Resistor        |     10kΩ      |          R1,R3,R5,R6,R7,R8,R9,R22,R23,R25          |                R0603                |      0603WAF1002T5E      |  UNI-ROYAL   |      |
| 13  |    2     |        Resistor        |     5.1kΩ     |                       R2,R4                        |                R0603                |      0603WAF1001T5E      |  UNI-ROYAL   |      |
| 14  |    4     |        Resistor        |      2kΩ      |                  R10,R12,R11,R15                   |                R0603                |      0603WAF1001T5E      |  UNI-ROYAL   |      |
| 15  |    1     |        Resistor        |     320kΩ     |                        R13                         |                R0603                |      0603WAF1001T5E      |  UNI-ROYAL   |      |
| 16  |    2     |        Resistor        |     100kΩ     |                      R14,R16                       |                R0603                |      0603WAF1001T5E      |  UNI-ROYAL   |      |
| 17  |    1     |        Resistor        |     220Ω      |                        R17                         |                R0603                |      0603WAF1001T5E      |  UNI-ROYAL   |      |
| 18  |    2     |        Resistor        |     5.1kΩ     |                      R18,R19                       |                R0603                |      0603WAF1001T5E      |  UNI-ROYAL   |      |
| 19  |    2     |        Resistor        |     220Ω      |                      R20,R21                       |                R0603                |      0603WAF1001T5E      |  UNI-ROYAL   |      |
| 20  |    1     |        Resistor        |    40.2kΩ     |                        R24                         |                R0603                |      0603WAF1001T5E      |  UNI-ROYAL   |      |
| 21  |    1     |         Switch         |    TS24CA     |                        SW1                         |            SW-SMD_TS24CA            |          TS24CA          |   SHOU HAN   |      |
| 22³ |    1     |          IMU           |    BNO085     |                         U1                         |               BNO08X                |          BNO085          |     CEVA     |      |
| 23  |    1     |       Controller       |    ESP-12F    |                         U2                         |    WIFIM-SMD_ESP-12F-ESP8266MOD     |         ESP-12F          |  Ai-Thinker  |      |
| 24  |    1     |         Diode          |    1N5819W    |                         U3                         |     SOD-123_L2.7-W1.6-LS3.7-FD      |         1N5819W          |  HXY MOSFET  |      |
| 25⁴ |    1     |    DC-DC Converter     | TPS82130SILR  |                         U4                         |    USIP-8_L3.0-W2.8-P0.65-TL-EP     |       TPS82130SILR       |      TI      |      |
| 26  |    1     |   Battery Indicator    |     HX70A     |                         U5                         |  SOT-23-6_L2.9-W1.7-P0.95-LS2.8-BL  |            -             |      -       |      |
| 27  |    1     |   Charge management    |    TP4056     |                         U6                         | ESOP-8_L4.9-W3.9-P1.27-LS6.0-BL-EP  |          TP4056          |     UMW      |      |
| 28⁵ |    1     |      Key control       |    OTPKEY     |                         U7                         |  SOT-23-6_L2.9-W1.7-P0.95-LS2.8-BL  |            -             |    HOKEC     |      |
| 29  |    1     | Serial port conversion |    CH340K     |                         U8                         | ESOP-10_L4.9-W3.9-P1.00-LS6.0-BL-EP |          CH340K          |     WCH      |      |
| 30  |    1     |  USB Type-C connector  | TYPE-C 16PIN  |                        USB1                        |    USB-C-SMD_TYPE-C-6PIN-2MD-073    |       TYPE-C 16PIN       |   SHOU HAN   |      |
| 31  |    1     |       Oscillator       |   32.768kHz   |                         X1                         |          FC-135R_L3.2-W1.5          |      Q13FC13500004       |    EPSON     |      |
| 32  |    1     |        Battery         | 503030-450mah |                         -                          |                  -                  |            -             |      -       |      |


_1. **H1** are used for connect battery, you don't have to buy this._

_2. You can use whatever colors of led, as long as they are 0603 size._

_3. Please do not purchase the 08X module that has already been soldered like the one in official document. Simply purchase the chip separately_

_4. This component is very small, about the size of a grain of rice. If you are unsure if you can complete its welding, please purchase it carefully or use other voltage conversion versions that will be released in the future_

_5. This component is a power on controller, and I am not sure if it is available outside of China. It is packaged in SOT23-6 and has the function of long pressing the button for 3 seconds to power on the device. If you have other better alternatives to choose from, please submit an issue_