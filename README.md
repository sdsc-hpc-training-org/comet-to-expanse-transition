# Comet to Expanse Transition Tutorial

**Thursday, October 29, 2020**
**11:00 AM - 2:30 PM PDT**

The SDSC Expanse system (https://expanse.sdsc.edu), goes into full production on November 1, 2020 and replaces Comet, which will be retired on March 31, 2021. 

The transition should be straightforward for most users, however, there are some important differences in both the hardware and software between these two systems. The _Comet to Expanse transition Tutorial_ is designed to explain to users the differences in both the hardware and software between these two systems and to provide some examples. 

## Goals:
* Explain Expanse architecture 
* AMD’s 64-core EPYC Rome processor and NVIDIA’s V100 GPU. 
* Introduces new set of compilers, math libraries and tools. 
* Explain how to use the AMD software stack to build and run applications for optimal performance. 
* Show how to port GPU applications to Expanse
* upgrade from Comet’s P100s to the newer V100s
* Explain the new module environment
* Demonstrate job submission changes; using Slurm resource manager. 
* Partition names unchanged, need to define larger core counts, and maximum job size. 
* Introduce a new charging model; takes into account the usage of all resources (memory, CPU, GPU). 
* Overview of interactive computing and the Expanse Portal 
* How to move data from Comet to Expanse.

## Agenda:

| **SCHEDULE**	| **TITLE**	| **PRESENTOR** | 
| :----------- | :----------- | :----------- | 
|_Overview/User Environment_  |
| 11:00 - 11:30 AM	| Overview of System and Allocations	| Mahidhar Tatineni, Director of User Services| 
| _Running Jobs_	 |  | |
| 11:30 AM - 12:15 PM| 	Slurm differences, Running Jobs	| Mahidhar Tatineni, Director of User Services| 
| 12:15 PM - 12:25 PM| 	10-minute break	| | 
| 12:25 PM - 12:55 PM| 	Modules, compiling and basic optimizaton - CPU	| Marty Kandes, Computational and Data Science Research Specialist| 
| 12:55 PM - 1:25 PM	| Modules, compiling and basic optimizaton - GPU	| Marty Kandes, Computational and Data Science Research Specialist| 
| 1:25 PM - 1:35 PM	| 10-minute break	| | 
| 1:35 PM - 1:45 PM	| Job Charging, TRES	| Nicole Wolter, Computational and Data Science Research Specialist| 
| 1:45 PM - 2:00 PM	| Using the Expanse portal 	| Subhashini Sivagnanam, Senior Computational and Data Science Specialist| 
| 2:00 PM - 2:15 PM	| Interactive computing and running Jupyter Notebooks	| Mary Thomas, Computational Data Scientist| 
| _Data Management_	| | | 	
| 2:15 PM - 2:30 PM	| Data transfer mechanisms	Nicole Wolter, Computational and Data Science Research Specialist| 
