## SFPC Nested Abstractions - Fall 2016

Instructor: [Phillip David Stearns](http://phillipstearns.com)
Class at [School for Poetic Computation](http://sfpc.io), Fall 2016.

"Nested Abstractions" is a class covering a range of nested material and functional abstractions embodied in physical circuits.

Students will be presented material on basic electrical theory, electronic circuits, passive and active electronic components, fabrication and prototyping techniques, and digital logic. Electronic theory will include introductions to the physics of electricity, charge and electro-magnetic forces. Basic materials, units and symbolic representation of electronic circuits will be presented. Basic electronic components such as resistors, capacitors, diodes and transistors will be introduced. The students then construct basic circuits using the P++CB system before moving to the breadboard for more complex circuits. Digital logic will be introduced at the transistor level and will transition to CMOS 4000 series logic devices for more complex functions. Students will explore logic as a musical medium through the construction of breadboarded CMOS 4000 logic based synthesizers. Music synthesis will be used as a way of teaching the inner workings of some fundamental building blocks of computer systems.

This class merges the material and techniqes of [P++CB](https://phillipstearns.wordpress.com/pcb/) and [PureDatrocessarduinoMOS](https://vimeo.com/97899618)
__________________________________________________________________________________________

## 10/19 -- SESSION 1

### #Depth 0: The Atoms of Electronic Computation (Analog Concepts)

Preparation: 

Topics:

* Electricity overview (voltage, resistance, current, Ohm's law, Kirchhoff's laws, circuit diagrams)
* Electrical tangibles: Simple components
* Basic circuits with LEDs, resistors, capacitors, transistors
* Breadboard prototyping

Exercise: wire up an analyze basic NPN transitor based LED driver circuit
  
## 10/25 -- SESSION 2

### Depth 1: The Molecules of Electronic Computation (Digital Concepts)

Topics:

* P++CB Modular electronics learning system
  * Circuit wiring: parallel and series
  * Circuitry with extra components: buttons, switches, and potentiometers
  * Soldering
* Analog and Digital signals
* Intro to Binary Logic
* Logic Gates from Transistors (TTL)
* Basic D type flip flops

Exercise: construct basic P++CB modules: LED driver, Speaker Driver, Oscillator, TTL Inverter, TTL NOR, TTL NAND.

Homework: construct a binary counter from D type flip flops

## 11/2 -- SESSION 3

### Depth 2: Integrated Circuits (Modular computational tasks and musical applications)

Topics:

* CMOS 4000 series digital logic
* Making music with the building blocks of computational systems
* Hex Inverters as Oscillators

Exercise: build a simple speaker driver and oscillator with 40106 Hex Schmitt Trigger

Homework: combine two oscillators using dual input logic gates (4081)

## 11/9 -- SESSION 4

### Depth 3: Basic Computation and Music

Topics:

* Counters as frequency dividers
* Multiplexers (and counters) as sequencers
* Shift Registers as resonant objects

Exercise: create a simple 8 note sequencer using a 40106, 4040, and 4051.

Homework: create a custom synthesizer using any combination of the chips covered in class.
Continue your journey here: https://docs.google.com/document/d/1V9qerry_PsXTZqt_UDx7C-wcuMe_6_gyy6M_MyAgQoA/edit
Lunetta Synths expand on this idea and bring in some hybrid analog-digital concepts as well.
