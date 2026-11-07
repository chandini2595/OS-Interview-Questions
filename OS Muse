OS Interview Questions — Syllabus Units I–V
For: Chandini — Supermicro Switch Design (29680), Nov 17, 2026
Questions only, in syllabus order. Covers every topic in Units I–V as supplied Nov 6, 2026.
UNIT I — Introduction, Processes, Threads
Introduction to OS
What is an operating system, and what are its two main goals?
What does the OS do as a resource manager vs as an extended/virtual machine?
What are the generations of operating systems, and what changed in each?
What are the types of operating systems — batch, multiprogrammed, multitasking/time-sharing, real-time, distributed, embedded?
Batch vs time-sharing OS — what is the difference in response time and CPU use?
Hard real-time vs soft real-time OS — give an example of each.
What are the main OS services provided to programs and to users?
What is a system call, and how is it different from a library/API call?
Name the types/categories of system calls with one example each.
Walk through what happens step-by-step when a program makes a system call.
What is a layered OS structure, and what are its advantages and disadvantages?
What is a monolithic kernel, and what are its advantages and disadvantages?
What is a microkernel, and how does it differ from a monolithic kernel?
Layered vs monolithic vs microkernel — compare performance, reliability, and modularity.
What is a virtual machine, and what is a hypervisor?
Type 1 vs Type 2 hypervisor — what is the difference?
What are the benefits and drawbacks of virtual machines?
UNIX case study: what are the key design features, structure, and philosophy of UNIX?
Windows case study: what are the key design features and structure of Windows?
UNIX vs Windows — compare kernel approach, file system, and process/thread model at a concept level.
Processes
What is a process, and how is it different from a program?
What is the relationship between parent and child processes?
How are processes created and terminated in UNIX (fork, exec, wait, exit)?
What are the different states of a process?
Draw/explain process state transitions — what event moves a process from Ready to Running, Running to Waiting, Waiting to Ready, Running to Ready?
What is a Process Control Block (PCB), and what information does it contain?
What is context switching, and what are its steps?
Why is context switching pure overhead, and what determines its cost?
Process vs thread context switch — why is one cheaper?
What is a zombie process and what is an orphan process?
Threads
What is a thread, and why were threads introduced?
What are the states of a thread?
What do threads of the same process share, and what is private to each thread?
What are the benefits of threads over processes?
What are the types of threads — user-level threads vs kernel-level threads?
User-level vs kernel-level threads — compare blocking, switching cost, and multicore use.
What is multithreading, and what are the multithreading models (many-to-one, one-to-one, many-to-many)?
What are the problems/issues with threaded programs?
Single-threaded vs multithreaded process — when would you choose each?
If one thread crashes/segfaults, what happens to the whole process, and why?
UNIT II — Process Scheduling & IPC
Process Scheduling
What is process scheduling, and what are its objectives/foundation?
What are the types of schedulers — long-term, short-term (CPU), and medium-term — and what does each control?
What is the difference between a scheduler and a dispatcher?
Define the scheduling criteria: CPU utilization, throughput, turnaround time, waiting time, and response time — with formulas.
Preemptive vs non-preemptive scheduling — difference, advantages, and risks.
FCFS scheduling: how does it work, calculate waiting/turnaround time for 3 processes, and what is the convoy effect?
SJF scheduling: how does it work, why is it optimal, and why is it hard to implement?
Preemptive SJF (SRTF) vs non-preemptive SJF — what changes?
In SJF, how is the next CPU burst predicted?
Round Robin scheduling: how does it work, and how does the time quantum size affect performance?
Round Robin with quantum = very large and quantum = very small — what does it become / what breaks?
Given arrival and burst times for 3–4 processes, draw the Gantt chart and calculate average waiting and turnaround time for FCFS, SJF, and RR.
What is starvation, and which algorithms can cause it?
What is multiprocessor scheduling, and what are its main challenges (affinity, load balancing, symmetric vs asymmetric)?
Processor affinity — soft vs hard affinity, why does it matter?
What is real-time scheduling, and what makes it different from normal scheduling?
Rate Monotonic (RM) scheduling: how are priorities assigned, and when is it optimal?
Earliest Deadline First (EDF) scheduling: how does it work, and how is it different from RM?
RM vs EDF — compare priority type (static vs dynamic), utilization, and implementation.
Which scheduling algorithm would you pick for an interactive system, a batch system, and a real-time system — and why?
Inter-Process Communication & Synchronization
What is a critical section, and what 3 requirements must a solution satisfy?
What is a race condition? Explain with a shared bank balance / counter example.
What is mutual exclusion, and why is it needed?
What are hardware solutions for mutual exclusion — disabling interrupts and test-and-set / atomic instructions — and their limits?
What is strict alternation, and which critical-section requirement does it violate?
What is Peterson's solution, how does it work for 2 processes, and what are its limits?
What is the Producer/Consumer (bounded buffer) problem?
How do you solve Producer/Consumer with semaphores and a mutex — which semaphores, and why?
What is a semaphore? What are wait/P and signal/V operations?
Binary semaphore vs counting semaphore — difference and use case for each.
Mutex vs semaphore — what is the difference in ownership and counting?
What are event counters, and how are they different from semaphores?
What is a monitor, and how do condition variables work inside it?
Monitor vs semaphore — which is higher level, and why are monitors safer for programmers?
What is message passing in IPC? Direct vs indirect communication, synchronous vs asynchronous?
Message passing vs shared memory — compare speed, synchronization, and use case.
What is the Readers & Writers problem, and what is the core tradeoff?
In Readers & Writers, how can writers starve, and how can readers starve?
What is the Dining Philosophers problem, and why is it a deadlock/starvation example?
How do you prevent deadlock in Dining Philosophers?
What is a pipe, a message queue, a socket, and a signal — one-line use case for each IPC mechanism?
UNIT III — Memory Management & Virtual Memory
Memory Management
What is memory management, and why does the OS need it?
Logical address vs physical address — what is the difference, and who generates each?
What is the Memory Management Unit (MMU), and how does logical-to-physical address mapping work?
What is contiguous memory allocation?
Fixed partition vs variable partition allocation — compare them.
In contiguous allocation, what are first-fit, best-fit, and worst-fit?
What is internal fragmentation, and where does it occur?
What is external fragmentation, and where does it occur?
Internal vs external fragmentation — give an example of each.
What is compaction, how does it solve external fragmentation, and why is it expensive / when is it possible?
What is paging, and what is its principle of operation?
Page vs frame vs page table — define each.
How is a logical address split in paging, and how is it translated to a physical address?
How does page allocation work, and what happens when there are no free frames?
What hardware support is used for paging — page table, TLB, registers?
What is a TLB, why is it needed, and what is a TLB hit vs miss?
How does paging provide protection and sharing of pages?
What are the disadvantages of paging?
Paging vs contiguous allocation — why does paging remove external fragmentation but not internal fragmentation?
Virtual Memory
What is virtual memory, and what problem does it solve?
What hardware and control structures are needed for virtual memory?
What is locality of reference — temporal locality vs spatial locality — and why does virtual memory depend on it?
What is a page fault, and what are the steps to handle it in order?
Page fault vs TLB miss vs invalid access/segfault — what is the difference?
What is a working set, and how is it used to prevent problems?
What is a dirty page / dirty bit, and why does it matter when evicting a page?
What is demand paging, and how is it different from bringing all pages in at load time?
Demand paging: what is an effective access time, and what makes it get worse?
What is thrashing, what causes it, and how does the working-set model prevent it?
Optimal page replacement: how does it work, why is it the benchmark, and why can't it be implemented?
FIFO page replacement: how does it work, calculate page faults for a reference string, and what is Belady's anomaly?
Second Chance (SC) page replacement: how does the reference bit and clock hand work?
Not Recently Used (NRU) page replacement: how do the R and M bits classify pages?
Least Recently Used (LRU) page replacement: how does it work, calculate page faults for a reference string, and how is it implemented/approximated?
FIFO vs LRU vs Optimal — compare page faults on the same reference string with 3 frames.
Why does LRU usually perform better than FIFO in practice?
UNIT IV — File Management & I/O
File Management
What is a file, and what are file attributes?
What are the file access methods — sequential, direct/random, and indexed — and when is each used?
What are the common file types, and how does the OS know a file's type?
What are the basic file operations? (create, open, read, write, seek, delete, close, etc.)
What is a directory, and what operations are performed on directories?
What are the directory structures — single-level, two-level, tree, acyclic graph, general graph — pros and cons of each?
What is the file system structure / layered design of a file system?
Contiguous file allocation: how does it work, pros and cons?
Linked file allocation: how does it work, pros and cons, and what is FAT?
Indexed file allocation: how does it work, pros and cons, and what is an inode?
Contiguous vs linked vs indexed allocation — compare random access, fragmentation, and overhead.
How is free space managed with a bit vector / bitmap?
How is free space managed with a linked list?
How is free space managed with grouping (and counting)?
Bit vector vs linked list vs grouping for free-space management — compare overhead and performance.
How is a directory implemented with a linear list?
How is a directory implemented with a hash table?
Linear list vs hash table directory implementation — compare search speed and complexity.
What factors affect file system efficiency and performance? (block size, caching, etc.)
I/O Hardware & Software
What are I/O devices, and how are they classified (block vs character, dedicated vs shared)?
What is a device controller, and what does it do between the CPU and the device?
What is Direct Memory Access (DMA), and how does a DMA transfer work step-by-step?
Why is DMA better than programmed/interrupt-driven I/O for large transfers?
What are the goals/principles of I/O software?
What is an interrupt handler, and what does it do when an I/O interrupt occurs?
Programmed I/O (polling) vs interrupt-driven I/O vs DMA — compare CPU involvement.
What is a device driver, and what is its role?
What is device-independent I/O software, and what functions does it provide?
Device driver vs device-independent I/O software vs device controller — who does what?
What are buffering, caching, and spooling in I/O — one example each?
UNIT V — Deadlocks & Disk Management
Deadlocks
What is deadlock? Explain with a 2-process, 2-resource example.
What are the 4 necessary and sufficient conditions for deadlock?
Mutual exclusion, hold and wait, no preemption, circular wait — explain each with an example.
What is a resource allocation graph, and how does a cycle relate to deadlock?
What are the strategies for handling deadlocks — prevention, avoidance, detection & recovery, and ignoring it?
Deadlock prevention: how do you break each of the 4 conditions in practice?
Which deadlock condition is cheapest/easiest to break in real systems, and how (lock ordering)?
What is deadlock avoidance, and how is it different from prevention?
Safe state vs unsafe state vs deadlocked state — what is the difference?
What is Banker's algorithm, and what data does it need (Available, Max, Allocation, Need)?
Walk through Banker's algorithm / safety algorithm on a small example — is the state safe, and what is a safe sequence?
How does resource-request algorithm in Banker's decide whether to grant a request?
What is deadlock detection, and how does wait-for graph / detection algorithm work?
Deadlock detection and recovery: what are the recovery options (kill process, preempt resources, rollback)?
Deadlock vs starvation vs livelock — compare them.
Why do most general-purpose OS ignore deadlocks (ostrich approach)?
Disk Management
What is the structure of a disk — tracks, sectors, cylinders, platters, heads?
What are seek time, rotational latency, and transfer time? Disk access time = ?
What is disk scheduling, and why is it needed?
FCFS disk scheduling: how does it work, calculate total head movement for a queue.
SSTF disk scheduling: how does it work, calculate total head movement, and what is its starvation problem?
SCAN (elevator) disk scheduling: how does it work, calculate total head movement.
C-SCAN disk scheduling: how does it work, and how is it different from SCAN?
FCFS vs SSTF vs SCAN vs C-SCAN — compare total head movement and fairness on the same request queue.
SCAN vs C-SCAN — why does C-SCAN give more uniform wait time?
What is disk reliability, and what is RAID / mirroring at a concept level?
What is disk formatting — physical/low-level vs logical formatting?
What is a boot block, and what happens from boot block during system startup?
What is a bad block, and how are bad blocks handled (spare sectors, sector sparing/slipping)?
How are bad blocks detected, and why can't you just ignore them?
