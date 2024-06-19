# Breaker Alert
This project was constructed for my solar system because the AC breaker between the inverter and the grid kept randomly tripping.  I would like to find out what causes it to trip, and knowing exactly when it trips is useful.  First I can reset it so we don't stop harvesting energy for long.  Second, it might help me know what causes it to trip.  This unit sends me an email when the breaker trips.  It also turns on the blue LED on the Wemos D1 Mini lite when it is tripped.  

This unit was made entirely out of junkbox parts I had laying around.  If I was to design a system for doing this without the restriction of using junkbox parts, I would find a better optocoupler.  This one requires 10 mA to trip, and that makes the dropping resistors dissipate 1.4 watts, which is slightly above their rating, and more than I would like.

To build this use VScode with the PlatformIO extension.