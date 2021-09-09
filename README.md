# BeyondTheremin
Semester project for the subject IAS (interactive audio systems) at the FH St. Pölten in 4th semester media technology.

Beyond Theremin uses a Leap Motion device to control a synthisizer with hand movement in MAX 8/MAX for Live.

FEATURES:
* Left Hand
  - Vertical axis
  - Grabstrength
* Right Hand
  - Horizontal axis volume control
  - Grabstrength lowpass cutoff control
        
*'Grabstrength' is the term Leap Motion uses to describe how far the fingers of each hand are stretched out.

CREDITS:
Beyond Theremin relies on the leapmotion Max external by xyz. In order to use LeapMotion on your device, the LeapMotion software (Orion) is required. (Different software versions seem to have compatibility issues with Max 8, as it would not allow Max to read any data from the Leap Motion controler, even though it worked fine in the software.)

DEV INFO:
For coding, the LeapSDK, Max-8-SDK, as well as MUBU (dependency of leapmotion) are required.
