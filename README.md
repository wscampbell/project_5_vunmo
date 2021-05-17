CS 502 Project 5 Alt.
=====================

This repository contains project code for my alternate Project 5 assignment for
CS 502 Operating Systems at Worcester Polytechnic Institute. 

The majority of this code is starter code for the original assignment, which 
was pulled from Brown's CS 300 class, Fundamentals of Computer Systems. 

More information can be found at the links below:
http://cs300.systems/
https://cs.brown.edu/courses/csci0300/2021/assign/projects/project5.html#Project-5-Vunmo-

My code is the implementations of synchronized_queue.cc and vunmo-server.cc

To test functionality of the queue, go to the vunmo directory and call
./run_tests queue

To test basic functionality of server, call
./run_tests -s server_part1

To test concurrency of server, call
./run_tests server_part2

Errata
-------
In the server part 2 tests, there is one test which fails for me, which is the 
first one (the basic load test). I tried for an extensive amount of time to
determine why, using gdb and vagrant to try to narrow it down, but I just
never got enough useful information about where the error was occuring or why.
I ultimately ran out of patience, and more importantly, ran out of time. 
Thankfully, all other concurrency tests pass
