GRBL-LinuxCNC-Controller
========================

Dual purpose controller to work with Arduino GRBL and Parallel port LinuxCNC

This controller is meant to be dual use. It can be used on the Arduino GRBL platform but can also be used with the LinuxCNC software via a parallel port.

It uses 3 Pololu or Stepstick drivers for XYZ steppers.

This hasn't yet been produced or made so it is totally possible that it doesn't work!

The design allows for 3 axis of movement, 3 limit/home switches, spindle activation and direction control.

Along on side there is a row of LEDs, these are connected to the enable, step and dir lines for the stepper drivers. While I could probably justify thier inclusion, honestly? I put them there as I love blinking lights as the machine moves ;)
