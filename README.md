# I2C-master-directory
All of the default I2C addresses used on Northern Widget devices, tabulated.


## Sensors

| **Device**                                                                                 	| **Default address(es)** 	| **Reprogrammable address** 	| **Function**                                                                         	| **Notes**                                       	|
|--------------------------------------------------------------------------------------------	|-------------------------	|----------------------------	|--------------------------------------------------------------------------------------	|-------------------------------------------------	|
| [Tally](https://github.com/NorthernWidget-Skunkworks/Project-Tally)                        	| 0x33                    	| Y                          	| Counts pulses (from sensor, etc.)                                                    	|                                                 	|
| [Haar](https://github.com/NorthernWidget-Skunkworks/Project-Haar)                          	| ?????                   	| Y                          	| Ruggedized & waterproof temperature, barometric pressure, & relative humidity        	|                                                 	|
| [Walrus](https://github.com/NorthernWidget-Skunkworks/Project-Walrus)                      	| 0x4D                    	| Y                          	| Submersible temperature and pressure; often for water level                          	|                                                 	|
| [Dyson SW](https://github.com/NorthernWidget-Skunkworks/Project-Dyson)                     	| 0x40, 0x1D              	| N                          	| Shortwave radiation: radiation (light), accelerometer (given in that order)          	| Default; upwards-facing                         	|
| [Dyson SW](https://github.com/NorthernWidget-Skunkworks/Project-Dyson)                     	| 0x41, 0x53              	| N                          	| Shortwave radiation (alternative I2C address set): radiation (light), accelerometer  	| Alternative addresses set in device firmware    	|
| [Dyson LW](https://github.com/NorthernWidget-Skunkworks/Project-Dyson)                     	| 0x4A                    	| N                          	| Longwave radiation                                                                   	|                                                 	|
| [LiDAR Lite Symbiont](https://github.com/NorthernWidget-Skunkworks/Project-Symbiont-LiDAR) 	| ?????                   	| Y                          	| Backpack board for laser rangefinder + MEMS accelerometer for orientation            	|                                                 	|
| [TP DownHole](https://github.com/NorthernWidget/TP-DownHole)                               	| 0x77, 0x6A              	| N                          	| Submersible pressure and temperature (I2C addresses in order); often for water level 	| 0x77 conflicts with BME280 on Resnik and Margay 	|


## [Margay](https://github.com/NorthernWidget-Skunkworks/Project-Margay)

| **Device**                                                	| **Default address** 	| **Reprogrammable address** 	| **Function**                                                     	|
|-----------------------------------------------------------	|---------------------	|----------------------------	|------------------------------------------------------------------	|
| [DS3231](https://github.com/NorthernWidget/DS3231_Logger) 	| 0x68                	| N                          	| Real-time clock                                                  	|
| [MCP3421](https://github.com/NorthernWidget/MCP3421)      	| 0x6A                	| N                          	| ADC                                                              	|
| [BME280](https://github.com/NorthernWidget/BME_Library)   	| 0x77                	| N                          	| On-board barometric pressure, temperature, and relative humidity 	|


## [Resnik](https://github.com/NorthernWidget-Skunkworks/Project-Resnik)

| **Device**                                                        	| **Default address** 	| **Reprogrammable address** 	| **Function**                                                     	|
|-------------------------------------------------------------------	|---------------------	|----------------------------	|------------------------------------------------------------------	|
| [DS3231](https://github.com/NorthernWidget/DS3231_Logger)         	| 0x68                	| N                          	| Real-time clock                                                  	|
| [MCP23018](https://github.com/NorthernWidget-Skunkworks/MCP23018) 	| 0x20                	| N                          	| I/O Expander                                                     	|
| [ADS1115](https://github.com/adafruit/Adafruit_ADS1X15)           	| 0x48                	| N                          	| ADC (on-board devices)                                           	|
| [ADS1115](https://github.com/adafruit/Adafruit_ADS1X15)           	| 0x49                	| N                          	| ADC (off-board devices)                                          	|
| [MCP4725](https://github.com/NorthernWidget-Skunkworks/MCP4725)   	| 0x62                	| N                          	| DAC                                                              	|
| [BME280](https://github.com/NorthernWidget/BME_Library)           	| 0x77                	| N                          	| On-board barometric pressure, temperature, and relative humidity 	|
