# Sonsors and i/o heating system


## Kelvin NTC10K
 - Core temperature furnace. (1)
 - Furnace heater out.
 - Furnace heater return.
 - Room furnace. (1)
  

## MAX6675 (Raspberry Pi)
 - Furnace smoke gas sensor 1. (SPI 0)
 - Furnace smoke gas sensor 2. (SPI 1)

## LCD (Raspberry Pi)
 * I2C

## 1-wire (Raspberry Pi)
 * Kernel driver

## Digital outputs (Raspberry Pi)
 - Water heater element LED (BCM 17-11)
 - Furnace Active LED       (BCM 27-13)
 - Furnace Heater LED       (BCM 22-15)
 - Furnace FAN              (BCM 23-16)
 - Furnace Transport 1      (BCM 24-18)
 - Furnace Transport 2      (BCM 25-22)


## Beijing unit 0 - Digital Outputs 
 - Water heater element LED (IO-0)


## Beijing unit 1 - Digital Inputs
 - Fire alarm (IO-1)
 - Button - Forward (IO-2)
 - Button - Up (IO-3)
 - Button - Down (IO-4)
 - Button - Enter (IO-5)
 - Force Pellets transport (IO-6)
 - Furnace transport (IO-7) (Origin is 24V)
 - Furnace Fan (IO-8)       (Origin is 24V)
 - Furnace heater (IO-9)    (Origin is 24V)


## Accra Analog inputs
 - Furnace IR LED (AD-0)   0-10V
 - Furnace overheat (AD-1) 0-10V


## Other
- LED display in furnace box
- CO sensor (future)
- Valve incoming water (future)
- Valve furnace -> water heater (future)


## Hygrometer
 - Storage cellar 1
 - Storage cellar 2


### Big Lamp's
 - RED LED - Power
 - GREEN LED - Forced transport


## pins used on Raspberry Pi (Pi5)

See [pinout](https://pinout.xyz/#)

* 1   +3.3V
* 2   + 5V 
* 3   I2C SDA1  LCD DISPLAY
* 4   +5V
* 5   I2C SCL1  LCD DISPLAY
* 6   GND
* 7   1-WIRE
* 8   TXDO
* 9   GND
* 10  RXD0
* 11  BCM 17
* 12  BCM 27
* 13  BCM 22
* 14  GND
* 15
* 16  BCM 23
* 17  +3.3V
* 18
* 19  MOSI SPI MAX6675A Temperature 
* 20  GND
* 21  MISO SPI MAX6675A Temperature
* 22  
* 23  SCLK SPI MAX6675A Temperature
* 24  CE0 SPI MAX6675A Temp 1
* 25  GND
* 26  CE0 SPI MAX6675B Temp 2
* 27
* 28
* 29
* 30  GND
  31
  32
  33
  34  GND
  35
  36
  37
  38
  39  GND
  40
