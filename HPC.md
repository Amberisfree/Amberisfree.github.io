---
title: "HPC and GPU Programming"
permalink: "/HPC/"
layout: page
---

There are some projects I have done at Durham University's several Scientfic Computing and High Performance Computing. Some original datasets are not available to the public. The purpose of this repo is to show my parallel computing skills, such as data parallelization, instruction parallelization, vectorization.
See the details in github repos by clicking links.

## 1. Shared and Distributed memory System and Parallelisation Strategy 

![HPC](/assets/hpc.png)

* [OPENMP&MPI](https://github.com/Amberisfree/Parallel-Computing)
* Applied loop optimisation to improve the use of memory, specify data environment to avoid data race, and add nowait to decrease the unnecessary time spent by threads waiting at implicit barrier.
* Implemented multiple combined parallel work-sharing loops rather than single parallel region enclosing all work-sharing for loops,


## 2. Vectorization and GPU programming
![CUDA](/assets/cuda.png)

* [CUDA](https://github.com/Amberisfree/CUDA)
* Thread Programming and vectorization
* Estimated data access and floating point operation,performance Engineering to identify hotspots, and performed roofline analysis to construct optimization strategies from resource bottleneck (either instrrction or data).
* Manipulated our data transfer and to define kernel configuration to optimize our code so that we could easily exploit loop parallelism and task parallelism from CUDA runtime library.


