Atmel C51ASM V1.2 assembler used for assembling the Source Assembly File. CH552T uses internal 24 MHz oscillator. Also uses on-chip internal xRAM. All the pins of PORT1 is available. The code also contains the I2C extension which is useful for interacting with I2C devices. SFR read and write also implemented which is useful for exploring the internal registers and ports. 
## CH552T TOP
<img width="2883" height="1015" alt="simpleCH552T_14012024T" src="https://github.com/user-attachments/assets/0606f393-09e7-48b9-ab9e-7a9910720948" />

## CH552T BOTTOM
<img width="3000" height="2000" alt="CH552T_BOT" src="https://github.com/user-attachments/assets/53b7b482-16c5-4905-8470-05b3c4aad443" />

All the passive components are 0603 size. Resistor R1 and PWR LED used for power indicator.

Resistor R2 (10k) used to pulled down the HW RESET line to LOW.
IC U1 is CH552T and IC U51 can be CH551G or CH552G. We can also use CH554G which is over kill for this application.
