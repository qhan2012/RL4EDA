# Reinforcement Learning in EDA

[![Page Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fqianghan%2FRL4EDA&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=false)](https://hits.seeyoufarm.com)

Reinforcement learning (RL) has gained substantial attention in recent years. The number of arXiv submissions that contain the phrase "reinforcement learning" in the title or abstract rose from 2,086 in 2019 to 6,455 in 2024. Interest from the electronic-design-automation (EDA) community—across both industry and academia—has grown in the same time. Inspired by the work of the [Awesome-AI4EDA](https://github.com/Thinklab-SJTU/awesome-ai4eda/blob/main/README.md) collection, we introduce RL4EDA, a dedicated collection highlighting recent reinforcement learning research tailored specifically for EDA applications.

## Brief on the RL Enthusiasm

People may think Reinforcement Learning Human Feedback (usually written RLHF) is a major reason why reinforcement-learning research is booming, as RLHF has markedly improved the post-training alignment and reasoning capabilities of large language models. However, RLHF alone does not fully explain the rising popularity of reinforcement learning. Other key factors—including hardware advancements, increased computational resources, breakthroughs in design-space exploration tools (such as Synopsys DSO.ai and Cadence Cerebrus), and landmark achievements by AI agents (including AlphaGo, AlphaStar, AlphaDev, and emerging LLM-based agents)—have collectively propelled the recent growth and excitement around RL.

---

## RL in Synthesis

"Aisyn: AI-Driven Reinforcement Learning-Based Logic Synthesis Framework"
arXiv preprint arXiv:2302.06415, 2023
Ghasem Pasandi, Sreedhar Pratty, and James Forsyth

"DRiLLS: Deep Reinforcement Learning for Logic Synthesis"
25th Asia and South Pacific Design Automation Conference (ASP-DAC), IEEE, 2020
Abdelrahman Hosny, Soheil Hashemi, Mohamed Shalan, and Sherief Reda

"MapTune: Advancing ASIC Technology Mapping via Reinforcement Learning Guided Library Tuning"
43rd IEEE/ACM International Conference on Computer-Aided Design (ICCAD), 2024
Mingju Liu, Zhuolun He, Yuzhe Ma, Bei Yu, and Martin D.F. Wong

"Rethinking Reinforcement Learning Based Logic Synthesis"
arXiv preprint arXiv:2205.07614, 2022
Chao Wang, Yuzhe Ma, Qiang Xu, Bei Yu, and Martin D.F. Wong

"EasySO: Exploration-Enhanced Reinforcement Learning for Logic Synthesis Sequence Optimization and a Comprehensive RL Environment"
IEEE/ACM International Conference on Computer Aided Design (ICCAD), 2023
Jianyong Yuan, Yingjie Li, Nan Wu, Weikang Qian, and Xuan Zeng

"Retrieval-Guided Reinforcement Learning for Boolean Circuit Minimization"
arXiv preprint arXiv:2401.12205, 2024
Animesh Basak Chowdhury, Ruiqi Xian, Mingfei Yu, William E. Byrd, and Westley Weimer

"Exploring Logic Optimizations with Reinforcement Learning and Graph Convolutional Network"
ACM/IEEE Workshop on Machine Learning for CAD, 2020
Keren Zhu, Mingjie Liu, Hao Chen, Zheng Zhao, and David Z. Pan

"Logic Synthesis Optimization Sequence Tuning using RL-based LSTM and Graph Isomorphism Network"
IEEE Transactions on Circuits and Systems II: Express Briefs, Vol. 69(8):3600-3604, 2022
Chenghao Yang, Guojie Luo, Wuxi Li, and Yuzhe Ma

---

## RL in Placement

"A Graph Placement Methodology for Fast Chip Design"
Nature, Vol. 594(7862):207-212, 2021
Azalia Mirhoseini, Anna Goldie, Mustafa Yazgan, Joe Woo Jiang, Ebrahim Songhori, et al.

"On Joint Learning for Solving Placement and Routing in Chip Design"
Advances in Neural Information Processing Systems (NeurIPS), Vol. 34:16508-16519, 2021
Ruoyu Cheng and Junchi Yan

"The Policy-Gradient Placement and Generative Routing Neural Networks for Chip Design"
Advances in Neural Information Processing Systems (NeurIPS), Vol. 35:26350-26362, 2022
Ruoyu Cheng, Junchi Yan, Xin Gao, and Hongyuan Zha

"MaskPlace: Fast Chip Placement via Reinforced Visual Representation Learning"
Advances in Neural Information Processing Systems (NeurIPS), Vol. 35:24019-24030, 2022
Yao Lai, Yao Mu, and Ping Luo

"Chipformer: Transferable Chip Placement via Offline Decision Transformer"
International Conference on Machine Learning (ICML), PMLR, 2023
Yao Lai, Yuzhe Ma, Yibo Lin, Jiaqi Gu, Zixuan Jiang, and David Z. Pan

"Reinforcement Learning within Tree Search for Fast Macro Placement"
International Conference on Machine Learning (ICML), 2024
Zijie Geng, Yibo Lin, Yuzhe Ma, Jiaqi Gu, and David Z. Pan

"Guiding Global Placement with Reinforcement Learning"
arXiv preprint arXiv:2109.02631, 2021
Robert Kirby, Yibo Lin, Zixuan Jiang, Nan Wu, Zhongzhi Yu, and David Z. Pan

"Parameter Optimization of VLSI Placement through Deep Reinforcement Learning"
IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, Vol. 42(4):1295-1308, 2022
Anthony Agnesina, Kyungwook Chang, and Sung Kyu Lim

"Placement in Integrated Circuits using Cyclic Reinforcement Learning and Simulated Annealing"
arXiv preprint arXiv:2011.07577, 2020
Dhruv Vashisht, Yash Sharma, and Rohit Sharma

"TransPlace: Transferable Circuit Global Placement via Graph Neural Network"
arXiv preprint arXiv:2501.05667, 2025
Yunbo Hou, Yuzhe Ma, Yibo Lin, and David Z. Pan

"GoodFloorplan: Graph Convolutional Network and Reinforcement Learning-based Floorplanning"
IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, Vol. 41(10):3492-3502, 2021
Qi Xu, Yibo Lin, Mingjie Liu, Nan Wu, and David Z. Pan

---

## RL in Routing

"Attention Routing: Track-Assignment Detailed Routing using Attention-based Reinforcement Learning"
International Design Engineering Technical Conferences and Computers and Information in Engineering Conference, Vol. 84003, ASME, 2020
Haiguang Liao, Wentai Zhang, Xuliang Dong, Yarui Zhao, Biying Xu, Wei Zhu

"A Deep Reinforcement Learning Approach for Global Routing"
Journal of Mechanical Design, Vol. 142(6):061701, 2020
Haiguang Liao, Wentai Zhang, Xuliang Dong, Yarui Zhao, Biying Xu, Wei Zhu

"An Enhanced Deep Reinforcement Learning‐Based Global Router for VLSI Design"
Wireless Communications and Mobile Computing, Vol. 2023:6593938, 2023
Saijuan Xu, Liliang Yang, Genggeng Liu

"RL-Ripper: A Framework for Global Routing using Reinforcement Learning and Smart Net Ripping Techniques"
Great Lakes Symposium on VLSI, 2023
Upma Gandhi, Vinay Kumar, Shiv Govind Singh, Amit Acharyya

"A Reinforcement Learning-based Framework for Solving Physical Design Routing Problem in the Absence of Large Test Sets"
ACM/IEEE 1st Workshop on Machine Learning for CAD (MLCAD), 2019
Upma Gandhi, Vinay Kumar, Shiv Govind Singh, Amit Acharyya

"Asynchronous Reinforcement Learning Framework and Knowledge Transfer for Net-order Exploration in Detailed Routing"
IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, Vol. 41(9):3132-3142, 2021
Yibo Lin, Zongqing Lu, Yaju Lin, Xiangyu Xu, Wuxi Li, David Z. Pan

"Reinforcement Learning Guided Detailed Routing for Custom Circuits"
International Symposium on Physical Design (ISPD), 2023
Hao Chen, Mingjie Liu, Yibo Lin, Bei Yu, David Z. Pan

"Efficient FPGA Routing using Reinforcement Learning"
12th International Conference on Information and Communication Systems (ICICS), IEEE, 2021
Umer Farooq, Habib Mehrez, Najam Ul Hasan

"A Reinforcement Learning Based Approach for Efficient Routing in Multi-FPGA Platforms"
Sensors, Vol. 25(1):42, 2024
Umer Farooq, Habib Mehrez, Najam Ul Hasan

"A Nesterov's Accelerated Quasi-Newton Method for Global Routing using Deep Reinforcement Learning"
Nonlinear Theory and Its Applications, IEICE, Vol. 12(3):323-335, 2021
Shahrzad Mahboubi, Hiromasa Tomita, Junichi Yamaguchi, Takeshi Ogita

---

## Timing Optimization (Post-Synthesis/ECO)

"RL-Sizer: VLSI Gate Sizing for Timing Optimization using Deep Reinforcement Learning"
58th ACM/IEEE Design Automation Conference (DAC), IEEE, 2021
Yi-Chen Lu, Sai Pentapati, Sung Kyu Lim, Ernest S. Kuh

"AiTO: Simultaneous Gate Sizing and Buffer Insertion for Timing Optimization with GNNs and RL"
Integration, Vol. 98:102211, 2024
Hongxi Wu, Mingyu Wang, Bei Yu, Martin D.F. Wong

"IR-Aware ECO Timing Optimization Using Reinforcement Learning"
ACM/IEEE International Symposium on Machine Learning for CAD (MLCAD), 2024
Wenjing Jiang, Vidya A. Chhabria, Sachin S. Sapatnekar

"RL-CCD: Concurrent Clock and Data Optimization using Attention-based Self-supervised Reinforcement Learning"
60th ACM/IEEE Design Automation Conference (DAC), IEEE, 2023
Yi-Chen Lu, Sai Pentapati, Sung Kyu Lim, Ernest S. Kuh

---

