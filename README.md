# Autonomous-driving-Research
记录自动驾驶领域研究

## 目录

- [感知与融合](#感知与融合)
- [规划与决策](#规划与决策)
- [控制与执行](#控制与执行)
- [数据集和评估](#数据集和评估)
- [安全和可靠性](#安全和可靠性)



## 感知与融合

研究如何通过传感器（如相机、激光雷达、雷达等）获取环境信息，进行物体检测、跟踪和场景理解，以实现精准的环境感知和障碍物识别。此外，还包括将多个传感器的数据进行融合，提高感知的鲁棒性和准确性。

- **[2023-IJCV]** Jiageng Mao, Shaoshuai Shi, Xiaogang Wang, Hongsheng Li. **3D object detection for autonomous driving: a review and new outlooks**[J]. arXiv preprint arXiv:2206.09474, 2022.（**CCF-A期刊**）
  - 关于3D目标检测的综述文章。
- **[2021-TITS]** Di Feng, Ai Harakeh, Steven L. Waslander, Klaus Dietmayer. **A review and comparative study on probabilistic object detection in autonomous driving**[J]. IEEE Transactions on Intelligent Transportation Systems, 2021, 23(8): 9961-9980.
  - 对现有的面向自动驾驶应用的概率目标检测方法进行了回顾和比较研究。
- **[2021-NeurIPS]** David Acuna, Jonah Philion, Sanja Fidler. **Towards Optimal Strategies for Training Self-Driving Perception Models in Simulation**[J]. Advances in Neural Information Processing Systems, 2021, 34: 1686-1699.
  - 自动驾驶依赖于大量高精度的真实数据。替代解决方案寻求利用驾驶模拟器，这些模拟器可以生成大量带有大量内容变化的标记数据。然而，合成数据和真实数据之间的领域差距仍然存在，提出了以下重要问题：利用自动驾驶模拟器进行感知任务的最佳方法是什么?本文在领域适应理论的最新进展基础上，从这个角度提出了最小化现实差距的方法。
- **[2020-ECCV]** Kelvin Wong, Qiang Zhang, Ming Liang, Bin Yang, Renjie Liao, Abbas Sadat & Raquel Urtasun. **Testing the safety of self-driving vehicles by simulating perception and prediction**[C]//Computer Vision–ECCV 2020: 16th European Conference, Glasgow, UK, August 23–28, 2020, Proceedings, Part XXVI 16. Springer International Publishing, 2020: 312-329.
  - 通过模拟感知和预测来测试自动驾驶汽车的安全性。由于传感器模拟昂贵且有很大的域差距，本文提出一种传感器模拟的替代方法：直接模拟自动驾驶汽车的感知和预测系统的输出，实现真实的运动规划测试。



## 规划与决策

研究如何基于感知信息和场景理解，生成安全、高效的行驶路径和决策策略。这包括：路径规划、车道保持、交通信号识别、规避障碍物等。



## 控制与执行

研究如何将规划和决策转化为实际的控制指令，以控制车辆的加速、制动、转向等行为。这包括：车辆动力学建模、控制算法设计、驾驶策略执行等。



## 数据集和评估

研究如何构建大规模的自动驾驶数据集，用于训练和评估自动驾驶系统的性能。这包括：数据采集、数据标注、数据增强等。

- **[2023-TITS]** Wenhao Ding, Chejian Xu, Mansur Arief, Haohong Lin, Bo Li, Ding Zhao. **A survey on safety-critical driving scenario generation—A methodological perspective**[J]. IEEE Transactions on Intelligent Transportation Systems, 2023.
  - 安全关键驾驶场景生成研究——方法论视角。
- **[2023-NeurIPS]** Benjamin Wilson, William Qi, Tanmay Agarwal, John Lambert, Jagjeet Singh, Siddhesh Khandelwal, Bowen Pan, Ratnesh Kumar, Andrew Hartnett, Jhony Kaesemodel Pontes, Deva Ramanan, Peter Carr, James Hays. **Argoverse 2: Next generation datasets for self-driving perception and forecasting**[J]. arXiv preprint arXiv:2301.00493, 2023. 
  - 下一代自动驾驶感知和预测数据集。
- **[2022-TPAMI]** Yiyi Liao, Jun Xie, Andreas Geiger. **KITTI-360: A novel dataset and benchmarks for urban scene understanding in 2d and 3d**[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2022.（**CCF-A期刊，引用量124+**）
  - KITTI-360是KITTI数据集的拓展，具有更丰富的输入模特、全面的语义实例注释和准确的定位。
- **[2021-TITS]** Ao Li, Shitao Chen, Liting Sun, Nanning Zheng, Masayoshi Tomizuka, Wei Zhan. **Scegene: Bio-inspired traffic scenario generation for autonomous driving testing**[J]. IEEE Transactions on Intelligent Transportation Systems, 2021, 23(9): 14859-14874.
  - ScenGene:基于生物技术的自动驾驶测试交通场景生成。受生物智能中遗传和突变过程的启发，提出了一种动态交通场景生成方法，SceGene应用交叉、变异等生物过程对场景内容进行交换和变异，并涉及自然选择过程来控制生成方向。
- **[2021-CVPR]** Yun Chen, Frieda Rong, Shivam Duggal, Shenlong Wang, Xinchen Yan, Sivabalan Manivasagam, Shangjie Xue, Ersin Yumer, Raquel Urtasun. **Geosim: Realistic video simulation via geometry-aware composition for self-driving**[C]//Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2021: 7230-7240.
  - Geosim:逼真的视频模拟，通过几何感知合成自动驾驶。Geosim是一种几何感知的图像合成过程，通过从其他场景中提取并以新的姿态渲染的动态对象来增加现有图像，从而合成新的城市驾驶场景。
- **[2020-CVPR]** Zhenpei Yang, Yuning Chai, Dragomir Anguelov, Yin Zhou, Pei Sun, Dumitru Erhan, Sean Rafferty, Henrik Kretzschmar. **Surfelgan: Synthesizing realistic sensor data for autonomous driving**[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2020: 11118-11127.
  - 基于自动驾驶汽车收集的有限的激光雷达和相机数据，使用SurfelGAN技术，来生成真实场景的传感器数据。

## 安全和可靠性

研究如何提高自动驾驶系统的安全性和鲁棒性，防止对抗性攻击、处理异常情况和极端天气条件等。这包括：异常检测与故障、对抗性攻击与防御、安全评估与验证、认证与授权、隐私与数据安全、数据安全与模型保护等。



- **[2022-TSE]** Andrea Stocco, Brian Pulfer, Paolo Tonella. **Mind the gap! a study on the transferability of virtual vs physical-world testing of autonomous driving systems**[J]. IEEE Transactions on Software Engineering, 2022.
  - 本文阐述了将在驾驶模拟器中获得的测试结果推广到物理平台的问题，并给出了影响自动驾驶汽车安全部署测试的sim2real间隙的表征和量化方法。
