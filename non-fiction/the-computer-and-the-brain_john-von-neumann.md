# The Computer and the Brain
## Finished 2018-07-01
This is a short work completed by Von Neumann before he died, intended to be used as his Silliman lectures at Yale University, but he died before he could give them. 
Essentially he gives a review of computation at the time, and a little bit about neuroscience, where he compares the signals in the brain to the signals in a computer. 
The work is unfinished, so there isn't a definitive conclusion, but the tone of the work implies that a computer can be built that could function as the human brain.
Honestly, reading this in 2018, it doesn't feel particularly insightful, but considering that it was written in 1956, the work inside it is groundbreaking.
Despite the ideas being very familiar to me in the 21st century, it was written in a way which was neither simple nor complex, which to me seems ingenius: he explains his own complex and original thoughts, but in a way that is simple enough to be understood (but not *too* simple).

The following points really stood out to me in the book:
- The basic operations of a computer don't have to be ones we are familiar with (e.g. +, -, \*, /). 
 They could really be anything, provided those operations can be combined to perform arbitrary calculations. 
 An interesting example is the [Differential Analyzer](https://en.wikipedia.org/wiki/Differential_analyser), which was an early mechanical computer that could solve ODEs. 
 Its main operation was integration, and it also had an averaging operator. These could be combined cleverly to yield other operations. 
 This made me think that our current choice of logical gates as the basic operating principal of a computer isn't necessarily universal.
- It seems that von Neumann was among the first to propose that a computer's program could be stored in its memory, instead of being a fixed part of the machine.
 Before this, most computers (for example the machine Turning built to decypher the enigma code) were hard coded to do a single calculation only.
-  An extension of above: it seems like von Neumann literally invented modern computer architecture, when he invented the "[Von Neumann Machine](https://en.wikipedia.org/wiki/Von_Neumann_architecture)"
- In the mid 20th century, there were various ideas about what the underlying mechanism for a computer should be: electrical, mechanical, chemical, etc. 
 Looking to the brain for inspiration, von Neumann points out that at the nano-scale, all of these mechanisms are really the same: chemical reactions always have electric potential, and are caused by mechanical collisions.
 This suggests that this appearance of choice is only an artifact of our limited ability to work on the nano-scale.
- Fundamentally, neurons are much slower than electronics, by many orders of magnitude. However, our brains compensate for this using massive parallel processing. So von Neumann's view was that nature would favour _parallel_ computation, whereas AI would favour _serial_ computation.
 In modern times this is less true, but still brains are *much* more distributed than modern computers.
- Neurons have a relatively high transmission error rate (~1e-3), whereas digital signals can be made to have arbitrarily high precision (maybe 1e-12).
 Yet despite this, the brain still manages to be an amazing computer. So clearly error rate isn't a decisive factor for the power/abilities of a computer.
