# Breaker Alert

This project was developed for my solar system to address an issue where the AC breaker between the inverter and the grid was randomly tripping. The goal is to identify the cause of these trips, and knowing exactly when they occur is beneficial for two reasons. First, it allows for immediate resetting to minimize energy harvesting downtime. Second, it may provide insights into the cause of the trips. 

When the breaker trips, this unit sends an email notification and also activates the blue LED on the Wemos D1 Mini Lite.

This unit was assembled entirely from spare parts I had on hand. If I were to design a system without the constraint of using only spare parts, I would opt for a more efficient optocoupler. The current one requires 10 mA to trip, causing the dropping resistors to dissipate 1.4 watts. This is slightly above their rating and more than I would prefer.

To build this project, use Visual Studio Code with the PlatformIO extension.