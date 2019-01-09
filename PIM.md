* [PIM](#PIM)
  * [Circuit level researches](#circuit-level-researches)
    * [DRAM based](#dram-based)
    * [SRAM based](#sram-based)
    * [RRAM based](#rram-based)
    * [PCRAM based](#pcram-based)
    * [STT-RAM based](#stt-ram-based)
  * [Architecture level researches](#architecture-level-researches)
    * [DRAM based](#dram-based-1)
    * [SRAM based](#sram-based-1)
    * [RRAM based](#rram-based-1)
    * [PCRAM based](#pcram-based-1)
    * [STT-RAM based](#stt-ram-based-1)
  * [System level researches](#system-level-researches)
    * [ISA / Compiler](#isa--compiler)
    * [Runtime Middleware and Scheduling](#runtime-middleware-and-scheduling)
    * [Coherence / Consistence / Concurrency (atomicity) issues](#coherence--consistence--concurrency-atomicity-issues)

**Application Scenario Marker**
- ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) General Purpose
- ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) Neural Network
- ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Graph Processing
- ![#af62ff](https://placehold.it/15/af62ff/000000?text=+) Bioinformatics
- ![#0abab5](https://placehold.it/15/0abab5/000000?text=+) Data Analytics
- ![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+) Associative Computing
- ![#f4f442](https://placehold.it/15/f4f442/000000?text=+) Automata Computing
- ![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+) Data Manipulation
- ![#161616](https://placehold.it/15/161616/000000?text=+) Security
- ![#003366](https://placehold.it/15/003366/000000?text=+) Others

# PIM

## Circuit level researches
### DRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISSCC 1997][Intelligent RAM (IRAM): chips that remember and compute]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[GLSVLSI 2005][PIM lite: A multithreaded processor-in-memory prototype]<br/>

### SRAM based
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[VLSI 2016][A machine-learning classifier implemented in a standard 6T SRAM array]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISSCC 2018][A 65nm 4Kb Algorithm-Dependent Computing-in-Memory SRAM Unit-Macro with 2.3ns and 55.8TOPS/W Fully Parallel Product-Sum Operation for Binary DNN Edge Processors]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISSCC 2018][Conv-RAM: An Energy-Efficient SRAM with Embedded Convolution Computation for Low-Power CNN-Based Machine Learning Applications]<br/>
![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[JSSC 2018][A 4 + 2T SRAM for Searching and In-Memory Computing With 0.3-V VDDmin]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ICASSP 2014][An Energy-Efficient VLSI Architecture for Pattern Recognition via Deep Embedding of Computation in SRAM]<br/>

### RRAM based
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[nature 2015][Training and operation of an integrated neuromorphic network based on metal-oxide memristors]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ASP-DAC 2017][MPIM: Multi-purpose in-memory processing using configurable resistive memory]<br/>

### PCRAM based
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[TED 2015][Experimental demonstration and tolerancing of a large-scale neural network (165,000 synapses), using phase-change memory as the synaptic weight element]<br/>

### STT-RAM based
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCAS 2014][Spin-Transfer Torque Magnetic Memory as a Stochastic Memristive Synapse]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISVLSI 2017][Hybrid Polymorphic Logic Gate with 5-Terminal Magnetic Domain Wall Motion Device]<br/>

![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ASP-DAC 2018][HieIM: Highly Flexible In-Memory Computing using STT MRAM]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[IEEE Transactions on Magnetics 2017][In-Memory Processing Paradigm for Bitwise Logic Operations in STT–MRAM]<br/>



## Architecture level researches
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Frontiers 1996][Pursuing a Petaflop: Point Designs for 100 TF Computers Using PIM Technologies]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 1997][Processing in memory: Chips to petaflops]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ASPDAC 2018][PIMCH: cooperative memory prefetching in processing-in-memory architecture]

### DRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CICC 1992][Computational RAM: A Memory-SIMD Hybrid and Its Application to DSP]<br/>
Arch: add logic within DRAM to perform vector operations<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICPP 1994][EXECUBE-A New Architecture for Scaleable MPPs]<br/>
Arch: add logic within DRAM to perform vector operations<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Computer 1995][Processing in memory: The Terasys massively parallel PIM array]<br/>
Arch: add logic within DRAM to perform vector operations<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE Micro 1997][A Case for Intelligent RAM]<br/>
Arch: add logic within DRAM to perform vector operations<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICCD 1997][Intelligent RAM (IRAM): the industrial setting, applications, and architectures]<br/>
Arch: add logic within DRAM to perform vector operations<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 1998][Active Pages: A Computation Model for Intelligent Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[SC 1999][Mapping Irregular Applications to DIVA, a PIM based Data-Intensive Architecture]<br/>
![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[MTDT 1999][The Dynamic Associative Access Memory Chip and its Application to SIMD Processing and Full-text Database Retrieval]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IEEE DT 1999][Computational RAM: Implementing processors in memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2000][Smart Memories: A Modular Reconfigurable Architecture]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[IPDPS 2002][Memory-intensive benchmarks: IRAM vs. cache-based machines]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICS 2002][The Architecture of the DIVA Processing-In-Memory Chip]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICCD 2012][FlexRAM: Toward an Advanced Intelligent Memory System]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[Micro 2013][RowClone: Fast and energy-efficient in-DRAM bulk data copy and initialization]<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[HPEC 2013][Accelerating Sparse Matrix-Matrix Multiplication with 3D-Stacked Logic-in-Memory Hardware]<br/>
![#0abab5](https://placehold.it/15/0abab5/000000?text=+)[SIGMOD 2015][JAFAR: Near-Data Processing for Databases]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CAL 2015][Fast Bulk Bitwise AND and OR in DRAM]<br/>
![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[MemSys 2015][NCAM: Near-Data Processing for Nearest Neighbor Search]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2015][Opportunities and Challenges of Performing Vector Operations inside the DRAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2015][SIMT-based Logic Layers for Stacked DRAM Architectures: A Prototype]<br/>
![#0abab5](https://placehold.it/15/0abab5/000000?text=+)[DaMoN 2015][Beyond the Wall: Near-Data Processing for Databases]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2016][DRAF: a low-power DRAM-based reconfigurable acceleration fabric]<br/>
FPGA style<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2016][Low-Cost Inter-Linked Subarrays (LISA): Enabling Fast Inter-Subarray Data Movement in DRAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[arXiv 2016][Buddy-RAM: Improving the Performance and Efficiency of Bulk Bitwise Operations Using DRAM]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2017][Ambit: In-Memory Accelerator for Bulk Bitwise Operations Using Commodity DRAM Technology]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Micro 2017][DRISA: a DRAM-based Reconfigurable In-Situ Accelerator]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[MemSys 2017][PHOENIX: Efficient Computation in Memory]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[TVLSI 2017][Excavating the Hidden Parallelism Inside DRAM Architectures With Buffered Compares]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[Micro 2018][SCOPE: A Stochastic Computing Engine for DRAM-based In-situ Accelerator]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[PACT 2018][In-DRAM Near-Data Approximate Acceleration for GPUs]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[DAC 2018][DrAcc: a DRAM based accelerator for accurate CNN inference]<br/>



### SRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[PACT 2014][SQRL: hardware accelerator for collecting software data structures]<br/>
![#f4f442](https://placehold.it/15/f4f442/000000?text=+)[Micro 2017][Cache automaton]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2017][Compute Caches]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCA 2018][Neural Cache: Bit-Serial In-Cache Acceleration of Deep Neural Networks]<br/>

### RRAM based

![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[MemSys 2016][Processing Acceleration with Resistive Memory-based Computation]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[HPCA 2016][Memristive Boltzmann machine: A hardware accelerator for combinatorial optimization and deep learning]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCA 2016][PRIME: a novel processing-in-memory architecture for neural network computation in ReRAM-based main memory]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ISCA 2016][ISAAC: a convolutional neural network accelerator with in-situ analog arithmetic in crossbars]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICCAD 2016][Reconfigurable In-Memory Computing with Resistive Memory Crossbar]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[DAC 2016][Pinatubo: A Processing-in-Memory Architecture for Bulk Bitwise Operations in Emerging Non-Volatile Memories]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[HPCA 2017][PipeLayer: A Pipelined ReRAM-Based Accelerator for Deep Learning]<br/>
![#1589F0](https://placehold.it/15/1589F0/000000?text=+)[HPCA 2017][GraphR: Accelerating Graph Processing Using ReRAM]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[TCAD 2017][MNSIM: Simulation Platform for Memristor-Based Neuromorphic Computing System]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CAL 2017][IMEC: A Fully Morphable In-Memory Computing Fabric Enabled by Resistive Crossbar]<br/>
RRAM FPGA<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICCAD 2017][RRAM-based Reconfigurable In-Memory Computing Architecture with Hybrid Routing]<br/>
RRAM FPGA<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[HPCA 2018][Making Memristive Neural Network Accelerators Reliable]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ISCA 2018][Enabling Scientific Computing on Memristive Accelerators]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ASPDAC 2018][ReGAN: A pipelined ReRAM-based accelerator for generative adversarial networks]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[ASPDAC 2018][Training Low Bitwidth Convolutional Neural Network on RRAM]<br/>
RRAM training<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[JESTCS 2018][Multiscale Co-Design Analysis of Energy, Latency, Area, and Accuracy of a ReRAM Analog Neural Training Accelerator]<br/>
RRAM training<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[IEEE Micro 2018][Newton: Gravitating Towards the Physical Limits of Crossbar Acceleration]


### PCRAM based
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[DAC 2015][ProPRAM: exploiting the transparent logic resources in non-volatile memory for near data computing]<br/>


### STT-RAM based
![#ff66cc](https://placehold.it/15/ff66cc/000000?text=+)[ISCA 2013][AC-DIMM: Associative computing with STT-MRAM]<br/>


## System level researches
### ISA / Compiler
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[HPCA 2001][Automatically mapping code on an intelligent memory architecture]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ICRC 2017][Generalize or Die: Operating Systems Support for Memristor-based Accelerators]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[ASPLOS 2018][Liquid Silicon-Monona: A Reconfigurable Memory-Oriented Computing Fabric with Scalable Multi-Context Support]<br/>
RRAM FPGA<br/>
![#f4f442](https://placehold.it/15/f4f442/000000?text=+)[IPDPS 2017][Similarity Search on Automata Processors]<br/>

### Runtime Middleware and Scheduling
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[SC 2002][Gilgamesh: A multithreaded processor-in-memory architecture for petaflops computing]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[arXiv 2017][CODA: Enabling Co-location of Computation and Data for Near-Data Processing]<br/>
Platform: GPU + HBM(SM style)<br/>
Programming model: GPU programming model<br/>
Two ideas: (1) selectively localize data / scatter data; (2) thread-block and data co-location<br/>
Virtual Memomry assumption: This paper assumes SMs in the memory stack are equipped with a hardware TLB and memory management units (MMUs) that access page tables and are capable of performing virtual address translation.<br/>

### Coherence / Consistence / Concurrency (atomicity) issues
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[CAL 2017][LazyPIM: An Efficient Cache Coherence Mechanism for Processing-in-Memory]<br/>
Also works for NDP architecture<br/>
PIM kernel identification: programmer / compiler<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[TACO 2015][GP-SIMD Processing-in-Memory]<br/>
Coherence: restrict PIM processing logic to execute on only non-cacheable data, which forces cores within the CPU to read PIM data directly from DRAM.<br/>
