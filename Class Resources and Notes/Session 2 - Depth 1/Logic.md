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
[Something like this...](http://www.falstad.com/circuit/e-rtlinverter.html)
A positive voltage (from the supply) applied to the resistor connected to the Base of the NPN will cause a positive current to flow between the Base and the Emitter.
This causes the transistor to behave as a closed switch. If we were to measure the voltage between the Collector and ground, we would notice that it's almost 0 volts.
When we remove the positive voltage from the Base resistor, the voltage at the Collector would be the same as the supply voltage.
Thus a high input produces a low output and visa versa.


Honestly, the NOT gate is not really a gate at all, just a bit flipper.

In CMOS, some chips that have gates with this behavior are the 4069, 40106, 4584

##AND

It's time to introduce two concepts here: asynchronous/synchronous circuits and combinational.

Asynchronous circuits change their output states as soon as the input states propogate through its transistors. This is opposed to synchronous circuits whose inputs change when a pulse is applied to a clock pin. Synchronous circuits can be triggered by either a rising clock edge (low to high) or falling edge (high to low) transition. Which type is generally specified in its datasheet.

All of the combinational logic circuits described here are asynchornous.

[Combinational logic](https://en.wikipedia.org/wiki/Combinational_logic) refers to the family of circuits whose output is determined by some [boolean logical](https://en.wikipedia.org/wiki/Boolean_algebra) evaluation of a combination of inputs.

AND circuits: AND (conjunction), denoted x∧y (sometimes x AND y or Kxy), satisfies x∧y = 1 if x = y = 1 and x∧y = 0 otherwise.

This can be summarized in a [truth table](http://www.ee.surrey.ac.uk/Projects/CAL/digital-logic/gatesfunc/#truth). Where all the combinations of inputs for a particular logic gate are listed along with the resultant output.

For AND, we have something like this:

 A | B | Y 
 - | - | - 
 0 | 0 | 0 
 1 | 0 | 0 
 0 | 1 | 0 
 1 | 1 | 1 
