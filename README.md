# Cinnamoroll-blinky-board
A blinky board in the shape of cinnamoroll!!
A 555 timer LED chaser in a PCB shaped in the shape of cinnamoroll. 
The 10 LEDs glow in a sequence using a potentiometer/variable resistor

# Components
- 555 Timer IC
- 10x LEDs of any color
- CD4017 IC (a decade counter for the LEDs)
- 1 electrolytic capacitor
- 1 normal capacitor
- 2x resistors (1kΩ and 470Ω)
- Power connector
- 1 potentiometer

# Softwares used
KiCAD 9.0 --> PCB and Schematic

# Working
The 555 timer works in astable mode and gets clock signals. The CD4017 IC then 'counts to 10' (as a decade counter) by activating its 10 outputs one at a time, thereby making the LEDs light up one by one in a 'chasing' manner. The potentiometer is used to control the speed of this chase.


<img width="1388" height="699" alt="Screenshot 2026-04-09 184306" src="https://github.com/user-attachments/assets/24c80df0-f25c-42d4-817a-5b234520b710" />
