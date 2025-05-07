# Awesome Reinforcement Learning for Autonomous Driving

A curated list of awesome Reinforcement Learning (RL)-based Autonomous Driving (AD) resources, with a specific focus on highly advanced technologies, including Vision-language models (VLMs), World Models (WMs) and so on.

## Contributing

Please feel free to send me (qu120@purdue.edu) requests to add links or new categories.

## Table of Contents

- [Courses for Beginners](#courses-for-beginners)
- [Simulators](#simulators)
- [Datasets](#datasets)
- [RL-based AD with VLMs](#rl-based-ad-with-vlms)
- [RL-based AD with WMs](#rl-based-ad-with-wms)
- [Human-robot Interaction](#human-robot-interaction)
- [Scenario Simulation](#scenario-simulation)
- [Sim2real](#sim2real)
- [Safe RL](#safe-rl)
- [Online RL](#online-rl)
- [Offline RL](#offline-rl)
- [Offline-to-online RL](#offline-to-online-rl)

## Contents

### Courses for Beginners
**Chinese**
[Shusen Wang](https://www.youtube.com/watch?v=vmkRMvhCW5c&list=PLvOO0btloRnsiqM72G4Uid0UWljikENlU)

[Hung-yi Lee](https://www.youtube.com/watch?v=z95ZYgPgXOY&list=PLJV_el3uVTsODxQFgzMzPLa16h6B8kWM_&index=1)

**English**
[Deep RL Berkley CS 285](https://www.youtube.com/watch?v=SupFHGbytvA&list=PL_iWQOsE6TfVYGEGiAOMaOzzv41Jfm_Ps)

[RL Stanford CS234](https://www.youtube.com/watch?v=WsvFL-LjA6U&list=PLoROMvodv4rN4wG6Nk6sNpTEbuOSosZdX)

### Simulators

Dosovitskiy, Alexey, et al. "CARLA: An open urban driving simulator." *Conference on robot learning*. PMLR, 2017. [📝 Paper](https://proceedings.mlr.press/v78/dosovitskiy17a/dosovitskiy17a.pdf) [💻 Github](https://github.com/carla-simulator/carla) [📚 Document](https://carla.readthedocs.io/en/latest/) 

DI-drive Contributors. *DI-drive: OpenDILab Decision Intelligence Platform for Autonomous Driving Simulation*. GitHub, 2021, https://github.com/opendilab/DI-drive. [💻 Github](https://github.com/opendilab/DI-drive) [📚 Document](https://opendilab.github.io/DI-drive/) 

Li, Quanyi, et al. "Metadrive: Composing diverse driving scenarios for generalizable reinforcement learning." *IEEE transactions on pattern analysis and machine intelligence* 45.3 (2022): 3461-3475.  [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9829243&casa_token=VvFmqd9OMoAAAAAA:ZVwvrpBhUhU_Wo2EnMJ3bV9cZmksdqM_TnElC65fOjI85pLZ87xS9BJC0NJ1CotExzATFRwbtp8&tag=1) [💻 Github](https://github.com/metadriverse/metadrive) [📚 Document](https://metadrive-simulator.readthedocs.io/en/latest/) 

Wu, Wayne, et al. MetaUrban: An Embodied AI Simulation Platform for Urban Micromobility. International Conference on Learning Representations (ICLR), 2025. [📝 Paper](https://arxiv.org/pdf/2407.08725) [💻 Github](https://github.com/metadriverse/metaurban) [📚 Document](https://metaurban-simulator.readthedocs.io/en/latest/) 

Ramamohanarao, Kotagiri, et al. "Smarts: Scalable microscopic adaptive road traffic simulator." *ACM Transactions on Intelligent Systems and Technology (TIST)* 8.2 (2016): 1-22. [📝 Paper](https://dl.acm.org/doi/pdf/10.1145/2898363?casa_token=q7vqnT9j2hoAAAAA:0PRq1bR3FpDqbQ_4dS0465Z-MgaLMaxGMF9P2tImZmQyozBU0k0oXsTCQHAhxhBtnkhlVXfJtCfj6hA) [💻 Github](https://github.com/SmartsDev/SMARTS) [📚 Document](https://smarts.readthedocs.io/en/latest/) 

Krajzewicz, Daniel, et al. "Recent development and applications of SUMO-Simulation of Urban MObility." *International journal on advances in systems and measurements* 5.3&4 (2012). [📝 Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=d1dbcb56fb58e437806505f8e865d69555d868af#page=48) [💻 Github](https://github.com/eclipse-sumo/sumo) [📚 Document](https://sumo.dlr.de/docs/) 

Gulino, Cole, et al. "Waymax: An accelerated, data-driven simulator for large-scale autonomous driving research." *Advances in Neural Information Processing Systems* 36 (2023): 7730-7742. [📝 Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/1838feeb71c4b4ea524d0df2f7074245-Paper-Datasets_and_Benchmarks.pdf) [💻 Github](https://github.com/waymo-research/waymax) [📚 Document](https://waymo-research.github.io/waymax/docs/) 

Huang, Zilin, et al. "Sky-Drive: A Distributed Multi-Agent Simulation Platform for Socially-Aware and Human-AI Collaborative Future Transportation." *arXiv preprint arXiv:2504.18010* (2025). [📝 Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/1838feeb71c4b4ea524d0df2f7074245-Paper-Datasets_and_Benchmarks.pdf) [🔗 Website](https://sky-lab-uw.github.io/Project%20SkyDrive/) 

Leurent, Edouard. *An Environment for Autonomous Driving Decision-Making*. GitHub, 2018. [💻 Github](https://github.com/Farama-Foundation/HighwayEnv) [📚 Document](https://highway-env.farama.org/) 

Wymann, Bernhard, et al. "Torcs, the open racing car simulator." *Software available at http://torcs. sourceforge. net* 4.6 (2000): 2. [💻 Github](https://github.com/jeremybennett/torcs) 

Cai, Panpan, et al. "Summit: A simulator for urban driving in massive mixed traffic." *2020 IEEE International Conference on Robotics and Automation (ICRA)*. IEEE, 2020. [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9197228&casa_token=3AYWSpU33ToAAAAA:r0rl1zZfCzIbB6vZdcCd0UHJo1g-xbfUn-M6f-4EcHTOrfkIqJaXSWLNBsrEP1LqgbOaPK73LVc&tag=1) [💻 Github](https://github.com/AdaCompNUS/summit) [📚 Document](https://adacompnus.github.io/summit-docs/getting_started/introduction/) 

Shah, Shital, et al. "Airsim: High-fidelity visual and physical simulation for autonomous vehicles." *Field and Service Robotics: Results of the 11th International Conference*. Springer International Publishing, 2018. [📝 Paper](https://arxiv.org/pdf/1705.05065) [💻 Github](https://github.com/microsoft/AirSim) [📚 Document](https://airsim-fork.readthedocs.io/en/docs/) 

Wu, Cathy, et al. "Flow: A modular learning framework for mixed autonomy traffic." *IEEE Transactions on Robotics* 38.2 (2021): 1270-1286. [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9489303&casa_token=BxejpYErNPgAAAAA:KorcCas_ivOBiGkLQcZB6N-en83XSQIFMjcf-xHsQtDGjIVid5JKt0d38B5WOtbTFxdLGMGYX8U&tag=1) [💻 Github](https://github.com/flow-project/flow) [🔗 Website](https://flow-project.github.io/) 

Carsim. [🔗 Website](https://www.carsim.com/) 

Matlab Simulink. [🔗 Website](https://www.mathworks.com/products/simulink.html) 

Vissim. [🔗 Website](https://www.ptvgroup.com/en/products/ptv-vissim) 

### Datasets

#### Vision-language-action datasets

Arai, Hidehisa, et al. "Covla: Comprehensive vision-language-action dataset for autonomous driving." *2025 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)*. IEEE, 2025. [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10944039&casa_token=36vyyQtliNUAAAAA:_v8BDOFo4F3XwKCxIHMBtGnG6ifDxu9ZLKnO_cmJSqPF0a73sBML92pdLDHfXBhFWp0eeFicUdE&tag=1) [🔗 Website](https://turingmotors.github.io/covla-ad/) 

Shao, Hao, et al. "Lmdrive: Closed-loop end-to-end driving with large language models." *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*. 2024. [📝 Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Shao_LMDrive_Closed-Loop_End-to-End_Driving_with_Large_Language_Models_CVPR_2024_paper.pdf) [💻 Github](https://github.com/opendilab/LMDrive) [🔗 Website](https://hao-shao.com/projects/lmdrive.html) 

Wang, Tianqi, et al. "Drivecot: Integrating chain-of-thought reasoning with end-to-end driving." *arXiv preprint arXiv:2403.16996* (2024). [📝 Paper](https://arxiv.org/pdf/2403.16996) [🔗 Website](https://drivecot.github.io/) 

#### Offline RL data collection

Liu, Zuxin, et al. "Datasets and benchmarks for offline safe reinforcement learning." *arXiv preprint arXiv:2306.09303* (2023). [📝 Paper](https://arxiv.org/pdf/2306.09303) [💻 Github](https://github.com/liuzuxin/DSRL) 

Fu, Justin, et al. "D4rl: Datasets for deep data-driven reinforcement learning." *arXiv preprint arXiv:2004.07219* (2020). [📝 Paper](https://arxiv.org/pdf/2004.07219) [💻 Github](https://github.com/Farama-Foundation/D4RL) 

### RL-based AD with VLMs

Qu, Yansong, et al. "VL-SAFE: Vision-Language Guided Safety-Aware Reinforcement Learning with World Models for Autonomous Driving"  [🔗 Website](https://ys-qu.github.io/vlsafe-website/) 

Huang, Zilin, et al. "VLM-RL: A Unified Vision Language Models and Reinforcement Learning Framework for Safe Autonomous Driving." *arXiv preprint arXiv:2412.15544* (2024). [📝 Paper](https://arxiv.org/pdf/2412.15544) [💻 Github](https://github.com/zihaosheng/VLM-RL) [🔗 Website](https://www.huang-zilin.com/VLM-RL-website/) 

Ye, Xin, et al. "Lord: Large models based opposite reward design for autonomous driving." *2025 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)*. IEEE, 2025. [📝 Paper](https://openaccess.thecvf.com/content/WACV2025/papers/Ye_LORD_Large_Models_Based_Opposite_Reward_Design_for_Autonomous_Driving_WACV_2025_paper.pdf) 

Sheng, Zihao, et al. "CurricuVLM: Towards Safe Autonomous Driving via Personalized Safety-Critical Curriculum Learning with Vision-Language Models." *arXiv preprint arXiv:2502.15119* (2025).  [📝 Paper](https://arxiv.org/pdf/2502.15119) [💻 Github](https://github.com/zihaosheng/CurricuVLM) [🔗 Website](https://zihaosheng.github.io/CurricuVLM/) 

Doroudian, Erfan, and Hamid Taghavifar. "CLIP-RLDrive: Human-Aligned Autonomous Driving via CLIP-Based Reward Shaping in Reinforcement Learning." arXiv preprint arXiv:2412.16201 (2024). [📝 Paper](https://arxiv.org/pdf/2412.16201) 

### RL-based AD with WMs
Hafner, Danijar, et al. "Mastering diverse domains through world models." arXiv preprint arXiv:2301.04104 (2023). [📝 Paper](https://arxiv.org/pdf/2301.04104) [💻 Github](https://github.com/danijar/dreamerv3) [🔗 Website](https://danijar.com/project/dreamerv3/) 

Gao, Dechen, et al. "Cardreamer: Open-source learning platform for world model based autonomous driving." *IEEE Internet of Things Journal* (2024). [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10714437&casa_token=Gd6U5OB6lHsAAAAA:-N7Puc7B4h5sgE5JicJAh7RLwi-kyJVOa-WMtC5HTJNQxpM_Zt0RVRjuFz_rZ3FbKcCuPzV69Dw) [💻 Github](https://github.com/ucd-dare/CarDreamer) [📚 Document](https://car-dreamer.readthedocs.io/en/latest/) 

Li, Qifeng, et al. "Think2Drive: Efficient Reinforcement Learning by Thinking with Latent World Model for Autonomous Driving (in CARLA-V2)." *European Conference on Computer Vision*. Cham: Springer Nature Switzerland, 2024. [📝 Paper](https://arxiv.org/pdf/2402.16720) [🔗 Website](https://thinklab-sjtu.github.io/CornerCaseRepo/) 

Wang, Xiaofeng, et al. "DriveDreamer: Towards Real-World-Drive World Models for Autonomous Driving." *European Conference on Computer Vision*. Cham: Springer Nature Switzerland, 2024. [📝 Paper](https://arxiv.org/pdf/2309.09777) [💻 Github](https://github.com/JeffWang987/DriveDreamer) [🔗 Website](https://drivedreamer.github.io/) 

Garg, Anant, and K. Madhava Krishna. "Imagine-2-Drive: High-Fidelity World Modeling in CARLA for Autonomous Vehicles." *arXiv preprint arXiv:2411.10171* (2024). [📝 Paper](https://arxiv.org/pdf/2411.10171) [🔗 Website](https://anantagrg.github.io/Imagine-2-Drive.github.io/) 

Wang, Hang, et al. "AdaWM: Adaptive World Model based Planning for Autonomous Driving." *arXiv preprint arXiv:2501.13072* (2025). [📝 Paper](https://arxiv.org/pdf/2501.13072) 

### Human-robot interaction

Huang, Zilin, et al. "Human as AI mentor: Enhanced human-in-the-loop reinforcement learning for safe and efficient autonomous driving." *Communications in Transportation Research* 4 (2024): 100127. [📝 Paper](https://www.sciencedirect.com/science/article/pii/S2772424724000106) [💻 Github](https://github.com/zilin-huang/HAIM-DRL) [🔗 Website](https://www.huang-zilin.com/HAIM-DRL-website/) 

Huang, Zilin, Zihao Sheng, and Sikai Chen. "Trustworthy human-ai collaboration: Reinforcement learning with human feedback and physics knowledge for safe autonomous driving." arXiv preprint arXiv:2409.00858 (2024). [📝 Paper](https://arxiv.org/pdf/2409.00858) [💻 Github](https://github.com/zilin-huang/PE-RLHF) [🔗 Website](https://www.huang-zilin.com/PE-RLHF-website/) 

Peng, Zhenghao Mark, et al. "Learning from active human involvement through proxy value propagation." *Advances in neural information processing systems* 36 (2023): 77969-77992. [📝 Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/f57ffe47d0b528fbb97901d16bd4eba2-Paper-Conference.pdf) [💻 Github](https://github.com/metadriverse/PVP) [🔗 Website](https://metadriverse.github.io/pvp/) 

Li, Quanyi, Zhenghao Peng, and Bolei Zhou. "Efficient learning of safe driving policy via human-ai copilot optimization." arXiv preprint arXiv:2202.10341 (2022). [📝 Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/f57ffe47d0b528fbb97901d16bd4eba2-Paper-Conference.pdf) [💻 Github](https://github.com/metadriverse/HACO) [🔗 Website](https://decisionforce.github.io/HACO/) 

Jiang, Zhaohui, et al. "Reinforcement Learning From Imperfect Corrective Actions And Proxy Rewards." *arXiv preprint arXiv:2410.05782* (2024). [📝 Paper](https://arxiv.org/pdf/2410.05782)

Luo, Jianlan, et al. "RLIF: Interactive imitation learning as reinforcement learning." *arXiv preprint arXiv:2311.12996* (2023). [📝 Paper](https://arxiv.org/pdf/2311.12996) [💻 Github](https://github.com/pd-perry/RLIF) [🔗 Website](https://rlif-page.github.io/) 

Huang, Wenhui, et al. "Safety-aware human-in-the-loop reinforcement learning with shared control for autonomous driving." IEEE Transactions on Intelligent Transportation Systems (2024). [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10596046&casa_token=u0r4P6mD4aEAAAAA:W2EpGJ4Q4UDgi_CBAjrHqLQQ11t1KfyqP_zdbyBo8F9G9B4ph8IcZqdLB3GL54cg84CWuoLt6W8&tag=1) [💻 Github](https://github.com/OscarHuangWind/Safe-Human-in-the-Loop-RL)

Kelly, Michael, et al. "Hg-dagger: Interactive imitation learning with human experts." *2019 International Conference on Robotics and Automation (ICRA)*. IEEE, 2019. [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8793698&casa_token=HT76ijvtMXgAAAAA:PggKo0rc4FKNfkiUDqZ0JYgzzUOPEMqHtbKLLMhQLuxFJzV-hH1eNHOQEOCora2nkKulW6duAfo) 

Peng, Zhenghao, et al. "Safe driving via expert guided policy optimization." *Conference on Robot Learning*. PMLR, 2022. [📝 Paper](https://proceedings.mlr.press/v164/peng22a/peng22a.pdf) [💻 Github](https://github.com/decisionforce/EGPO) [🔗 Website](https://decisionforce.github.io/EGPO/) 

Xue, Zhenghai, et al. "Guarded policy optimization with imperfect online demonstrations." *arXiv preprint arXiv:2303.01728* (2023). [📝 Paper](https://arxiv.org/pdf/2303.01728) [💻 Github](https://github.com/metadriverse/TS2C) [🔗 Website](https://metadriverse.github.io/TS2C/) 

Liu, Xu-Hui, et al. "How to guide your learner: Imitation learning with active adaptive expert involvement." arXiv preprint arXiv:2303.02073 (2023). [📝 Paper](https://arxiv.org/pdf/2303.02073) [💻 Github](https://github.com/liuxhym/AdapMen)

Xue, Zhenghai, and Bo An. "Policy Optimization under Imperfect Human Interactions with Agent-Gated Shared Autonomy." *The Thirteenth International Conference on Learning Representations*. [📝 Paper]([pdf](https://openreview.net/pdf?id=LfekK1E0QE)) [🔗 Website](https://agsa4rl.github.io/) 

Huang, Zhiyu, et al. "Learning interaction-aware motion prediction model for decision-making in autonomous driving." *2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC)*. IEEE, 2023. [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10422695&casa_token=QQ39VmKykOAAAAAA:UO9N8647xDaSbjrw_BT_sK65YX28O4HywJ9FCLQ9yE1NoUVLZbaBsvW3p8S2hV6N-g--LPEDT_A&tag=1) [💻 Github](https://github.com/MCZhi/Predictive-Decision)

Wu, Jingda, et al. "Toward human-in-the-loop AI: Enhancing deep reinforcement learning via real-time human guidance for autonomous driving." *Engineering* (2023).[📝 Paper](https://dr.ntu.edu.sg/bitstream/10356/169074/2/1-s2.0-S2095809922004878-main.pdff) 

Wu, Jingda, et al. "Prioritized experience-based reinforcement learning with human guidance for autonomous driving." IEEE Transactions on Neural Networks and Learning Systems 35.1 (2022): 855-869. [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9793564&casa_token=IM1SFT7fbN8AAAAA:mnf6phf-zMVjDl9Jvq3HPDFgkGO7G-PUXkg2Cm8mLhVGPTtX8bnPnrTDJz6IJiNvpLRErCuECF0) [💻 Github](https://github.com/wujingda/Prioritized-Human-in-the-loop-End-to-end-Autonomous-Driving)

Huang, Zhiyu, Jingda Wu, and Chen Lv. "Efficient deep reinforcement learning with imitative expert priors for autonomous driving." *IEEE Transactions on Neural Networks and Learning Systems* 34.10 (2022): 7391-7403. [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9694460&casa_token=HMx8RvZhhNUAAAAA:9tVdK2k39i3SpX_LohGGHWkrGewwXWfdqXL0Iw3Qmiij-LqZEr2mR6Vej0wC7lUTjV7txlCwO-A) [💻 Github](https://github.com/MCZhi/Expert-Prior-RL)

### Scenario Simulation

Li, Quanyi, et al. "Scenarionet: Open-source platform for large-scale traffic scenario simulation and modeling." *Advances in neural information processing systems* 36 (2023): 3894-3920. [📝 Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/0c26a501df8fb919a0350e2df06b5d39-Paper-Datasets_and_Benchmarks.pdf) [💻 Github](https://github.com/metadriverse/scenarionet) [🔗 Website](https://metadriverse.github.io/scenarionet/) 

Xu, Chejian, et al. "Safebench: A benchmarking platform for safety evaluation of autonomous vehicles." *Advances in Neural Information Processing Systems* 35 (2022): 25667-25682. [📝 Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/a48ad12d588c597f4725a8b84af647b5-Paper-Datasets_and_Benchmarks.pdf) [💻 Github](https://github.com/trust-ai/SafeBench) [🔗 Website](https://safebench.github.io/) [📚 Document](https://safebench.readthedocs.io/en/latest/) 

Zhang, Jiawei, Chejian Xu, and Bo Li. "Chatscene: Knowledge-enabled safety-critical scenario generation for autonomous vehicles." *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*. 2024. [📝 Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_ChatScene_Knowledge-Enabled_Safety-Critical_Scenario_Generation_for_Autonomous_Vehicles_CVPR_2024_paper.pdf) [💻 Github](https://github.com/javyduck/ChatScene) [🔗 Website](https://javyduck.github.io/chatscene/)

Sheng, Zihao, Zilin Huang, Yansong Qu, Yue Leng, and Sikai Chen. Talk2Traffic: Interactive and Editable Traffic Scenario Generation for Autonomous Driving with Multimodal Large Language Model. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPR Workshops), 2025. [🔗 Website](https://zihaosheng.github.io/Talk2Traffic/)

Wei, Yuxi, et al. "Editable scene simulation for autonomous driving via collaborative llm-agents." *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*. 2024. [📝 Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wei_Editable_Scene_Simulation_for_Autonomous_Driving_via_Collaborative_LLM-Agents_CVPR_2024_paper.pdf) [💻 Github](https://github.com/yifanlu0227/ChatSim) [🔗 Website](https://yifanlu0227.github.io/ChatSim/)

Rempe, Davis, et al. "Generating useful accident-prone driving scenarios via a learned traffic prior." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022. [📝 Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Rempe_Generating_Useful_Accident-Prone_Driving_Scenarios_via_a_Learned_Traffic_Prior_CVPR_2022_paper.pdf) [💻 Github](https://github.com/nv-tlabs/STRIVE) [🔗 Website](https://research.nvidia.com/labs/toronto-ai/STRIVE/)

Xu, Chejian, et al. "Diffscene: Diffusion-based safety-critical scenario generation for autonomous vehicles." Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 39. No. 8. 2025. [📝 Paper](https://openreview.net/forum?id=hclEbdHida)

Charraut, Valentin, et al. "V-Max: Making RL practical for Autonomous Driving." arXiv preprint arXiv:2503.08388 (2025). [📝 Paper](https://arxiv.org/pdf/2503.08388?) [💻 Github](https://github.com/valeoai/v-max) 

Pronovost, Ethan, et al. "Scenario diffusion: Controllable driving scenario generation with diffusion." Advances in Neural Information Processing Systems 36 (2023): 68873-68894. [📝 Paper](https://arxiv.org/pdf/2311.02738) 

Charraut, Valentin, et al. "V-Max: Making RL practical for Autonomous Driving." arXiv preprint arXiv:2503.08388 (2025). [📝 Paper](https://arxiv.org/pdf/2503.08388?) [💻 Github](https://github.com/valeoai/v-max) 

Zhou, Yunsong, et al. "Simgen: Simulator-conditioned driving scene generation." Advances in Neural Information Processing Systems 37 (2024): 48838-48874. [📝 Paper](https://arxiv.org/pdf/2406.09386) [💻 Github](https://github.com/metadriverse/SimGen) [🔗 Website](https://metadriverse.github.io/simgen/)

Li, Xinqing, et al. "SimWorld: A Unified Benchmark for Simulator-Conditioned Scene Generation via World Model." arXiv preprint arXiv:2503.13952 (2025). [📝 Paper](https://arxiv.org/pdf/2503.13952?) [💻 Github](https://github.com/Li-Zn-H/SimWorld)

### Sim2real

Li, Dianzhao, and Ostap Okhrin. "A platform-agnostic deep reinforcement learning framework for effective sim2real transfer towards autonomous driving." *Communications Engineering* 3.1 (2024): 147. [📝 Paper](https://www.nature.com/articles/s44172-024-00292-3.pdf) [💻 Github](https://github.com/DailyL/Sim2Real_autonomous_vehicle) [🔗 Website](https://dailyl.github.io/sim2realVehicle.github.io/)

Wu, Jingda, et al. "Human-guided reinforcement learning with sim-to-real transfer for autonomous navigation." *IEEE Transactions on Pattern Analysis and Machine Intelligence* 45.12 (2023): 14745-14759. [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10250993&casa_token=l_hThLb8FtwAAAAA:EUIlh6smTZs7r8KsB5u6WuAp4d_6z7x3RkvdL0lV7rU3sGxHlIxveWrAo6jmuQM1KodUpjP6QE8) 

Hong, Zhiming. "Effective Learning Mechanism Based on Reward-Oriented Hierarchies for Sim-to-Real Adaption in Autonomous Driving Systems." *IEEE Transactions on Intelligent Transportation Systems* (2025). [📝 Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10840284&casa_token=-OT0rdycyXUAAAAA:gsMkMMy-Wi-SKiyohLq3fq0OHKhldQjWlBZQ52Tzh7tsWNkN0hB16UqNvXHGIUHbOxMMLK4Y2MM) 

### Safe RL

Huang, Weidong, et al. "Safedreamer: Safe reinforcement learning with world models." *arXiv preprint arXiv:2307.07176* (2023). [📝 Paper](https://arxiv.org/pdf/2307.07176) [💻 Github](https://github.com/PKU-Alignment/SafeDreamer) 

Cao, Chenyang, et al. "FOSP: Fine-tuning Offline Safe Policy through World Models." *arXiv preprint arXiv:2407.04942* (2024). [📝 Paper](https://arxiv.org/pdf/2407.04942) [🔗 Website](https://sunlighted.github.io/fosp_web/)

### Online RL

**SB3** Raffin, Antonin, et al. "Stable-baselines3: Reliable reinforcement learning implementations." *Journal of machine learning research* 22.268 (2021): 1-8. [📝 Paper](https://www.jmlr.org/papers/volume22/20-1364/20-1364.pdf) [💻 Github](https://github.com/DLR-RM/stable-baselines3) [📚 Document](https://stable-baselines3.readthedocs.io/en/master/guide/install.html) 

**DQN** Mnih, Volodymyr, et al. "Playing atari with deep reinforcement learning." arXiv preprint arXiv:1312.5602 (2013). [📝 Paper](https://arxiv.org/pdf/1312.05602)

**DDPG** Lillicrap, Timothy P., et al. "Continuous control with deep reinforcement learning." arXiv preprint arXiv:1509.02971 (2015). [📝 Paper](https://arxiv.org/pdf/1509.02971)

**TD3** Fujimoto, Scott, Herke Hoof, and David Meger. "Addressing function approximation error in actor-critic methods." International conference on machine learning. PMLR, 2018. [📝 Paper](https://proceedings.mlr.press/v80/fujimoto18a/fujimoto18a.pdf)

**PPO** Schulman, John, et al. "Proximal policy optimization algorithms." arXiv preprint arXiv:1707.06347 (2017). [📝 Paper](https://arxiv.org/pdf/1707.06347)

**SAC** Haarnoja, Tuomas, et al. "Soft actor-critic: Off-policy maximum entropy deep reinforcement learning with a stochastic actor." International conference on machine learning. Pmlr, 2018. [📝 Paper](https://proceedings.mlr.press/v80/haarnoja18b/haarnoja18b.pdf)

### Offline RL

Seno, Takuma, and Michita Imai. "d3rlpy: An offline deep reinforcement learning library." *Journal of Machine Learning Research* 23.315 (2022): 1-20. [📝 Paper](https://www.jmlr.org/papers/volume23/22-0017/22-0017.pdf) [💻 Github](https://github.com/takuseno/d3rlpy) [📚 Document](https://d3rlpy.readthedocs.io/en/v2.8.1/) 

Kumar, Aviral, et al. "Conservative q-learning for offline reinforcement learning." Advances in neural information processing systems 33 (2020): 1179-1191. [📝 Paper](https://proceedings.neurips.cc/paper/2020/file/0d2b2061826a5df3221116a5085a6052-Paper.pdf) [💻 Github](https://github.com/aviralkumar2907/CQL) 

Kostrikov, Ilya, Ashvin Nair, and Sergey Levine. "Offline reinforcement learning with implicit q-learning." arXiv preprint arXiv:2110.06169 (2021). [📝 Paper](https://arxiv.org/pdf/2110.06169) [💻 Github](https://github.com/ikostrikov/implicit_q_learning) 

### Offline-to-online RL

Zheng, Qinqing, Amy Zhang, and Aditya Grover. "Online decision transformer." *international conference on machine learning*. PMLR, 2022. [📝 Paper](https://proceedings.mlr.press/v162/zheng22c/zheng22c.pdf) [💻 Github](https://github.com/facebookresearch/online-dt)

Zhang, Haichao, We Xu, and Haonan Yu. "Policy expansion for bridging offline-to-online reinforcement learning." *arXiv preprint arXiv:2302.00935* (2023). [📝 Paper](https://arxiv.org/pdf/2302.00935) [💻 Github](https://github.com/Haichao-Zhang/PEX)

Ball, Philip J., et al. "Efficient online reinforcement learning with offline data." International Conference on Machine Learning. PMLR, 2023. [📝 Paper](https://proceedings.mlr.press/v202/ball23a/ball23a.pdf) [💻 Github](https://github.com/ikostrikov/rlpd)


