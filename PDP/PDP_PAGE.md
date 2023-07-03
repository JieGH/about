JLEI@DISCA.UPV.ES | Jie.Lei.contact@gmail.com 
 
[❇️ Linkedin](https://www.linkedin.com/in/jie-l-142889139/){:target="_blank"} 
  |
[🎓 ORCiD](https://orcid.org/0000-0002-9998-9503){:target="_blank"} 
  |   [🎓 Google Scholar](https://scholar.google.com/citations?user=g0nZZiMAAAAJ&hl=en&oi=ao){:target="_blank"} 
  |   [🎓 ResearchGate](https://www.researchgate.net/profile/Jie-Lei-2){:target="_blank"}
 |   [🐧 Twitter](https://twitter.com/That_JieLei){:target="_blank"}

---

[⇦ Back Home](https://jiegh.github.io/about/)

#### **GEMM-Like Convolution for Deep Learning Inference on the Xilinx Versal**
Jie Lei, Héctor Martínez, José Flich, Enrique S. Quintana-Ortí
2023 WORKSHOP: HPC ON HETEROGENEOUS HARDWARE (H3), https://icl.utk.edu/~luszczek/conf/2023/h3/

- [📜 Paper ](https://github.com/JieGH/about/raw/d60e16e2edb045a473c70a8203b3ce8c6ffb8bfd/H32023/2023_H3_Convolution_on_Versal.pdf){:target="_blank"}

<!-- - [📽 Presentation](https://github.com/JieGH/about/raw/gh-pages/H32023/keynote.pdf){:target="_blank"} -->



ESR Paper – Toward Matrix Multiplication for Deep Learning Inference on the Xilinx Versal

Introduction

Over the past two decades, the advancement of computer processing has faced challenges due to the slowing down of Moore's law and the end of Dennard scaling. To overcome these limitations, the industry has turned to multicore processors and specialized accelerators, such as NVIDIA tensor cores and Google TPUs. Xilinx, recognizing the benefits of specialized hardware in terms of performance and power efficiency, has introduced the Versal AI Engine (AIE) Core. This design comprises a set of compute engines, advanced I/O, and integrated DDR controllers, catering to a wide range of workloads.

In response to this technological landscape, the paper [Toward Matrix Multiplication for Deep Learning Inference on the Xilinx Versal](https://zenodo.org/record/8009676) published by Jie Lei focuses on analyzing the mapping of the general matrix multiplication (GEMM) onto the AIE-enabled Xilinx Versal Adaptive Compute Accelerated Platform (ACAP). The choice of GEMM as the target computational kernel stems from its central role in many scientific and engineering applications. Particularly in deep learning, GEMM is frequently employed in training and inference tasks using convolutional neural networks (CNNs) and more recent transformers.

The paper presents two major contributions in achieving efficient GEMM realization on the Xilinx Versal:

The authors demonstrate that the concepts behind modern GEMM implementations on traditional processor architectures, featuring hierarchical memory structures and single-instruction multiple-data (SIMD) arithmetic units, can be applied to the AIE-enabled Xilinx Versal ACAP. This involves mapping the matrix operands to different levels of the memory hierarchy and developing an architecture-specific micro-kernel for the AIE tile.
The general algorithm design is customized for the Xilinx Versal VCK190, a specific variant of the Versal ACAP. The paper includes a comprehensive experimental analysis conducted on this platform, highlighting performance considerations and the significant role of cache configuration parameters.
It is important to note that while the design is focused on the Versal VCK190, it can be easily adapted for other AIE-enabled Versal ACAPs.

The remaining sections of the paper are organized as follows: Section III provides a brief overview of the Versal VCK190 platform, while Section IV revisits the modern implementation of GEMM. Section V describes the design of a GEMM micro-kernel for the Versal AIE tile and explains how the GEMM algorithm is mapped onto the memory organization of the AIE-enabled ACAP. Section VI presents a comprehensive experimental evaluation of the proposed algorithm, and Section VII discusses the insights gained from the study, as well as outlines future work. Finally, the paper concludes with a glossary of acronyms used throughout the text.

In summary, this paper focuses on achieving efficient matrix multiplication for deep learning inference on the Xilinx Versal ACAP. By leveraging the capabilities of the AIE-enabled platform and employing innovative design techniques, the authors aim to optimize the performance of GEMM operations and enhance the overall efficiency of deep learning workloads on the Versal architecture.

Check out the full paper [here](https://zenodo.org/record/8009676).

Cite as: Lei, Jie, Flich, José, & Quintana-Ort, Enrique S. (2023, June 1). Toward Matrix Multiplication for Deep Learning Inference on the Xilinx Versal. 2023 31st Euromicro International Conference on Parallel, Distributed and Network-Based Processing (PDP). https://doi.org/10.1109/PDP59025.2023.00043

