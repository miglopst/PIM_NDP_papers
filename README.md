# PIM_NDP_papers
This page contains a survey of Process-In-Memory (PIM) and Near-Data-Processing (NDP) papers. 
To distinguish between PIM and NDP, we assume that PIM architecture either involves analog computation using memory array, or incorparating digital computing logic and memory components on the same die; 
whereas NDP architecture has seperate implementations of computing logic and memory components in different dies. Therefore in our categorization, recent 3D stacking based design belongs to NDP architecture.

We only include circuit, architecture and system level researches (The list is expected to grow as we add more new / dated papers).  

# Application Scenario Marker
- ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) General Purpose
- ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) Neural Network
- ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Graph Processing
- ![#af62ff](https://placehold.it/15/af62ff/000000?text=+) Bioinformatics
- ![#0abab5](https://placehold.it/15/0abab5/000000?text=+) Data Analytics
- ![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+) Associative Computing
- ![#f4f442](https://placehold.it/15/f4f442/000000?text=+) Automata Computing
- ![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+) Data Manipulation
- ![#161616](https://placehold.it/15/161616/000000?text=+) Security

# Pioneering Papers
[IEEE Transactions on Computers 1970][A Logic-in-Memory Computer]<br/>

# Survey Papers
[MemSys 2016][Data-Centric Computing Frontiers: A Survey On Processing-In-Memory]<br/>
[arXiv 2018][Enabling the Adoption of Processing-in-Memory: Challenges, Mechanisms, Future Research Directions]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[arXiv 2016][The Processing Using Memory Paradigm:In-DRAM Bulk Copy, Initialization, Bitwise AND and OR]<br/>
[Micro 2014][Near-Data Processing: Insights from a MICRO-46 Workshop]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[Advances in Computers 2017][Simple Operations in Memory to Reduce Data Movement]<br/>

# PIM

## Circuit level researches
### DRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISSCC 1997][Intelligent RAM (IRAM): chips that remember and compute]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[GLSVLSI 2005][PIM lite: A multithreaded processor-in-memory prototype]<br/>

### SRAM based
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[VLSI 2016][A machine-learning classifier implemented in a standard 6T SRAM array]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISSCC 2018][A 65nm 4Kb Algorithm-Dependent Computing-in-Memory SRAM Unit-Macro with 2.3ns and 55.8TOPS/W Fully Parallel Product-Sum Operation for Binary DNN Edge Processors]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISSCC 2018][A 42pJ/Decision 3.12TOPS/W Robust In-Memory Machine Learning Classifier with On-Chip Training]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISSCC 2018][Conv-RAM: An Energy-Efficient SRAM with Embedded Convolution Computation for Low-Power CNN-Based Machine Learning Applications]<br/>

### RRAM based
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[nature 2015][Training and operation of an integrated neuromorphic network based on metal-oxide memristors]<br/>

## Architecture level researches
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICPP 1994][EXECUBE-A New Architecture for Scaleable MPPs]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Frontiers 1996][Pursuing a Petaflop: Point Designs for 100 TF Computers Using PIM Technologies]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 1997][Processing in memory: Chips to petaflops]<br/>



### RRAM based

![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[MemSys 2016][Processing Acceleration with Resistive Memory-based Computation]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[HPCA 2016][Memristive Boltzmann machine: A hardware accelerator for combinatorial optimization and deep learning]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCA 2016][PRIME: a novel processing-in-memory architecture for neural network computation in ReRAM-based main memory]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCA 2016][ISAAC: a convolutional neural network accelerator with in-situ analog arithmetic in crossbars]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICCAD 2016][Reconfigurable In-Memory Computing with Resistive Memory Crossbar]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[HPCA 2017][PipeLayer: A Pipelined ReRAM-Based Accelerator for Deep Learning]<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[HPCA 2017][GraphR: Accelerating Graph Processing Using ReRAM]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[TCAD 2017][MNSIM: Simulation Platform for Memristor-Based Neuromorphic Computing System]<br/>

### PCM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[DAC 2015][ProPRAM: exploiting the transparent logic resources in non-volatile memory for near data computing]<br/>


