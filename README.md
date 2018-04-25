# PIM_NDP_papers
This page contains a survey of Process-In-Memory (PIM) and Near-Data-Processing (NDP) papers. 
To distinguish between PIM and NDP, we assume that PIM architecture either involves analog computation using memory array, or incorparating digital computing logic and memory components on the same die; 
whereas NDP architecture has seperate implementations of computing logic and memory components in different dies. Therefore in our categorization, recent 3D stacking based design belongs to NDP architecture.

We only include circuit, architecture and system level researches (The list is expected to grow as we add more new / dated papers).  

# Application Scenario Marker
- ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) General Purpose
- ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) Neural Network
- ![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+) Computer Vision
- ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Graph Processing
- ![#af62ff](https://placehold.it/15/af62ff/000000?text=+) Bioinformatics

# Survey Papers
[MemSys 2016][Data-Centric Computing Frontiers: A Survey On Processing-In-Memory]<br/>
[arXiv 2016][The Processing Using Memory Paradigm:In-DRAM Bulk Copy, Initialization, Bitwise AND and OR]<br/>
[Micro 2014][Near-Data Processing: Insights from a MICRO-46 Workshop]<br/>

# PIM

## Circuit level researches
### DRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISSCC 1997][Intelligent RAM (IRAM): chips that remember and compute]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[GLSVLSI 2005][PIM lite: A multithreaded processor-in-memory prototype]<br/>


## Architecture level researches
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICPP 1994][EXECUBE-A New Architecture for Scaleable MPPs]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Frontiers 1996][Pursuing a Petaflop: Point Designs for 100 TF Computers Using PIM Technologies]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 1997][Processing in memory: Chips to petaflops]<br/>

### RRAM based

### PCM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[DAC 2015][ProPRAM: exploiting the transparent logic resources in non-volatile memory for near data computing]<br/>


### STT-MRAM based

### DRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Computer 1995][Processing in memory: The Terasys massively parallel PIM array]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Micro 1997][A Case for Intelligent RAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 1998][Active Pages: A Computation Model for Intelligent Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[SC 1999][Mapping Irregular Applications to DIVA, a PIM based Data-Intensive Architecture]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE DT 1999][Computational RAM: Implementing processors in memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IPDPS 2002][Memory-intensive benchmarks: IRAM vs. cache-based machines]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICCD 2012][FlexRAM: Toward an Advanced Intelligent Memory System]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2013][RowClone: Fast and energy-efficient in-DRAM bulk data copy and initialization]<br/>
![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[MemSys 2015][NCAM: Near-Data Processing for Nearest Neighbor Search]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2016][DRAF: a low-power DRAM-based reconfigurable acceleration fabric]<br/>
* FPGA style<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2017][Ambit: In-Memory Accelerator for Bulk Bitwise Operations Using Commodity DRAM Technology]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2017][DRISA: a DRAM-based Reconfigurable In-Situ Accelerator]<br/>

### SRAM based

## System level research
### ISA / Compiler
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2001][Automatically mapping code on an intelligent memory architecture]<br/>

### Runtime Middleware and Scheduling
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[SC 2002][Gilgamesh: A multithreaded processor-in-memory architecture for petaflops computing]<br/>

### Coherence / Consistence / Concurrency (atomicity) issues
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CAL 2017][LazyPIM: An Efficient Cache Coherence Mechanism for Processing-in-Memory]<br/>
* Also works for NDP architecture.<br/>


# NDP

## Architecture level researches
### NDP
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CF 2015][An architecture for near-data processing systems]<br/>

### General 3D NDP
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Micro 2013][Centip3De: A 64-Core, 3D stacked near threshold system]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Springer Chapter 2013][3D-MAPS: 3D Massively Parallel Processor with Stacked Memory]<br/>

### 3D-HMC NDP
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MSPC 2013][A new perspective on processing-in-memory architecture design]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IBM 2015][Active Memory Cube: A processing-in-memory architecture for exascale systems]<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[ISCA 2015][A scalable processing-in-memory accelerator for parallel graph processing]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2015][Data-reorganization: Data Reorganization in Memory Using 3D-stacked DRAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2015][NDA: Near-DRAM acceleration architecture leveraging commodity DRAM devices and standard memory modules]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[DATE 2016][Large vector extensions inside the HMC]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCA 2016][Neurocube: A Programmable Digital Neuromorphic Architecture with High-Density 3D Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2016][HRL: Efficient and Flexible Reconfigurable Logic for Near-Data Processing]
* FPGA / CGRA style NDP<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[ICCD 2016][Accelerating pointer chasing in 3D-stacked memory: Challenges, mechanisms, evaluation]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICS 2016][Prefetching Techniques for Near-memory Throughput Processors]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[TPDS 2017][Neurostream: Scalable and Energy Efficient Deep Learning with Smart Memory Cubes]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ASPLOS 2017][TETRIS: Scalable and Efficient Neural Network Acceleration with 3D Memory]<br/>


## System level researches
### ISA / Compiler
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[WoNDP 2013][A Processing-in-Memory Taxonomy and a Case for Studying Fixed-function PIM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2015][PIM-enabled instructions: a low-overhead, locality-aware processing-in-memory architecture]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ASPLOS 2018][In-Memory Data Parallel Processor]<br/>

### Runtime Middleware and Scheduling
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[PACT 2015][Practical Near-Data Processing for In-memory Analytics Frameworks]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CF 2015][Data Access Optimization in a Processing-in-Memory System]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2016][Transparent offloading and mapping (TOM): Enabling programmer-transparent near-data processing in GPU systems]<br/>

### Coherence / Consistence / Concurrency (atomicity) issues




