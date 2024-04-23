This repo contains config files for my build of Voron Legacy.

I'll add profiles for OrcaSlicer as soon as I tweak it.

Printer specs:

- BTT Octopus V1.1
- Raspberry Pi 4
- Printing area: 235x235x240
- Afterburner toolhead (Direct-Drive)
- Phaetus Dragon ST hotend
- Inductive probe PL-xxx
- X and Y sensorless homing
- RPi4 as secondary MCU
- RepRap LCD 2004
- TMC2209 on X,Y and E
- TMC2208 on Z.
- Dual Z drivers

Features: 

- Switching beetween silent/perfomance stepper mod using gcode macros.
- Adaptive meshing
- Adaptive purging
- Smart park 
- Auto shutdown printer after print finished and hotend is below 50C. Via smart plug with Tasmota FW.*  

Used pluggins: KAMP, TMC Auto Tune, auto-power-off-klipper

To-Do list:

- Webcam support
- LED stripe control via RPi GPIO
- Resonance Compensation aka Input shaper with ADXL345
- Shutdown RPi before turning off Tasmota smart plug.*


  
