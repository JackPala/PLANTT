# PLANTT
Yet another MQTT garden/farm hydration system

This system allows ESP32 (And eventually ESP8266) microcontrollers to automate the hydration, fertilization, and monitorring functions of your garden with the capability to transmit data to an MQTT broker of your choosing (We like MOSQUITTO), and have that data read by the Home Automation controller or Data Visualization controller of your choice.

We believe that using robotics to control fluid transfer inside a garden has the potential to save precious water, a key component in reducing argicultural operating costs for (currently) small scale gardeners and botanists. 

A myriad of non-profit organizations believe that we are currently inside of, or are entering a water crisis. We believe that technology can help mitigate that, especially when made open source and available to all - thanks to low cost publically available microcontroller systems that can be powered by small solar panels, PoE, USB, or any other method capable of delivering 5 volts.

Version 0.1 (WIP) will be based upon the ESP32 microcontroller and a 3-wire capacitive soil sensor. It will communicate over MQTT with the variables specified directly in the code. Eventually a web interface (Similar to the way Tasmota has webUI management) will be developed. The plan after that is to develop outwards to different communication protocols, most notably Zigbee (for mesh support) and LoraWAN (Helium?).

Possibly, in my dreams there is an app that can manage all of this, but we'll see how much energy I have left after the working prototype.
