# icinga2-plugin-raspberrypi_temp
Check and report Raspberry Pi system temperature

### Usage
```
Usage: check_raspberrypi_temp [-w warning_value] [-c critical_value]
   -w: warning threshold, default 60°C when unset
   -c: critical threshold, default 75°C when unset
```

### Example
```
$ ./check_raspberrypi_temp
OK: Current system temperature is 45.08°C.
|temp=45.08;60;75;0;100
```

