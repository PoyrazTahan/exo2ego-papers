# Core list: exo-to-ego video, paired ego+exo data, policies and benchmarks

The checked subset (see PAPERS.md for everything). Checked 16 Nov 2026 against arXiv (id, title, date, authors, abstract). Numbers are quoted from the abstract only. Project pages and licences were not checked, so read the licence on a dataset before you use it.

## Exo-to-ego generation and paired datasets

| work | year | link | what it is | number from the abstract |
|---|---|---|---|---|
| LEGO: A Lifting-Free Approach for Exocentric-to-Egocentric Video Generation (Cho, Choi, Kim, Park, Lim) | 2026 | https://arxiv.org/abs/2610.12442 · https://suhwan-cho.github.io/LEGO | Generates an egocentric video from one exocentric recording with a video diffusion model, without lifting to a point cloud first | not in the excerpt read |
| Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives (Grauman et al.) | 2023, CVPR 2024 | https://arxiv.org/abs/2311.18259 · https://ego-exo4d-data.org | Simultaneous ego and exo video of skilled activities, with gaze, poses and point clouds | 1,286 h, 740 participants, 123 scene contexts |
| Ego4D: Around the World in 3,000 Hours of Egocentric Video (Grauman et al.) | 2021, CVPR 2022 | https://arxiv.org/abs/2110.07058 · https://ego4d-data.org | Egocentric dataset and benchmark suite | 3,670 h, 931 camera wearers, 74 locations, 9 countries |
| EgoMimic: Scaling Imitation Learning via Egocentric Video (Kareer et al.) | 2024 | https://arxiv.org/abs/2410.24221 · https://egomimic.github.io | Co-trains robot policies on egocentric human video and robot data | not read in this pass |

## Robot policies

| work | year | link | what it is | number from the abstract |
|---|---|---|---|---|
| ACT: Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware (Zhao, Kumar, Levine, Finn) | 2023 | https://arxiv.org/abs/2304.13705 · https://tonyzhaozh.github.io/aloha/ | Imitation policy predicting action chunks, on cheap bimanual hardware | 80-90% success on 6 tasks from 10 minutes of demonstrations |
| Diffusion Policy: Visuomotor Policy Learning via Action Diffusion (Chi, Xu, Feng, Cousineau et al.) | 2023 | https://arxiv.org/abs/2303.04137 · https://diffusion-policy.cs.columbia.edu | Policy as a conditional denoising process | 46.9% average improvement, 12 tasks, 4 benchmarks |
| OpenVLA: An Open-Source Vision-Language-Action Model (Kim, Pertsch, Karamcheti, Xiao et al.) | 2024 | https://arxiv.org/abs/2406.09246 · https://openvla.github.io | Open 7B vision-language-action model with an efficient fine-tuning recipe | 7B parameters, 970k real-world demonstrations |
| π0.5: a Vision-Language-Action Model with Open-World Generalization (Physical Intelligence) | 2025 | https://arxiv.org/abs/2504.16054 · https://www.pi.website/blog/pi05 | VLA co-trained on multi-robot, web and semantic data | none in the abstract |
| LocoFormer: Generalist Locomotion via Long-context Adaptation (Liu, Pathak, Agarwal) | 2025 | https://arxiv.org/abs/2509.23745 · https://generalist-locomotion.github.io | Locomotion model that adapts at test time to unseen bodies | none in the abstract |
| Do as I Do: Dexterous Manipulation Data from Everyday Human Videos (Paliwal, Etukuru, Liang, Abbeel, Shafiullah, Malik) | 2026 | https://arxiv.org/abs/2606.19333 · https://do-as-i-do.com | Reconstructs hand-object interaction from monocular RGB video and retargets it to dexterous hands | not read in this pass |
| Emergent Dexterity via Diverse Resets and Large-Scale Reinforcement Learning (Yin, Westenbroek, ... Kolobov, Gupta) | 2026 | https://arxiv.org/abs/2603.15789 | Scalable simulation RL (OmniReset) for long-horizon contact-rich manipulation | not read in this pass |

## Sim-to-real, evaluation and benchmarks

| work | year | link | what it is | number from the abstract |
|---|---|---|---|---|
| TRANSIC: Sim-to-Real Policy Transfer by Learning from Online Correction (Jiang, Wang, Zhang, Wu et al.) | 2024 | https://arxiv.org/abs/2405.10315 · https://transic-robot.github.io | Closes sim-to-real gaps with human corrections during real execution | none in the abstract |
| RoboRender: Robot-Oriented Video Generation for Visual Sim-to-Real Transfer (Huang, Ai, Chen, Wang et al.) | 2026 | https://arxiv.org/abs/2610.09254 | Turns simulated trajectories into photorealistic video for policy training | 71% average success, about 7.1x over raw sim renderings, 3.6x over domain randomisation |
| Real-to-Sim Robot Policy Evaluation with Gaussian Splatting Simulation of Soft-Body Interactions (Zhang, Sha, Jiang, Loper et al.) | 2025 | https://arxiv.org/abs/2511.04665 · https://real2sim-eval.github.io | Evaluates policies in photorealistic 3D Gaussian Splatting twins built from real video | none in the abstract |
| RoboDojo: A Unified Sim-and-Real Benchmark for Comprehensive Evaluation of Generalist Robot Manipulation Policies (Chen et al.) | 2026 | https://arxiv.org/abs/2607.04434 · https://robodojo-benchmark.com | Benchmark spanning simulation and real hardware | 42 sim + 18 real tasks, 30 policies on a leaderboard |
| BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation (Li, Zhang, Wong, Gokmen et al.) | 2024 | https://arxiv.org/abs/2403.09227 · https://behavior.stanford.edu | Simulation benchmark of everyday activities in OmniGibson | 1,000 activities, 50 scenes, 9,000+ objects |
| Open X-Embodiment: Robotic Learning Datasets and RT-X Models (Open X-Embodiment Collaboration) | 2023 | https://arxiv.org/abs/2310.08864 · https://robotics-transformer-x.github.io | Pooled multi-robot datasets in one format, plus RT-1-X and RT-2-X | 22 robots, 21 institutions, 527 skills (160,266 tasks) |

## Video

- Approximate Imitation Learning for Event-based Flight in Cluttered Environments (CoRL 2026), UZH Robotics and Perception Group: https://www.youtube.com/watch?v=yI8wGTaoYHA (title and channel checked; video not watched)

## Not verified

- Which of these a given claim comes from: figures such as "Ego4D has 10 tasks of 100 h each" are not in the Ego4D abstract.
- Anything not in the tables.
