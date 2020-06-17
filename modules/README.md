# Course modules

The course modules are in this directory.
An overview of the modules is below.

Inside every module folder, you should create a special folder called `_posts`, e.g., `learning/_posts`.
Inside the folder called `_posts`, you should create a file for every section in the module.
The name of the file should start with the date in the format `YYYY-MM-DD-sectionname.md`.
The date determines the order of the sections in your module.

## Learning gem5 modules

- Intro
  - What is gem5? What is it used for?
  - About this course
  - Where to get help
- Getting started
  - Downloading and building
  - Simple use cases
  - Understanding the output of gem5
- Configuring the memory system
  - Classic vs Ruby
  - Classic cache configuration
  - Ruby configuration
  - Ruby protocols
  - DRAM configuration
  - Testing the memory system
- Configuring and using CPU models
  - Simple CPUs
  - Minor CPU
  - O3 CPU
  - Predictors
  - Elastic trace CPU
- Full system simulation
  - What is full system simulation?
  - Resources for FS simulation
    - Disk images
    - Kernels
  - Running full system simulations
- Preparing workloads/benchmarks for simulation
  - ROI/pseudo insts
  - SE mode restrictions
- Other things to cover...
  - KVM mode
- GPU Model
  - Note: Make sure to do SE mode section first
  - What it models (and doesn't)
  - Requirements (ROcM)
  - Using the GPU model
- gem5 Internals: Modifying and extending gem5
  - Development environment
  - Simple SimObject
  - Debugging gem5
  - Event-driven programming
  - Adding parameters
  - Creating SimObjects in the memory system
  - Creating a simple cache
- gem5 Internals: Modeling cache coherence with Ruby
- gem5 Internals: Creating a CPU model
- Other gem5 Internals
  - SE mode
    - Virtual file system
    - System calls
    - Other things
- Contributing to gem5
  - Setting up a development environment
  - Creating an account on gerrit
  - Submitting your first patch
  - Code review
  - Becoming part of the community
