## 2021 Comet to Expanse Transition Tutorial

**Thursday, March 4, 2021**
**9:00 AM - 1:00 PM PST**
This event will be held remotely.

### <a name="top">**Contents:**
* [Description](#description)
* [Agenda](#agenda)
* [Instructors](#instructors)
* Interactive Video: [Comet to Expanse Transition Tutorial (2021)](https://education.sdsc.edu/training/interactive/202010_comet_to_expanse/index.html)
* All presentations located in the folder: [2021-Comet-to-Expanse-Transition-Tutorial](https://github.com/sdsc-hpc-training-org/comet-to-expanse-transition/tree/main/2021-Comet-to-Expanse-Transition-Tutorial)
 
## Description:<a name="description"></a>
SDSC’s new supercomputer, Expanse, went into full production on December 7, 2020 as a follow-on to Comet. Although the transition should be straightforward for most users, there are some important differences in both the hardware and software between these two systems. We will start with an overview of the Expanse architecture, which is based on AMD’s 64-core EPYC Rome processor and NVIDIA’s V100 GPU device. Moving from Intel to AMD processors introduces a new set of compilers, math libraries and tools. We’ll explain how to use the AMD software stack to build and run applications for optimal performance. GPU applications will port easily to Expanse and the upgrade from Comet’s P100s to the newer V100s generally results in significantly reduced run times. With regards to job submission, we continue to use the Slurm workload manager. Partition names are left unchanged, but job scripts will have to be updated to reflect the larger core counts and, for highly scalable applications, maximum job size. We also introduce a new charging model that fairly takes into account the usage of all resources (memory, CPU, GPU). The tutorial concludes with a discussion of interactive computing using the Expanse Portal and efficiently moving data from Comet to Expanse.

## Agenda<a name="agenda"></a>
| **TIME (PST)** | **TOPIC** | **PRESENTER** |
| --- | ----------- | ----------- |
| *Section:* | *Overview/User Environment*| |
| 9:00 AM – 9:05 AM | Welcome & Introduction | [Mary Thomas](#thomas) |
| 9:05 AM - 9:30 AM | Overview of System and Allocations [[download]](https://github.com/sdsc-hpc-training-org/comet-to-expanse-transition/raw/main/2021-Comet-to-Expanse-Transition-Tutorial/Sinkovits_Expanse_Overview-03-04-2021.pdf) | [Bob Sinkovits](#sinkovits)
| *Section:* | *Running Jobs*| | 
| 9:30 AM - 10:15 AM  | Slurm differences, Running Jobs [[download]](https://github.com/sdsc-hpc-training-org/comet-to-expanse-transition/raw/main/2021-Comet-to-Expanse-Transition-Tutorial/Tatineni_Expanse_Running_Jobs-03-04-2021.pdf)| [Mahidhar Tatineni](tatineni)|
| 10:15 AM - 10:25 AM |  10-minute break| | 
| 10:25 AM – 11:25 AM |  Software module environment, basic compilation and optimization [[download]](https://github.com/sdsc-hpc-training-org/comet-to-expanse-transition/raw/main/2021-Comet-to-Expanse-Transition-Tutorial/managing-your-hpc-software-environment.pdf) | [Marty Kandes](#kandes)  |
| 11:25 AM - 11:35 AM |  10-minute break| |
| 11:35 AM - 11:45 AM |  Job Charging, TRES [[download]](https://github.com/sdsc-hpc-training-org/comet-to-expanse-transition/raw/main/2021-Comet-to-Expanse-Transition-Tutorial/NWolter_Expanse101_mng_allocations.pdf) | [Nicole Wolter](#wolter) |
| 11:45 AM - 12:00 PM |  Using the Expanse portal [[download]](https://github.com/sdsc-hpc-training-org/comet-to-expanse-transition/raw/main/2021-Comet-to-Expanse-Transition-Tutorial/SSivagnanam_Expanse_Portal-03-04-2021.pdf) | [Subhashini Sivagnanam](#sivagnanam) |
| 12:00 PM - 12:15 PM |  Interactive computing and running Jupyter Notebooks [[download]](https://github.com/sdsc-hpc-training-org/comet-to-expanse-transition/raw/main/2021-Comet-to-Expanse-Transition-Tutorial//MThomas-Expanse-Interactive-Computing-03-04-2021.pdf) | [Mary Thomas](#thomas) |
| *Section:* | *Data Management* |  | 
| 12:15 PM - 12:30 PM  |  Data Transfer Mechanisms [[download]](https://github.com/sdsc-hpc-training-org/comet-to-expanse-transition/raw/main/2021-Comet-to-Expanse-Transition-Tutorial/NWolter_Expanse101_data_xfer.pdf) | [Nicole Wolter](#wolter) |
| 12:30 PM – 1:00 PM  |  Q&A |  |

## Instructors<a name="instructors"></a>
| **NAME** | **TITLE** | **ORG** |
| ---------- | ----------- | ----------- |
| Marty Kandes<a name="kandes"></a>  |  Computational and Data Science Research Specialist [(bio)](https://www.linkedin.com/in/marty-kandes-b53a34144/) |  SDSC |
| Bob Sinkovits<a name="sinkovits"></a>  | Director for Scientific Computing Applications [(bio)](https://www.sdsc.edu/research/researcher_spotlight/sinkovits_robert.html) | SDSC|
| Subhashini Sivagnanam | Senior Computational and Data Science Specialist [(bio)](http://users.sdsc.edu/~sivagnan/) | SDSC |
| Mahidhar Tatineni<a name="tatineni"></a> | Director of User Services [(bio)](https://www.sdsc.edu/research/researcher_spotlight/tatineni_mahidhar.html)   | SDSC |  |
| Mary Thomas<a name="thomas"></a>  | Computational Data Scientist, HPC Training Lead [(bio)]( https://www.sdsc.edu/research/researcher_spotlight/thomas_mary.html)| SDSC |
| Nicole Wolter | Computational and Data Science Research Specialist [(bio)](https://www.linkedin.com/in/nicole-wolter-bbb94a3/)| SDSC |
