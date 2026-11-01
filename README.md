# OS-Interview-Questions

## **1. OS Fundamentals**
- What is an Operating System? - Interface between user and system hardware
- Kernel - kernal is main component in OS that controls hardware
- User Mode vs Kernel Mode
When an application needs to run on system hardware e.g., saving a file.
user mode raises a system call
kernal take that API request and change it to kernal mode and do that operation and give the result to user
- System Calls - its a request by an application or user to do some harware level operation
- Interrupts - When CPU is busy, it saves its current process state and run interrupt handler and then after that it come back to current state
- OS Architecture
2. Processes
- Program vs Process
- Process States
- Process Control Block (PCB)
PCB is a data structure maintained by the OS that stores information needed to manage a process.

Typical contents:
1. Process ID (PID)
2. Process State — ready, running, waiting, etc.
3. Program Counter — address of the next instruction to execute
4. CPU Registers
5. Scheduling information — priority, scheduling data
6. Memory-management information — page-table-related information, address-space metadata
7. I/O information — open files/devices and related state
8. Accounting/resource information
   
- Process Creation & Termination
- fork()
- exec()
- Zombie Process
- Orphan Process
- Context Switching
3. Threads
- Process vs Thread
- User-Level vs Kernel-Level Threads
- Multithreading
- Concurrency vs Parallelism
- Benefits of Multithreading
- Thread Context Switching
4. CPU Scheduling
- Preemptive vs Non-Preemptive Scheduling
- Scheduling Criteria
- FCFS
- SJF / SRTF
- Priority Scheduling
- Round Robin
- Starvation
- Aging
- Multiprocessor Scheduling
- Real-Time Scheduling
- Rate Monotonic (RM)
- Earliest Deadline First (EDF)
5. Process Synchronization
- Critical Section
- Race Condition
- Mutual Exclusion
- Atomic Operations
- Locks
- Mutex
- Semaphore
- Binary vs Counting Semaphore
- Spinlock
- Peterson's Solution
- Monitors
- Condition Variables
- Producer–Consumer Problem
- Readers–Writers Problem
- Dining Philosophers Problem
6. Inter-Process Communication (IPC)
- Shared Memory
- Message Passing
- Pipes
- Named Pipes
- Sockets
- Signals
- Shared Memory vs Message Passing
7. Deadlocks
- What is Deadlock?
- Four Necessary Conditions
- Deadlock Prevention
- Deadlock Avoidance
- Banker's Algorithm
- Deadlock Detection
- Deadlock Recovery
- Deadlock vs Starvation
- Livelock
8. Memory Management
- RAM vs ROM
- Address Space
- Logical / Virtual Address
- Physical Address
- MMU
- Memory Allocation
- Contiguous Memory Allocation
- Fixed Partitioning
- Variable Partitioning
- Internal Fragmentation
- External Fragmentation
- Compaction
9. Paging
- Pages and Frames
- Page Size
- Page Table
- Virtual-to-Physical Address Translation
- Page Number & Offset
- Multi-Level Page Tables
- TLB
- TLB Hit / TLB Miss
- Paging Protection
- Shared Pages
- Internal Fragmentation in Paging
10. Segmentation
- Segments
- Segment Table
- Base & Limit
- Segmentation Address Translation
- Paging vs Segmentation
11. Virtual Memory
- Virtual Memory Basics
- Demand Paging
- Page Fault
- Page Fault Handling
- Present / Valid Bit
- Dirty Bit
- Locality of Reference
- Temporal Locality
- Spatial Locality
- Working Set
- Thrashing
- Swapping
12. Page Replacement
- FIFO
- Optimal
- LRU
- Clock / Second Chance
- NRU
- Belady's Anomaly
- Page Fault Rate
13. Stack & Heap
- Stack Memory
- Heap Memory
- Stack vs Heap
- malloc()
- calloc()
- realloc()
- free()
- Memory Leaks
- Dangling Pointers
- Stack Overflow
14. File Systems
- File Concepts
- File Operations
- File Descriptors
- Access Methods
- Directory Structure
- File-System Structure
- File Allocation
- Contiguous Allocation
- Linked Allocation
- Indexed Allocation
- Inodes
- Free-Space Management
- Hard Link vs Symbolic Link
15. I/O Management
- I/O Devices
- Device Controllers
- Device Drivers
- Interrupts
- Polling
- DMA
- Interrupt-Driven I/O
- Blocking vs Non-Blocking I/O
- Synchronous vs Asynchronous I/O
16. Disk / Storage Management
- Disk Structure
- FCFS
- SSTF
- SCAN
- C-SCAN
- Disk Formatting
- Boot Block
- Bad Blocks
- HDD vs SSD
17. High-Priority Interview Comparisons
- Process vs Thread
- Concurrency vs Parallelism
- Mutex vs Semaphore
- Deadlock vs Starvation vs Livelock
- Paging vs Segmentation
- Virtual vs Physical Memory
- Stack vs Heap
- TLB Miss vs Page Fault
- Internal vs External Fragmentation
- User Mode vs Kernel Mode
- Interrupt vs System Call
- fork() vs exec()
- Blocking vs Non-Blocking I/O
- Synchronous vs Asynchronous I/O
