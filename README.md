java c
DSCI550: Data Science at Scale 
Homework 5, Spring 2024 
1. [20 points] Considering the following descriptions of a computer system setup:
• The user program continuously performs reads of 64KB blocks, and requires 2 million cycles to process each block.
• The clock rate is 3GHz.
• The maximum sustained transfer rate of the memory bus is 640MB/sec
• The read/write bandwidth of the disk controller and the disk drives is 64MB/sec, disk average seek plus rotational latency is 9ms.
a) How much time is needed for CPU to process each 64 KB block?
b) How much time is spent in memory transfer for a 64 KB block?
c) How much time is spent in I/O transfer for a 64 KB block?
d) Based on the answers of a) – c), what is the bottleneck (slowest component) in this computer system setup, the CPU, memory bus, or the disk set?
2. (20 pts) Answer the following questions in a disk system with multiple hard disks:
a) On a disk system with: a data block (consecutive sectors which is the access unit) size is 4 Kbytes, RPM is 7200, average seek time is 3 msec, and the data transfer rate is 20 MB/s, what is the access time to read a data block at a random location? If the data block size is 64 Mbytes, what would be the access time?
b) A program repeatedly performs a three-step process: It reads in a 4-KB block of data from disk, does some processing on that data, and then writes out the result as another 4-KB block elsewhere on the disk. Each block is contiguous and randomly located on a single track on the disk. The disk driv代 写DSCI550: Data Science at Scale Homework 5 Spring 2024R
代做程序编程语言e rotates at 7200RPM, has an average seek time of 8ms, and has a transfer rate of 20MB/sec. No other program is using the disk or processor, and there is no overlapping of disk operation with processing. The processing step takes 20 million clock cycles, and the clock rate is 2 GHz. What is the overall speed of the system in blocks processed per second assuming no other overhead?
c) If a disk system contains 1,000 disk drives (uniquely numbered as HID 0001 – HID1000), and the probability of an individual disk failure is 1/100,000. What will be the probability that the system experiences any disk failure? Note that failures happen independently.
d) In the same system as described in c), two copies of a data block are stored in HID200 and HID300. What is the probability that the system loses the data block due to the concurrent failure of HID200 and HID300?
3. (15 pts) What are the two types of master nodes in Hadoop and what are their functions in the system? How does the master solve the problem of the single point of failure?
4. (15 pts) What is speculative execution (also called backup tasks)? What problem does it solve?
5. (30 pts) You have a data file (480MB) and want to store it in HDFS which block size is 128 MB. Your Hadoop cluster has 10 data nodes.
1) Explain (draw a figure if needed) how this file is divided and stored in this system in details (e.g., with specific locations of data blocks).
2) And explain the steps how this file can be accessed later.





         
加QQ：99515681  WX：codinghelp
