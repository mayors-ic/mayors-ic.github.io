---
layout: base
---

# Leading a workshop

HPC Carpentry workshops are interactive affairs, 
designed to help users get started using an HPC system.
As an instructor, you should ideally set up or arrange access to a computing cluster for your workshop.
Each student will need their own account on the cluster.
Our materials assume that you are using some form of environment modules to manage software installation, and use a batch scheduler to schedule jobs.
Though our materials have been developed for systems using the SLURM scheduler, 
it should be fairly easy to adapt them to other systems - 
the concepts covered are not scheduler-specific.

In terms of venue, 
you should arrange access to a room with wifi, 
a projector, and enough power outlets or extension cords for students to bring their laptops.
You can also quickly create a lesson website using the Software Carpentry 
[workshop-template](https://github.com/swcarpentry/workshop-template)
and arrange for attendee registration through Eventbrite.
It is recommended (though not strictly required) that instructors be a Software Carpentry certified instructor and be familiar with that style of interactive teaching.

-----------------------------------------------------------

# Lesson-specific setup

In addition to the steps above, 
there are several additional pieces of setup to be performed depending on which lessons are being taught.

## Analysis Pipelines with Python

Although most work will be performed on student's laptops, 
the final segment (scaling jobs across a cluster) will occur on your cluster environment.
You should have some version of Python 3 preinstalled for students to use.
[Anaconda Python](https://www.anaconda.com/download/#linux) is a good choice for most use cases.
Don't preinstall Snakemake on the system for users (unless it's already there), 
as this is good practice for students to install local Python packages on their account.

## Parallel Computing with Chapel

Chapel can be a tricky package to setup for newcomers and does not run on Windows (except through Cygwin).
We recommend setting up an installation of Chapel on your cluster beforehand for use in the workshop.
For instructions on compiling/installing Chapel, see the Chapel [quickstart documentation](https://chapel-lang.org/docs/latest/usingchapel/QUICKSTART.html), 
specifically the sections on "Using a more full-featured Chapel" 
and "Using Chapel in multi-locale mode". 
It is also possible to use the Chapel [Docker image](https://hub.docker.com/r/chapel/chapel-gasnet/) for teaching on student laptops.
If you choose to use the Chapel Docker image, 
make sure students install [Docker](https://www.docker.com/) before the workshop.

