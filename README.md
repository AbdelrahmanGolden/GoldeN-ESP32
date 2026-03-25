
# GoldeN-ESP32

This project presents a custom-designed ESP32 development board created to solve common issues found in standard dev boards:
- Noise during code uploading
- Incompatibility with breadboards
- Risk of damage when connecting USB and external 5V simultaneously


## Problems in Existing Boards
Many ESP32 boards suffer from:
- Unstable serial communication during flashing (due to poor layout / noise)
- Cannot fit on breadboards
- No proper power path management → risk of backfeeding and burning components

## My Solution
This custom PCB introduces:
- Safe Power Path Design
- Prevents current conflict between USB and external 5V input
- Noise-Reduced Layout
- Improved grounding and decoupling
- Better signal routing for stable uploading
- Breadboard-Compatible Design
- Standard 2.54 mm pin spacing
## Tools Used
EasyEDA (schematic + PCB design)
## Hardware Features
- ESP32 module
- 3.3V voltage regulation
- USB to UART interface
- Dual power input (USB + external 5V)
- Protection against reverse/back power
## Files Included
-  Manufacturing: BOM and Gerber Files needed if you want to manufacture the ESP32.
- Photos: All Photos taken to the ESP32.
- Refrence: The main Datasheets I took as a refrence during the design of this ESP32 PCB.
- Schematic: The PDF of the schematic, you can take it as a refrence for your future projects.
## Future Improvements
- USB-C support
- Improved EMI shielding
- On-board debugging interface
## Author
- [@Abdelrahman Abdelkhaliq](https://github.com/AbdelrahmanGolden)

Embedded Systems Engineer

