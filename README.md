# BB8 Sequencer

This is my version of a baby 8 sequencer. It has a built-in oscillator or can be driven by another clock source. Either way, the clock can be stopped and single-stepped for tuning. A clock output lets you use this as the clock source for something else, or daisy chain the input clock.

The output is in the range of roughly 0-4V. A switch lets you add or subtract 1V. It uses a standard 16-pin eurorack power header. It is 11HP wide.

## BOM

| Qty | Designator | Part | Notes |
| --- | --- | ---- | ----- |
|   1 | U3 | CD4022 |
|   1 | U2 | TL072 |
|   1 | U1 | CD40106 |
|   3 |    | 8-pin DIP socket | optional
|   1 |    | 14-pin DIP socket | optional
|  11 | R7, R8, R9, R10, R11, R12, R13, R21, R22, R23, R24, R26, R27 | 1k resistor 1/4W | Increase for dimmer LEDs
|   1 | R4 | 2.2k resistor 1/4W |
|   1 | R2 | 6.8k resistor 1/4W |
|   3 | R5 | 10k resistor 1/4W |
|   1 | R3 | 33k resistor 1/4W |
|   7 | R6, R15, R17, R18, R19, R20, R25 | 100k resistor 1/4W |
|   9 | R1, VR1, VR2, VR3, VR4, VR5, VR6, VR7, VR8 | B100k Alpha potentiometer | 
|   1 | R16 | 100k 3296W trim pot |
|   5 | C2, C6, C7, C8, C9 | 100nF capacitor | 0.1" pitch
|   4 | C1, C3, C4, C5 | 10uF electrolytic capacitor | One is for the oscillator, the others are for decoupling
|   8 | LED1, LED2, LED3, LED4, LED5, LED6, LED7, LED8 | 3mm LED |
|  10 | D1, D2, D3, D4, D5, D6, D7, D8, D9, D10 | 1N4148 |
|   2 | D11, D12 | BZX55B2V4 2.4V zener diodes | Or something similar
|   3 | J1, J2, J3 | Thonkiconn jacks |
|   1 | S2 | ON-OFF-ON mini toggle |
|   1 | S1 | ON-OFF-MOM mini toggle |
|   1 | J8 | 16-pin shrouded header | Substitute nonpolarized header at your own risk

## License

* You are free to build this design, modify it, and use parts of it in other designs.
* Most PCB fabs have a minimum order of 5 units. You may sell excess PCBs as bare PCBs, kits, or fully assembled modules. Just don't order extras with the intent of selling them.
* If you make substantial changes to the design, then you may treat the design as your own. For example, adding features, removing features, or changing the form factor. Changing the font on the panel and other superficial changes would not count.
* I urge you to release any derivative works under similar terms, but you don't have to.
