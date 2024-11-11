# STM32 CAN-Do! Development Board
|Layout|3D View|
|------|-------|
|<img src ="/images/stm32-can-do-layout.png?raw=true">|<img src="/images/stm32-can-do-3d.png?raw=true">|

A development board featuring:
- A STM32F103C8 microcontroller
- External high-speed crystal oscillator
- GPIO breakout, SWD and USB connectors
- CAN transceiver
- 5V LDO regulator
- 24V buck converter

This was primarily designed for testing CAN communication and voltage regulation before a
final design which will be used in the OSU DAM Robotics Club Mars Rover gripper.

This board is a bit of a step up in complexity from my previous boards, and due to
time constraints, wasn't able to do as much due dillgence and research as I'd have likes.

In future boards/revisions, I would like to revisit voltage regulators as newer chips
could be used and give more care to layout (which is not done as well as it could be here).
Also plan to learn more about designing 4-layer boards as the CAN and USB signal routing here
is not great at all and could use additional layers for signal integrity and ease of routing.

## Schematic
See `stm32-can-do-schematic.pdf` for full board schematic.

## Manufacturing
See the `KiCad/Manufacturing` folder. This contains the necessary
Gerber and BOM files for manufacturing by JLCPCB.

## License
This project is licensed under the MIT license and is completely free to use and modify.