### STT-MRAM based
![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[ISCA 2013][AC-DIMM: Associative computing with STT-MRAM]<br/>


### DRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Computer 1995][Processing in memory: The Terasys massively parallel PIM array]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Micro 1997][A Case for Intelligent RAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICCD 1997][Intelligent RAM (IRAM): the industrial setting, applications, and architectures]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 1998][Active Pages: A Computation Model for Intelligent Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[SC 1999][Mapping Irregular Applications to DIVA, a PIM based Data-Intensive Architecture]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE DT 1999][Computational RAM: Implementing processors in memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2000][Smart Memories: A Modular Reconfigurable Architecture]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IPDPS 2002][Memory-intensive benchmarks: IRAM vs. cache-based machines]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICS 2002][The Architecture of the DIVA Processing-In-Memory Chip]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICCD 2012][FlexRAM: Toward an Advanced Intelligent Memory System]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[Micro 2013][RowClone: Fast and energy-efficient in-DRAM bulk data copy and initialization]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[Micro 2015][Gather-Scatter DRAM: In-DRAM Address Translation to Improve the Spatial Locality of Non-unit Strided Accesses]<br/>
![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[MemSys 2015][NCAM: Near-Data Processing for Nearest Neighbor Search]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2015][Opportunities and Challenges of Performing Vector Operations inside the DRAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2015][SIMT-based Logic Layers for Stacked DRAM Architectures: A Prototype]<br/>
![#0abab5](https://placehold.it/15/0abab5/000000?text=+)[DaMoN 2015][Beyond the Wall: Near-Data Processing for Databases]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2016][DRAF: a low-power DRAM-based reconfigurable acceleration fabric]<br/>
FPGA style<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2017][Ambit: In-Memory Accelerator for Bulk Bitwise Operations Using Commodity DRAM Technology]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2017][DRISA: a DRAM-based Reconfigurable In-Situ Accelerator]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2017][PHOENIX: Efficient Computation in Memory]<br/>


### SRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[PACT 2014][SQRL: hardware accelerator for collecting software data structures]<br/>
![#f4f442](https://placehold.it/15/f4f442/000000?text=+)[Micro 2017][Cache automaton]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2017][Compute Caches]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCA 2018][Neural Cache: Bit-Serial In-Cache Acceleration of Deep Neural Networks]<br/>



## System level research
### ISA / Compiler
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2001][Automatically mapping code on an intelligent memory architecture]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICRC 2017][Generalize or Die: Operating Systems Support for Memristor-based Accelerators]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ASPLOS 2018][Liquid Silicon-Monona: A Reconfigurable Memory-Oriented Computing Fabric with Scalable Multi-Context Support]<br/>

### Runtime Middleware and Scheduling
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[SC 2002][Gilgamesh: A multithreaded processor-in-memory architecture for petaflops computing]<br/>

### Coherence / Consistence / Concurrency (atomicity) issues
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CAL 2017][LazyPIM: An Efficient Cache Coherence Mechanism for Processing-in-Memory]<br/>
Also works for NDP architecture<br/>


# NDP

## Architecture level researches
### NDP
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CF 2015][An architecture for near-data processing systems]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[MemSys 2017][The sparse data reduction engine: chopping sparse data one byte at a time]<br/>
![#0abab5](https://placehold.it/15/0abab5/000000?text=+)[MemSys 2017][Identifying the potential of Near Data Processing for Apache Spark]<br/>

### General 3D NDP
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2008][3D-Stacked Memory Architectures for Multi-Core Processors]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Micro 2013][Centip3De: A 64-Core, 3D stacked near threshold system]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Springer Chapter 2013][3D-MAPS: 3D Massively Parallel Processor with Stacked Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[3DIC 2013][A 3D-stacked logic-in-memory accelerator for application-specific data intensive computing]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2015][Near Data Processing: Impact and Optimization of 3D Memory System Architecture on the Uncore]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2016][Integrated Thermal Analysis for Processing In Die-Stacking Memory]<br/>
Thermal Analysis<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2018][PM3: Power Modeling and Power Management for Processing-in-Memory]<br/>
Power Analysis<br/>

