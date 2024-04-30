next steps to finish:

* maybe stiction in fans
* automation of lighting with camera

Also, when the ESP CAM is streaming, the LED light will turn itself on automatically so there is a picture that is visible.  This is likely to be accomplished by an automation inside the ESPHome device because it knows when the device switches between streaming and idle — when it's streaming, it should turn the light on, and turn it off when it is not streaming.  Later on we can take stills during the printing period, which will need to turn the light on and off.

Future improvements:

* SMD for passive components and sockets on board.
* Riser pin rows for ESP32 so it can be pushed into place and pulled out for maintenance.
  * Enclosure lid should take risen ESP32 and fuse box into account (I think it already does in its current size).
* Board that can use 3.3v / 5v converter depending on what is wired how

