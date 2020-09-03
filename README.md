<!-- Please use this as comment -->
# PIM_NDP_papers
This page contains a survey of Process-In-Memory (PIM) and Near-Data-Processing (NDP) papers. 
To distinguish between PIM and NDP (**from technology perspective**), we assume that PIM architecture either involves analog computation using memory array, or incorparating digital computing logic and memory components on the same die; 
whereas NDP architecture has seperate implementations of computing logic and memory components in different dies. Therefore in our categorization, recent 3D stacking based design belongs to NDP architecture.

**From an architecture perspective**, although some hardware uses memory technology to implement computation, they are still used as an accelerator for the host (for example, attached to PCIe as a slave device). These hardware designs assume separate physical address space from the host processor, and kenerl execution is similar to GPU (data copy-->kernel launch-->finish computation-->data copy). In contrast, some designs, though categorized as "NDP" in our survey, are truly "process-in-memory" from architectural standpoint. For example, "HMC + logic layer" can be used as memory device (read and written by the host) and a computation device (computation offloading). Also, some designs that have relatively large on-chip managed memory (For example, GPU has scratchpad memory, and DianNao has eDRAM) should be categorized as "memory-rich processor". These memory are local to the processor, and have no computing capability, so we do not include these papers in our survey.

We only include circuit, architecture and system level researches (The list is expected to grow as we add more new / dated papers).

I collect all related papers (not 100% matching) in PIM / NDP domain.
All of the papers are arranged in chronological order in the following page:
* [The list of paper (continuously updated)](https://github.com/miglopst/PIM_NDP_papers/blob/master/paper_list.md) (1989 - 2019):

The following image shows the trend of PIM / NDP publication count, 
the trend for [commodity DRAM bandwidth](https://blog.westerndigital.com/cpu-bandwidth-the-worrisome-2020-trend/),
the trend for [GDDR bandwidth](https://en.wikipedia.org/wiki/GDDR_SDRAM),
and the trend for [HBM bandwidth](https://en.wikipedia.org/wiki/High_Bandwidth_Memory).
We can see that as the bandwidth is increasing in a slower pace these years, more and more researchers are exploring PIM / NDP technology to tackle the memory wall.

![Publication trend in NDP / PIM v.s. memory bandwidth trend](https://github.com/miglopst/PIM_NDP_papers/blob/master/trend.png)

The outline of the survey:
* [Pioneering Papers](#pioneering-papers)
* [Survey Papers](#survey-papers)
* [PIM](https://github.com/miglopst/PIM_NDP_papers/blob/master/PIM.md)
* [NDP](https://github.com/miglopst/PIM_NDP_papers/blob/master/NDP.md)

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

# Pioneering Papers
[IEEE Transactions on Computers 1970][A Logic-in-Memory Computer]<br/>
Arch: small processing elements are combined with small amounts of RAM to provide a distributed array of memories that perform computation<br/>
[IEEE Database 1981][The NON-VON Database Machine: An Overview]<br/>
Arch: small processing elements are combined with small amounts of RAM to provide a distributed array of memories that perform computation<br/>

# Survey Papers
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[WoNDP 2013][A Processing-in-Memory Taxonomy and a Case for Studying Fixed-function PIM]<br/>
[Micro 2014][Near-Data Processing: Insights from a MICRO-46 Workshop]<br/>
[MemSys 2016][Data-Centric Computing Frontiers: A Survey On Processing-In-Memory]<br/>
[IEEE Solid-State Circuits Magazine 2016][Making the Case for Feature-Rich Memory Systems: The March Toward Specialized Systems]<br/>
![#ece5b8](https://placehold.it/15/ece5b8/000000?text=+)[Advances in Computers 2017][Simple Operations in Memory to Reduce Data Movement]<br/>
![#f03c15](https://placehold.it/15/f03c15/000000?text=+)[Nature Electronics 2018][The future of electronics based on memristive systems]<br/>
![#c5f015](https://placehold.it/15/c5f015/000000?text=+)[arXiv 2018][Neuro-memristive circuits for edge computing: A review]<br/>




