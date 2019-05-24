# Minux
Dream =))
Minux  is  a  recommender  system  that  creates  an  optimized  kernel  according  to  theusers  hardware  configuration,  to  provide  better  performance.   Now  Im  studying  tomatch kernel requests to memory specifications.

## !

### 
we have two approaches for configuring kernel based on hardware:
1. scan the system and decide based on detected information from hardware. this decision may be taken by a trained intelligent machine.
2. create a lookup table and have a suggested configuration based on hardware details.

#### deciding base
1. based on all board information: how to get this information(search about JTAG)
2. based on CPU information: Memory Management Unit, Memory Hierarchy(affects on the miss and hit percentage), Memory Type(affects on miss clock penalty)

#### what we need to develop
1. a compiler that compiles codes according to Memory design
2. change kernel for the size of Memory access


### Learning
* #### Computer Architecture: learn from 'Operating Systems by William Stallings'  
https://www.pearson.com/us/higher-education/program/Stallings-Operating-Systems-Internals-and-Design-Principles-9th-Edition/PGM1262980.html?tab=contents

I. Background

- [x] 1. Computer System Overview
- [ ] 2. Operation System overview
- [ ] 2.1. Operating System Objectives and Functions
- [ ] 2.2. The Evolution of Operating Systems
- [ ] 2.3. Major Achievements
- [ ] 2.4. Developments Leading to Modern Operating Systems
- [ ] 2.5. Fault Tolerance
- [ ] 2.6. Os Design Considerations for Multiprocessor and Multicore
- [ ] 2.7. Microsoft Windows Overview
- [ ] 2.8. Traditional Unix Systems
- [ ] 2.9. Modern Unix Systems
- [ ] 2.10. Linux
- [ ] 2.11. Android

#### OS kernel: learn from 'Operating System Concepts by Avi Silberschatz'

### Check existing works and articles
https://www.phoronix.com/

### Find criteria of performance
* watch out difference between OS and Computer performance

### notes
* #### Desktop Design: simple like Windows,Beautiful like OSX - comfy?
