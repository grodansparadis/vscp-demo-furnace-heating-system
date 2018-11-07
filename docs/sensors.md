# Sonsors and i/o heating system


## Kelvin NTC10K

 - Core temperature furnace. (1)
 - Furnace heater out.
 - Furnace heater return.
 - Room furnace. (1)
  

## MAX6675
 - Furnace smoke gas sensor low. (1)
 - Furnace smoke gas sensor high. (2)


## Digital Outputs
 - Water heater element LED (1)
 - Valve incoming water (future)
 - Valve furnace -> water heater (future)


## Digital Inputs
 - Fire alarm (4)
 - Button - Forward (5)
 - Button - Up (6)
 - Button - Down (7)
 - Button - Enter (8)
 - Motor Pellets transport (9)
 - FAN furnace
- Heater furnace

## Other

- LED display in furnace box
- CO sensor
- 

## Hygrometer
 - Storage cellar 1
 - Storage cellar 2
- 
## Raspberry Pi digital outputs
 - Water heater element 2/LED (2)  - Furnace Active
 - Water heater element 3/LED (3)  - Transport
 - RED
 - GREEN

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
* 11
* 12
* 13
* 14  GND
* 15
* 16
* 17  +3.3V
* 18
* 19  MOSI SPI MAX6675A Temperature (Not used)
* 20  GND
* 21  MISO SPI MAX6675A Temperature
* 22  
* 23  SCLK SPI MAX6675A Temperature
* 24  CE0 SPI MAX6675A
* 25  GND
* 26  CE0 SPI MAX6675B
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
