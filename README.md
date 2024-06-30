# StepperDriver-Shield_FRDM-MCXA153

This is a shield for the FRDM-MCXA153 microcontroller, developed as part of my mechatronic course project at the Hochschule Wismar, University of Applied Sciences: Technology, Economy and Design.

The board acts as a carrier for the TMC-2209 stepper drivers and allows up to four stepper motors to be controlled simultaneously.

It is designed for 24V operation and has three freely programmable buttons, connections for four limit switches and a manual stepper driver enable circuit.
In addition, by soldering a DC-DC converter to the microcontroller, it is possible to supply 24V through the shield.
![StepperDriver-Shield_FRDM-MCXA153_Top](https://github.com/Fi-schi/StepperDriver-Shield_FRDM-MCXA153/blob/main/pictures/StepperDriver-Shield_FRDM-MCXA153_Top.png)
![StepperDriver-Shield_FRDM-MCXA153_3D](https://github.com/Fi-schi/StepperDriver-Shield_FRDM-MCXA153/blob/main/pictures/StepperDriver-Shield_FRDM-MCXA153_3D.png)

# Parts for the shield

| Qty. | Part          | Size   | Links |
|------|:-------------:|:------:|------:|
|  4x  |     0.1µF     | 0805   |  |
|  4x  |    100µF/35V  | 6.3mm  |  |
|  13x |    10K&Omega; | 0805   |  |
|  4x  |    100&Omega; | 0805   |  |
|  1x  |    1K&Omega;  | 0805   |  |
|  4x  |TVS-Diode 3.3V | 0603   | https://www.mouser.de/ProductDetail/652-CG0603MLC-3.3LE |
|  1x  |   74LVC2G00   |TSSOP-8 | https://www.mouser.de/ProductDetail/771-LVC2G00DP125 |
|  5x  |Tactile Switch | 6x6mm  | https://www.mouser.de/ProductDetail/710-430133050816 |
|  4x  | 1x02 JST_XH   | 2,54mm |  |
|  4x  | 1x04 JST_XH   | 2,54mm |  |
|  1x  | 1x02 PinHeader| 2,54mm |  |
|  8x  | 1x03 PinHeader| 2,54mm |  |
|  9x  | jumper bridge | 2,54mm |  |
|  1x  | AMASS XT60PW-M|        |  |
|  1x  | 2x06 PinHeader (SSW-106-23-G-D) | 2,54mm| https://www.samtec.com/de/products/ssw-106-23-g-d |
|  1x  | 2x08 PinHeader (SSW-108-23-G-D) | 2,54mm| https://www.samtec.com/de/products/ssw-108-23-g-d |
|  2x  | 3x10 PinHeader (SSW-110-23-G-D) | 2,54mm| https://www.samtec.com/de/products/ssw-110-23-g-d |
|  4x  | BTT TMC2019 Stepp Stick | |  |

# Parts for the microcontroller external power supply

| Qty. | Part          | Size   | Links |
|------|:-------------:|:------:|------:|
|  1x  | DC/DC to 5v/500mA| SIP-3  | https://www.mouser.de/ProductDetail/919-R-78CK5.0-0.5 |
|  2x  |    1µF/35V  | 0603  |  |
