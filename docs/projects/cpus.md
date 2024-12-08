# CPUs
## Introduction
### What these are
- Not a research project
- Mostly just for fun and to get a bit accustomed to computer archtecture
- The first big projects I did (incidentally making Verilog one of the first coding languages I really learned)
- These probably don't fully work. Not sure how much testing I did
- I did eventually design a fully working CPU in a class CSE141L, though the class forbids open sourcing :(

## [R100](https://github.com/ryankosta/r100)
### Introduction
- Risc-V
- Verilog
- Mostly gate level logic
- Non-pipelined

This was my first cpu to learn simple logic design. I never tested it using full Risc-V tests rather I used smaller tests just to ensure basic functionality.

## [R200](https://github.com/ryankosta/r200)
- Partial redesign of r100 
- Verilog
- Pipelined 
 
This CPU adds pipelining. I planned on expanding it but I quickly realized the design limitations of the gate level logic used in R100. 
