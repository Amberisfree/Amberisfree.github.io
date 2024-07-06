---
title: "HPC and GPU Programming"
permalink: "/HPC/"
layout: post
---

There are some projects I have done at Durham University's several Statistical Machine Leanring Courses and MIT Applied Data Science Program as a student. Some original datasets are not available to the public. The purpose of this repo is to show my data science skills, such as importing and cleaning data, regression, classification, decision tree, random forest, network analysis, time series analysis and data visualization.

See the details in Jupyter Notebook by clicking links.

## 1. Shared and Distributed memory System and Parallelisation Strategy 

![HPC](/assets/hpc.png)

* [OPENMP&MPI](http://htmlpreview.github.io/?https://github.com/Amberisfree/datascience.github.io/blob/main/Bank_loan_Analysis/bank_loan.html)
* Applied loop optimisation to improve the use of memory, specify data environment to avoid data race, and add nowait to decrease the unnecessary time spent by threads waiting at implicit barrier.
* Implemented multiple combined parallel work-sharing loops rather than single parallel region enclosing all work-sharing for loops,


## 2. Vectorization and GPU programming
![CUDA](/assets/cuda.png)

* [CUDA](http://htmlpreview.github.io/?https://github.com/Amberisfree/datascience.github.io/blob/main/Bank_loan_Analysis/bank_loan.html)
* Thread Programming and vectorization
* Estimated data access and floating point operation,performance Engineering to identify hotspots, and performed roofline analysis to construct optimization strategies from resource bottleneck (either instrrction or data).
* Manipulated our data transfer and to define kernel configuration to optimize our code so that we could easily exploit loop parallelism and task parallelism from CUDA runtime library.


