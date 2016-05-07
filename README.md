# Flow-meter
A waterwheel powers an arduino with a radio transmitter attached to the serial port. 
The arduno reads the voltage that the waterwheel is putting out (via a voltage divider) and posts this reading to it's serial port. 
Another arduino, located 300m away, recieves this on its serial port (via another HC12 433Mhz serial module), 
converts it into a useful string for openenergymonitor and repeats it over a hoperfm module a raspberry pi base station 
running an open energy monitor gateway forwarder.
