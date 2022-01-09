Files for the Dual Z Version. The files are slightly modified from the V3 files. With this version, the transmission sits on the outside (see photo). This allows you to use the metal 80T pulley as well as larger gears than 80T to increase the z-axis resolution.
Instead of one long, you now need two 65mm rods. Besides a second motor, all other transmission parts are needed twice.

Dual Z can also be used with the normal V3 files, but the transmission would be on the inside (see CAD photo). Therefore the inner top part is replaced by the (mirrored) transmission.

If the motors can be controlled independently (two drivers on the board, not both on the same driver), G34 can be used. If both motors cannot be controlled separately, G34 will not work and Tram Z must be used instead (as with Prusa Mk2s/Mk3s). For all Klipper users I have written a macro that can be used. A demonstration of the macro can be seen on Youtube:

https://youtu.be/GGOv1CKP1a4

The macro should be done whenever the axis is moved by hand (this also includes the X axis when the power is off, the axis may moved).
