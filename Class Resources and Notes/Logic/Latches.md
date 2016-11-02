#Latches

This topic is assigned as extra curricular homework. It's not totally necessary to make or expolre these circuits, but the information will enrich your understanding of Taeyoon's lectures.

At this point basic logic gates are your friends. But these are all asynchronous elements and don't deal with storing states or transmitting things in sequence or synchronously. Latches are the crucial step to making logic circuits dynamic, able to send receive and store data.

"In electronics, a flip-flop or latch is a circuit that has two stable states and can be used to store state information. A flip-flop is a bistable multivibrator. The circuit can be made to change state by signals applied to one or more control inputs and will have one or two outputs. It is the basic storage element in sequential logic. Flip-flops and latches are fundamental building blocks of digital electronics systems used in computers, communications, and many other types of systems." ([https://en.wikipedia.org/wiki/Flip-flop_(electronics)](https://en.wikipedia.org/wiki/Flip-flop_(electronics)) accessed 11/2/2016 6PM EST )

A crucial feature of the latch is that it is build using feedback loops made from our basic logic gates. The most basic is the [RS latch](https://en.wikipedia.org/wiki/Flip-flop_(electronics)#/media/File:SR_Flip-flop_Diagram.svg).

Read up on Latches:
[https://en.wikipedia.org/wiki/Flip-flop_(electronics)](https://en.wikipedia.org/wiki/Flip-flop_(electronics))

Build a D Latch:
[http://www.play-hookey.com/digital/sequential/d_nand_latch.html](http://www.play-hookey.com/digital/sequential/d_nand_latch.html)

By chaining the outputs to the inputs of several D latches, one can construct a shift register.
All latch clocks must connect to a common oscillator.