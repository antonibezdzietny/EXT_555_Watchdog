# External Watchdog build on NE555

### Brief information
Project create for logic 3.3V (STM32 / ESP32 e.t.c)

The most important parameters:
- $t_{WD}$ (watchdog timeout) : 30s *(depends on R4 & C1)*
- $t_{HB}$ (heart beat minimal duration) : 2ms (depends on R3)
- $t_{RST}$ (duration reset pulse) : 100ms *(depends on R1)*

Time modulation can be done by changing resistors and capacitor parameters. 

![Alt text](NE555_EXT_WATCHDOG.svg)


### More about
---
- xx555 Precision Timers [https://datasheet.lcsc.com/lcsc/2212101330_XINLUDA-XD555_C521185.pdf]
- RC Time Constant Calculator [https://www.allaboutcircuits.com/tools/resistor-capacitor-time-constant-calculator/]
- Time Constant Calculator [https://www.digikey.com/en/resources/conversion-calculators/conversion-calculator-time-constant]
- Capacitor Safety Discharge Calculator [https://www.digikey.com/en/resources/conversion-calculators/conversion-calculator-capacitor-safety-discharge]