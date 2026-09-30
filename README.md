# Arduino Head Tracker

I built a webcam-based head tracker that controls a pan/tilt mechanism using an Arduino and two servos. An LCD displays the servo angles.

## My Work

I assembled a purchased pan/tilt mount, attached the laser module, and wired the electronics. I connected the tracking software to the Arduino and tested the system.

During testing, I adjusted the servo direction, movement range, and tilt calibration to match the mount. Both pan and tilt now work.

## How It Works

OpenTrack tracks head movement through a webcam. A Python script passes angle commands to the Arduino, which controls the servos. The code uses smoothing and a deadzone to reduce small, shaky movements.

## Main Components

- Arduino UNO R3
- Two servos and a pan/tilt mount
- Laser module
- LCD display
- Webcam

## What I Learned

This project gave me practice assembling a moving mechanism, wiring electronics, and connecting software to hardware. It also helped me understand how testing and calibration affect the movement of a physical system.

## Photos and Demo

Photos of the build and a demonstration video will be added here.
