# What is virtual memory?

### Address space

The virtual memory is the memory that is availible for a process to see and use. The size of the address space is dependent on the architecture of the processor. Also called the address space.

* 64bit CPU
  * 64bit memory addresses
  * In reality the addresses are 48, and 40 bits depending on if it is Intel or AMD
* 32 bit CPU
  * 32 bit memory address
  * Pentium pro could use 36 bits

### The theoretical size of virtual  memory

The theoretical size of of virtual memory also depends on the architecture. On the register we are addressing on a Byte\(one Byte is 8 bits\) level. This means we can have 2⁶⁴ different addresses in a 64 bit system. This leads to a theoretical limit of 64 exabytes. In a 32 bit system, the memory limit is 4GB, because 2³²Bytes is 4GB.

### Typical memory sizes

The theoretical limit of memory sizes is still bound by the physical amount of memory on the system. We can't physically have matching sets of virtual and physical memory. There needs to be mapping from the virtual to the physical memory.







