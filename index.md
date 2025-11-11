# Methodology Assignment 4
## Task 2

### Name: Edgar Guzman
#### Email: eiguzman@ucsd.edu
#### Section: A02
#### TA: Amirhossein Panahi

**What is the most interesting topic covered in your domain this quarter?**
One topic that I found the most interesting while working on this project is the Verilog and hardware design languages that are used for FPGAs and ASIC systems. During my educational career at UCSD, Python and Java were the only programming languages I was exposed to. Verilog and SystemVerilog are two languages I had to understand before I could understand the project I am replicating. While my experience is with software and running neural networks through python, learning a hardware design language allows me to delve into the hardware side of Data Science and gives me the experience I need to pursue a career working in a new range of fields closer to computer systems.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
For our quarter 2 project, I would like to continue the previous year’s project through the implementation of pipelining. Due to pyRTL’s generation of Verilog, parallelism exists independently between each operation. Runtimes are only improved from standard numpy and IEEE through parallel processing and the benefits of the l-Mul algorithm. Through the use of pipelining in Verilog, parallelism exists between operations and can potentially reduce the number of cycles where variables undergo multiple operations.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
While running performance simulations for our l-Mul algorithm, there is a heavy dependency on packages that convert python instructions into Verilog test benches. Hand-writing Verilog code instead guarantees that our writing style can benefit more from parallelism (through additional “always”, “fork” and “assign” statements). This may cause issues in the near future as our Verilog files become increasingly large, as the previous year’s project contained files over 100,000 lines long.

**What other techniques would you be interested in using in your project?**
Our group has brainstormed implementing LSTM architecture as a replacement for the systolic array schema used in the project we are replicating. Additionally, a conversion from software implementation to ASIC implementation has been discussed in order to take advantage of the general problem’s complex design.
