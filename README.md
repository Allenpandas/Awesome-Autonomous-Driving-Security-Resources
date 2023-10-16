# Autonomous Driving Security Papers
Welcome to my GitHub repository dedicated to the field of **autonomous driving security**. Autonomous driving technology is rapidly transforming our transportation systems and modes of travel. However, along with these advancements, we must also focus on addressing the safety and security challenges associated with autonomous driving. The goal of this repository is to gather and curate literature, research papers, reports, and resources related to autonomous driving safety to assist researchers, engineers, and the general public in better understanding and exploring this critical domain. If you have any literature or resources related to autonomous driving safety, please feel free to contribute to this repository as we work together to promote the safe development of autonomous driving technology.

欢迎来到我的GitHub仓库，这里是一个专注于 **自动驾驶安全** 的知识库。自动驾驶技术正日益改变着我们的交通系统和出行方式，但与之同时，我们也必须关注和解决与自动驾驶相关的安全挑战。这个仓库的目标是收集和整理与自动驾驶安全相关的文献、研究论文、报告和资源，以帮助研究人员、工程师和社会大众更好地了解和探讨这一重要领域的问题。如果您有任何有关自动驾驶安全的文献或资源，欢迎贡献到这个仓库，让我们一起努力推动自动驾驶技术的安全发展。

## News

- 2023/10/10: I initialize the repository and add papers.

## Contributing

This is a collection of research and review papers for **autonomous driving security (AD security)**. Feel free to star and fork.

Maintainers:

