################################################
# CS:APP Malloc Implementation from CMU 15213(computer systems a programmer's perspective) 
Name:  Karthikeyan
################################################

***********
Main Files:
***********

mdriver
        Once you've run make, run ./mdriver to test your solution.

traces/
	Directory that contains the trace files that the driver uses
	to test your solution. Files short1-bal.rep, short2-bal.rep
	are tiny trace files that you can use for debugging correctness.

**********************************
Other support files for the driver
**********************************
config.h	Configures the malloc lab driver
fsecs.{c,h}	Wrapper function for the different timer packages
clock.{c,h}	Routines for accessing the x86-64 cycle counters
fcyc.{c,h}	Timer functions based on cycle counters
ftimer.{c,h}	Timer functions based on interval timers and gettimeofday()
memlib.{c,h}	Models the heap and sbrk function

***********************
Available malloc packages
***********************
mm.c            Working Implicit Free List Malloc Implementation
*******************************
Building and running the driver
*******************************
To build the driver, type "make" to the shell.

To run the driver on a tiny test trace:

	unix> ./mdriver -V -f short1-bal.rep

To get a list of the driver flags:

	unix> ./mdriver -h

The -V option prints out helpful tracing information
