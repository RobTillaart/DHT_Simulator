# DHT_Simulator

Arduino sketch to simulate a DHT22

## Description

The DHT22 is an often used sensor and many libraries are written for it
including my own DHTNEW library. To better understand the protocol and 
to be able to debug my library I wrote a simulator for the DHT sensors
in 2014.

The simulator can be used to test applications to that use a DHT sensor,
e.g. to get high alarm temp or whatever.

Currently the code uses two analog ports to get some value for temperature
and humidity. Just connect two potmeters to play and simulate increase and 
decrease of the temperature and humidity.

The simulator is not tested extensively so please report bugs.

## Note

The sketch does not compile for ESP32 yet.

## Future

Idea is to use the code of the simulator in combination with a 
Senserion or two separate sensors (DS18B20 + ? ) to provide an 
accurate temperature and humidity. These could then be readable 
with any DHT library with the performance of a DHT (~ 5ms).
(when time permits)

## Operation

Compile and use/tweak it to your needs.

Have fun.
