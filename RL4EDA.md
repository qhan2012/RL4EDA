# Reinforcement Learning in EDA

Reinforcement learning (RL) has gained substantial attention in recent years. The number of arXiv submissions that contain the phrase “reinforcement learning” in the title or abstract rose from 2,086 in 2019 to 6,455 in 2024. Interest from the electronic-design-automation (EDA) community—across both industry and academia—has grown in the same time. Inspired by the work of the [Awesome-AI4EDA](https://github.com/Thinklab-SJTU/awesome-ai4eda/blob/main/README.md) collection, we introduce RL4EDA, a dedicated collection highlighting recent reinforcement learning research tailored specifically for EDA applications.

## Brief on the RL Enthusiasm

People may think Reinforcement Learning Human Feedback (usually written RLHF) is a major reason why reinforcement-learning research is booming, as RLHF has markedly improved the post-training alignment and reasoning capabilities of large language models. However, RLHF alone does not fully explain the rising popularity of reinforcement learning. Other key factors—including hardware advancements, increased computational resources, breakthroughs in design-space exploration tools (such as Synopsys DSO.ai and Cadence Cerebrus), and landmark achievements by AI agents (including AlphaGo, AlphaStar, AlphaDev, and emerging LLM-based agents)—have collectively propelled the recent growth and excitement around RL.

---

## RL in Synthesis

Pasandi, Ghasem, Sreedhar Pratty, and James Forsyth. "Aisyn: Ai-driven reinforcement learning-based logic synthesis framework." arXiv preprint arXiv:2302.06415 (2023).

Hosny, Abdelrahman, et al. "DRiLLS: Deep reinforcement learning for logic synthesis." 2020 25th Asia and South Pacific Design Automation Conference (ASP-DAC). IEEE, 2020.

Liu, Mingju, et al. "MapTune: Advancing ASIC Technology Mapping via Reinforcement Learning Guided Library Tuning." Proceedings of the 43rd IEEE/ACM International Conference on Computer-Aided Design. 2024.

Wang, Chao, et al. "Rethinking reinforcement learning based logic synthesis." arXiv preprint arXiv:2205.07614 (2022).

Yuan, Jianyong, et al. "Easyso: Exploration-enhanced reinforcement learning for logic synthesis sequence optimization and a comprehensive rl environment." 2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD). IEEE, 2023.

Chowdhury, Animesh Basak, et al. "Retrieval-Guided Reinforcement Learning for Boolean Circuit Minimization." arXiv preprint arXiv:2401.12205 (2024).

Zhu, Keren, et al. "Exploring logic optimizations with reinforcement learning and graph convolutional network." Proceedings of the 2020 ACM/IEEE Workshop on Machine Learning for CAD. 2020.

Yang, Chenghao, et al. "Logic synthesis optimization sequence tuning using RL-based LSTM and graph isomorphism network." IEEE Transactions on Circuits and Systems II: Express Briefs 69.8 (2022): 3600-3604.



---

## RL in Placement

Mirhoseini, Azalia, et al. "A graph placement methodology for fast chip design." Nature 594.7862 (2021): 207-212.

Cheng, Ruoyu, and Junchi Yan. "On joint learning for solving placement and routing in chip design." Advances in Neural Information Processing Systems 34 (2021): 16508-16519.

Cheng, Ruoyu, et al. "The policy-gradient placement and generative routing neural networks for chip design." Advances in Neural Information Processing Systems 35 (2022): 26350-26362.

Lai, Yao, Yao Mu, and Ping Luo. "Maskplace: Fast chip placement via reinforced visual representation learning." Advances in Neural Information Processing Systems 35 (2022): 24019-24030.

Lai, Yao, et al. "Chipformer: Transferable chip placement via offline decision transformer." International Conference on Machine Learning. PMLR, 2023.

Geng, Zijie, et al. "Reinforcement learning within tree search for fast macro placement." Forty-first International Conference on Machine Learning. 2024.

Kirby, Robert, et al. "Guiding global placement with reinforcement learning." arXiv preprint arXiv:2109.02631 (2021).

Agnesina, Anthony, Kyungwook Chang, and Sung Kyu Lim. "Parameter optimization of VLSI placement through deep reinforcement learning." IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 42.4 (2022): 1295-1308.

Vashisht, Dhruv, et al. "Placement in integrated circuits using cyclic reinforcement learning and simulated annealing." arXiv preprint arXiv:2011.07577 (2020).

Hou, Yunbo, et al. "TransPlace: Transferable Circuit Global Placement via Graph Neural Network." arXiv preprint arXiv:2501.05667 (2025).

Xu, Qi, et al. "GoodFloorplan: Graph convolutional network and reinforcement learning-based floorplanning." IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 41.10 (2021): 3492-3502.



---

## RL in Placement


Liao, Haiguang, et al. "Attention routing: track-assignment detailed routing using attention-based reinforcement learning." International Design Engineering Technical Conferences and Computers and Information in Engineering Conference. Vol. 84003. American Society of Mechanical Engineers, 2020.

Liao, Haiguang, et al. "A deep reinforcement learning approach for global routing." Journal of Mechanical Design 142.6 (2020): 061701.

Xu, Saijuan, Liliang Yang, and Genggeng Liu. "An Enhanced Deep Reinforcement Learning‐Based Global Router for VLSI Design." Wireless Communications and Mobile Computing 2023.1 (2023): 6593938.

Gandhi, Upma, et al. "RL-ripper: A framework for global routing using reinforcement learning and smart net ripping techniques." Proceedings of the Great Lakes Symposium on VLSI 2023. 2023.

Gandhi, Upma, et al. "A reinforcement learning-based framework for solving physical design routing problem in the absence of large test sets." 2019 ACM/IEEE 1st Workshop on Machine Learning for CAD (MLCAD). IEEE, 2019.

Lin, Yibo, et al. "Asynchronous reinforcement learning framework and knowledge transfer for net-order exploration in detailed routing." IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 41.9 (2021): 3132-3142.

Chen, Hao, et al. "Reinforcement learning guided detailed routing for custom circuits." Proceedings of the 2023 International Symposium on Physical Design. 2023.

Farooq, Umer, et al. "Efficient FPGA routing using reinforcement learning." 2021 12th International Conference on Information and Communication Systems (ICICS). IEEE, 2021

Farooq, Umer, Habib Mehrez, and Najam Ul Hasan. "A Reinforcement Learning Based Approach for Efficient Routing in Multi-FPGA Platforms." Sensors 25.1 (2024): 42.

Mahboubi, Shahrzad, et al. "A Nesterov's accelerated quasi-Newton method for global routing using deep reinforcement learning." Nonlinear Theory and Its Applications, IEICE 12.3 (2021): 323-335.


---

## Timing Optimization (Post-Synthesis/ECO)

Lu, Yi-Chen, et al. "Rl-sizer: Vlsi gate sizing for timing optimization using deep reinforcement learning." 2021 58th ACM/IEEE Design Automation Conference (DAC). IEEE, 2021.

Wu, Hongxi, et al. "AiTO: Simultaneous gate sizing and buffer insertion for timing optimization with GNNs and RL." Integration 98 (2024): 102211.

Jiang, Wenjing, Vidya A. Chhabria, and Sachin S. Sapatnekar. "IR-Aware ECO Timing Optimization Using Reinforcement Learning." Proceedings of the 2024 ACM/IEEE International Symposium on Machine Learning for CAD. 2024.

Lu, Yi-Chen, et al. "RL-CCD: Concurrent clock and data optimization using attention-based self-supervised reinforcement learning." 2023 60th ACM/IEEE Design Automation Conference (DAC). IEEE, 2023.



---

