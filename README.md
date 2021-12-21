# Mproject
The primary objective of this electrical project idea is to monitor distribution transformer health and send data to the IoT dashboard. Transformer Health parameters to be monitored in these projects are as follows:

Oil Level
Temperature
Voltage level
Current level
silica gel colour

It monitors all the above parameters in real-time and shown on the LCD display and it sends the same data to the IoT dashboard through the esp32 module. In case of over-temperature, we start the fan in the first stage, if the temperature is still not in control, then we disconnect the transformer from the main supply. In case of low oil level, over voltage, and over current, we disconnect the main supply to protect the transformer.
