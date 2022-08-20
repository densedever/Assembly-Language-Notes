# Assembly Intro: Logic, Circuits, and Memory

This first file will touch on the basic hardware model of a computer (as far as simple programs are concerned), the basics of electric circuits and logic gates, and the basics of logic itself. 

A computer program is a set of instructions for the computer to carry out one-by-one. The computer executes these instructions in the central-processing unit (CPU). The instructions themselves live in memory (called RAM). 

A computer at its [simplest level](https://en.wikipedia.org/wiki/Von_Neumann_architecture) is made up of a *processor* and *memory*.

Computers compute. This seems obvious, but it's easily forgotten in the high-up and far-away world of modern operating systems, GUIs, email, social media, and video games. All this is the result of many billions of calculations done by the computer, down to how each individual pixel lights up. Computers, at their heart, are computational, number-crunching machines. 

The entirety of cyberspace is made up of nothing but electricity flowing through wires and circuits. The same charge powering batteries, wall outlets, and even the nerves in your body and brain is in operation when you hit that power button. This is the world of atoms, electrons, charge, current, voltage, amps, ohms, etc. This is how our world looks up close. 

Imagining this isn't that hard, but think a bit on how these electrons zipping through wires ends up with calculations that never fail to be correct and guide the workings of scientists and mathematicians in the real world. 

This phenomenon was used in calculations critical enough to fly us to the moon! The movement of particles through wires allowed a species growing up from organic molecules in the dirt to leave the planet we've always called home for roughly 3.8 billion years!

Think about that a second. 

How?

How could this be? How could something so simple and fundamental to existence be exploited to allow us to achieve such astounding ends?

Let's step back to the beginning for a second. 


---

Think of the rules we live by. Not the rules that say we should always be nice to one another, or should always eat our vegetables, or shouldn't steal from people, but the rules by which reality works such as the most fundamental of all: **a thing is itself**. 

The [Law of Identity](https://en.wikipedia.org/wiki/Law_of_identity) is the most basic and pervasive rule of all existence. **A thing is itself.** In our universe, and in any number of other dimensions, this rule cannot possibly *not* hold true. To say otherwise leads to fantastical absurdity and absolute insanity.

Logic governs every aspect of being, everywhere, always, from that very first rule. So it's no surprise logic and reason permeates all of human thought from earliest philosophy to latest cutting-edge science. We know that it works because it *not* working means not being in reality. 

So naturally, it encompasses the fabric of computation, of information, of math, and of computer science. 

A thing is itself. The concepts of **is**, and its opposite: **is not**, are the ultimate starting point by which reasoning about the universe in which we live can begin. There is nothing more fundamental. 

[Binary code](https://en.wikipedia.org/wiki/Binary_code), a concept many people know *about*, but fewer people actually *know*, perfectly encompasses this primal starting point of *is* and *is not* by putting those two base concepts into symbolic form: a **one** and a **zero**. An *is* and an *is not*.

The electricity running through those circuits is either present, or it is not. [Hook](https://www.youtube.com/watch?v=INBYuA6KoLA) a battery's nodes up to one another with a wire, and energy will naturally and automatically flow along the wire continuously, forming a *closed* circuit. Unhook it, and the circuit will *open*, stopping the flow of electricity. 

[The same phenomenon](https://www.youtube.com/watch?v=p7SkE5pERtA) behind putting two magnets close to each other and watching them snap together on their own is what drives this movement of electricity along the circuit. 

A circuit is meant to direct the natural flow of electricity so that it can be manipulated, the force therein used to power mechanisms just like water powers a wheel or wind spins a turbine. 

To make circuits useful, they have to direct electricity in certain ways to give an understandable, predictable, consistent result out the other end. Several circuits are used as the basis of computer chips, and are called *logic gates*, so called because they operate on the aforementioned principles of *is* and *is not*.

[This video](https://youtu.be/VBDoT8o4q00) shows you the basics of logic gates and how they're used in CPUs to give understandable and useful results.

[Here](https://youtu.be/lNuPy-r1GuQ) is another slightly easier-to-understand one, which really hits the point home that interactions between inanimate objects are capable of counting and computing, things normally only attributed to intelligent minds.

Computer memory is where all the magic happens in a program. Your program spends every waking moment of its runtime in RAM. [This video](https://youtu.be/XETZoRYdtkw) shows how memory circuits hold values.

Memory circuits in RAM chips are *ordinal*, meaning they are numbered first, second, third, etc. with every circuit having a unique number associated with it. This is also called *addressed* memory. The compiler sets aside a certain number of memory locations for holding values whenever a variable is declared. 

Each singular memory location is made up of eight individual circuits, with each circuit called a *bit*, and a set of eight bits being called an *octet*, or a *byte*. Bytes are the smallest unit of addressable memory, but not all bytes are eight bits. Old computers used to use one bit, two, four, ten, even twelve bit addresses, but the most popular architectures won out in the end, standardizing the 8-bit byte across the computing world. 

[This video](https://youtu.be/-Ecf7lb4aZ0) shows how memory circuits are wired together to form chucks of memory capable of holding multiple pieces of information as seen in RAM chips.

Memory is measured in sizes just like liquid is measured in milliliters and dry stuff is measured in grams. 

- One circuit is a *bit* 
- four is a *nibble*
- eight is a *byte*
- 16 is a *word*
- 32 is a *double-word*
- 64 is a *quadword* or *paragraph*.

All this talk in C of 8-bit `int`s and 32-bit `long`s is addressing (get it?) the size of the memory space reserved for the variable. 

I will stop here for now, and in the next file, I'll get around to a few possible development environments one can use to make assembly language programs. I'll mainly be doing Linux, which won't be a problem because you guys could just install Virtualbox. Happy coding.
