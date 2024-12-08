# Operating System
## Introduction
### What this page is
- Originally (~2021) this was a list of how I first got into OS
- Now its a bit of a combination of how to get into OS and my musings on undergraduate OS classes
- This needs more updating
### How OS is traditionally taught
- Most OS classes have a "theory" component and a project component
### Theory Component
- The goal of this part is to teach you the fundamental mechanisms and policies of operating systems
#### Stratifications/Topics
1. Virtualization / Isolation: What is a process
	- process abstraction
	- context switch
	- virtual memory / paging
	- Note: this is really the key mechanisms part
2. Resource management: How do processes share resources
	- Memory allocation
	- Scheduling
3. Synchronization: How can concurrent processes (or threads) communicate 
	- Locks
	- Other synchronization structures
4. File Systems: How do we store data 
#### What is typically ignored 
- drivers
- Network subsystem 
### Project component
#### Approach 1: Build an OS
- in this style of class, you build an OS "from scratch", building it up with new components as you learn throughout class
- Typically, these projects are done in a virtual environment (as OS natively runs directly on a CPU)
- Pro: Get a good feel for the low-level coding style which is OS coding
- Con: Spend a lot of time doing menial tasks, can distract from learning concepts 
#### Approach 2: Userspace OS 
- in this style of class, you build OS-related components that run in userspace
- Pro: You get to write code in a realistic environment
- Con: Don't get exposed to the low-level stuff
	- especially paging 
## Theory
### Lecture Series
My favorite OS lecture series are by Prof. [Geoffrey Challen](https://www.geoffreychallen.com/). The assignments, sample exams, and lectures are all available at [ops-class](https://ops-class.org/).

## Do it yourself
[OSDev](https://wiki.osdev.org) is by and far the best resource in this aspect. I reccomend building an understanding of ISAs before beginning in this project.

### Which ISA to choose
Many people choose x86 as their first ISA as it has extensive documentation. This is a solid choice, however, I think Risc-V offers a compelling open source option thats fairly easy to work with.
### Tools
- Gnu toolchain (cross compiler version for target ISA) 
- GDB
- Qemu
- Gnu Make 


### Writing an OS in Risc-V resources

|Title|Description|Author|
|-----|-----------|------|
|[RISC-V OS Using Rust](https://osblog.stephenmarz.com/ch1.html)|Good tutorial of how to work with Risc-v (in rust)|[Stephen Marz](https://marz.utk.edu/)|
|[Xv6-RISCV Source](https://github.com/mit-pdos/xv6-riscv#readme)|Unix-v6 in RISC-V (also availaible in x86)|See Authors on [readme](https://github.com/mit-pdos/xv6-riscv/blob/riscv/README)|
|[Xv6-RISCV Book](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf) | Unix-v6 in RISC-V Book documentation|[Russ Cox](https://swtch.com/~rsc/), [Frans Kaashoek](http://people.csail.mit.edu/kaashoek/), [Robert Morris](https://www.csail.mit.edu/person/robert-morris)|

## Learn about production operating systems
### Comprehensive books
- Since Operating Systems are extremely complicated, it is difficult (impossible) to find a comprehensive resource which covers all aspects of a modern OS
- That said, some books can be useful in giving either a historical perspective, or high level overview 

#### Examples

|Title|Description|Author|
|-----|-----------|------|
|The design of the Unix Operating System|Great to learn historical (simple + fundamental) OS design choices|Maurice J. Bach|
|[Design and Implementation of the 4.4BSD Operating System](https://docs.freebsd.org/en/books/design-44bsd/)|Covers transition into more modern OS design|[Kirk McKusick](https://www.mckusick.com/), [Keith Bostic](https://bostic.com), [Mike Karels](https://www.linkedin.com/in/mike-karels-9b890020/),[John Quarterman](https://www.wikiwand.com/en/John_Quarterman)|
|Design and Implementation of the FreeBSD Operating System (2nd edition)|Covers more modern OS design|[Kirk McKusick](https://www.mckusick.com/), [George V. Neville-Neil](https://http://www.neville-neilconsulting.com/), [Robert Watson](https://www.cl.cam.ac.uk/~rnw24/)|

