# Cheng Chen

Ph.D. student in Computer Engineering at Purdue University, advised by [Dr. Saurabh Bagchi](https://www.saurabhbagchi.us/). My research focuses on 3D computer vision and autonomous driving.

[Website](https://chengchen2020.github.io/) · [Email](mailto:chen4384@purdue.edu) · [LinkedIn](https://www.linkedin.com/in/chengc98/) · [Resume (PDF)](./Resume.pdf) · [Download PDF](https://github.com/ChengChen2020/ChengChen2020/raw/refs/heads/main/Resume.pdf)

## Research Summary

My research focuses on semantic scene understanding, spanning collaborative 3D semantic occupancy perception, BEV map segmentation, lane topology reasoning, and 4D world modeling for forecasting and planning. I develop structured scene representations and efficient inference methods using Gaussian-based modeling, generative priors, and knowledge distillation.

My current work explores distilling autoregressive models into feedforward perception networks and improving the accuracy and efficiency of lane topology prediction. My broader interests include multi-modal perception, open-world generalization through foundation models, and applying large language models (LLMs), vision-language models (VLMs), and vision-language-action models (VLAs) to perception, reasoning, and planning for autonomous driving.

## Technical Skills

**Programming:** Python (NumPy, OpenCV, Pandas), C/C++, Java, Shell scripting, MATLAB, HTML/JavaScript.

**Deep and machine learning:** PyTorch (3D, video), Scikit-learn (metrics, decomposition), Einops, Transformers, SpConv, LangChain.

## Education

- **Purdue University**, West Lafayette, IN, USA — Ph.D. in Computer Engineering, Aug 2022 - Dec 2027 (expected). GPA: 4.0/4.0. Research area: Computer Vision Systems; advisor: Dr. Saurabh Bagchi.
- **New York University**, Brooklyn, NY, USA — M.Sc. in Computer Engineering, Sep 2020 - May 2022. GPA: 4.0/4.0.
- **University of California, Berkeley**, Berkeley, CA, USA — Exchange student in Electrical Engineering and Computer Science, Jan 2019 - May 2019. GPA: 3.9/4.0.
- **Nanjing University**, Nanjing, Jiangsu, China — B.Sc. in Computer Science (Elite Program), Sep 2016 - Jun 2020. GPA: 4.38/5.0; rank: 5/29.

## Publications

- **Cheng Chen**, et al. **GEM: Gaussian Evolution Model for Occupancy Forecasting and Motion Planning.** Manuscript submitted.
- **Cheng Chen**, et al. [**Vision-Only Gaussian Splatting for Collaborative Semantic Occupancy Prediction.**](https://arxiv.org/abs/2508.10936) AAAI 2026, **Oral**.
- **Cheng Chen**, et al. **E2D2: Energy-Efficient and Deadline-Driven Ensemble Inference at the Edge.** Manuscript submitted.
- Yuan-Yao Lou, **Cheng Chen**, et al. [**AD-VRAN: DRL-based Adaptive Deployment of Virtualized RAN in an Open Telco Edge Cloud.**](https://ieeexplore.ieee.org/document/11488363) IEEE Journal on Selected Areas in Communications (JSAC), 2026.
- Hao Huang, **Cheng Chen**, Yi Fang. [**Manifold Adversarial Learning for Cross-domain 3D Shape Representation.**](https://link.springer.com/chapter/10.1007/978-3-031-19809-0_16) ECCV 2022.
- Hao Huang, **Cheng Chen**, Yi Fang. [**Non-Rigid Multiple Point Set Registration Using Latent Gaussian Mixture.**](https://ieeexplore.ieee.org/document/9897166) ICIP 2022.

## Experience

### Perception PhD Intern · Waymo

**May 2026 - Aug 2026**

Mentors: [Xianghao Xu](https://xxh43.github.io/), [Kyle Zhang](https://www.linkedin.com/in/kyleghz/), [Shiyu Song](https://scholar.google.com/citations?user=1VZ6vXwAAAAJ&hl=en).

Proposed a camera-only BEV segmentation framework that transfers autoregressive map priors through expanding-horizon feature distillation, achieving state-of-the-art performance on nuScenes and Argoverse 2 while running at over **11 FPS**.

### Research Assistant · Dependable Computing Systems Laboratory, Purdue University

**Aug 2022 - Present**

Mentors: [Dr. Saurabh Bagchi](https://www.saurabhbagchi.us/), [Dr. Kwang Taik Kim](https://kimkt.com/), [Dr. Hao Huang](https://scholar.google.com/citations?user=SsZ7BooAAAAJ&hl=en).

**Evolving Gaussians for 4D occupancy forecasting and motion planning.** Proposed the first continuous occupancy world model that represents dynamic scenes using interpretable evolving 4D Gaussian primitives, enabling arbitrary timestamp querying without sequential decoding over fixed future steps. Developed a unified end-to-end framework that combines primitive-based scene evolution with ego-motion reasoning, achieving state-of-the-art performance in both 4D occupancy forecasting and motion planning.

**Sparse Gaussians for collaborative 3D semantic occupancy.** Proposed the first vision-only framework using sparse 3D semantic Gaussian splatting for multi-vehicle perception. Designed neighborhood-based cross-agent attention to fuse Gaussian primitives, removing duplicates and suppressing noise. Achieved mIoU gains of **+8.42** versus single-agent perception and **+3.28** versus collaborative perception, with corresponding IoU gains of **+5.11** and **+22.41**.

**Deadline-aware collaborative inference at the edge.** Introduced the first deadline-driven, energy-efficient ensemble inference framework for heterogeneous edge devices. Demonstrated ensemble accuracy gains across diverse models, modalities, and data distributions. Built a six-device NVIDIA Jetson testbed with ZeroMQ and message quantization to emulate dynamic real-world conditions. Achieved up to **+4.06%** accuracy improvement and over **60%** reduction in energy waste under strict deadline guarantees.

**Deep reinforcement learning for next-generation communication.** Formulated a DRL-based policy for optimized deployment of virtualized Radio Access Networks (vRAN). Achieved up to **17%** reduction in resource consumption while improving QoS, supporting Beyond-5G and 6G applications requiring adaptive and efficient networking.

### Research Assistant · Multimedia and Visual Computing Lab, New York University

**May 2021 - May 2022**

Mentors: [Dr. Yi Fang](https://engineering.nyu.edu/faculty/yi-fang), [Dr. Hao Huang](https://scholar.google.com/citations?user=SsZ7BooAAAAJ&hl=en).

**Adversarial learning for Sim2Real.** Proposed a 3D point cloud representation method for domain generalization. Unified geometric transformations within a Lie group manifold using geodesic distance. Integrated adaptive memory to retain effective adversarial samples, improving robustness in transfer.

**Weakly supervised indoor scene segmentation.** Developed a low-rank sparse point transformer for large-scale point cloud segmentation. Achieved strong performance using only **0.1%** labeled points, reducing annotation cost.

## Teaching, Mentorship & Service

**Teaching Assistant, ECE 20001 Electrical Engineering Fundamentals · Purdue University · Summer 2025.** Led recitation sessions on core problem sets and held office hours. Coordinated TAs to respond to ad-hoc tutoring requests.

**Teaching Assistant, ECE Senior Design · Purdue University · 2025 & 2026.** Mentored four senior design teams, providing structured feedback on journals and assignments. Supported teams with PCB verification, software debugging, and project guidance.

**Teaching Assistant, CS-GY 6953 / ECE-GY 7123 Deep Learning · New York University · Spring 2022.** Designed mini-projects and developed auto-grading scripts to streamline evaluation.

**Undergraduate Research Mentor · Purdue University · Spring 2024.** Mentored Ana Milena Espinosa Jiménez on *Measurement-based Experiments and Evaluation for Digital Transformation in Smart Factory* through the Undergraduate Research Experience Purdue-Colombia (UREP-C) Program, and on *Latency, Velocity, and Accuracy Evaluation of Classification Models on Edge Devices* under the Summer Undergraduate Research Fellowship (SURF).

**Reviewer:** ICLR, KDD, AAAI, NeurIPS, JSAC, ICIP.

## Selected Awards

- **Phi Kappa Phi Honor Society (Top 10%)**, Purdue University, 2025.
- **Best M.S. Academic Achievement (Top 3)**, New York University, 2022.
- **Graduate School of Engineering Scholarship**, New York University, 2020.
- **International and Domestic Exchange Award**, Nanjing University, 2019.
- **National Elite Program Scholarship**, Nanjing University, 2018.

## Contact

[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:chen4384@purdue.edu) [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/chengc98/) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://www.instagram.com/ccjuliusss/)
