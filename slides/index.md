- title : No Silver Bullet
- description : A 'Papers We Love' talk on Fred Brooks' 'No Silver Bullet' paper
- author : Bill Berry
- theme : moon
- transition : default

***

### No Silver Bullet
#### ~ Dr. Fred Brooks ~ 
#####(1985)
' these are speaker notes

---
#### I "liked" this paper, but ... 

' fed ego
' looked to the commoditization of hardware for comparison
' even hardware no single activity 
' placated by stuff that makes us feel good
' want software to be hard

***
### Influence
+ System/360
+ OS/360

' By all accounts successful 
' Transformative to the mainframe market
' announced in '64

---
### S360 Features
+ 8-bit Byte
+ Byte Addressable Memory
+ 32-Bit Words
+ 9 track tape

' dominated offline backup for 30 years.

---
### Problems
- Multiple OS across Multiple Machines
- TSS/360 Never Released
- OS/360 Year Late 
- Significantly Over Budget
- Heavy Resource Consumer  
- Personnel Loss from Fatigue

' Time Sharing System
' Lots of problems, crazy schedule huge staff as competitive attack on Multics
' not a snow-flake, lots of failed systems 

---
#### Software Crisis
> How does a project get to be a year late?... One day at a time. - Mythical Man Month [p153]

' By 1960 USAF was spending more on software than hardware.

---
> "The time has arrived to switch from home-made software to manufactured software, from tinkering to engineering - twelve year after a similar transition has taken place in the computer hardware field ... it is high time to take this step. The use of computer has reached the stage that software production ... has become a bottleneck for further expansion" - Bauer @ 1968 Software Engineering Conference

' S/360 by 1970 became wildly successful

*** 
### So what is this paper?

' Write about process expressing our intuitions about how humans behave in systems 
' this is a reflection on S/360 after 20 years - not discussed 
' MMM was a 10 year recap.


***
### Mythical Man Month
- External interfaces before internal implementations.
- Great Designers Design Great Things.
- Good management leads to good implementations.
- Adding labor to a late project only makes the project later.
- Programming requires communication.
 
' Dr. Cliff Snotes 

---
> Men and months are interchangeable commodities only when a task can be partitioned among many workers with no communication between them. 

---
> Since software construction in inherently a systems effort - an exercise in complex interrelationships - communication effort is great, and it quickly dominates the decrease in individual task time brought about by partitioning. Adding more men then lengthens, not shortens, the schedule. 

' this is systemic disease within IBM
' Document for others not

---
Programming **Requires** Communication

> There are only two problems in software and it's communication.

' problem is brooks got it wrong
' Paths escalate logarithmically communication doesn't have to
' writers rooms

***
### Order of What?
> There is no single development, in either technology or management technique, which by itself promises even one order-of-magnitude improvement within a decade in productivity, in reliability, in simplicity.

' what exactly is Brooks measuring here?
' talking specifically about the software process.
' Alluded to MMM & Software Crisis

---
### The Roots?
>"You cannot expect society to accept this, and therefore we must learn to program an order of magnitude more effectively." - Dijkstra

***
#### Improve ALL THE THINGS!

- **Productivity**
- **Reliability** 
- **Simplicity**

' to get 10x improvement 90% need to be accidents 
' tools reduce accidents to 0
' brooks things the former is false latter impossible

---
#### Essential vs Accidental Complexity  

+ Essential - complexity arising because of the nature of software
+ Accidental - complexity arising from production of software

Brooks suggests that most techniques attack the accidents of software engineering.

' Building abstract data structures vs language representations
' this is to say there exists a pure model 
' problem was this was from an OS/Tooling perspective.

***
### Essential Difficulties
+ Complexity 
+ Conformity 
+ Changeability 
+ Invisibility 

---
### Complexity
+ Software is complex for its size
+ Lots of state
+ Essential Complexity increases non-linearly w/size 
+ Complexity is intrinsic in many domains 

' what size?
' Linux has little problem communicating, poor organization design
' hand-waving 
' intrinsic complexity due to lack of abstractions

--- 
### Complexity creates:
+ Communication problems (MMM)
+ Flaws, overruns, delays
+ Lots of possible states 
+ Lack of extensibility 
+ Unrecognized state leads to security flaws
+ Steep learning curves put pressure on labor turn-over

