# My Klipper configuration files

## Installation

```
git clone git@github.com:pbogut/klipper-conf
```

## Configuration

In `printer.cfg` add:
```
[include path/to/klipper-conf/printer-name.cfg]
```

## Post installation

For each printer run PID calibration. Send gcode to printer:
```
PID_CALIBRATE HEATER=extruder TARGET=200
SAVE_CONFIG
```

Use printer `Probe calibration` menu to calibrate the leveling probe.
