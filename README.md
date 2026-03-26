## Parts Required

- 1x ESP WROOM 32
- 1x micro USB to USB connector
- 1MB102 830 pin Breadboard
- 1x RGY / RGB light (Common anode)
- 1x Register
- Jumper wires
- 2x Rubber bands (optional)

## Circuit
<img width="580" height="660" alt="circuit" src="https://github.com/user-attachments/assets/9074a57c-be3a-4924-b7b1-817b144fe7ff" />

## Instructions
- can choose any but I chose GPIO pin 5 and 19 to connect to the 2 cathodes of my led.
- The anode got the 3.3 -> 220 Ohm Register -> anode
- The unit is powered my micro USB.
- I used only 2 of the colors from the led, red for "-" and green for "."
- Special chars were not handled. 

## Refrences
- https://esp32.implrust.com/
- https://docs.espressif.com/projects/rust/book/getting-started/toolchain.html
