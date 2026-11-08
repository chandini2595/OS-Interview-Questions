# UNIT V — Deadlocks & Disk Management Deadlocks 

1. What is deadlock? Explain with a 2-process, 2-resource example.
2. What are the 4 necessary and sufficient conditions for deadlock?
3. Mutual exclusion, hold and wait, no preemption, circular wait — explain each with an example.
4. What is a resource allocation graph, and how does a cycle relate to deadlock?
5. What are the strategies for handling deadlocks — prevention, avoidance, detection & recovery, and ignoring it?
6. Deadlock prevention: how do you break each of the 4 conditions in practice?
7. Which deadlock condition is cheapest/easiest to break in real systems, and how (lock ordering)?
8. What is deadlock avoidance, and how is it different from prevention?
9. Safe state vs unsafe state vs deadlocked state — what is the difference?
10. What is Banker's algorithm, and what data does it need (Available, Max, Allocation, Need)?
11. Walk through Banker's algorithm / safety algorithm on a small example — is the state safe, and what is a safe sequence?
12. How does resource-request algorithm in Banker's decide whether to grant a request?
13. What is deadlock detection, and how does wait-for graph / detection algorithm work?
14. Deadlock detection and recovery: what are the recovery options (kill process, preempt resources, rollback)?
15. Deadlock vs starvation vs livelock — compare them.
16. Why do most general-purpose OS ignore deadlocks (ostrich approach)?
17. Disk Management What is the structure of a disk — tracks, sectors, cylinders, platters, heads?
18. What are seek time, rotational latency, and transfer time?
19. Disk access time = ?
20. What is disk scheduling, and why is it needed?
21. FCFS disk scheduling: how does it work, calculate total head movement for a queue.
22. SSTF disk scheduling: how does it work, calculate total head movement, and what is its starvation problem?
23. SCAN (elevator) disk scheduling: how does it work, calculate total head movement.
24. C-SCAN disk scheduling: how does it work, and how is it different from SCAN?
25. FCFS vs SSTF vs SCAN vs C-SCAN — compare total head movement and fairness on the same request queue.
26. SCAN vs C-SCAN — why does C-SCAN give more uniform wait time?
27. What is disk reliability, and what is RAID / mirroring at a concept level?
28. What is disk formatting — physical/low-level vs logical formatting?
29. What is a boot block, and what happens from boot block during system startup?
30. What is a bad block, and how are bad blocks handled (spare sectors, sector sparing/slipping)?
31. How are bad blocks detected, and why can't you just ignore them?
