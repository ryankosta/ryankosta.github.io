#Operating System
##Do it yourself
[OSDev](https://wiki.osdev.org) is by and far the best resource in this aspect. I reccomend building an understanding of ISAs before beginning in this project.

##Which ISA to choose
Many people choose x86 as their first ISA as it has extensive documentation. This is a solid choice, however, I think Risc-V offers a compelling open source option thats fairly easy to work with.

##Lecture Series
My favorite OS lecture series are by Prof. [Geoffrey Challen](https://www.geoffreychallen.com/). The assignments, sample exams, and lectures are all available at [ops-class](https://ops-class.org/).
##Working with Risc-V resources
|Title|Description|Author|
|-----|-----------|------|
|[RISC-V OS Using Rust](https://osblog.stephenmarz.com/ch1.html)|Good tutorial of how to work with Risc-v (in rust)|[Stephen Marz](https://marz.utk.edu/)|
|[Xv6-RISCV Source](https://github.com/mit-pdos/xv6-riscv#readme)|Unix-v6 in RISC-V (also availaible in x86)|See Authors on [readme](https://github.com/mit-pdos/xv6-riscv/blob/riscv/README)|
|[Xv6-RISCV Book](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf) | Unix-v6 in RISC-V Book documentation|[Russ Cox](https://swtch.com/~rsc/), [Frans Kaashoek](http://people.csail.mit.edu/kaashoek/), [Robert Morris](https://www.csail.mit.edu/person/robert-morris)|

##Learn how its already done
|Title|Description|Author|
|-----|-----------|------|
|The design of the Unix Operating System|Great to learn historical (simple + fundamental) OS design choices|Maurice J. Bach|
|[Design and Implementation of the 4.4BSD Operating System](https://docs.freebsd.org/en/books/design-44bsd/)|Covers transition into more modern OS design|[Kirk McKusick](https://www.mckusick.com/), [Keith Bostic](https://bostic.com), [Mike Karels](https://www.linkedin.com/in/mike-karels-9b890020/),[John Quarterman](https://www.wikiwand.com/en/John_Quarterman)|
|Design and Implementation of the FreeBSD Operating System (2nd edition)|Covers more modern OS design|[Kirk McKusick](https://www.mckusick.com/), [George V. Neville-Neil](https://http://www.neville-neilconsulting.com/), [Robert Watson](https://www.cl.cam.ac.uk/~rnw24/)|

##Tools
- Gnu toolchain (cross compiler version for target ISA) 
- GDB
- Qemu
- Gnu Make 
- Real hardware + jtag (or swd)