- [Yalun Wu](https://github.com/Allenpandas) (Beijing Jiaotong University)

We are looking for more contributors and maintainers! Please feel free to [pull request](https://github.com/Allenpandas/Autonomous-Driving-Security-Papers/pulls).

<p align="center">
  <img src="./we-need-you.jpeg" alt="We Need You!">
</p>
Markdown format:

```
- [year-conference/journal] **Paper Name**.
  [[pdf](link)]
  [[code](link)]
  - Author 1, Author 2, and Author 3. *journal/conference, year*.
```

For any questions, feel free to contact: [wuyalun1@bjtu.edu.cn](mailto:wuyalun1@bjtu.edu.cn)

## Table of Contents

- [Survey](#Survey)

- [Perception Module](#Percepton-Module)

  - [Camera Attack](#Camera-Attack)

  - [Lane Detection Attack](#Lane-Detection-Attack)
  - [LiDAR Attack](#LiDAR-Attack)

- [System Testing](#System-Testing)

- [Scenario Generation](#Scenario-Generation)

- [Anomaly Detection](#Anomaly-Detection)

- [Other](#Other)

- [Datasets](#Datasets)

## Survey

- [2021-TITS] Deep learning for safe autonomous driving: Current challenges and future directions. [[pdf](https://www.researchgate.net/profile/Khan-Muhammad-5/publication/347865238_Deep_Learning_for_Safe_Autonomous_Driving_Current_Challenges_and_Future_Directions/links/5fec60fba6fdccdcb817162a/Deep-Learning-for-Safe-Autonomous-Driving-Current-Challenges-and-Future-Directions.pdf)]
  - Khan Muhammad , Amin Ullah, Jaime Lloret, Javier Del Ser, Victor Hugo C. de Albuquerque.

## Perception Module

### Camera Attack

- [2020-JSA] **Attacking vision-based perception in end-to-end autonomous driving models**. [[pdf](https://www.sciencedirect.com/science/article/abs/pii/S1383762120300606)] [[code](https://github.com/xz-group/AdverseDrive)]
  - Adith Boloor, Karthik Garimella, Xin He, Christopher Gill, Yevgeniy Vorobeychik, Xuan Zhang. *Journal of Systems Architecture, 2020*.



### Lane Detection Attack

- [2023-arxiv] **Lateral-Direction Localization Attack in High-Level Autonomous Driving: Domain-Specific Defense Opportunity via Lane Detection**. [[pdf](https://arxiv.org/abs/2307.14540)]
  - Junjie Shen, Yunpeng Luo, Ziwen Wan, Qi Alfred Chen\*.

- [2022-MM] Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving. [[pdf](https://arxiv.org/pdf/2203.00858.pdf)] [[note](https://blog.csdn.net/m0_38068876/article/details/132547172)]
  - Xingshuo Han, Guowen Xu, Yuan Zhou\*, Xuehuan Yang, Jiawei Li, Tianwei Zhang.



### LiDAR Attack

- [2023-Usenix Security] You Can't See Me: Physical Removal Attacks on LiDAR-based Autonomous Vehicles Driving Frameworks. [[pdf](https://www.usenix.org/conference/usenixsecurity23/presentation/cao)]
  - Yulong Cao, S. Hrushikesh Bhupathiraju, Pirouz Naghavi, Takeshi Sugawara, Z. Morley Mao\*, Sara Rampazzi.



## Test and Evaluate

- [2022-TSE] Mind the gap! a study on the transferability of virtual vs physical-world testing of autonomous driving systems. [[pdf](https://arxiv.org/pdf/2112.11255)]
  - Andrea Stocco, Brian Pulfer, Paolo Tonella.
- [2020-ECCV] Testing the safety of self-driving vehicles by simulating perception and prediction. [[pdf](https://arxiv.org/pdf/2008.06020.pdf)]
  - Kelvin Wong, Qiang Zhang, Ming Liang, Bin Yang, Renjie Liao, Abbas Sadat & Raquel Urtasun.
- [2021-TITS] Adversarial Evaluation of Autonomous Vehicles in Lane-Change Scenarios. [[pdf](https://ieeexplore.ieee.org/abstract/document/9468363)]
  - Baiming Chen, Xiang Chen, Qiong Wu, Liang Li.
- [2018-ASE] DeepRoad: GAN-based Metamorphic Testing and Input Validation Framework for Autonomous Driving Systems. [[pdf](https://dl.acm.org/doi/abs/10.1145/3238147.3238187)]
  - MengshiZhang, Yuqun Zhang, Lingming Zhang, Cong Liu, Sarfraz Khurshid.
- [2018-ICSE] DeepTest: Automated Testing of Deep-Neural-Network-driven Autonomous Cars. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3180155.3180220)]
  - Yuchi Tian, Kexin Pei, Suman Jana, Baishakhi Ray.
- [2017-arxiv] Systematic Testing of Convolutional Neural Networks for Autonomous Driving. [[pdf](https://arxiv.org/abs/1708.03309)]
  - Tommaso Dreossi, Shromona Ghosh, Alberto Sangiovanni-Vincentelli, Sanjit A. Seshia.



## Scenario Generation

- [2023-TITS] A survey on safety-critical driving scenario generation—A methodological perspective. [[pdf](https://arxiv.org/pdf/2202.02215)]
  - Wenhao Ding, Chejian Xu, Mansur Arief, Haohong Lin, Bo Li, Ding Zhao.

- [2023-TITS] Online Adaptive Generation of Critical Boundary Scenarios for Evaluation of Autonomous Vehicles. [[pdf](https://ieeexplore.ieee.org/document/10056393)]
  - Junjie Zhou, Lin Wang, Xiaofan Wang.
- [2022-TITS] SceGene: Bio-Inspired Traffic Scenario Generation for Autonomous Driving Testing. [[pdf](https://ieeexplore.ieee.org/abstract/document/9662987)]
  - Ao Li, Shitao Chen, Liting Sun, Nanning Zheng, Masayoshi Tomizuka, Wei Zhan.
- [2020-TSM] Test Scenario Generation and Optimization Technology for Intelligent Driving Systems. [[pdf](https://ieeexplore.ieee.org/abstract/document/8985542)]
  - Jianli Duan, Feng Gao, Yingdong He.
- [2020-IROS] Learning to Collide: An Adaptive Safety-Critical Scenarios Generating Method. [[pdf](https://arxiv.org/abs/2003.01197)]
  - Wenhao Ding, Baiming Chen, Minjun Xu, Ding Zhao.


## Anomaly Detection

- [2023-arxiv] Detecting the Anomalies in LiDAR Pointcloud. [[pdf](https://arxiv.org/abs/2308.00187)]
  - Chiyu Zhang, Ji Han, Yao Zou, Kexin Dong, Yujia Li, Junchun Ding, Xiaoling Han.



## End to End

- [2023-arxiv] Recent Advancements in End-to-End Autonomous Driving using Deep Learning: A Survey [[pdf](https://arxiv.org/pdf/2307.04370.pdf)]
  - Pranav Singh Chib, Pravendra Singh.



## Other

- [2018-DAC] Reasoning about Safety of Learning-Enabled Components in Autonomous Cyber-physical Systems. [[pdf](https://dl.acm.org/doi/abs/10.1145/3195970.3199852)]
  - Cumhur Erkan Tuncali, James Kapinski, Hisahiro Ito, Jyotirmoy V. Deshmukh.

## Datasets

- [2023-arxiv] AmodalSynthDrive: A Synthetic Amodal Perception Dataset for Autonomous Driving. [[pdf](https://arxiv.org/pdf/2309.06547.pdf)]
  - Ahmed Rida Sekkat, Rohit Mohan, Oliver Sawade, Elmar Matthes, Abhinav Valada.
- [2023-arxiv] ADD: An Automatic Desensitization Fisheye Dataset for Autonomous Driving. [[pdf](https://arxiv.org/pdf/2308.07590.pdf)]
  - Zizhang Wu, Xinyuan Chen, Hongyang Wei, Fan Song, Tianhao Xua.
- [2023-arxiv] SUPS: A Simulated Underground Parking Scenario Dataset for Autonomous Driving. [[pdf](https://arxiv.org/pdf/2302.12966.pdf)]
  - Jiawei Hou, Qi Chen, Yurong Cheng, Guang Chen, Xiangyang Xue, Taiping Zeng, Jian Pu\*.
- [2023-arxiv] A Survey on Datasets for Decision-making of Autonomous Vehicle. [[pdf](https://arxiv.org/pdf/2306.16784.pdf)]
  - Yuning Wang, Zeyu Han, Yining Xing, Shaobing Xu\*, Jianqiang Wang\*.
- [2017-CVPR] CityPersons: A Diverse Dataset for Pedestrian Detection. [[pdf](http://ieeexplore.ieee.org/document/8099957/)]
  - Shanshan Zhang, Rodrigo Benenson, Bernt Schiele.
- [2012-CVPR] Are we ready for autonomous driving? The KITTI vision benchmark suite. [[pdf](https://projet.liris.cnrs.fr/imagine/pub/proceedings/CVPR2012/data/papers/424_O3C-04.pdf)]
  - Andreas Geiger, Philip Lenz, Raquel Urtasun.
