---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}


**EDUCATION BACKGROUND**
* Ph.D. in Computer Science and Technology, School of Computer Science, Peking University, 09/2024 - Present
  
* M. S. in Computer Technology, Institute of Computing Technology (ICT), Chinese Academy of Sciences, 09/2020 - 06/2023

* B. S. in Mathematics and Applied Mathematics, Zhengzhou University, 09/2016 - 06/2020

<br>

**RESEARCH INTERESTS**

* High-performance computing

<br>

**RESEARCH EXPERIENCE**

* _**IrGEMM: An Input-Aware Tuning Framework for Irregular GEMM on ARM and X86 CPUs**_,	10/2022 - 04/2023

    * Generated hundreds of highly optimized assembly kernels for diverse irregular GEMM types based on computing templates, the instruction mapping rules between templates and assembly codes, and pipeline optimization strategies.
    * Abstracted tiling problems of GEMM into boxing problems that utilizes dynamic programming approach to minimum memory access of Irregular GEMM and maximum computational memory access ratio.
    * Built a load-balanced multithreaded scheduling framework for processing batch matrix multiplication to achieve the ultimate multi-threaded speedup.
    * Implemented a high-performance irregular matrix multiplication library for ARMv8 and Intel cascade Lake architectures. 
    * Increased the speed-up ratio of irregular DGEMM in a single-threaded environment to 2.3x, 2.7x, and 2.5x in comparison to Intel MKL, ARMPL, LIBXSMM, and BLIS; increased the speed-up ratio of irregular DGEMM in a multi-threaded environment to 3.4x, 14.6x, and 14.3x in comparison to Intel MKL, ARMPL, LIBXSMM, and BLIS.

* _**IATF: An Input-Aware Tuning Framework for Compact BLAS Based on ARMv8 CPUs**_,	10/2021 - 04/2022                         


    * Proposed computing kernel templates for GEMM and TRSM based on the SIMD-friendly data layout and analyzed the compute-to-memory-access ratio to find the optimal kernel size; and optimized instruction selection.  
    * Carefully designed the data packing kernel so that the memory accesses of the computing kernel are contiguous.  
    * Proposed an adaptive tuning framework to chooses an appropriate number of matrices for batch operation each time according to L1 cache size and matrix size, and chooses the optimal data packing kernel and computing kernel according to the input matrix properties.
    * Increased the speed-up ratio of GEMM and TRSM to 4x and 5x in comparison to ARMPL under double-precision floating-point operation.

* _**LBBGEMM: A Load-Balanced Batch GEMM Framework on ARM CPUs**_,	05/2022 - 10/2022                                          


    * Designed high-performance small GEMM kernels without data packaging to greatly reduce the memory accessing overhead.                                                                                                      
    * Presented a load-balanced multi-thread task scheduling strategy for batch GEMM to improve multi-core performance dramatically.
    * Increased the speed-up ratio of DGEMM\_Batch to 2.3x for a single thread and 4.2x for 48 threads in comparison to ARMPL.   

* _**High-performance Image Processing Algorithms Optimization Based On ARMv8 CPUs**_,	10/2020 - 10/2021

    * Sorted image processing algorithms into three types (data irrelevant algorithm, data sharing algorithm and irregular memory access algorithm). 
    * Built a high-performance image processing algorithms library by writing the underlying code with Arm Neon Intrinsic and optimizing multi-threaded performance with OpenMP.
    * Presented optimized image processing algorithm library based on ARMv8 architecture and substantially improved the image processing performance by optimizing the algorithms, memory access, SIMD, and assembly instruction. 
    * Increased the speed-up ratio of cvtColor, Resize and Filter modules to 1.2x, 2x, and 2x in comparison to the OpenCV algorithms library.                                                                                                 
<br>

**PUBLICATIONS**

- **Cunyang Wei**, Haipeng Jia, Yunquan Zhang, Jianyu Yao, Chendi Li, Wenxuan Cao. 2023. *IrGEMM: An Input-Aware Tuning Framework for Irregular GEMM on ARM and X86 CPUs*. IEEE Transactions on Parallel and Distributed Systems (**TPDS**). (Under review) 
- **Cunyang Wei**, Haipeng Jia, Yunquan Zhang, Liusha Xu, and Ji Qi. 2022. *IATF: An Input-Aware Tuning Framework for Compact BLAS Based on ARMv8 CPUs*. In 51st International Conference on Parallel Processing (**ICPP**), 2022. 
- **Cunyang Wei**, Haipeng Jia, Yunquan Zhang, Kun Li, Luhan Wang. 2022. *LBBGEMM: A Load-Balanced Batch GEMM Framework on ARM CPUs*. The 24th IEEE International Conference on High Performance Computing & Communications (**HPCC**), 2022. 
- Luhan Wang, Haipeng Jia, Yunquan Zhang, Kun Li, **Cunyang Wei**. 2022. *EgpuIP: An Embedded GPU Accelerated Library for Image Processing*. The 24th IEEE International Conference on High Performance Computing & Communications (**HPCC**), 2022. 

<br>

**HONORS AND AWARDS**

- 2023 Outstanding Graduate, University of Chinese Academy of Sciences (Top 3%)              

- 2022 National Scholarship for Postgraduates, Ministry of Education of the People's Republic of China	

- 2022 First Prize Scholarship, University of Chinese Academy of Sciences	

- 2022 Merit Student, University of Chinese Academy of Sciences	

- 2017 First Prize Scholarship, Zhengzhou University		

- 2017 Merit Student, Zhengzhou University		

<br>

**EXTRACURRICULAR ACTIVITIES**

&emsp;&emsp;Academic Conference Host & Coordinator,   _Conference of China Computer Federation Technical Committee on High Performance Computing (CCF TCHPC) 2021_           

<br>

**PROFESSIONAL SKILLS**

- Mastered ARM assembly, X86 assembly, and programming with C 
- Proficient in OpenMP, Arm Neon, Intel AVX512 and etc. 
- Solid knowledge in Linux basic commands, data structure and computer architecture

