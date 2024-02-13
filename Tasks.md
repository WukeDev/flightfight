# Sub Tasks
## Create a Plane
- Design in Fusion 360
Plane 1:
- Stable platform
- High mounted wing, with low cube loading
- Able to carry weight
- 
## Make a FlightFight Module
### Physical
- Procure all materials: IR emitter, detector, micro controller, transistors etc.
- Solder pins to board
- Design circuit schematics
- Create a barebones wiring
- Maybe finalize a manufactured PCB
- Design 3d printed enclosure
  * with potential for a pan and tilt servo mechanism
- Make and fit the circuit to the enclosure
### Software
- Relearn basic python
- Learn and explore the circuitpython library
- Flash circuitpython to microcontroller

- Create a program to control an LED(normal or IR)
  * Hook up LED to one of the pins
  * Create a program that flashes and LED upon a certain clock
  * Then expand and send a certain signal through the IR LED

- Create a program to detect an IR LED signal
  * Detect a certain code sent by a TV remote or IR LED

- Combine the two programs and flash them to two microcontrollers
  * Measure and calibrate beam angle
- Add a PWM input to microcontroller that comes from an RC receiver/flight controller
  * the IR LED should fire a signal on cue and send it to another microcontroller
  * potentially power the LED with a transistor that takes current from the RC receiver/flight controller
  
- Explore how to daisy chain IR detectors
- Add a dashboard to display data from FlightFight "game"
  * a simple concpet could be to use an LED array
  * explore connecting to an Analog OSD and outputting data there (potentially very complex problem)

## Combine both aspects
- Keep the module light, so maybe a sub-250g application is possible
- Keep it universal, for cars, drones, planes
- 
