---
layout: default
---

![Branching](https://user-images.githubusercontent.com/5705572/190949258-6678a21c-b33d-468c-bdba-0cd25c8ce0cd.png)

# Introduction

Today's modern applications are producing too large volumes of data to be stored, processed, or transferred efficiently. Data reduction is becoming an indispensable technique in many domains because it can offer a great capability to reduce the data size by one or even two orders of magnitude, significantly saving the memory/storage space, mitigating the I/O burden, reducing communication time, and improving the energy/power efficiency in various parallel and distributed environments, such as high-performance computing (HPC), cloud computing, edge computing, and Internet-of-Things (IoT). An HPC system, for instance, is expected to have a computational capability of <img src="https://render.githubusercontent.com/render/math?math=10^{18}"> floating-point operations per second, and large-scale HPC scientific applications may generate vast volumes of data (several orders of magnitude larger than the available storage space) for post-anlaysis.  Moreover, runtime memory footprint and communication could be non-negligible bottlenecks of current HPC systems.

Tackling the big data reduction research requires expertise from computer science, mathematics, and application domains to study the problem holistically, and develop solutions and harden software tools that can be used by production applications. Specifically, the big-data computing community needs to understand a clear yet complex relationship between application design, data analysis and reduction methods, programming models, system software, hardware, and other elements of a next-generation large-scale computing infrastructure, especially given constraints on applicability, fidelity, performance portability, and energy efficiency. New data reduction techniques also need to be explored and developed continuously to suit emerging applications and diverse use cases.

There are at least three significant research topics that the community is striving to answer: (1) whether several orders of magnitude of data reduction is possible for extreme-scale sciences; (2) understanding the trade-off between the performance and accuracy of data reduction; and (3) solutions to effectively reduce data size while preserving the information inside the big datasets. 

The goal of this workshop is to provide a focused venue for researchers in all aspects of data reduction in all related communities to present their research results, exchange ideas, identify new research directions, and foster new collaborations within the community.

<em>Please note this year’s IEEE BigData conference and IWBDR workshop will be held **online**. Proceedings of the workshop will be published as planned. We will provide more details about how to attend this workshop virtually.</em>

# Submissions

### Topics of Interest

The focus areas for this workshop include, but are not limited to:

- Data reduction techniques for big data issues in _high-performance computing (HPC)_, _cloud computing_, _Internet-of-Things (IoT)_, _edge computing_, _machine learning and deep learning_, and other big data areas:
  - Lossy and lossless compression methods
  - Approximate computation methods
  - Compressive/compressed sensing methods
  - Tensor decomposition methods
  - Data deduplication methods
  - Domain-specific methods, e.g., structured/unstructured meshes, particles, tensors
  - Accuracy-guarantee data reduction methods
  - Optimal design of data reduction methods
- Data reduction challenges and solutions in observational and experimental environments
- Mathematical methods with robustly estimable or provable error bounds for both data and quantities of interest
- Metrics and infrastructures to evaluate reduction methods and assess quality/fidelity of reduced data
- Uncertainty quantification for reduction methods/models/representations
- Benchmark applications and datasets for big data reduction 
- Data analysis and visualization techniques leveraging reduced data
- Characterizing the impact of data reduction techniques on applications
- Hardware-software co-design of data reduction
- Trade-offs between accuracy and performance on emerging computing hardware and platforms
- Resource-constrained and/or time-constrained data reduction methods
- Software, tools, and programming models for managing reduced data
- Runtime systems and supports for data reduction
- Development of composable data reduction pipelines/workflows
- Automation of data reduction in scientific workflows
- Data reduction challenges and solutions in observational and experimental environments 

### Proceedings

All papers accepted for this workshop will be published in the Workshop Proceedings of IEEE Big Data Conference, made available in the IEEE eXplore digital library.

### Submission Instructions

* Camera-ready version of accepted papers must be compliant with the IEEE Xplore format for publication.
* Submissions must be in PDF format.
* Submissions are required to be within **6 pages** for short paper or **10 pages** for full paper (including references).
* Submissions must be single-spaced, 2-column pages in IEEE Xplore format.
* Submissions are NOT double-blind.
* Only web-based submissions are allowed.
* All submission deadlines are Anywhere on Earth (AOE).
* Please submit your paper via the submission system.
* Submission link: [Cyberchair submissions website](https://wi-lab.com/cyberchair/2022/bigdata22/scripts/submit.php?subarea=S11&undisplay_detail=1&wh=/cyberchair/2022/bigdata22/scripts/ws_submit.php).

### Important Dates

* Paper Submission: November 11, 2022
* Paper Acceptance Notification: November 18, 2022
* Camera-ready Deadline: November 25, 2022
* Workshop: December 18, 2022

# Organizers

### Program Chairs

* Dingwen Tao, _Indiana University_
* Xin Liang, _University of Kentucky_
* Sheng Di, _Argonne National Laboratory_

### Web Chair

* Jiannan Tian, _Indiana University_

### Program Committee (Planned)

* Allison Baker, _National Center for Atmospheric Research_
* Mehmet Belviranli, _Colorado School of Mines_
* Martin Burtscher, _Texas State University_
* Franck Cappello, _Argonne National Laboratory_
* Jon Calhoun, _Clemson University_
* Jong Youl Choi, _Oak Ridge National Laboratory_
* Jieyang Chen, _Oak Ridge National Laboratory_
* Soumya Dutta, _Los Alamos National Laboratory_
* William Godoy, _Oak Ridge National Laboratory_
* Pascal Grosset, _Los Alamos National Laboratory_
* Hanqi Guo, _Ohio State University_
* Shaomeng Li, _National Center for Atmospheric Research_
* Qing Liu, _New Jersey Institute of Technology_
* Ben E. Whitney, _Oak Ridge National Laboratory_
* Panruo Wu, _University of Houston_
* Wen Xia, _Harbin Institute of Technology, Shenzhen_
* Xiaodong Yu, _Argonne National Laboratory_
* Kai Zhao, _University of Alabama, Birmingham_


# Program Schedule

Date: December 18, 2022

Timezone: Japan Time (JST), UTC+9

- 2:00 pm -- 6:15 pm JST
- 12:00 AM -- 4:15 AM ET
- 11:00 PM -- 3:15 AM CT
- 10:00 PM -- 2:15 AM MT
- 9:00 PM -- 1:15 AM PT

| **Time**           | **Title**                                                                                                           |
| ------------------ | ------------------------------------------------------------------------------------------------------------------- |
| 2:00 - 2:05 pm | Opening Remarks and Welcome                                                                                         |
|                     | Dingwen Tao, Xin Liang, Sheng  Di                                                                                   |
| 2:05 - 3:00 pm | **Invited Talk 1**: Compressed Data Direct Processing for Big Data Reduction                                                                                            |
|                    | **Feng Zhang**, Associate Professor, Renmin University                                                                                                                 |
| 3:00 - 3:20 pm | **S11201**: Machine Learning Platform for Extreme Scale Computing on Compressed IoT Data.           |
|                    | Seshu Tirupathi, Dhaval Salwala, Giulio Zizzo, Ambrish Rawat, Mark Purcell, Søren Kejser Jensen, Christian Thomsen, Nguyen Ho, Carlos E. Muniz Cuza, Jonas Brusokas, Torben Bach Pedersen, Giorgos Alexiou, Giorgos Giannopoulos, Panagiotis Gidarakos, Alexandros Kalimeris, Stavros Maroulis, George Papastefanatos, Ioannis Psarros, Vassilis Stamatopoulos, and Manolis Terrovitis                                                     |
| 3:20 - 3:40 pm | **S11202**: Lossy Compression to Reduce Latency of Local Image Transfer for Autonomous Off-Road Perception Systems                                                         |
|                    | Max Faykus, Bradley Selee, Jon Calhoun, and Melissa Smith                                               |
| 3:40 - 4:00 pm | **BigD616**: Estimating Potential Error in Sampling Interpolation                                    |
|                    | Megan Hickman Fulp, Dakota Fulp, and Jon Calhoun                                |
| 4:00 - 4:15 pm | **Coffee Break**                                                                                                    |
| 4:15 - 5:10 pm | **Invited Talk 2**: TBD                                                                                            |
|                    | TBD                                                                                                                 |
| 5:10 - 5:30 pm | **S11204**: Towards Guaranteeing Error Bound in DCT-based Lossy Compression                                   |
|                    | Jiaxi Chen, Aekyeung Moon, and Seung Woo Son                                                                            |
| 5:30 - 5:50 pm | **S11203**: Exploring Data Corruption Inside SZ                                   |
|                    | Ruiwen Shan and Jon C. Calhoun                                                                            |
| 5:50 - 6:10 pm | **BigD247**: Extraction of Power Consumption Patterns using Non-negative Tucker Decomposition  |
|                    | Taku Moriyama, Mio Hosoe, Masashi Kuwano, and Yuka Minamino                                                                            |
| 6:10 - 6:15 pm | **Closing Remarks**                                                                                                 |


# Participation

TBD
