# arduino-balloon
This is a project to launch an Arduino into space (okay, not quite, but close enough) using a helium balloon!
During the flight of the balloon the onboard Arduino will perform the following functions:

1. Record in-flight GPS, temperature, pressure(altitude), accelerometer data onto an SD card.
2. Take pictures in-flight.
3. Once on the ground, the Arduino will use APRS or other methods to transmit its coordinates.

A parachute will be deployed mechanically when payload is in free fall.

# Sub-projects
1. GPS logger function
2. Camera function (Arducam)
3. APRS transponder
