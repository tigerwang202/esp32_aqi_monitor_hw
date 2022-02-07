# ESP32 AQI(Air Quality Index) Monitor Hardware

This repository contains ESP32 AQI(Air Quality Index) monitor's hardware design files, including schematics, PCB layout, Mechanical Assembly documents.

![CAD real view](.\Mechanical_Assembly\cad_view.png)


## PCB Manufacturing Notes:

The thickness of the PCB board is 1.6mm.

## Mechanical Assembly Notes

The device consists of 2 PCB boards, the vertical PCB board is called the display board, the horizontally placed PCB board is called the interface board.The two PCB boards are connected by two double-row 4*2 2.0mm pitch pin headers. The LCD screen is glued to the display panel by double-sided adhesive. The underside of the interface board is supported by 4 5mm high knurled studs with a 2.0mm hold. All screws are M2 size.

Print this [file](.\Mechanical_Assembly\wood_case_drilling_hole(scale_1_1).pdf) in 1:1 scale on A4 size paper to determine the location of the casing opening.

MCU firmware is at [esp32_aqi_monitor](https://github.com/tigerwang202/esp32_aqi_monitor) repository.
