# ArtilleryGenius

Firmware Artillery Genius With Mods

MODS:
    - Upgrade with e3d Volcano Eruption Pack: Need upgrade TEMP_SENSOR_0 with value 5. Upgrade e3d Thermistor to Semitec 104GT2 
    - Upgrade with e3d Nozzle X .4/1.75

- Marlin 1.1:
    - #define TEMP_SENSOR_0 5
    - Calibration Extruder set new Value to 478.49

- Marlin 2.0. bugfix   

- Marlin 2.0.6.1
    - #define TEMP_SENSOR_0 1
    - Calibration Extruder set new Value to 478.49
    - #define DEFAULT_Kp 15.32
    - #define DEFAULT_Ki 1.18
    - #define DEFAULT_Kd 49.88 
    - #define DEFAULT_bedKp 23.94
    - #define DEFAULT_bedKi 2.66
    - #define DEFAULT_bedKd 143.82

- Marlin 2.0.7.2
- Marlin Molise MOD 2.0.8 + BLTOUCH
- Marlin Molise MOD 2.0.9.1 + BLTOUCH + TFT MOD 5.2

GCODE COMMANDS:

- AutoTune PID BED: M303 E-1 S60 C8
- AutoTune PID EXTRUDER:  M106 F255 (FAN) + M303 E0 S220 C8  