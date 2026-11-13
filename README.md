# STM32 Electronic Dice

An electronic dice project built around the STM32F103C8T6 microcontroller. The board includes fourteen LEDs, two push buttons and five 2N7000 transistors.

![PCB rendering](hardware/images/pcb-3d.png)

## Hardware

[Altium project](hardware/altium/stm32-electronic-dice.PrjPcb) · [Top layout](hardware/images/pcb-layout-top.png) · [Bottom layout](hardware/images/pcb-layout-bottom.png)

## Drawings

- [E1 block diagram](docs/original-ru/stm32-electronic-dice_E1_block-diagram.PDF)
- [E2 functional diagram](docs/original-ru/stm32-electronic-dice_E2_functional-diagram.PDF)
- [E3 schematic](docs/original-ru/stm32-electronic-dice_E3_schematic.PDF)
- [PE3 parts list](docs/original-ru/stm32-electronic-dice_PE3_parts-list.pdf)
- [PP board drawing](docs/original-ru/stm32-electronic-dice_PP_board-drawing.PDF)
- [SB assembly drawing](docs/original-ru/stm32-electronic-dice_SB_assembly-drawing.pdf)
- [SP specification](docs/original-ru/stm32-electronic-dice_SP_specification.pdf)

## Bill of materials

The [CSV export](docs/stm32-electronic-dice.csv) lists 43 components. It specifies 47 µF for C5. The included ActiveBOM was prepared from an earlier schematic revision. Verify its grouping and capacitor part numbers before ordering.

| Reference | Qty | Value or part |
| --- | ---: | --- |
| C1, C7, C8 | 3 | 10uF |
| C2, C3, C4, C6 | 4 | 0,1uF |
| C5 | 1 | 47uF |
| DA1 | 1 | AMS1117 |
| DD1 | 1 | STM32F103C8T6 |
| HL1, HL2, HL3, HL4, HL5, HL6, HL7, HL8, HL9, HL10, HL11, HL12, HL13, HL14 | 14 | HL_LED |
| R1, R2, R3, R4, R5 | 5 | 10k O |
| R6, R7 | 2 | 100 O |
| R8 | 1 | 220 O |
| SW1, SW2 | 2 | SW_Switch |
| VD1, VD2 | 2 | 1N4148 |
| VT1, VT2, VT3, VT4, VT5 | 5 | 2N7000 |
| XS1 | 1 | 2Pin 5.0mm |
| XS2 | 1 | 4Pin 5.0mm |

## Fabrication files

[Gerber archive](fabrication/stm32-electronic-dice_gerber.zip) · [STEP model](fabrication/stm32-electronic-dice.step)
