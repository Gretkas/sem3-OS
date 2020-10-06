# Address translation concept

![Address translation](../../../.gitbook/assets/adress-translation.png)

### The goals of address translation

* Memory protection
* Memory sharing
  * shared libraries, interprocess communication
* Sparse addresses
  * Multiple regions of dynamic allocation\(heaps/stacks\)
* Efficiency
  * Memory placement
  * Runtime lookup
  * Compact translation tables
* portability

### Virtually addressed base and bounds

![Base and bounds](../../../.gitbook/assets/base-and-bounds.png)

Each process gets a base and bound register. When a

