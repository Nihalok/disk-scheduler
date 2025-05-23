﻿# disk-scheduler
# disk-scheduler
Disk Scheduling Explained Simply
What is Disk Scheduling?
Imagine a library robot arm that fetches books (data) from shelves (disk tracks). Since the arm can’t be everywhere at once, it needs a smart way to decide which book to grab next to save time. That’s disk scheduling!

Why is it Needed?
Disks are slow (mechanical movement takes time).

Multiple programs request data simultaneously.

A good scheduling algorithm reduces wait time and makes the system faster.

How Does it Work?
The disk arm moves to read/write data at specific locations (like a record player needle). Scheduling algorithms decide the order of serving requests to minimize:

Seek Time: Time to move the arm to the correct track.

Latency: Time for the disk to rotate to the right sector.

Real-Life Example
Scenario: You’re a waiter serving tables (disk requests) in a restaurant.

FCFS (First-Come-First-Served): Serve tables in the order they called you.

✅ Fair, but inefficient if tables are far apart.

SSTF (Shortest Seek Time First): Serve the nearest table first.

✅ Faster service, but some tables might starve.

SCAN (Elevator Algorithm): Move up and down the restaurant, serving tables along the way.

✅ Balanced, no starvation.

C-SCAN: Serve all tables in one direction, then teleport back and repeat.

✅ Predictable wait times.

