---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

This tutorial by the [Molecular Sciences Software Institute]({{ site.molssi_site }}) (MolSSI) 
presentes a series of advanced topics and concepts in CUDA programming with C/C++ accompanied 
by applications in computer and molecular sciences.

The MolSSI's full education mission statement can be found [here](http://molssi.org/education/education-mission-statement/).

> ## Prerequisites
>
> - Previous knowledge of High-performance Computing (HPC) basic concepts are helpful but not required for starting this course.
Nevertheless, we encourage students to take a glance at our [Parallel Programming](https://education.molssi.org/parallel-programming)
tutorial, specifically, Chapters 1, 2 and 5 for a brief overview of some of the fundamental concepts in HPC.
> - Basic familiarity with Bash, C and C++ programming languages is required.
> - [MolSSI's Fundamentals of Heterogeneous Parallel Programming with CUDA C/C++ at the beginner level](http://education.molssi.org/gpu_programming_beginner)
and [CUDA C/C++ Programming and GPU Architecture: A Closer Look](http://education.molssi.org/gpu_programming_intermediate) at the intermediate level are
pre-requisites for the present tutorial.
{: .prereq}

> ## Software/Hardware Specifications  {#sh-specifications}
>
> The following NVIDIA CUDA-enabled GPU devices have been used throughout this tutorial:
> - Device 0: [GeForce GTX 1650](https://www.nvidia.com/en-us/geforce/graphics-cards/gtx-1650)
> with Turing architecture (Compute Capability = 7.5)
> - Device 1: [GeForce GT 740M](https://www.techpowerup.com/gpu-specs/geforce-gt-740m.c2299) 
> with Kepler architecture (Compute Capability = 3.5)
>
> Linux 18.04 (Bionic Beaver) OS is the target platform for CUDA Toolkit v11.2.0 on the two host
> machines armed with devices 0 and 1.
{: .callout}

{% include links.md %}
