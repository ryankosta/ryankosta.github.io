#CPUs

My CPU projects have been thus far designed simply to get me accustomed to learning digital design and Computer Architecture. 

My initial projects mostly use very low level constructs (such as gate level logic) that are great for learning but not as good for actual production code.

I hope to design another CPU using SpinalHDL utilizing it's features for a more testible CPU with advanced design elements such as out of order execution and branch prediction. I'm really interested in designing a CPU with dissagregation in mind. 

##[R100](https://github.com/ryankosta/r100)
- Risc-V
- Verilog
- Mostly gate level logic
- Non-pipelined

This was my first cpu to learn simple logic design. I never tested it using full Risc-V tests rather I used smaller tests just to ensure basic functionality.

##[R200](https://github.com/ryankosta/r200)
- Partial redesign of r100 
- Verilog
- Pipelined 
 
This CPU adds pipelining. I planned on expanding it but I quickly realized the design limitations of the gate level logic used in R100. 
