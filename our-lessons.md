---
layout: base
---

# Our lessons

This is a detailed overview of current HPC Carpentry lessons.
Topics have been chosen primarily on their ease-of-use and utility
(i.e. students should be able to finish the lesson and 
immediately go out and do something useful with it). 

---------------------------------------

## Intro to HPC

**[Lesson website](https://hpc-carpentry.github.io/hpc-intro/)** / [Lesson repository](https://github.com/hpc-carpentry/hpc-intro/)

This lesson focuses on teaching the basics of using a computing cluster, 
including the basics of bash, accessing installed software, and submitting jobs.
Students should be able to understand and use an HPC system at a basic level after the workshop.
The materials focus on SLURM as a scheduler, 
though the concepts taught are generally applicable to all traditional HPC systems.
Topics covered include the following:

* Logging onto a cluster using SSH
* Basics of using the bash command line
* Editing files with `nano`
* Writing and running shell scripts
* Environment variables and `$PATH`
* Loading software modules and compiling basic software packages from the internet
* Submitting jobs to a scheduler
* Transferring files to and from a cluster

-------------------------------------------

## Analysis Pipelines with Python

**[Lesson website](https://hpc-carpentry.github.io/hpc-python/)** / [Lesson repository](https://github.com/hpc-carpentry/hpc-python/)

This set of materials focuses on two things: 
teaching the basics of programming using Python, 
as well as how to use Python to automate and parallelize a data analysis workflow 
(using [Snakemake](http://snakemake.readthedocs.io/en/stable/)).
After the workshop, students will be able to write basic Python programs
and automate/parallelize the execution of compute jobs on a cluster (or their laptop).
Topics covered include the following:

* Basic Python syntax
* Writing and executing Python scripts
* Storing data using lists, dicts, and Numpy arrays
* An overview of parallel programming concepts (`multiprocessing` is used as a demo)
* Writing an analysis pipeline with Snakemake
* Executing a Snakemake pipeline in parallel across a local machine or remote computing cluster

----------------------------------------------

## Parallel Computing with Chapel

**[Lesson website](https://hpc-carpentry.github.io/hpc-chapel/)** / [Lesson repository](https://github.com/hpc-carpentry/hpc-chapel/)

Our Chapel lesson is an in-depth overview of parallel programming, 
using [Chapel](https://chapel-lang.org/) as a teaching tool.
Students will leave the workshop able to write fast, performant code, 
and be able to parallelize a program across a set of compute nodes.
Topics covered include the following:

* Basic Chapel language syntax
* An overview of parallel programming concepts
* Writing shared-memory parallel programs
* Writing distributed-memory parallel programs (to be executed across several nodes in a cluster)

