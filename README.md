# Low-Power-Modes
A function that handles all enabled different low power modes

For Modem sleep the wake up timer does not not re-enable modems, you must reintialize the wifi and bluetooth

*Current consumption measurements, with 5v in
Active Mode
Measured current consumption: 73.16mA (wifi/radio on but not initialised, closer to 100mA if initialized)

Modem Sleep
Measured current consumption: 44.82mA

Light Sleep
Measured current consumption: 5.43mA

Deep Sleep
Measured current consumption: 3.78mA
