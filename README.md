# kiBoard
Full 104-key Keyboard designed as a submission for the **2026 Hackclub Stardance/Outpost Event**, created using KiCAD and Fusion 360. Uses the QMK firmware for ease of use and modularity.

## Features
* Raspberry Pi Pico based microcontroller
* 160 Keys
* Second function row + built in macro pad

## Layout
<img width="1463" height="423" alt="kiBoard" src="https://github.com/user-attachments/assets/99cb0f77-bf4b-42f3-861a-86d042c9cfb6" />

## Enclosure
<img width="2085" height="866" alt="Screenshot 2026-06-19 at 11 47 09 PM" src="https://github.com/user-attachments/assets/724b77c5-ceb0-4e2b-a7fb-980e4420d357" />
-- I made the enclosure screwless so that you could nudge the top on for easier access to the internal board. (feel free to mess with it)


## BOM
| Reference | Qty | Value | Footprint | Datasheet |
|-----------|-----|-------|-----------|-----------|
| A1 | 1 | RaspberryPi_Pico | Module:RaspberryPi_Pico_Common_Unspecified | https://datasheets.raspberrypi.com/pico/pico-datasheet.pdf |
| D1–D158 | 158 | 1N4148 | Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal | https://assets.nexperia.com/documents/data-sheet/1N4148_1N4448.pdf |
| SW1–SW158 | 158 | SW_Push_45deg | Button_Switch_Keyboard:SW_Cherry_MX_1.00u_PCB | |
| SW159 | 1 | SW_Push | Button_Switch_Keyboard:SW_Cherry_MX_1.00u_PCB | |
| U1 | 1 | PCF8574AP | Package_DIP:DIP-16_W7.62mm | https://www.nxp.com/docs/en/data-sheet/PCF8574_PCF8574A.pdf |
