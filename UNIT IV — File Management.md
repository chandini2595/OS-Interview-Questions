
# UNIT IV — File Management & I/O File Management 

1. What is a file, and what are file attributes?
2. What are the file access methods — sequential, direct/random, and indexed — and when is each used?
3. What are the common file types, and how does the OS know a file's type?
4. What are the basic file operations? (create, open, read, write, seek, delete, close, etc.)
5. What is a directory, and what operations are performed on directories?
6. What are the directory structures — single-level, two-level, tree, acyclic graph, general graph — pros and cons of each?
7. What is the file system structure / layered design of a file system? Contiguous file allocation: how does it work, pros and cons?
8. Linked file allocation: how does it work, pros and cons, and what is FAT? Indexed file allocation: how does it work, pros and cons, and what is an inode?
9. Contiguous vs linked vs indexed allocation — compare random access, fragmentation, and overhead.
10. How is free space managed with a bit vector / bitmap? How is free space managed with a linked list?
11. How is free space managed with grouping (and counting)?
12. Bit vector vs linked list vs grouping for free-space management — compare overhead and performance.
13. How is a directory implemented with a linear list? How is a directory implemented with a hash table?
14. Linear list vs hash table directory implementation — compare search speed and complexity.
15. What factors affect file system efficiency and performance? (block size, caching, etc.) I/O Hardware & Software
16. What are I/O devices, and how are they classified (block vs character, dedicated vs shared)?
17. What is a device controller, and what does it do between the CPU and the device?
18. What is Direct Memory Access (DMA), and how does a DMA transfer work step-by-step?
19. Why is DMA better than programmed/interrupt-driven I/O for large transfers?
20. What are the goals/principles of I/O software? What is an interrupt handler, and what does it do when an I/O interrupt occurs?
21. Programmed I/O (polling) vs interrupt-driven I/O vs DMA — compare CPU involvement.
22. What is a device driver, and what is its role? What is device-independent I/O software, and what functions does it provide?
23. Device driver vs device-independent I/O software vs device controller — who does what?
24. What are buffering, caching, and spooling in I/O — one example each?
