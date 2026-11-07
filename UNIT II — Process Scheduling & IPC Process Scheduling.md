## UNIT II — Process Scheduling & IPC Process Scheduling 

1. What is process scheduling, and what are its objectives/foundation?
   
2. What are the types of schedulers — long-term, short-term (CPU), and medium-term — and what does each control?

3. What is the difference between a scheduler and a dispatcher?

4. Define the scheduling criteria: CPU utilization, throughput, turnaround time, waiting time, and response time — with formulas.

5. Preemptive vs non-preemptive scheduling — difference, advantages, and risks.

6. FCFS scheduling: how does it work, calculate waiting/turnaround time for 3 processes, and what is the convoy effect?

7. SJF scheduling: how does it work, why is it optimal, and why is it hard to implement?

8. Preemptive SJF (SRTF) vs non-preemptive SJF — what changes?

9. In SJF, how is the next CPU burst predicted?

10. Round Robin scheduling: how does it work, and how does the time quantum size affect performance?

11. Round Robin with quantum = very large and quantum = very small — what does it become / what breaks?

12. Given arrival and burst times for 3–4 processes, draw the Gantt chart and calculate average waiting and turnaround time for FCFS, SJF, and RR.

13. What is starvation, and which algorithms can cause it?

14. What is multiprocessor scheduling, and what are its main challenges (affinity, load balancing, symmetric vs asymmetric)?

15. Processor affinity — soft vs hard affinity, why does it matter?

16. What is real-time scheduling, and what makes it different from normal scheduling?

17. Rate Monotonic (RM) scheduling: how are priorities assigned, and when is it optimal?

18. Earliest Deadline First (EDF) scheduling: how does it work, and how is it different from RM?

19. RM vs EDF — compare priority type (static vs dynamic), utilization, and implementation.

20. Which scheduling algorithm would you pick for an interactive system, a batch system, and a real-time system — and why?

21. Inter-Process Communication & Synchronization What is a critical section, and what 3 requirements must a solution satisfy?

22. What is a race condition? Explain with a shared bank balance / counter example.

23. What is mutual exclusion, and why is it needed?

24. What are hardware solutions for mutual exclusion — disabling interrupts and test-and-set / atomic instructions — and their limits?

25. What is strict alternation, and which critical-section requirement does it violate?

26. What is Peterson's solution, how does it work for 2 processes, and what are its limits? What is the Producer/Consumer (bounded buffer) problem?

27. How do you solve Producer/Consumer with semaphores and a mutex — which semaphores, and why? What is a semaphore?

28. What are wait/P and signal/V operations?

29. Binary semaphore vs counting semaphore — difference and use case for each.

30. Mutex vs semaphore — what is the difference in ownership and counting?

31. What are event counters, and how are they different from semaphores?

32. What is a monitor, and how do condition variables work inside it?

33. Monitor vs semaphore — which is higher level, and why are monitors safer for programmers?

34. What is message passing in IPC? Direct vs indirect communication, synchronous vs asynchronous?

35. Message passing vs shared memory — compare speed, synchronization, and use case.

36. What is the Readers & Writers problem, and what is the core tradeoff?

37. In Readers & Writers, how can writers starve, and how can readers starve?

38. What is the Dining Philosophers problem, and why is it a deadlock/starvation example?

39. How do you prevent deadlock in Dining Philosophers?

40. What is a pipe, a message queue, a socket, and a signal — one-line use case for each IPC mechanism?

