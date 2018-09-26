Comparative Benchmarking
------------------------

Andy Turner
...........

Can benchmarking help users answer, 'where's best to run my code?'
More generally 'What is benchmarking, who is it for, what is it for?'

HECBioSim, James Gebbie
  Supporting users from consortia, experimentalists, not HPC experts
  Code choice, 
  Potential (molecular interactions) choice

GW4 Isambard
  Comparison across CPU types
  Mem vs CPU bound

Open Source Benchmarking
  Aim is to develop quantitatitve comparison
  Publications, not open science
  As far as possible compilation details, simulation inputs, job scripts included

Purpose
  Help users, RSEs, to make informed choice/advise on best approach
  Develop suite for and dataset of hpc-uk/archer benchmarks 

Comments
  Would be good to include profiling as part of benchmarking to better understand code and system performance/scaling.
  Ideally RSEs and users can work together to improve efficiency/use of resources

POP
---

Jon Gibson
..........

ERC funded project
  Phase 1 10/2015-3/2018
  Phase 2 11/2018 - 10/21
  Providing free services
  ToAcademic and Industrial

Aim to deliver
  **Precise** understanding of **parallel** application
  All areas/platforms/scales 
  Projects have been 50:25:25, Academia, Industry, Government/Public sector

Developed expertise in profiler tools:
  BSC tools, extrae, paraver
  Scalasca
  Vtune/others

Typical project:
  Performance assessment report
  Load balancing
  Proof of concept, + software demonstrator

Case studies:
  k-wave, C++ hybrid mpi-openmp refactor periodic domains
  Quantum Espresso, I/O by mpi processes not parallelised, 450 improvement in performance for write, increased scalability.

Pop services, free at point of use
Code developers, code users

Webinars: 18th October 14:00 MPI+X Hybrid parallelisation

`POP Website <https://pop-coe.eu>`_

Supercomputing Wales
--------------------

Mark Dawson
...........

What is it?
  Successor to HPC Wales
  £15m Welsh government investment
  Cardiff and Swansea dominated, also at Aberystwyth, Bangor
  Mix of  capability and capacity machines
  Also RSE support

Different models at each University:
  Cardiff group embedded RSEs
  Swansea etc, Central group, HPC-centric

`Supercomputing Wales <https://www.supercomputing.wales/>`_

A Whilestlestop Tour of Isambard Hacks
--------------------------------------

James Grant
...........

3 Hackathons/Events:
  Porting 5 TOP10 Archer codes on test installations
  Porting remaining TOP10 on upgraded hardware
  Results presented at SC17 and CUG2018
  Further Hackevent to discuss policy

Hackathon
  Hands on events
  Learning about systems/libraries/tools
  Compiling and profiling
  Good for developing communities within centre and with code developers

Havkevent
  More about documentation:
  Policy
  Practicalities
  Documentation
  Training material
  Developing OPS-RSE community

Future events
  To prepare for delivery
  For supporters/OPs/RSEs
  Potential users/test users
  Final Hackathon for interested parties?

HPC Champions
  Would this work regionally/nationally for other centres/champions events
  Would a National symposuim/conference in HPC with co-located workshops be of interest.
  And how would it work for a mixed audience of users, RSEs and supporters
  

Aem: Porting HPC Applications to Arm
------------------------------------

Phil Ridley
...........

Arm HPC role
  Isambard
  Catalyst HPE Machines
  ARM (formerly Allinea) MAP, DDT, Performance Reports
  OpenSource software stack
  LLVM and GCC Arm enhanced compilers
  OpenHPC now out
  Community building for HPC apps porting and perofmrance.
  https://gitlab.com/arm-hpc/

arm compiler: llvm backend, issues underliying in compiler will persist
SVE support, for once it is incorporated, instructions can already be generated

Performance library, new version due out around SC18 (v19)
Some know issues with config.guess and libtool

Archer/HPC Champions
--------------------

Alan Simpson
............

Past, future
  Original discussion EPCC, CLare Gryce (UCL) EPSRC
  Outreach research grant
  RSEs in HPC support
  Co-located with HPC-SIG and other events
  Interactive workshops

RSE network supporting HPC/each other
Career development
A part of diversity/Engagement/Outreach/Impact

What is a champion? 
  Regional/national/early career user/anyone intersted

Need a specific `archer` champions link!
  Moving to `hpc-uk <http://hpc-uk.ac.uk>`_

Opportunity to sell ourselves
  HPC Champions
  Training Champions
  Funders

Existential: Do we want to continue:
  Scope:
  Lessons Learned:
  Content:
  Logistics:

Usable systems.

Discussion comments:
  30 responses 50% All, 40% All academic, 10% Champion
  Inclusive, Ops who don't necessarily get funding, ignored
  Lightning problems
  Commentary on HPC-SIG
  Champions includes RSE/Ops/Users
  Bios of champions? who what where when
  Links centres, include contacts and leads, champions associated with clusters

:download:`Champions Poll <docs/Champions_Poll.pdf>`
