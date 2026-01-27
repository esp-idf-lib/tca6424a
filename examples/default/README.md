## What the example does

* Initializes the driver
* Configure a pin as input
* Registers an interrupt that logs port value of the INT pin
* Blinks, or toggles, P10 output

## Wiring

Connect an LED with an appropriate current-limiting resistor to pin P10 of the TCA6424A.
Connect buttons between pins P01, P02, and P03 of the TCA9564A and ground.
Connect the INT pin of the TCA9564A to a selected GPIO of the ESP32.

The GPIO for connecting INT can be chosen in `menuconfig`. 
See the default settings in `Kconfig.projbuild`.