' Functional Programming
' why is labor turn-over bad? needs to be strategic  

---
### Conformity
+ Humans design poor interfaces, therefore complexity 
+ Software must conform: 
    + because it's the newest tech
    + because it's the most conformable

' this is a value argument 

---
### Changeability 
+ Software constantly subject to pressures for change
+ Argues manufactured products rarely change after manufacture
+ Software is 'thought stuff', infinitely malleable 
+ Designed for Hardware which it outlives

We change software due to edge cases or success drives further innovation

' Not a requirement not implicit 
' cloud abstractions 

---
### Invisibility 
+ UML
+ Domain Driven Design
+ Functional Programming 
    + Domain & Range
    + Map X => Y 
    + Filter X where Y
    + Reduce  X,Y => Z 
+ MIT's Scratch, Labview, etc.

' brooks speaks about what cannot be visualized
' geometric visualizations, software not in embedded space

---
### Invisibility cont.
+ Software diagrams (complex systems) are several directed graphs, super-imposed
+ Graphs Represent
    + Flow Control
    + Patterns of Dependency
    + Time Sequence 
    + Name-Space Relationships  


*** 
#### The software task
+ Buy don't Build
+ Incremental & Iterative Development
+ Prototype, Prototype, Prototype
+ Identify & Develop Great Designers 

' Might be OSS

---
### You think it started with a manifesto?
>  "We were doing incremental development as early as 1957, in Los Angeles, under the direction of Bernie Dimsdale [at IBM's ServiceBureau Corporation]." - Larman

--- 
> "If the waterfall model risks not building the right product, then agile risks not building the product right. I’m very fond of Erlang creator Mike Williams point: “If you don’t make experiments before starting a project, then your whole project will be an experiment”. My hunch is what a lot of Agile process misses is that you need to experiment before you build." - Jesper Louis Andersen

---
### Requirements & the Prototype
+ Clear argument for prototyping 
+ Evolution of MMM's Second System Argument
+ Sets up case for (a)gile

' complexity really comes from poor assesmsent of problem domain - DDD
' weird argument about building vs writing programs

---
### Write Software, Grow Systems 
<br />
Brooks proposes:
+ Top Down Design
+ Fill in the blank (rewarding)

' lisp and functional support bottom up & top down


---
### Designer
+ Identification 
+ Career Development & Mentorship
+ Interactions

' Really about retention 

---
> "Simplicity and elegance are unpopular because they require hard work and discipline to achieve and education to be appreciated" - Dijkstra

---
> "The one opinion was that a really competent programmer should be puzzle-minded and very fond of clever tricks; the other opinion was that programming was nothing more than optimizing the efficiency of the computational process, in one direction or the other." - Dijkstra

***
#### Why do we need a "silver bullet"?
+ Software Crisis
+ Coupled to Hardware due to limited abstractions

' reference back to SE crisis
' limited abstractions coupled us tightly to hardware 
' see gains in h/w want them for software
' keen to tie software to manufacturing - cloud 
' creative process managed as such

---
#### Price to Performance gains 
+ Commoditized Software engineering 
+ Cost Cutting 
+ Software Engineering Crisis 

>"There seem to be three major conditions that must be fulfilled. The world at large must recognize the need for the change; secondly the economic need for it must be sufficiently strong; and, thirdly, the change must be technically feasible." - Dijkstra








***

What's Really Hard?

- Specification & Estimation 
- Design
- Testing

' software is the servant of many domains.
' testing is of the conceptual not the artifacts

---


***


***
### What Did Brooks Get Wrong?
+ Speech Recognition & Image Recognition 
+ Manufacturing Retro-Fitting Not Hard - Design for it.

' Speech & Image not for programming domain

***
### What Did Brooks Miss?
+ We've No Context
+ OS/Tools vs. Product/Contracting
+ Achieving for ourselves vs. target domain

' 2 tings at play
' ability to achieve in problem domain and in programming domain

***
### Things To Think On
+ Why do we impose scientific reasoning/rigor on the systems crafted by humans, but not the system of humans that crafted them?
+ Should we ever write formal process papers that neglect to mention context?
