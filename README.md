# adafruit_lightsaber-featherwing

Code modifications to Adafruit's Lightsaber located at https://learn.adafruit.com/lightsaber-featherwing/overview

Update includes:
* Moved the slider on/off button to a latching switch tied to green.led
* I didn't use an $15 RGB led for the switch. Instead, I used a one color led switch for each color position. This is wired to the `red.led`.
* Turn on the `green.led` when the latching switch is pressed
* Randomized blade color - This changes every time the blade is powered on.

Unrelated, but useful if you're buildling one of these:
* You can eliminate the usb breakout/extension piece if you make your wires long enough and rotate the entire assembly of featherboard and propmaker by 180 degrees (this puts the featherboard's usb port pointing up towards the blade). Saves you a couple bucks and some more soldering

Be sure to update the number of neopixels and your swing thresholds to suit your needs. I used a short blade, so these values changed.
