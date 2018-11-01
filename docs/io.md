# Sonsors and i/o heating system


## Counter

  - Flow meter water in
  - Flow meter heat water out

## Temperature

 - Core temperature furnace. (1)
 - Core temperature water heater. (1)
 - Boiler temperature water heater. (1)
 - Warm water out flow temperature. (1)
 - Furnace heater return. (1)
 - Furnace smoke gas sensor low. (2)
 - Furnace smoke gas sensor high. (2)
 - Room furnace. (1)
 - Room Washing. (2)
 - Room storage cellar 1 (2)
 - Room Storage cellar 2 (2)


## Hygrometer
 - Storage cellar 1
 - Storage cellar 2

## Digital Outputs
 - Alarm 
 - Water heater element 1/Led
 - Water heater element 2/Led
 - Water heater element 3/Led
 - Valve incoming water (future)
 - Valve furnace -> water heater (future)


## Digital Inputs
 - Fire alarm
 - Button - Forward
 - Button - Up
 - Button - Down
 - Button - Enter
 - Motor Pellets transport

## Other

- LED display in furnace box
- CO sensor



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
