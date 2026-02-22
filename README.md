Atmel C51ASM V1.2 assembler used for assembling the Source Assembly File. CH552T uses internal 24 MHz oscillator. Also uses on-chip internal xRAM. All the pins of PORT1 is available. The code also contains the I2C extension which is useful for interacting with I2C devices. SFR read and write also implemented which is useful for exploring the internal registers and ports. 
## CH552T TOP
<img width="2847" height="2000" alt="CH552T_TOP" src="https://github.com/user-attachments/assets/4362dc87-7127-4560-ad7e-b9e0e7bab565" />

## CH552T BOTTOM
<img width="2851" height="2000" alt="CH552T_BOT" src="https://github.com/user-attachments/assets/23c3921f-fe93-4bdf-a29f-e6d626866a6b" />

All the passive components are 0603 size. Resistor R1 and PWR LED used for power indicator.

Resistor R2 (10k) used to pulled down the HW RESET line to LOW.
IC U1 is CH552T and IC U51 can be CH551G or CH552G. We can also use CH554G which is over kill for this application.

R1	330E	0603
R2	10k	0603
C1	0.1uF	0603
C4	0.1uF	0603
C2	0.1uF	0603
C3	10uF	0603
C5	0.1uF	0603
C6	10uF	0603
PWR	LED	0603
U1	CH552T	TSSOP20
U2 	CH551G	SOP16
X0120	20 pin machined header	2.54mm
X2140	20 pin machined header	2.54mm
uUSB	5 pin square pin Header	2.54mm
[+5-]	2 pin Header	2.54mm
<img width="339" height="361" alt="image" src="https://github.com/user-attachments/assets/abd5cd86-a135-41c9-8c93-1c63ff25ef36" />

