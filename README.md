# External-Watchdog-Timer
A PCB in for an external watchdog timer to reset an mcu if it is halted. 

The project is inspired by this project by Ralph Bacon: https://github.com/RalphBacon/194-External-Watchdog-Timer-555-with-PCB 
described in this video: https://www.youtube.com/watch?v=WpihLPvY9Ac&tthat 
that is an modified version of this orginal project: https://www.electronics-lab.com/free-elektor-circuit-ne555-watchdog-timer/ by Wolfgang Borst 

notes: 
      The SO-8 IC's footprint matches NE555 and SI4599 even though an attiny13 has been selected in Eagle
      The 0 ohm resistor R7 is not recommended for battery operation, if not populatet the led will not 
      light on, when the signal is triggered by the countdown in the watchdog timer, to save power
      
      Components are named on the pcb with walues, and can be replaced for another 
      trigger time for the NE555 timer current triggertime are 100mS
      
      Sizes for footprints are 0603, so-8 and sot-23
