# Awesome-Video-Robotic-Papers

This repository compiles a list of seminal and cutting-edge papers that explore the application of video technology in the field of robotics. Continual improvements are being made to this repository, and contributions are welcome. If you come across any relevant papers that should be included, please don't hesitate to open an issue.

## Table of Contents

1. [Review Papers](#review-papers)
2. [Robot Arm](#robot-arm)
3. [SPOT](#spot)
4. [Dataset](#dataset)
5. [Other Useful Sources](#other-useful-sources)

## Review Papers
- **Towards Generalist Robot Learning from Internet Video: A Survey**
  - Robert McCarthy, Daniel C.H. Tan, Dominik Schmidt, Fernando Acero, Nathan Herr, Yilun Du, Thomas G. Thuruthel, Zhibin Li
  - [Paper](https://arxiv.org/pdf/2404.19664)

- **Learning by Watching: A Review of Video-based Learning Approaches for Robot Manipulation**
  - Chrisantus Eze, Christopher Crick
  - [Paper](https://arxiv.org/abs/2402.07127)

## Robot Arm
- **Let Me Help You! Neuro-Symbolic Short-Context Action Anticipation**
  - Sarthak Bhagat, Samuel Li, Joseph Campbell, Yaqi Xie, Katia Sycara, Simon Stepputtis
  - [Paper](https://ieeexplore.ieee.org/document/10582423)
  - [Website](https://sarthak268.github.io/NeSCA/)
  - [Code](https://github.com/sarthak268/nesca-pytorch)
  - IEEE Robotics and Automation Letters
  - The Robotics Institute, Carnegie Melon University

- **Generalization with Lossy Affordances: Leveraging Broad Offline Data for Learning Visuomotor Tasks**
  - Kuan Fang, Patrick Yin, Ashvin Nair, Homer Walke, Gengchen Yan, Sergey Levine
  - [Paper](https://arxiv.org/abs/2210.06601)
  - [Code](https://github.com/kuanfang/flap)
  - CoRL 2022
  - UC Berkeley

- **VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training**
  - Yecheng Jason Ma, Shagun Sodhani, Dinesh Jayaraman, Osbert Bastani, Vikash Kumar, Amy Zhang
  - [Paper](https://arxiv.org/abs/2210.00030)
  - [Website](https://sites.google.com/view/vip-rl)
  - [Code](https://github.com/facebookresearch/vip)
  - ICLR 2023, Notable-Top-25% (Spotlight)
  - FAIR, Meta AI || University of Pennsylvania

- **SOAR: Autonomous Improvement of Instruction Following Skills via Foundation Models**
  - Zhiyuan Zhou, Pranav Atreya, Abraham Lee, Homer Walke, Oier Mees, Sergey Levine
  - [Paper](https://arxiv.org/abs/2407.20635)
  - [Website](https://auto-improvement.github.io/)
  - [Code](https://github.com/rail-berkeley/soar)
  - [Dataset](https://rail.eecs.berkeley.edu/datasets/soar_release/)
  - UC Berkeley

- **HRP: Human Affordances for Robotic Pre-Training**
  - Mohan Kumar Srirama, Sudeep Dasari, Shikhar Bahl, Abhinav Gupta
  - [Paper](https://arxiv.org/abs/2407.18911)
  - Robotics Science and Systems 2024
  - CMU

- **Action2Sound: Ambient-Aware Generation of Action Sounds from Egocentric Videos**
  - Changan Chen, Puyuan Peng, Ami Baid, Zihui Xue, Wei-Ning Hsu, David Harwath, Kristen Grauman
  - [Paper](https://arxiv.org/abs/2406.09272)
  - [Website](https://vision.cs.utexas.edu/projects/action2sound/)
  - [Code] not release yet
  - University of Texas at Austin || FAIR, Meta AI

- **This&That: Language-Gesture Controlled Video Generation for Robot Planning**
  - Boyang Wang, Nikhil Sridhar, Chao Feng, Mark Van der Merwe, Adam Fishman, Nima Fazeli, Jeong Joon Park
  - [Paper](https://arxiv.org/abs/2407.05530)
  - [Website](https://cfeng16.github.io/this-and-that/)
  - [Code] not release yet
  - University of Michigan || University of Washington

- **Policy Composition From and For Heterogeneous Robot Learning**
  - Lirui Wang, Alan Zhao, Yilun Du, Ted Adelson, Russ Tedrake
  - [Paper](https://arxiv.org/abs/2402.02511)
  - [Website](https://liruiw.github.io/policycomp/)
  - MIT CSAIL
  - Robotics: Science and Systems (R:SS), 2024

- **Simultaneous Localization and Affordance Prediction for Tasks in Egocentric Video**
  - Zachary Chavis, Hyun Soo Park, and Stephen J. Guy
  - [Paper](https://arxiv.org/abs/2407.13856)
  - Department of Computer Science and Engineering, University of Minnesota

- **Flow as the Cross-domain Manipulation Interface**
  - Mengda Xu, Zhenjia Xu, Yinghao Xu, Cheng Chi, Gordon Wetzstein, Manuela Veloso, Shuran Song
  - [Paper](https://arxiv.org/abs/2407.15208)
  - [Website](https://im-flow-act.github.io/)
  - Stanford University || Columbia University || JP Morgan AI Research || Carnegie Mellon University

- **R+X: Retrieval and Execution from Everyday Human Videos**
  - Georgios Papagiannis, Norman Di Palo, Pietro Vitiello, Edward Johns
  - [Paper](https://arxiv.org/abs/2407.12957)
  - [Website](https://www.robot-learning.uk/r-plus-x)
  - the Robot Learning Lab at Imperial College London

- **Octo: An Open-Source Generalist Robot Policy**
  - Dibya Ghosh, Homer Walke, Karl Pertsch, Kevin Black, Oier Mees, Sudeep Dasari, Joey Hejna, Tobias Kreiman, Charles Xu, Jianlan Luo, You Liang Tan, Lawrence Yunliang Chen, Pannag Sanketi, Quan Vuong, Ted Xiao, Dorsa Sadigh, Chelsea Finn, Sergey Levine
  - [Paper](https://arxiv.org/pdf/2405.12213)
  - [Website](https://octo-models.github.io/)
  - [Code](https://github.com/octo-models/octo)
  - UC Berkeley || Stanford || Carnegie Mellon University || Google Deepmind

- **HRP: Human Affordances for Robotic Pre-Training**
  - Mohan Kumar Srirama, Sudeep Dasari, Shikhar Bahl, Abhinav Gupta
  - [Paper](https://hrp-robot.github.io/hrp.pdf)
  - [Website](https://hrp-robot.github.io/)
  - [Code](https://github.com/SudeepDasari/data4robotics/tree/hrp_release)
  - Carnegie Mellon University
  - RSS 2024

- **RAM: Retrieval-Based Affordance Transfer for Generalizable Zero-Shot Robotic Manipulation**
  - Yuxuan Kuang*, Junjie Ye*, Haoran Geng*, Jiageng Mao, Congyue Deng, Leonidas Guibas, He Wang, Yue Wang
  - [Paper](https://arxiv.org/abs/2407.04689)
  - [Website](https://yxkryptonite.github.io/RAM/)
  - [Code](https://github.com/yxKryptonite/RAM_code)
  - University of Southern California || Peking University || Stanford University

- **Vid2Robot: End-to-end Video-conditioned Policy Learning with Cross-Attention Transformers**
  - Vidhi Jain, Maria Attarian, Nikhil J Joshi, Ayzaan Wahid, Danny Driess, Quan Vuong, Pannag R Sanketi, Pierre Sermanet, Stefan Welker, Christine Chan, Igor Gilitschenski, Yonatan Bisk, Debidatta Dwibedi
  - [Paper](https://arxiv.org/abs/2403.12943)
  - [Website](https://vid2robot.github.io/)
  - Google DeepMind || Carnegie Mellon University || University of Toronto

- **OpenVLA: An Open-Source Vision-Language-Action Model**
  - Moo Jin Kim, Karl Pertsch, Siddharth Karamcheti, Ted Xiao, Ashwin Balakrishna, Suraj Nair, Rafael Rafailov, Ethan Foster, Grace Lam, Pannag Sanketi, Quan Vuong, Thomas Kollar, Benjamin Burchfiel, Russ Tedrake, Dorsa Sadigh, Sergey Levine, Percy Liang, Chelsea Finn
  - [Paper](https://arxiv.org/abs/2406.09246)
  - [Website](https://openvla.github.io/)
  - [Code](https://github.com/openvla/openvla)
  - Stanford University || UC Berkeley || Toyota Research Institute || Google DeepMind || Physical Intelligence || MIT

- **Video Language Planning**
  - Yilun Du, Mengjiao Yang, Pete Florence, Fei Xia, Ayzaan Wahid, Brian Ichter, Pierre Sermanet, Tianhe Yu, Pieter Abbeel, Joshua B. Tenenbaum, Leslie Kaelbling, Andy Zeng, Jonathan Tompson
  - [Paper](https://arxiv.org/abs/2310.10625)
  - [Website](https://video-language-planning.github.io/)
  - [Code](https://github.com/video-language-planning/vlp_code)
  - Google Deepmind || MIT || UC Berkeley

- **Manipulate-Anything: Automating Real-World Robots using Vision-Language Models**
  - Jiafei Duan, Wentao Yuan, Wilbert Pumacay, Yi Ru Wang, Kiana Ehsani, Dieter Fox, Ranjay Krishna
  - [Paper](https://arxiv.org/pdf/2406.18915)
  - [Website](https://robot-ma.github.io/)
  - University of Washington || NVIDIA || Allen Institute for Artifical Intelligence || Universidad Católica San Pablo

- **Dreamitate: Real-World Visuomotor Policy Learning via Video Generation**
  - Junbang Liang, Ruoshi Liu, Ege Ozguroglu, Sruthi Sudhakar, Achal Dave, Pavel Tokmakov, Shuran Song, Carl Vondrick
  - [Paper](https://arxiv.org/abs/2406.16862)
  - [Website](https://dreamitate.cs.columbia.edu/)
  - [Code](https://github.com/cvlab-columbia/dreamitate)
  - Columbia University || Toyota Research Institute || Stanford University,

- **Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation**
  - Hongtao Wu, Ya Jing, Chilam Cheang, Guangzeng Chen, Jiafeng Xu, Xinghang Li, Minghuan Liu, Hang Li, Tao Kong
  - [Paper](https://arxiv.org/abs/2312.13139)
  - [Website](https://gr1-manipulation.github.io/)
  - [Code](https://github.com/bytedance/GR-1)
  - ByteDance Research

- **Large-Scale Actionless Video Pre-Training via Discrete Diffusion for Efficient Policy Learning**
  - Haoran He, Chenjia Bai, Ling Pan, Weinan Zhang, Bin Zhao, Xuelong Li
  - [Paper](https://arxiv.org/abs/2402.14407)
  - [Website](https://video-diff.github.io/)
  - Hong Kong University of Science and Technology || Shanghai Artificial Intelligence Laboratory || Shanghai Jiao Tong University || Northwestern Polytechnical University || Institute of Artificial In- telligence (TeleAI), China Telecom Corp Ltd.

- **ManiWAV: Learning Robot Manipulation from In-the-Wild Audio-Visual Data**
  - Zeyi Liu, Cheng Chi, Eric Cousineau, Naveen Kuppuswamy, Benjamin Burchfiel, Shuran Song
  - [Paper](https://arxiv.org/abs/2406.19464)
  - [Website](https://mani-wav.github.io/)
  - [Code](https://github.com/real-stanford/maniwav)
  - [Dataset](https://real.stanford.edu/maniwav/data/)
  - Stanford University || Columbia University || Toyota Research Institute

- **Vision-based Manipulation from Single Human Video with Open-World Object Graphs**
  - Yifeng Zhu, Arisrei Lim, Peter Stone, Yuke Zhu
  - [Paper](https://arxiv.org/abs/2405.20321)
  - [Website](https://ut-austin-rpl.github.io/ORION-release/)
  - The University of Texas at Austin || Sony AI

- **Learning to Act from Actionless Videos through Dense Correspondences**
  - Po-Chen Ko, Jiayuan Mao, Yilun Du, Shao-Hua Sun, Joshua B. Tenenbaum
  - [Paper](https://arxiv.org/abs/2310.08576)
  - [Website](https://flow-diffusion.github.io/)
  - [Code](https://github.com/flow-diffusion/AVDC)
  - National Taiwan University | MIT

## SPOT
- **Track2Act: Predicting Point Tracks from Internet Videos Enables Diverse Zero-shot Manipulation**
  - Homanga Bharadhwaj, Roozbeh Mottaghi*, Abhinav Gupta*, Shubham Tulsiani*
  - [Paper](https://arxiv.org/abs/2405.01527)
  - [Website](https://homangab.github.io/track2act/)
  - [Code](https://github.com/homangab/Track-2-Act/)

## Dataset

- **DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**
  - Alexander Khazatsky, Karl Pertsch, Suraj Nair, Ashwin Balakrishna, Sudeep Dasari, Siddharth Karamcheti, Soroush Nasiriany, Mohan Kumar Srirama, Lawrence Yunliang Chen, Kirsty Ellis, Peter David Fagan, Joey Hejna, Masha Itkina, Marion Lepert, Yecheng Jason Ma, Patrick Tree Miller, Jimmy Wu, Suneel Belkhale, Shivin Dass, Huy Ha, Arhan Jain, Abraham Lee, Youngwoon Lee, Marius Memmel, Sungjae Park, Ilija Radosavovic, Kaiyuan Wang, Albert Zhan, Kevin Black, Cheng Chi, Kyle Beltran Hatch, Shan Lin, Jingpei Lu, Jean Mercat, Abdul Rehman, Pannag R Sanketi, Archit Sharma, Cody Simpson, Quan Vuong, Homer Rich Walke, Blake Wulfe, Ted Xiao, Jonathan Heewon Yang, Arefeh Yavary, Tony Z. Zhao, Christopher Agia, Rohan Baijal, Mateo Guaman Castro, Daphne Chen, Qiuyu Chen, Trinity Chung, Jaimyn Drake, Ethan Paul Foster, Jensen Gao, David Antonio Herrera, Minho Heo, Kyle Hsu, Jiaheng Hu, Donovon Jackson, Charlotte Le, Yunshuang Li, Kevin Lin, Roy Lin, Zehan Ma, Abhiram Maddukuri, Suvir Mirchandani, Daniel Morton, Tony Nguyen, Abigail O'Neill, Rosario Scalise, Derick Seale, Victor Son, Stephen Tian, Emi Tran, Andrew E. Wang, Yilin Wu, Annie Xie, Jingyun Yang, Patrick Yin, Yunchu Zhang, Osbert Bastani, Glen Berseth, Jeannette Bohg, Ken Goldberg, Abhinav Gupta, Abhishek Gupta, Dinesh Jayaraman, Joseph J Lim, Jitendra Malik, Roberto Martín-Martín, Subramanian Ramamoorthy, Dorsa Sadigh, Shuran Song, Jiajun Wu, Michael C. Yip, Yuke Zhu, Thomas Kollar, Sergey Levine, Chelsea Finn
  - [Paper](https://arxiv.org/abs/2403.12945)
  - [Website](https://droid-dataset.github.io/)
  - check the website and get much sources
  - <img width="1469" alt="image" src="https://github.com/user-attachments/assets/b7e1db76-8af4-471e-b09d-c98ec96555a4">


- **Open X-Embodiment: Robotic Learning Datasets and RT-X Models**
  - Open X-Embodiment Collaboration, Abby O'Neill, Abdul Rehman, Abhinav Gupta, Abhiram Maddukuri, Abhishek Gupta, Abhishek Padalkar, Abraham Lee, Acorn Pooley, Agrim Gupta, Ajay Mandlekar, Ajinkya Jain, Albert Tung, Alex Bewley, Alex Herzog, Alex Irpan, Alexander Khazatsky, Anant Rai, Anchit Gupta, Andrew Wang, Andrey Kolobov, Anikait Singh, Animesh Garg, Aniruddha Kembhavi, Annie Xie, Anthony Brohan, Antonin Raffin, Archit Sharma, Arefeh Yavary, Arhan Jain, Ashwin Balakrishna, Ayzaan Wahid, Ben Burgess-Limerick, Beomjoon Kim, Bernhard Schölkopf, Blake Wulfe, Brian Ichter, Cewu Lu, Charles Xu, Charlotte Le, Chelsea Finn, Chen Wang, Chenfeng Xu, Cheng Chi, Chenguang Huang, Christine Chan, Christopher Agia, Chuer Pan, Chuyuan Fu, Coline Devin, Danfei Xu, Daniel Morton, Danny Driess, Daphne Chen, Deepak Pathak, Dhruv Shah, Dieter Büchler, Dinesh Jayaraman, Dmitry Kalashnikov, Dorsa Sadigh, Edward Johns, Ethan Foster, Fangchen Liu, Federico Ceola, Fei Xia, Feiyu Zhao, Felipe Vieira Frujeri, Freek Stulp, Gaoyue Zhou, Gaurav S. Sukhatme, Gautam Salhotra, Ge Yan, Gilbert Feng, Giulio Schiavi, Glen Berseth, Gregory Kahn, Guangwen Yang, Guanzhi Wang, Hao Su, Hao-Shu Fang, Haochen Shi, Henghui Bao, Heni Ben Amor, Henrik I Christensen, Hiroki Furuta, Homanga Bharadhwaj, Homer Walke, Hongjie Fang, Huy Ha, Igor Mordatch, Ilija Radosavovic, Isabel Leal, Jacky Liang, Jad Abou-Chakra, Jaehyung Kim, Jaimyn Drake, Jan Peters, Jan Schneider, Jasmine Hsu, Jay Vakil et al. (192 additional authors not shown)
  - [Paper](https://arxiv.org/abs/2310.08864)
  - [Website](https://robotics-transformer-x.github.io/)
  - [Code](https://github.com/google-deepmind/open_x_embodiment)
  - ![image](https://github.com/user-attachments/assets/3707d035-146e-47cb-8f0e-c50edcaff279)

- **BridgeData V2: A Dataset for Robot Learning at Scale**
  - Homer Walke, Kevin Black, Abraham Lee, Moo Jin Kim, Max Du, Chongyi Zheng, Tony Zhao, Philippe Hansen-Estruch, Quan Vuong, Andre He, Vivek Myers, Kuan Fang, Chelsea Finn, Sergey Levine
  - [Paper](https://arxiv.org/abs/2308.12952)
  - [Website](https://rail-berkeley.github.io/bridgedata/)
  - [Code](https://github.com/rail-berkeley/bridge_data_v2)
  - <img width="677" alt="image" src="https://github.com/user-attachments/assets/eaf13917-28ef-4478-8c23-3776bb1ea567">


- **Ego4DSounds:A diverse egocentric dataset with high action-audio correspondence**
  - Changan Chen, Puyuan Peng, Ami Baid, Zihui Xue, Wei-Ning Hsu, David Harwath, Kristen Grauman
  - [Paper](https://arxiv.org/abs/2406.09272)
  - [Website](https://ego4dsounds.github.io)
  - [Code](https://github.com/Ego4DSounds/Ego4DSounds)
  - <img width="911" alt="image" src="https://github.com/user-attachments/assets/833ab02e-3f2b-4f3f-8508-17b98c9dce06">

- **RH20T: A Comprehensive Robotic Dataset for Learning Diverse Skills in One-Shot**
    - Hao-Shu Fang, Hongjie Fang, Zhenyu Tang, Jirong Liu, Chenxi Wang, Junbo Wang, Haoyi Zhu, Cewu Lu
    - [Paper](https://arxiv.org/abs/2307.00595)
    - [Website](https://rh20t.github.io/)
    - [API](https://github.com/rh20t/rh20t_api)
    - [Dataset](https://rh20t.github.io/#download)
    - Shanghai Jiao Tong University


## Other Useful Sources

- [Awesome-VideoLLM-Papers](https://github.com/yyyujintang/Awesome-VideoLLM-Papers)
- [Awesome-LLMs-for-Video-Understanding](https://github.com/yunlong10/Awesome-LLMs-for-Video-Understanding)
- [VLM-Eval: A General Evaluation on Video Large Language Models](https://github.com/zyayoung/Awesome-Video-LLMs)
- [LLMs Meet Multimodal Generation and Editing: A Survey](https://github.com/YingqingHe/Awesome-LLMs-meet-Multimodal-Generation)
