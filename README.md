# Features
- Afro ESC hex files for quadcopter with motor ID 1,2,3, & 4
- I2C address 0x29, 0x2A, 0x2B & 0x2C (40,41,42 & 43)

--------
# Afro ESC I2C assignment
- Default firmware ships for motor #1 only. User needs to build and flash firmware for other motor index. https://github.com/sim-/tgy/blob/master/tgy.asm#L173
- Set I2C_ADDR to 0x50 (default motor start address). Then change MOTOR_ID to 1, 2, 3, 4,... etc to match motor index, rebuild firmware, and flash afro_nfet.hex using USB linker.

--------
# Hardware 
- Uploaded in supporting files folder

--------
# Notes
For SimonK source code, binaries, and other information, see GitHub, SimonK ESC
firmware compatability chart and [SimonK's tgy](https://github.com/sim-/tgy) — Open Source Software. 