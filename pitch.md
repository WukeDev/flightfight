# FlightFight

## Goal:
- Establish a micro controller based "Augmented Reality" platform for virtual combat
  * [Inspiration](https://www.youtube.com/watch?v=qTf5LPve-ZU)
  * similar to laser tag
- Implement an analog FPV system that uses 5.8ghz transmission frequency
  * Digital systems may be explored in the future
- Primary platform of installment will be on Remote Controlled planes, with cross platform support for cars and tanks

## Implementation:
- Low beam IR emitter will be used as a "turret"
- IR detector will be used to sense the beam
- SEEED Studio Xiao will be used as a micro controller
  * further research will be needed to narrow down choices
  * attractive choice for its tiny design and flexible platform usage
- Development language of choice will probably be CircuitPython or Arduino
- All electronics will be housed in a 3d printed enclosure
  * potential for a pan and tilt system for more precise aiming
- The "turret" will need to be aligned with camera
- Main module should will access a PWM channel from receiver and external IR sensors will be daisy chained to it


