# sensor_pcb
## External sensors
Those sensors just go over I2C. A connector needs to be placed on the PCB. The Leak sensor will just expose the probes.


* Temperature: https://bluerobotics.com/store/sensors-cameras/sensors/celsius-sensor-r1/
* Pressure: https://bluerobotics.com/store/sensors-cameras/sensors/bar-depth-pressure-sensor/
* Leak sensor: https://bluerobotics.com/store/sensors-cameras/leak-sensor/sos-leak-sensor/


## Internal sensors
Those are also connected to the I2C bus but are on the pcb thus internal. 

* Temperature + Humidity: SHT45-AD1B Datasheet
* Pressure Sensor: BMP581 Product Page
* Tank Pressure: ADS1115  Datesheet Note: The tank pressure is an analog signal. Plase design and layout the pcb so that a optional resistor devider could be used but normaly is not used

