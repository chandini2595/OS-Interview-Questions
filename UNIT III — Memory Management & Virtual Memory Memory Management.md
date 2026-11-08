# UNIT III — Memory Management & Virtual Memory Memory Management 

1. What is memory management, and why does the OS need it?
2. Logical address vs physical address — what is the difference, and who generates each?
3. What is the Memory Management Unit (MMU), and how does logical-to-physical address mapping work?
4. What is contiguous memory allocation? Fixed partition vs variable partition allocation — compare them.
5. In contiguous allocation, what are first-fit, best-fit, and worst-fit?
6. What is internal fragmentation, and where does it occur?
7. What is external fragmentation, and where does it occur?
8. Internal vs external fragmentation — give an example of each.
9. What is compaction, how does it solve external fragmentation, and why is it expensive / when is it possible?
10. What is paging, and what is its principle of operation?
11. Page vs frame vs page table — define each.
12. How is a logical address split in paging, and how is it translated to a physical address?
13. How does page allocation work, and what happens when there are no free frames?
14. What hardware support is used for paging — page table, TLB, registers?
15. What is a TLB, why is it needed, and what is a TLB hit vs miss?
16. How does paging provide protection and sharing of pages?
17. What are the disadvantages of paging?
18. Paging vs contiguous allocation — why does paging remove external fragmentation but not internal fragmentation?
19. Virtual Memory What is virtual memory, and what problem does it solve?
20. What hardware and control structures are needed for virtual memory?
21. What is locality of reference — temporal locality vs spatial locality — and why does virtual memory depend on it?
22. What is a page fault, and what are the steps to handle it in order?
23. Page fault vs TLB miss vs invalid access/segfault — what is the difference?
24. What is a working set, and how is it used to prevent problems?
25. What is a dirty page / dirty bit, and why does it matter when evicting a page?
26. What is demand paging, and how is it different from bringing all pages in at load time?
27. Demand paging: what is an effective access time, and what makes it get worse?
28. What is thrashing, what causes it, and how does the working-set model prevent it?
29. Optimal page replacement: how does it work, why is it the benchmark, and why can't it be implemented?
30. FIFO page replacement: how does it work, calculate page faults for a reference string, and what is Belady's anomaly?
31. Second Chance (SC) page replacement: how does the reference bit and clock hand work?
32. Not Recently Used (NRU) page replacement: how do the R and M bits classify pages?
33. Least Recently Used (LRU) page replacement: how does it work, calculate page faults for a reference string, and how is it implemented/approximated?
34. FIFO vs LRU vs Optimal — compare page faults on the same reference string with 3 frames.
35. Why does LRU usually perform better than FIFO in practice?

