
## Memory
##### Buffered Memory (RDIMM)
- includes buffer between IMC and DRAM chips
- register between IMC and actual memory
- helps to control electrical load on memory bus
- when you add more memory the electrical load on the bus increases
- improves system load and integrity

##### Memory CAS Latency
- Column Address strobe latency (CAS)
- CAS latency is measured in clock cycles
- lower CAS latency gives better memory performance

##### Error Correcting Code (EEC)
- includes additional bits for error detection and correction
- improves reliability

## Expansion Cards
- aka dedicated cards
- designed to use particular expansion bus standard
- supports plug and play
- supports **full duplex** - **simultaneous bidirectional data transfer**

##### PCIe (peripheral component interconnect express)
- defines x2, x4, x8, x16, and x32
	- x1 is one lane transmission
	- x16 is sixteen lane transmission
	- GPUs are x16
- cross size compatible
	- smaller cards can fit in larger PCIe slots
	- x4 card can fit in 8x slot
![[Pasted image 20231005110733.png]]