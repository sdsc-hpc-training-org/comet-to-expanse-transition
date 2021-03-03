# Comet to Expanse Transition Tutorial (2021)
(repeat event from 2020)

**Thursday, March 4, 2021**
**9:00 AM - 1:00 PM PST**
This event will be held remotely.

**Note:** Copies of presentations will be uploaded soon after the event has ended.

## Description:
SDSC’s new supercomputer, Expanse, went into full production on December 7, 2020 as a follow-on to Comet. Although the transition should be straightforward for most users, there are some important differences in both the hardware and software between these two systems. We will start with an overview of the Expanse architecture, which is based on AMD’s 64-core EPYC Rome processor and NVIDIA’s V100 GPU device. Moving from Intel to AMD processors introduces a new set of compilers, math libraries and tools. We’ll explain how to use the AMD software stack to build and run applications for optimal performance. GPU applications will port easily to Expanse and the upgrade from Comet’s P100s to the newer V100s generally results in significantly reduced run times. With regards to job submission, we continue to use the Slurm workload manager. Partition names are left unchanged, but job scripts will have to be updated to reflect the larger core counts and, for highly scalable applications, maximum job size. We also introduce a new charging model that fairly takes into account the usage of all resources (memory, CPU, GPU). The tutorial concludes with a discussion of interactive computing using the Expanse Portal and efficiently moving data from Comet to Expanse.

## More details and the agenda can be found here:
[Comet to Expanse Transition Tutorial 2021](https://www.sdsc.edu/event_items/202103_Comet_to_Expanse_TransitionTutorial.html)
