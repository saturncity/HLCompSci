# Computer Architecture
#Topic2 #ComputerArchitecture #CPU #Memory

- Computing Systems use the (input -> process -> output) model.
	- The IB uses the (input -> process -> storage -> output) model.
	- The storage phase is used during the process phase.
	- Input is data and the output is information
- Computing system system consist of hardware and software components.
- The CPU is responsible for the processing.

##### Hardware
- Hardware is physical components of the computer.
- Some examples are:
	- The CPU (Central Processing Unit)
	- The RAM (Random Access Memory)
	- The SSD (Soild-State Drive)
	- The GPU (Graphics Processing Unit)

##### Software
- Software is the components of the computer that utilize the physical components to do something.
- Some examples are:
	- BIOS (Basic Input Output System)
	- Operating Systems
	- Applications

##### Data
- Data is raw and unprocessed.

##### Information
- Information is processed and has been put through the CPU.

### The CPU
- The CPU is the main processing compenent of a computing system.
- The CPU, unlike humans, cannot think for its self which is why it can only take instructions in Machine Language which is in Binary.

##### Control Unit (CU)
- This unit is responsible for the retrieval of data from the primary memory.
- The MAR and MDR is located in the CU.

##### Arithmetic Logic Unit (ALU)
- This unit does all the basic arithmetic and logical operations.
- This unit gets its information from the CU and outputs to the Primary Memory.

##### Memory Address Resgister (MAR)
- The MAR gets the data addresses from the RAM to tell the MDR where to get the data. The MAR queues this information.
- The MAR fetches this info through the Memory Address Bus.

##### Memory Data Resgister (MDR)
- This unit loads and takes data with instructions from the MAR. The MDR then sends this data the the ALU for processing
- The CU uses the address from the MAR to get the data through the Data Bus.

#### Primary Memory 
- This is the only type of memory accessable by the CPU.
- Holds Data & Instructions that are currently running on the system.

##### RAM / DRAM
- Random Access Memory.
- Read and writeable memory.
- Holds instructions ready to be loaded and executed, whenever needed.
- RAM is volatile which means that the memory is lost when power is removed.

##### ROM
- Read-Only Memory.
- Unwriteable memory.
- ROM is non-volatile which means that its contents cannot changed.
- Used to store instuctions and data.

### The Cache 
- The cache holds information from the RAM that is most activly used and accessed most often.
- The computer will run faster as the slower memory (DRAM) will be accessed less.
- Usually 3 levels of cache, L1, L2 & L3. (It was 2)
- Checking for data follows: (L1 -> L2 -> L3 -> DRAM)

##### SRAM
- Static RAM (SRAM) is faster and more expensive than DRAM.
- Is volatile

### The Machine Instruction Cycle [[Day 5; Machine Instruction Cycle]]

 ![[part of a computing system - memory & cpu.png]]

### Secondary Memory / Persistent Storage
- Non-volitle and writeable
- Holds onto data when power is lost.
- Data from here gets loaded on the RAM then from there it can be used in processing

##### Examples
- Hard drive (a.k.a. hard disk)
- CD-RW, DVD-RW
- USB Flash drive
- Secure Digital (SD) or Compact Flash (CF) card
- Zip disk
- Floppy disk
- Magnetic Tape

##### Virtual Memory (VRAM)
- VRAM is when secondary memory can be used as primary memory.
- This can help when there is a RAM shortage.
- Commonly used in Operating Systems [[Day 6; Operating Systems]]
- The data still has to be loaded from the RAM but the memory in the RAM can be unloaded and put back into secondary storage.

## Memory Hierarchy #Memory

![[memory hierachy.jpeg]]