### 3D-HMC NDP
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MSPC 2013][A new perspective on processing-in-memory architecture design]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[WoNDP 2014][3D-Stacked Memory-Side Acceleration: Accelerator and System Design]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISPASS 2014][NDC: Analyzing the impact of 3D-stacked memory + logic devices on MapReduce workloads]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IBM 2015][Active Memory Cube: A processing-in-memory architecture for exascale systems]<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[ISCA 2015][A scalable processing-in-memory accelerator for parallel graph processing]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[ISCA 2015][Data-reorganization: Data Reorganization in Memory Using 3D-stacked DRAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2015][NDA: Near-DRAM acceleration architecture leveraging commodity DRAM devices and standard memory modules]<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[MemSys 2015][Instruction Offloading with HMC 2.0 Standard — a Case Study for Graph Traversals]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2015][Understanding Energy Aspect of Processing Near Memory for HPC Workloads]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[MemSys 2015][Near Memory Data Structure Rearrangement]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[ASBD 2015][Sort vs. Hash Join Revisited for Near-Memory Execution]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCA 2016][Neurocube: A Programmable Digital Neuromorphic Architecture with High-Density 3D Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2016][HRL: Efficient and Flexible Reconfigurable Logic for Near-Data Processing]<br/>
FPGA / CGRA style NDP<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2016][Scheduling techniques for GPU architectures with processing-in-memory capabilities]<br/>
GPU-HMC<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Micro 2016][Near-DRAM Acceleration with Single-ISA Heterogeneous Processing in Standard Memory Modules]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[IEEE Micro 2016][HAMLeT Architecture for Parallel Data Reorganization in Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[DATE 2016][Large vector extensions inside the HMC]<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[ICCD 2016][Accelerating pointer chasing in 3D-stacked memory: Challenges, mechanisms, evaluation]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICS 2016][Prefetching Techniques for Near-memory Throughput Processors]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ARCS 2016][Design and Evaluation of a Processing-in-Memory Architecture for the Smart Memory Cube]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2017][The Mondrian Data Engine]<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[HPCA 2017][GraphPIM: Enabling Instruction-Level PIM Offloading in Graph Computing Frameworks]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2017][Processing-in-Memory Enabled Graphics Processors for 3D Rendering]<br/>
GPU-HMC for graphics<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ASPLOS 2017][TETRIS: Scalable and Efficient Neural Network Acceleration with 3D Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[TVLSI 2017][Logic-Base Interconnect Design for Near Memory Computing in the Smart Memory Cube]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[TPDS 2017][Neurostream: Scalable and Energy Efficient Deep Learning with Smart Memory Cubes]<br/>
![#0abab5](https://placehold.it/15/0abab5/000000?text=+)[MemSys 2017][Near memory key/value lookup acceleration]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2017][Lightweight SIMT Core Designs for Intelligent 3D Stacked DRAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[SC 2017][Toward Standardized Near-Data Processing with Unrestricted Data Placement for GPUs]<br/>
GPU-HMC<br/>
![#af62ff](https://placehold.it/15/af62ff/000000?text=+)[arXiv 2017][GRIM-Filter: Fast Seed Location Filtering in DNA Read Mapping Using Processing-in-Memory Technologies]<br/>

### DIMM style NDP
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Micro 2014][Comparing Implementations of Near-Data Computing with In-Memory MapReduce Workloads]<br/>

### Wide-I/O style NDP
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISLPED 2017][XNOR-POP: A processing-in-memory architecture for binary Convolutional Neural Networks in Wide-IO2 DRAMs]<br/>

## System level researches
### ISA / Compiler
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[WoNDP 2013][A Processing-in-Memory Taxonomy and a Case for Studying Fixed-function PIM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[WoNDP 2013][High-level Programming Model Abstractions for Processing in Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2015][PIM-enabled instructions: a low-overhead, locality-aware processing-in-memory architecture]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2017][Data movement aware computation partitioning]<br/>
GPU in manycore system<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[TACO 2017][CAIRO: A Compiler-Assisted Technique for Enabling Instruction-Level Offloading of Processing-in-Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ASPLOS 2018][In-Memory Data Parallel Processor]<br/>

### Runtime Middleware and Scheduling
![#0abab5](https://placehold.it/15/0abab5/000000?text=+)[PACT 2015][Practical Near-Data Processing for In-memory Analytics Frameworks]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CF 2015][Data Access Optimization in a Processing-in-Memory System]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2016][Transparent offloading and mapping (TOM): Enabling programmer-transparent near-data processing in GPU systems]<br/>

### Security
![#161616](https://placehold.it/15/161616/000000?text=+)[WoNDP 2014][A Case for Near Data Security]<br/>

### Coherence / Consistence / Concurrency (atomicity) issues

### Libraries
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2015][Enabling Portable Energy Efficiency with Memory Accelerated Library]<br/>



