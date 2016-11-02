#Binary Logic Basics

Numbers are represented by a sequence of binary bits.
Bits contain two states, on or off, true or false, high or low, zero or one.
In circuits, positive voltage corresponding to the powersupply equates to a logical 1 or true, this voltage is called high.
Conversely a zero or ground voltage represents the logical 0 or false, also known as low.

Numbers in digital circuits are always represented by two distinct voltage states. Most common is the 0v (low) = 0, and +5V (high) = 1.

#Basic Gates

##NOT

Our LED circuit is very close to the first, most elementary gate, the NOT gate.
If we remove the LED and conect the 470 Ohm resistor to the collector of our NPN, we have a basic NOT gate.
A positive voltage (from the supply) applied to the resistor connected to the Base of the NPN will cause a positive current to flow between the Base and the Emitter.
This causes the transistor to behave as a closed switch. If we were to measure the voltage between the Collector and ground, we would notice that it's almost 0 volts.
When we remove the positive voltage from the Base resistor, the voltage at the Collector would be the same as the supply voltage.
Thus a high input produces a low output and visa versa.

Honestly, the NOT gate is not really a gate at all, just a bit flipper.
