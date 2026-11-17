# All papers, by category

329 entries in 12 categories. A check mark means the entry was checked against arXiv on 16 Nov 2026 (`CORE.md` adds abstract numbers for the exo-to-ego, policy and benchmark subset). Unmarked entries are leads: the title comes from the fetched page, and an arXiv id is shown only when arXiv's own title for that id matched.

38 entries are checked. The same data is in `papers.tsv`.

Contents

1. [Feed-forward 3D reconstruction (DUSt3R / VGGT family)](#1) (20)
2. [Structure-from-Motion, calibration, SLAM, odometry](#2) (29)
3. [Gaussian splatting](#3) (47)
4. [NeRF and neural fields (the lineage 3DGS replaced; still the background)](#4) (23)
5. [Dynamic scenes and 4D (4D Gaussians, scene flow, 4D reconstruction)](#5) (19)
6. [Human body, pose and mesh recovery (HMR family, SMPL, egocentric human)](#6) (34)
7. [Ego-exo, robot-learning-from-human-video, and datasets](#7) (49)
8. [Robot policies, sim-to-real, evaluation and benchmarks](#8) (13)
9. [Auto-labeling: segmentation, tracking, 3D instance / open-vocabulary understanding](#9) (44)
10. [Depth and stereo (monocular, video, metric)](#10) (12)
11. [Adjacent: generative 3D, world models, object/scene generation (context, lower priority)](#11) (22)
12. [Tools, viewers, editors, libraries (3DGS ecosystem)](#12) (17)

<a id="1"></a>
## 1. Feed-forward 3D reconstruction (DUSt3R / VGGT family)

- **VGGT: Visual Geometry Grounded Transformer.** — arXiv:2503.11651  
  [paper](https://arxiv.org/abs/2503.11651) · [page](https://vgg-t.github.io/) · [code](https://github.com/facebookresearch/vggt)
- **Pi3**  
  [page](https://yyfz.github.io/pi3/) · [code](https://github.com/yyfz/Pi3)
- **CUT3R: Continuous 3D Perception Model with Persistent State** — arXiv:2501.12387  
  [paper](https://arxiv.org/abs/2501.12387) · [page](https://cut3r.github.io/) · [code](https://github.com/CUT3R/CUT3R)
- **MonST3R: A Simple Approach for Estimating Geometry in the Presense of Motion** — arXiv:2410.03825  
  [paper](https://arxiv.org/abs/2410.03825) · [page](https://monst3r-project.github.io/ https://monst3r-project.github.io/files/monst3r_paper.pdf) · [code](https://github.com/Junyi42/monst3r)
- **MV-DUSt3R+: Single-Stage Scene Reconstruction from Sparse Views In** — arXiv:2412.06974  
  [paper](https://arxiv.org/abs/2412.06974) · [page](https://mv-dust3rp.github.io/) · [code](https://github.com/facebookresearch/mvdust3r)
- **TTT3R: 3D Reconstruction as Test-Time Training** — arXiv:2509.26645  
  [paper](https://arxiv.org/abs/2509.26645) · [page](https://rover-xingyu.github.io/TTT3R/) · [code](https://github.com/Inception3D/TTT3R)
- **NIRVANALAN/STream3R: Dynamic 3D Foundation Model using Causal Transformer. [ICLR 2026]**  
  [page](https://nirvanalan.github.io/projects/stream3r/ https://nirvanalan.github.io/projects/stream3r) · [code](https://github.com/NIRVANALAN/STream3R)
- **PKU-VCL-3DV/SLAM3R: [CVPR 2025 Highlight] Real-time dense scene reconstruction with SLAM3R** — arXiv:2412.09401  
  [paper](https://arxiv.org/abs/2412.09401) · [code](https://github.com/PKU-VCL-3DV/SLAM3R)
- **SAIL-Recon: Large SfM by Augmenting Scene Regression with Localization** — arXiv:2508.17972  
  [paper](https://arxiv.org/abs/2508.17972) · [page](https://hkust-sail.github.io/sail-recon/) · [code](https://github.com/HKUST-SAIL/sail-recon https://github.com/HKUST-SAIL/NoiseAR)
- **Glob3R | Global Structure-from-Motion with 3D Foundation Models** — arXiv:2607.09225  
  [paper](https://arxiv.org/abs/2607.09225) · [page](https://junyuandeng.github.io/Glob3r/ https://junyuandeng.github.io/Glob3r) · [code](https://github.com/aigc3d/Glob3R)
- **FLARE** — arXiv:2502.12138  
  [paper](https://arxiv.org/abs/2502.12138) · [page](https://zhanghe3z.github.io/FLARE/) · [code](https://github.com/ant-research/FLARE)
- **nv-dvl/vgg-ttt: [CVPR'26] Official code for the paper "VGG-T³: Offline Feed-Forward 3D Reconstruction** — arXiv:2602.23361  
  [paper](https://arxiv.org/abs/2602.23361) · [page](https://research.nvidia.com/labs/dvl/projects/vgg-ttt/)
- **StreamVGGT**  
  [page](https://wzzheng.net/StreamVGGT/) · [code](https://github.com/wzzheng/StreamVGGT)
- **IGGT4D: Streaming 4D Instance-Grounded Geometry Transformer** — arXiv:2607.19228  
  [paper](https://arxiv.org/abs/2607.19228) · [page](https://iggt4d.github.io/) · [code](https://github.com/HorizonRobotics/IGGT4D)
- **wyddmw/POMATO: [ICCV 2025] This is the official implementation of POMATO: Marrying Pointmap Matching**  
  [code](https://github.com/wyddmw/POMATO)
- **MASt3R-SLAM: Real-Time Dense SLAM with 3D Reconstruction Priors** — arXiv:2412.12392  
  [paper](https://arxiv.org/abs/2412.12392) · [page](https://edexheim.github.io/mast3r-slam/) · [code](https://github.com/rmurai0610/mast3r-slam)
- **Fast3R: Towards 3D Reconstruction of 1000+ Images in One Forward Pass** — arXiv:2501.13928  
  [paper](https://arxiv.org/abs/2501.13928) · [page](https://fast3r-3d.github.io/) · [code](https://github.com/facebookresearch/fast3r)
- **PF-LRM: Pose-Free Large Reconstruction Model for Joint Pose and Shape Prediction** — arXiv:2311.12024  
  [paper](https://arxiv.org/abs/2311.12024) · [page](https://totoro97.github.io/pf-lrm/)
- **lpiccinelli-eth/UniK3D: [CVPR 2025] UniK3D: Universal Camera Monocular 3D Estimation** — arXiv:2503.16591  
  [paper](https://arxiv.org/abs/2503.16591) · [page](https://lpiccinelli-eth.github.io/pub/unik3d/ https://lpiccinelli-eth.github.io/pub/unik3d) · [code](https://github.com/lpiccinelli-eth/unik3d https://github.com/lpiccinelli-eth/UniK3D)
- **Introducing SAM 3D: Powerful 3D Reconstruction for Physical World Images**  
  [page](https://ai.meta.com/blog/sam-3d/)

<a id="2"></a>
## 2. Structure-from-Motion, calibration, SLAM, odometry

- **XM: Convex Bundle Adjustment and Structure from Motion (arXiv title: Building Rome with Convex Optimization; Han & Yang, Harvard)** — arXiv:2502.04640  
  [paper](https://arxiv.org/abs/2502.04640) · [page](https://computationalrobotics.seas.harvard.edu/XM/) · [code](https://github.com/ComputationalRobotics/XM-code)
- **cvg/mpsfm: MP-SfM: Monocular Surface Priors for Robust Structure-from-Motion (CVPR 2025)** — arXiv:2504.20040  
  [paper](https://arxiv.org/abs/2504.20040) · [code](https://github.com/cvg/mpsfm)
- **cvg/vidmap: VidMap: Exploiting Temporal Structure for Video-Based Structure-from-Motion (ECCV 2026)** — arXiv:2607.27194  
  [paper](https://arxiv.org/abs/2607.27194) · [page](https://cvg.github.io/vidmap/) · [code](https://github.com/cvg/vidmap)
- **colmap/colmap: COLMAP - Structure-from-Motion and Multi-View Stereo**  
  [page](https://colmap.github.io/ https://colmap.github.io/install.html) · [code](https://github.com/colmap/colmap https://github.com/colmap/colmap.github.io)
- **FastMap: Revisiting Dense and Scalable Structure from Motion** — arXiv:2505.04612  
  [paper](https://arxiv.org/abs/2505.04612) · [page](https://jiahao.ai/fastmap/) · [code](https://github.com/pals-ttic/fastmap)
- **DiffusionSfM: Predicting Structure and Motion via Ray Origin and Endpoint Diffusion** — arXiv:2505.05473  
  [paper](https://arxiv.org/abs/2505.05473) · [page](https://qitaozhao.github.io/DiffusionSfM) · [code](https://github.com/QitaoZhao/DiffusionSfM)
- **Accelerated Coordinate Encoding: Learning to Relocalize in Minutes using RGB and Poses** — arXiv:2305.14059  
  [paper](https://arxiv.org/abs/2305.14059) · [page](https://nianticlabs.github.io/ace/) · [code](https://github.com/nianticlabs/ace)
- **Pixel-Perfect Structure-from-Motion with Featuremetric Refinement** — arXiv:2108.08291  
  [paper](https://arxiv.org/abs/2108.08291)
- **MarkYu98/madpose: [CVPR 2025 Highlight] Official implementation of the solvers and estimators propose**  
  [code](https://github.com/MarkYu98/madpose)
- **cvg/LightGlue: LightGlue: Local Feature Matching at Light Speed (ICCV 2023)** — arXiv:2306.13643  
  [paper](https://arxiv.org/abs/2306.13643) · [code](https://github.com/cvg/LightGlue https://github.com/cvg/lightglue)
- **cvg/GlueStick: Joint Deep Matcher for Points and Lines 🖼️💥🖼️ (ICCV 2023)**  
  [page](https://iago-suarez.com/gluestick) · [code](https://github.com/cvg/GlueStick)
- **verlab/accelerated_features: Implementation of XFeat (CVPR 2024). Do you need robust and fast local f**  
  [code](https://github.com/verlab/accelerated_features)
- **princeton-vl/DROID-SLAM**  
  [page](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) · [code](https://github.com/princeton-vl/DROID-SLAM)
- **HengyiWang/Co-SLAM: [CVPR'23] Co-SLAM: Joint Coordinate and Sparse Parametric Encodings for Neural Re** — arXiv:2304.14377  
  [paper](https://arxiv.org/abs/2304.14377) · [page](https://hengyiwang.github.io/projects/CoSLAM https://hengyiwang.github.io/projects/CoSLAM.html) · [code](https://github.com/HengyiWang/Co-SLAM)
- **ToniRV/NeRF-SLAM: NeRF-SLAM: Real-Time Dense Monocular SLAM with Neural Radiance Fields. https://arxi** — arXiv:2210.13641  
  [paper](https://arxiv.org/abs/2210.13641) · [code](https://github.com/ToniRV/NeRF-SLAM)
- **cvg/nice-slam: [CVPR'22] NICE-SLAM: Neural Implicit Scalable Encoding for SLAM** — arXiv:2112.12130  
  [paper](https://arxiv.org/abs/2112.12130) · [page](https://pengsongyou.github.io/nice-slam) · [code](https://github.com/cvg/nice-slam)
- **SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM** — arXiv:2312.02126  
  [paper](https://arxiv.org/abs/2312.02126) · [page](https://spla-tam.github.io/) · [code](https://github.com/spla-tam/splatam https://github.com/spla-tam/SplaTAM)
- **WildGS-SLAM** — arXiv:2504.03886  
  [paper](https://arxiv.org/abs/2504.03886) · [page](https://wildgs-slam.github.io/) · [code](https://github.com/GradientSpaces/WildGS-SLAM)
- **MAC-VO: Metric-Aware Covariance for Learning-based Stereo Visual Odometry** — arXiv:2409.09479  
  [paper](https://arxiv.org/abs/2409.09479) · [page](https://mac-vo.github.io/) · [code](https://github.com/MAC-VO/MAC-VO)
- **FoundationVIO: Enforcing Metric Scale in Feed-forward Visual-Inertial** ✓ — arXiv:2610.14951  
  [paper](https://arxiv.org/abs/2610.14951) · [page](https://dynamic.robots.ox.ac.uk/projects/foundation-vio/) · [code](https://github.com/ori-drs/FoundationVIO)
- **3R-GS: Best Practice in Optimizing Camera Poses Along with 3DGS** — arXiv:2504.04294  
  [paper](https://arxiv.org/abs/2504.04294) · [page](https://zsh523.github.io/3R-GS/) · [code](https://github.com/zsh523/3rgs)
- **Self-Calibrating Gaussian Splatting for Large FOV Reconstruction** — arXiv:2502.09563  
  [paper](https://arxiv.org/abs/2502.09563) · [page](https://denghilbert.github.io/self-cali/) · [code](https://github.com/denghilbert/Self-Cali-GS)
- **Camera Pose Refinement via 3D Gaussian Splatting** — arXiv:2508.17876  
  [paper](https://arxiv.org/abs/2508.17876)
- **Kai-46/SatelliteSfM: A library for solving the satellite structure from motion problem**  
  [page](https://kai-46.github.io/website/) · [code](https://github.com/Kai-46/SatelliteSfM https://github.com/Kai-46/ARF-svox2)
- **Kimera: from SLAM to Spatial Perception with 3D Dynamic Scene Graphs** — arXiv:2101.06894  
  [paper](https://arxiv.org/abs/2101.06894)
- **JohannaXie/GauSS-MI: [RSS 2025] GauSS-MI: Gaussian Splatting Shannon Mutual Information for Active 3D** — arXiv:2504.21067  
  [paper](https://arxiv.org/abs/2504.21067) · [code](https://github.com/JohannaXie/GauSS-MI)
- **A survey on SLAM (Tosi et al., survey-slam.pdf)**  
- **edexheim/DepthCov: [CVPR 2023] Learning a Depth Covariance Function**  
  [page](https://edexheim.github.io/DepthCov/) · [code](https://github.com/edexheim/DepthCov)
- **End2End Multi-View Feature Matching with Differentiable Pose Optimization (ICCV'2023)** — arXiv:2205.01694  
  [paper](https://arxiv.org/abs/2205.01694)

<a id="3"></a>
## 3. Gaussian splatting

- **3D Gaussian Splatting for Real-Time Radiance Field Rendering** — arXiv:2308.04079  
  [paper](https://arxiv.org/abs/2308.04079) · [page](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) · [code](https://github.com/graphdeco-inria/gaussian-splatting)
- **MrNeRF/awesome-3D-gaussian-splatting: Curated list of papers and resources focused on 3D Gaussian Spl**  
  [page](https://mrnerf.github.io/awesome-3D-gaussian-splatting/) · [code](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)
- **kwea123/gaussian_splatting_notes: A detailed formulae explanation on gaussian splatting**  
  [page](https://youtube.com/live/1buFrKUaqwM) · [code](https://github.com/kwea123/gaussian_splatting_notes)
- **cvg/depthsplat: [CVPR'25] DepthSplat: Connecting Gaussian Splatting and Depth** — arXiv:2410.13862  
  [paper](https://arxiv.org/abs/2410.13862) · [page](https://haofeixu.github.io/depthsplat/) · [code](https://github.com/cvg/depthsplat)
- **EDGS: Eliminating Densification for Efficient Convergence of 3DGS** — arXiv:2504.13204  
  [paper](https://arxiv.org/abs/2504.13204) · [page](https://compvis.github.io/EDGS/) · [code](https://github.com/CompVis/EDGS)
- **RAIN-GS: Accurate Initialization Constraint for 3D Gaussian Splatting** — arXiv:2403.09413  
  [paper](https://arxiv.org/abs/2403.09413) · [page](https://cvlab-kaist.github.io/RAIN-GS/)
- **Efficient Perspective-Correct 3D Gaussian Splatting Using Hybrid Transparency** — arXiv:2410.08129  
  [paper](https://arxiv.org/abs/2410.08129) · [page](https://fhahlbohm.github.io/htgs/)
- **Self-Organizing Gaussians** — arXiv:2312.13299  
  [paper](https://arxiv.org/abs/2312.13299) · [page](https://fraunhoferhhi.github.io/Self-Organizing-Gaussians/ https://fraunhoferhhi.github.io/Self-Organizing-Gaussians/static/images/teaser.png) · [code](https://github.com/fraunhoferhhi/Self-Organizing-Gaussians)
- **On the Error Analysis of 3D Gaussian Splatting and an Optimal Projection Strategy** — arXiv:2402.00752  
  [paper](https://arxiv.org/abs/2402.00752) · [page](https://letianhuang.github.io/op43dgs/) · [code](https://github.com/LetianHuang/op43dgs)
- **QuickSplat** — arXiv:2505.05591  
  [paper](https://arxiv.org/abs/2505.05591) · [page](https://liu115.github.io/quicksplat) · [code](https://github.com/liu115/QuickSplat)
- **RadSplat: Radiance Field-Informed Gaussian Splatting for Robust Real-Time Rendering with 900+ FPS** — arXiv:2403.13806  
  [paper](https://arxiv.org/abs/2403.13806) · [page](https://m-niemeyer.github.io/radsplat/)
- **Compact 3D Gaussian Splatting** — arXiv:2408.03822  
  [paper](https://arxiv.org/abs/2408.03822) · [page](https://maincold2.github.io/c3dgs/) · [code](https://github.com/maincold2/Dynamic_C3DGS https://github.com/maincold2/Compact-3DGS)
- **Mip-Splatting** — arXiv:2311.16493  
  [paper](https://arxiv.org/abs/2311.16493) · [page](https://niujinshuchong.github.io/mip-splatting/) · [code](https://github.com/autonomousvision/mip-splatting)
- **PUP 3D-GS: Principled Uncertainty Pruning for 3D Gaussian Splatting** — arXiv:2406.10219  
  [paper](https://arxiv.org/abs/2406.10219) · [page](https://pup3dgs.github.io) · [code](https://github.com/j-alex-hanson/gaussian-splatting-pup https://github.com/pup3dgs/pup3dgs.github.io)
- **No Pose at All: Self-Supervised Pose-Free 3D Gaussian Splatting from Sparse Views** — arXiv:2508.01171  
  [paper](https://arxiv.org/abs/2508.01171) · [page](https://ranrhuang.github.io/spfsplat/ https://matchlab-imperial.github.io/Hypo3D/) · [code](https://github.com/MatchLab-Imperial/Hypo3D https://github.com/ranrhuang/SPFSplat)
- **Speedy-Splat: Fast 3D Gaussian Splatting with Sparse Pixels and Sparse Primitives** — arXiv:2412.00578  
  [paper](https://arxiv.org/abs/2412.00578) · [page](https://speedysplat.github.io) · [code](https://github.com/j-alex-hanson/speedy-splat https://github.com/speedysplat/speedysplat.github.io)
- **Triangle Splatting for Real-Time Radiance Field Rendering** — arXiv:2505.19175  
  [paper](https://arxiv.org/abs/2505.19175) · [page](https://trianglesplatting.github.io/) · [code](https://github.com/trianglesplatting/triangle-splatting)
- **HAC++: Towards 100X Compression of 3D Gaussian Splatting** — arXiv:2501.12255  
  [paper](https://arxiv.org/abs/2501.12255) · [page](https://yihangchen-ee.github.io/project_hac++/ https://yihangchen-ee.github.io) · [code](https://github.com/YihangChen-ee/HAC-plus https://github.com/YihangChen-ee/PCGS)
- **FSGS** — arXiv:2312.00451  
  [paper](https://arxiv.org/abs/2312.00451) · [page](https://zehaozhu.github.io/FSGS/) · [code](https://github.com/vita-group/fsgs)
- **Free360: Layered Gaussian Splatting for Unbounded 360-Degree View Synthesis from Extremely Sparse and Unposed** — arXiv:2503.24382  
  [paper](https://arxiv.org/abs/2503.24382) · [page](https://zju3dv.github.io/free360/) · [code](https://github.com/chobao/Free360)
- **Murre: Multi-view Reconstruction via SfM-guided Monocular Depth Estimation** — arXiv:2503.14483  
  [paper](https://arxiv.org/abs/2503.14483) · [page](https://zju3dv.github.io/murre/ https://zju3dv.github.io/murre) · [code](https://github.com/zju3dv/Murre)
- **GSFix3D: Diffusion-Guided Repair of Novel Views in Gaussian Splatting** — arXiv:2508.14717  
  [paper](https://arxiv.org/abs/2508.14717) · [page](https://gsfix3d.github.io https://gsfix3d.github.io/) · [code](https://github.com/GSFix3D/GSFix3D)
- **Deblurring 3D Gaussian Splatting** — arXiv:2401.00834  
  [paper](https://arxiv.org/abs/2401.00834) · [page](https://benhenryl.github.io/Deblurring-3D-Gaussian-Splatting/?s=08) · [code](https://github.com/benhenryL/Deblurring-3D-Gaussian-Splatting)
- **CoSurfGS** — arXiv:2412.17612  
  [paper](https://arxiv.org/abs/2412.17612) · [page](https://gyy456.github.io/CoSurfGS/) · [code](https://github.com/zju3dv/CoSurfGS)
- **gwilczynski95/meshsplats: This repo contains the official authors implementation associated with the**  
  [code](https://github.com/gwilczynski95/meshsplats)
- **waczjoan/gaussian-mesh-splatting: Official implementation of "Mesh-Based Adapting and Modification of** — arXiv:2402.01459  
  [paper](https://arxiv.org/abs/2402.01459) · [page](https://waczjoan.github.io/gaussian-mesh-splatting/) · [code](https://github.com/waczjoan/gaussian-mesh-splatting)
- **nv-tlabs/3dgrut: Ray tracing and hybrid rasterization of Gaussian particles**  
  [page](https://research.nvidia.com/labs/toronto-ai/3DGRT/) · [code](https://github.com/nv-tlabs/3dgrut)
- **NVlabs/svraster: [CVPR 2025] Sparse Voxels Rasterization: Real-time High-fidelity Radiance Field Rend** — arXiv:2412.04459  
  [paper](https://arxiv.org/abs/2412.04459) · [page](https://svraster.github.io/) · [code](https://github.com/NVlabs/svraster)
- **LangSplat: 3D Language Gaussian Splatting** — arXiv:2312.16084  
  [paper](https://arxiv.org/abs/2312.16084) · [page](https://langsplat.github.io/ https://minghanqin.github.io/) · [code](https://github.com/minghanqin/LangSplat)
- **SceneSplat: Gaussian Splatting-based Scene Understanding with Vision-Language Pretraining** — arXiv:2503.18052  
  [paper](https://arxiv.org/abs/2503.18052) · [page](https://unique1i.github.io/SceneSplat_webpage/ https://unique1i.github.io/) · [code](https://github.com/unique1i/scenesplat https://github.com/unique1i/SceneSplat)
- **SEELE: A Unified Acceleration Framework for Real-Time Gaussian Splatting on Mobile Devices** — arXiv:2503.05168  
  [paper](https://arxiv.org/abs/2503.05168) · [page](https://seele-project.netlify.app/) · [code](https://github.com/SJTU-MVCLab/SeeLe)
- **Gaussian Point Splatting**  
  [page](https://jorisar.nl/gaussian_point_splatting/) · [code](https://github.com/JorisAR/gaussian-point-splatting)
- **Anttwo/Surflo: [NeurIPS 2026 - Oral] Official implementation of Surflo: Consistent 3D Surface Flow Mo** — arXiv:2606.13644  
  [paper](https://arxiv.org/abs/2606.13644) · [page](https://anttwo.github.io/surflo/ https://anttwo.github.io/) · [code](https://github.com/Anttwo/Surflo https://github.com/Anttwo/MILo)
- **Anttwo/MAtCha: [CVPR 2025 - Spotlight] Official PyTorch implementation of MAtCha Gaussians: Atlas of**  
  [page](https://anttwo.github.io/matcha/ https://anttwo.github.io/) · [code](https://github.com/Anttwo/MAtCha https://github.com/Anttwo/SuGaR)
- **PRBonn/PINGS: 📌 PINGS: Gaussian Splatting Meets Distance Fields within a Point-Based Implicit Neural** — arXiv:2502.05752  
  [paper](https://arxiv.org/abs/2502.05752) · [code](https://github.com/PRBonn/PINGS)
- **hugoycj/2.5d-gaussian-splatting: an unofficial 2DGS implementation based on GauStudio**  
  [page](https://turandai.github.io/projects/gaussian_surfels/ https://turandai.github.io/projects/gaussian_surfels/index.html) · [code](https://github.com/hugoycj/2.5d-gaussian-splatting https://github.com/turandai/gaussian_surfels)
- **Difix3D+: Improving 3D Reconstructions with Single-Step Diffusion Models** — arXiv:2503.01774  
  [paper](https://arxiv.org/abs/2503.01774) · [page](https://research.nvidia.com/labs/toronto-ai/difix3d/ https://research.nvidia.com/labs/toronto-ai/difix3d) · [code](https://github.com/nv-tlabs/Difix3D)
- **Fillerbuster: Unified Generative Scene Completion Model for Casual Captures** — arXiv:2502.05175  
  [paper](https://arxiv.org/abs/2502.05175) · [page](https://ethanweber.me/fillerbuster/) · [code](https://github.com/facebookresearch/fillerbuster)
- **AuraFusion360: Augmented Unseen Region Alignment for Reference-based 360° Unbounded Scene Inpainting** — arXiv:2502.05176  
  [paper](https://arxiv.org/abs/2502.05176) · [page](https://kkennethwu.github.io/aurafusion360/ https://kkennethwu.github.io/) · [code](https://github.com/kkennethwu/AuraFusion360_official https://github.com/kkennethwu/pdm-f23)
- **Feature 3DGS: Supercharging 3D Gaussian Splatting to Enable Distilled Feature Fields** — arXiv:2312.03203  
  [paper](https://arxiv.org/abs/2312.03203) · [code](https://github.com/ShijieZhou-UCLA/feature-3dgs)
- **LightGaussian: Unbounded 3D Gaussian Compression with 15x Reduction and 200+ FPS** — arXiv:2311.17245  
  [paper](https://arxiv.org/abs/2311.17245) · [page](https://lightgaussian.github.io/) · [code](https://github.com/VITA-Group/LightGaussian)
- **Gaussian Surfels** — arXiv:2503.04079  
  [paper](https://arxiv.org/abs/2503.04079)
- **SuGaR: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction**  
- **Deformable Beta Splatting** — arXiv:2501.18630  
  [paper](https://arxiv.org/abs/2501.18630) · [page](https://rongliu-leo.github.io/beta-splatting https://rongliu-leo.github.io/beta-splatting/) · [code](https://github.com/RongLiu-Leo/beta-splatting https://github.com/RongLiu-Leo/arxsite)
- **3D Gaussians Plugin for Unreal Engine 5**  
  [page](https://neuralradiancefields.io/3d-gaussians-plugin-for-unreal-engine-5/)
- **NeRFshop: Interactive Editing of Neural Radiance Fields**  
  [page](https://repo-sam.inria.fr/fungraph/nerfshop/) · [code](https://github.com/graphdeco-inria/nerfshop)
- **On-the-fly Reconstruction for Large-Scale Novel View Synthesis from Unposed Images**  
  [page](https://repo-sam.inria.fr/nerphys/on-the-fly-nvs/)

<a id="4"></a>
## 4. NeRF and neural fields (the lineage 3DGS replaced; still the background)

- **NeRF: Neural Radiance Fields** — arXiv:2003.08934  
  [paper](https://arxiv.org/abs/2003.08934) · [page](https://www.matthewtancik.com/nerf) · [code](https://github.com/bmild/nerf)
- **Zip-NeRF: Anti-Aliased Grid-Based Neural Radiance Fields** — arXiv:2304.06706  
  [paper](https://arxiv.org/abs/2304.06706) · [page](https://jonbarron.info/zipnerf/) · [code](https://github.com/SuLvXiangXin/zipnerf-pytorch)
- **Compressing Volumetric Radiance Fields to 1 MB** — arXiv:2211.16386  
  [paper](https://arxiv.org/abs/2211.16386)
- **NVlabs/instant-ngp: Instant neural graphics primitives: lightning fast NeRF and more**  
  [page](https://nvlabs.github.io/instant-ngp https://nvlabs.github.io/instant-ngp/assets/mueller2022instant.pdf) · [code](https://github.com/NVlabs/instant-ngp)
- **NVlabs/neuralangelo: Official implementation of "Neuralangelo: High-Fidelity Neural Surface Reconstru** — arXiv:2306.03092  
  [paper](https://arxiv.org/abs/2306.03092) · [page](https://research.nvidia.com/labs/dir/neuralangelo/) · [code](https://github.com/NVlabs/neuralangelo)
- **nerfstudio-project/nerfstudio: A collaboration friendly studio for NeRFs**  
  [page](https://docs.nerf.studio) · [code](https://github.com/nerfstudio-project/nerfstudio)
- **CamP: Camera Preconditioning for Neural Radiance Fields** — arXiv:2308.10902  
  [paper](https://arxiv.org/abs/2308.10902) · [page](https://camp-nerf.github.io/) · [code](https://github.com/jonbarron/camp_zipnerf)
- **Ref-NeRF: Structured View-Dependent Appearance for Neural Radiance Fields** — arXiv:2112.03907  
  [paper](https://arxiv.org/abs/2112.03907) · [page](https://dorverbin.github.io/refnerf/)
- **MobileNeRF** — arXiv:2208.00277  
  [paper](https://arxiv.org/abs/2208.00277) · [page](https://mobile-nerf.github.io/) · [code](https://github.com/google-research/jax3d)
- **F2-NeRF**  
  [page](https://totoro97.github.io/projects/f2-nerf/) · [code](https://github.com/totoro97/f2-nerf)
- **VITA-Group/SinNeRF: [ECCV 2022] "SinNeRF: Training Neural Radiance Fields on Complex Scenes from a Si** — arXiv:2204.00928  
  [paper](https://arxiv.org/abs/2204.00928) · [page](https://vita-group.github.io/SinNeRF/) · [code](https://github.com/VITA-Group/SinNeRF)
- **autonomousvision/murf: [CVPR'24] MuRF: Multi-Baseline Radiance Fields** — arXiv:2312.04565  
  [paper](https://arxiv.org/abs/2312.04565) · [page](https://haofeixu.github.io/murf/) · [code](https://github.com/autonomousvision/murf)
- **facebookresearch/robust-dynrf: An algorithm for reconstructing the radiance field of a dynamic scene** — arXiv:2301.02239  
  [paper](https://arxiv.org/abs/2301.02239) · [page](https://robust-dynrf.github.io/) · [code](https://github.com/facebookresearch/robust-dynrf)
- **Adaptive Shells for Efficient Neural Radiance Field Rendering** — arXiv:2311.10091  
  [paper](https://arxiv.org/abs/2311.10091) · [page](https://research.nvidia.com/labs/toronto-ai/adaptive-shells/) · [code](https://github.com/nv-tlabs/adaptive-shells-website)
- **Neural Kernel Surface Reconstruction** — arXiv:2305.19590  
  [paper](https://arxiv.org/abs/2305.19590) · [page](https://research.nvidia.com/labs/toronto-ai/NKSR/ https://research.nvidia.com/labs/toronto-ai/NKSR) · [code](https://github.com/nv-tlabs/nksr)
- **fabiotosi92/NeRF-Supervised-Deep-Stereo: A novel paradigm for collecting and generating stereo traini**  
  [page](https://nerfstereo.github.io/ https://fabiotosi92.github.io/) · [code](https://github.com/fabiotosi92/NeRF-Supervised-Deep-Stereo https://github.com/fabiotosi92/ZipDepth)
- **Neural Volumes** — arXiv:2009.07823  
  [paper](https://arxiv.org/abs/2009.07823) · [page](https://stephenlombardi.github.io/projects/neuralvolumes/)
- **google-research/merf at master · google-research/google-research**  
  [page](https://research.google) · [code](https://github.com/google-research/google-research)
- **lfranke/TRIPS**  
  [page](https://radiancefields.com/trips-trilinear-point-splatting-for-real-time-radiance-field-rendering/ https://lfranke.github.io/trips/) · [code](https://github.com/lfranke/trips)
- **Memory-Efficient Radiance Fields (MERF) Code now Available**  
  [page](https://neuralradiancefields.io/memory-efficient-radiance-fields-merf-code-now-available/)
- **Neural Radiance Fields from Sparse and Noisy Poses (8 min video)**  
- **RobustNerf: Ignoring Distractors with Robust Losses (CVPR 2023)** — arXiv:2302.00833  
  [paper](https://arxiv.org/abs/2302.00833)
- **PhysGaussian gives 3D Gaussian Splatting Physics**  
  [page](https://neuralradiancefields.io/physgaussian-gives-3d-gaussian-splatting-physics/)

<a id="5"></a>
## 5. Dynamic scenes and 4D (4D Gaussians, scene flow, 4D reconstruction)

- **1000+ FPS 4D Gaussian Splatting for Dynamic Scene Rendering** — arXiv:2310.10642  
  [paper](https://arxiv.org/abs/2310.10642) · [page](https://4dgs-1k.github.io https://logosintelligencelab.github.io/4d-gaussian-splatting/) · [code](https://github.com/fudan-zvg/4d-gaussian-splatting https://github.com/LogosIntelligenceLab/4d-gaussian-splatting)
- **7DGS** — arXiv:2503.07946  
  [paper](https://arxiv.org/abs/2503.07946) · [page](https://gaozhongpai.github.io/7dgs/)
- **Geo4D: Leveraging Video Generators for Geometric 4D Scene Reconstruction** — arXiv:2504.07961  
  [paper](https://arxiv.org/abs/2504.07961) · [page](https://geo4d.github.io/ https://geo4d.github.io) · [code](https://github.com/jzr99/Geo4D)
- **4D Reconstruction Research**  
  [page](https://davidyao99.github.io/uni4d/) · [code](https://github.com/Davidyao99/uni4d)
- **MoDGS: Dynamic Gaussian Splatting from Casually-captured Monocular Videos** — arXiv:2406.00434  
  [paper](https://arxiv.org/abs/2406.00434) · [page](https://modgs.github.io/) · [code](https://github.com/MobiusLqm/MoDGS)
- **Flow4R: Unifying 4D Reconstruction and Tracking with Scene Flow** — arXiv:2602.14021  
  [paper](https://arxiv.org/abs/2602.14021) · [page](https://shenhanqian.github.io/flow4r)
- **St4RTrack: Simultaneous 4D Reconstruction and Tracking in the World** — arXiv:2504.13152  
  [paper](https://arxiv.org/abs/2504.13152) · [page](https://st4rtrack.github.io) · [code](https://github.com/HavenFeng/St4RTrack)
- **Time of the Flight of the Gaussians: Optimizing Depth Indirectly in Dynamic Radiance Fields (CVPR 2025)** — arXiv:2505.05356  
  [paper](https://arxiv.org/abs/2505.05356) · [page](https://visual.cs.brown.edu/projects/gftorf-webpage/)
- **GIFStream: 4D Gaussian-based Immersive Video with Feature Stream** — arXiv:2505.07539  
  [paper](https://arxiv.org/abs/2505.07539) · [page](https://xdimlab.github.io/GIFStream/) · [code](https://github.com/XDimLab/GIFStream)
- **jiawei-ren/dreamgaussian4d: [arXiv 2023] DreamGaussian4D: Generative 4D Gaussian Splatting** — arXiv:2312.17142  
  [paper](https://arxiv.org/abs/2312.17142) · [page](https://jiawei-ren.github.io/projects/dreamgaussian4d/) · [code](https://github.com/jiawei-ren/dreamgaussian4d)
- **ant-research/4DAnyone: [SIGGRAPH Asia 2026] 4DAnyone: Create Anyone in 4D from a Casual Monocular Vid** — arXiv:2608.20335  
  [paper](https://arxiv.org/abs/2608.20335) · [page](https://4danyone.github.io/) · [code](https://github.com/ant-research/4DAnyone)
- **GSTAR: Gaussian Surface Tracking and Reconstruction**  
- **Control4D Project Page**  
- **NSS Benchmark**  
  [page](http://nothing-stands-still.com/)
- **GaussianGPT: Towards Autoregressive 3D Gaussian Scene Generation** — arXiv:2603.26661  
  [paper](https://arxiv.org/abs/2603.26661) · [page](https://nicolasvonluetzow.github.io/GaussianGPT/) · [code](https://github.com/nicolasvonluetzow/gaussiangpt)
- **Animatable Gaussians: Learning Pose-dependent Gaussian Maps for High-fidelity Human Avatar Modeling** — arXiv:2311.16096  
  [paper](https://arxiv.org/abs/2311.16096)
- **HiFi4G: High-Fidelity Human Performance Rendering via Compact Gaussian Splatting**  
- **SplatArmor: Articulated Gaussian splatting for animatable humans from monocular RGB videos** — arXiv:2311.10812  
  [paper](https://arxiv.org/abs/2311.10812) · [page](https://jenaroh.it/splatarmor/) · [code](https://github.com/rohitrango/splatarmor)
- **Visualito - webxr.cz, Gaussian Splatting, AR/VR, 4D GS, Panorama 4D GS, Thermal 4D GS**  
  [page](https://webxr.cz/xr.html)

<a id="6"></a>
## 6. Human body, pose and mesh recovery (HMR family, SMPL, egocentric human)

- **4DH**  
  [page](https://shubham-goel.github.io/4dhumans/) · [code](https://github.com/shubham-goel/4D-Humans)
- **facebookresearch/sam-3d-body: The repository provides code for running inference with the SAM 3D Body**  
  [code](https://github.com/facebookresearch/sam-3d-body)
- **yufu-wang/tram: TRAM: Global Trajectory and Motion of 3D Humans from in-the-wild Videos** — arXiv:2403.17346  
  [paper](https://arxiv.org/abs/2403.17346) · [page](https://yufu-wang.github.io) · [code](https://github.com/yufu-wang/tram https://github.com/yufu-wang/PromptHMR)
- **Unable to run on Cloud GPU · Issue #30 · vye16/slahmr**  
  [page](https://vye16.github.io/slahmr/) · [code](https://github.com/vye16/slahmr)
- **ScoreHMR**  
  [page](https://statho.github.io/ScoreHMR/) · [code](https://github.com/statho/ScoreHMR)
- **IDEA-Research/DWPose: "Effective Whole-body Pose Estimation with Two-stages Distillation" (ICCV 2023,** — arXiv:2307.15880  
  [paper](https://arxiv.org/abs/2307.15880) · [code](https://github.com/IDEA-Research/DWPose https://github.com/idea-research/dwpose)
- **IDEA-Research/OSX: [CVPR 2023] Official implementation of the paper "One-Stage 3D Whole-Body Mesh Rec** — arXiv:2303.16160  
  [paper](https://arxiv.org/abs/2303.16160) · [page](https://osx-ubody.github.io/) · [code](https://github.com/IDEA-Research/OSX)
- **Walter0807/MotionBERT: [ICCV 2023] PyTorch Implementation of "MotionBERT: A Unified Perspective on Le**  
  [page](https://motionbert.github.io/) · [code](https://github.com/Walter0807/MotionBERT)
- **YuliangXiu/ECON: [CVPR'23, Highlight] ECON: Explicit Clothed humans Optimized via Normal integration** — arXiv:2212.07422  
  [paper](https://arxiv.org/abs/2212.07422) · [page](https://xiuyuliang.cn/econ) · [code](https://github.com/YuliangXiu/ECON)
- **Human as Points: Explicit Point-based 3D Human Reconstruction from Single-view RGB Images** — arXiv:2311.02892  
  [paper](https://arxiv.org/abs/2311.02892)
- **apple-aiml-research/ml-comotion**  
  [code](https://github.com/apple/ml-comotion)
- **brjathu/LART: Code repository for the paper "On the Benefits of 3D Pose and Tracking for Human Action** — arXiv:2304.01199  
  [paper](https://arxiv.org/abs/2304.01199) · [code](https://github.com/brjathu/LART)
- **facebookresearch/AGRoL: Code release for "Avatars Grow Legs Generating Smooth Human Motion from Spars**  
  [code](https://github.com/facebookresearch/AGRoL)
- **climbingdaily/SLOPER4D: SLOPER4D: A Scene-Aware Dataset for Global 4D Human Pose Estimation in Urban**  
  [page](http://www.lidarhumanmotion.net/sloper4d/ https://climbingdaily.github.io/) · [code](https://github.com/climbingdaily/SLOPER4D)
- **genforce/JOSH: [ICLR 2026] Official Implementation for Paper "Joint Optimization for 4D Human-Scene R** — arXiv:2501.02158  
  [paper](https://arxiv.org/abs/2501.02158) · [page](https://vail-ucla.github.io/JOSH/) · [code](https://github.com/genforce/JOSH)
- **EgoAllo**  
  [page](https://egoallo.github.io/) · [code](https://github.com/brentyi/egoallo)
- **Predicting 4D Hand Trajectory from Monocular Videos** — arXiv:2501.08329  
  [paper](https://arxiv.org/abs/2501.08329) · [page](https://judyye.github.io/haptic-www/) · [code](https://github.com/judyye/haptic)
- **Ego-Exo4D-HM** ✓ — arXiv:2609.30187  
  [paper](https://arxiv.org/abs/2609.30187) · [page](https://abhiram824.github.io/egoexo4d_human_meshes/) · [code](https://github.com/Abhiram824/egoexo4d_human_meshes)
- **EventEgoHands+: Event-based Egocentric 3D Hand Mesh Reconstruction with Real Dataset** ✓ — arXiv:2609.17189  
  [paper](https://arxiv.org/abs/2609.17189) · [page](https://ryhara.github.io/EventEgoHandsV2/ https://ryhara.github.io/) · [code](https://github.com/ryhara/EventEgoHandsV2 https://github.com/ryhara/hand_visibility_detector)
- **HUMOTO Project Page**  
  [page](https://jiaxin-lu.github.io/humoto/) · [code](https://github.com/Jiaxin-Lu/humoto)
- **VolHuMe Dataset** — arXiv:2606.23062  
  [paper](https://arxiv.org/abs/2606.23062) · [page](Https://giuli13.github.io/volhume-website)
- **https://mirapurkrabek.github.io/RePoGen-paper/https://mirapurkrabek.github.io/RePoGen-paper/**  
- **KevinyWu/hug: Official Implementation of "Human Universal Grasping".** — arXiv:2606.17054  
  [paper](https://arxiv.org/abs/2606.17054) · [page](https://grasping.io/ https://junhong-3dv.github.io/s2m2-project/) · [code](https://github.com/KevinyWu/hug https://github.com/junhong-3dv/s2m2)
- **EgoExo4D Body Pose Challenge – Codabench**  
  [page](https://www.codabench.org/competitions/15376/#/pages-tab) · [code](https://github.com/codalab/codabench)
- **SMPL**  
  [page](https://download.is.tue.mpg.de/download.php?domain=smpl&sfile=SMPL_python_v.1.0.0.zip)
- **BEDLAM: A Synthetic Dataset of Bodies Exhibiting Detailed Lifelike Animated Motion (CVPR 2023)** — arXiv:2306.16940  
  [paper](https://arxiv.org/abs/2306.16940) · [page](https://bedlam.is.tuebingen.mpg.de/) · [code](https://github.com/pixelite1201/BEDLAM)
- **HUMANISE: Language-conditioned Human Motion Generation in 3D Scenes (NeurIPS 2022)** — arXiv:2210.09729  
  [paper](https://arxiv.org/abs/2210.09729)
- **Mocap Everyone Everywhere: Lightweight Motion Capture With Smartwatches and a Head-Mounted Camera** — arXiv:2401.00847  
  [paper](https://arxiv.org/abs/2401.00847)
- **Vid2Avatar: 3D Avatar Reconstruction from Videos in the Wild via Self-supervised Scene Decomposition** — arXiv:2302.11566  
  [paper](https://arxiv.org/abs/2302.11566) · [page](https://moygcc.github.io/vid2avatar/ https://skype-line.github.io/projects/X-Avatar/) · [code](https://github.com/MoyGcc/vid2avatar https://github.com/Skype-line/X-Avatar)
- **NeuMan: Neural Human Radiance Field from a Single Video** — arXiv:2203.12575  
  [paper](https://arxiv.org/abs/2203.12575) · [code](https://github.com/apple/ml-neuman)
- **DreamActor-M1: Holistic, Expressive and Robust Human Image Animation with Hybrid Guidance** — arXiv:2504.01724  
  [paper](https://arxiv.org/abs/2504.01724) · [page](https://grisoon.github.io/DreamActor-M1/)
- **Move AI - Markerless Motion Capture & 3D Animation**  
  [page](https://www.move.ai/)
- **yztang4/HaP**  
  [code](https://github.com/yztang4/HaP)
- **SLOPER4D: A Scene-Aware Dataset for Global 4D Human Pose Estimation in Urban Environments** ✓ — arXiv:2303.09095  
  [paper](https://arxiv.org/abs/2303.09095) · [code](https://github.com/climbingdaily/SLOPER4D)

<a id="7"></a>
## 7. Ego-exo, robot-learning-from-human-video, and datasets

- **Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives** ✓ — arXiv:2311.18259  
  [paper](https://arxiv.org/abs/2311.18259) · [page](https://ego-exo4d-data.org/)
- **ENIGMA360: A Multi-view Dataset for Human Behavior Understanding in Industrial Scenarios** ✓ — arXiv:2603.09741  
  [paper](https://arxiv.org/abs/2603.09741) · [page](https://fpv-iplab.github.io/ENIGMA-360/) · [code](https://github.com/fpv-iplab/ENIGMA-360)
- **LEGO: A Lifting-Free Approach for Exocentric-to-Egocentric Video Generation** ✓ — arXiv:2610.12442  
  [paper](https://arxiv.org/abs/2610.12442) · [page](https://suhwan-cho.github.io/LEGO https://suhwan-cho.github.io/LEGO/) · [code](https://github.com/suhwan-cho/LEGO)
- **EgoVerse** ✓ — arXiv:2604.07607  
  [paper](https://arxiv.org/abs/2604.07607) · [page](https://egoverse.ai https://egoverse.ai/) · [code](https://github.com/GaTech-RL2/EgoVerse)
- **Do as I Do: Dexterous Manipulation Data from Everyday Human Videos** ✓ — arXiv:2606.19333  
  [paper](https://arxiv.org/abs/2606.19333) · [page](https://do-as-i-do.com/)
- **Ropedia W0: Scaling Loco-Manipulation World Models across Embodiments with Human Experience** ✓ — arXiv:2610.26855  
  [paper](https://arxiv.org/abs/2610.26855) · [page](https://ropedia.github.io/ropedia-w0/) · [code](https://github.com/Ropedia/ropedia-w0)
- **CLIFT: Turning Gemini Robotics On-Device into Humanoid Specialists via Non-Invasive Closed-Loop Iterative Fine** ✓ — arXiv:2607.29172  
  [paper](https://arxiv.org/abs/2607.29172) · [page](https://thomaschen98.github.io/clift/)
- **UMI on Legs: Making Manipulation Policies Mobile with a Manipulation-Centric Whole-body Controller** — arXiv:2407.10353  
  [paper](https://arxiv.org/abs/2407.10353) · [page](https://umi-on-legs.github.io) · [code](https://github.com/real-stanford/umi-on-legs)
- **Agentic World Action Models** — arXiv:2610.30136  
  [paper](https://arxiv.org/abs/2610.30136) · [page](https://agentic-wam.github.io/) · [code](https://github.com/ZhuoyangLiu2005/agentic-wam)
- **FlowWAM — Optical Flow as a Unified Action Representation for World Action Models** — arXiv:2607.13017  
  [paper](https://arxiv.org/abs/2607.13017) · [page](https://flow-wam.github.io/) · [code](https://github.com/YixiangChen515/FlowWAM)
- **RoboSimStudio** — arXiv:2610.18835  
  [paper](https://arxiv.org/abs/2610.18835) · [page](https://robosimstudio.github.io/) · [code](https://github.com/robosimstudio/robosimstudio)
- **Real2Sem2Real**  
  [page](https://real2sem2real.github.io)
- **LA-Pose: Latent Action Pretraining Meets Pose Estimation** — arXiv:2604.27448  
  [paper](https://arxiv.org/abs/2604.27448) · [page](https://la-pose.github.io/)
- **TacClaw-Infinity — Vision-Tactile-Language-Action Dataset** — arXiv:2610.20320  
  [paper](https://arxiv.org/abs/2610.20320)
- **https://faculty.cc.gatech.edu/~danfei/corl24.pdf**  
- **Aria Digital Twin Dataset** — arXiv:2306.06362  
  [paper](https://arxiv.org/abs/2306.06362) · [page](https://www.projectaria.com/datasets/adt/)
- **apple-aiml-research/ARKitScenes: This repo accompanies the research paper, ARKitScenes - A Diverse Re**  
  [code](https://github.com/apple/ARKitScenes)
- **ScanNet++**  
  [page](https://cy94.github.io/scannetpp/)
- **ScanNet/ScanNet**  
  [page](http://www.scan-net.org/) · [code](https://github.com/ScanNet/ScanNet)
- **DL3DV-10K: A Large-Scale Scene Dataset for Deep Learning-based 3D Vision** — arXiv:2312.16256  
  [paper](https://arxiv.org/abs/2312.16256) · [page](https://dl3dv-10k.github.io/DL3DV-10K/ https://htmlpreview.github.io/?https://github.com/DL3DV-10K/Dataset/blob/main/visualize/index.html) · [code](https://github.com/DL3DV-10K/Dataset https://github.com/htmlpreview/htmlpreview.github.com)
- **RealEstate10K: A Large Dataset of Camera Trajectories from Video Clips**  
  [page](https://google.github.io/realestate10k/)
- **OmniObject3D: Large-Vocabulary 3D Object Dataset for Realistic  Perception, Reconstruction and Generation** — arXiv:2301.07525  
  [paper](https://arxiv.org/abs/2301.07525) · [page](https://omniobject3d.github.io/) · [code](https://github.com/omniobject3d/omniobject3d https://github.com/omniobject3d/OmniObject3D)
- **CO3D Dataset**  
  [page](https://ai.meta.com/datasets/CO3D-dataset/)
- **MegaDepth: Learning Single-View Depth Prediction from Internet Photos** — arXiv:1804.00607  
  [paper](https://arxiv.org/abs/1804.00607) · [page](https://www.cs.cornell.edu/projects/megadepth/) · [code](https://github.com/lixx2938/MegaDepth)
- **DIODE: A Dense Indoor and Outdoor DEpth Dataset** — arXiv:1908.00463  
  [paper](https://arxiv.org/abs/1908.00463) · [page](https://diode-dataset.org/) · [code](https://github.com/diode-dataset/diode-devkit)
- **YoYo000/BlendedMVS: BlendedMVS: A Large-scale Dataset for Generalized Multi-view Stereo Networks** — arXiv:1911.10127  
  [paper](https://arxiv.org/abs/1911.10127) · [code](https://github.com/YoYo000/BlendedMVS)
- **TartanAir: A Dataset to Push the Limits of Visual SLAM** — arXiv:2003.14338  
  [paper](https://arxiv.org/abs/2003.14338) · [page](https://theairlab.org/tartanair-dataset/) · [code](https://github.com/castacks/tartanair_tools)
- **About – Waymo Open Dataset**  
  [page](https://waymo.com/open/)
- **Benchmark Results - E3D-Bench**  
  [page](https://e3dbench.github.io/) · [code](https://github.com/VITA-Group/E3D-Bench)
- **NSS Benchmark**  
  [page](http://nothing-stands-still.com/)
- **Embodied Intelligence from Human Experience - Simar Kareer**  
- **Stanford Robotics Seminar ENGR319 | Spring 2026 | Robot Learning from**  
- **Danfei Xu**  
  [page](https://faculty.cc.gatech.edu/~danfei/)
- **Ruohan Zhang**  
  [page](https://ruohanzhang.com/)
- **climbingdaily/SLOPER4D: SLOPER4D: A Scene-Aware Dataset for Global 4D Human Pose Estimation in Urban**  
  [page](http://www.lidarhumanmotion.net/sloper4d/ https://climbingdaily.github.io/) · [code](https://github.com/climbingdaily/SLOPER4D)
- **MV-UMI: A Scalable Multi-View Interface for Cross-Embodiment Learning** ✓ — arXiv:2509.18757  
  [paper](https://arxiv.org/abs/2509.18757) · [page](https://mv-umi.github.io)
- **EgoMimic: Scaling Imitation Learning via Egocentric Video** ✓ — arXiv:2410.24221  
  [paper](https://arxiv.org/abs/2410.24221) · [page](https://egomimic.github.io/)
- **EgoScale: Scaling Dexterous Manipulation with Diverse Egocentric Human Data** ✓ — arXiv:2602.16710  
  [paper](https://arxiv.org/abs/2602.16710) · [page](https://research.nvidia.com/labs/gear/egoscale/)
- **Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots** ✓ — arXiv:2402.10329  
  [paper](https://arxiv.org/abs/2402.10329) · [page](https://umi-gripper.github.io) · [code](https://github.com/real-stanford/universal_manipulation_interface)
- **DexWild: Dexterous Human Interactions for In-the-Wild Robot Policies** ✓ — arXiv:2505.07813  
  [paper](https://arxiv.org/abs/2505.07813) · [page](https://dexwild.github.io)
- **Egocentric-100K** ✓  
  [page](https://huggingface.co/datasets/builddotai/Egocentric-100K)
- **EgoDex: Learning Dexterous Manipulation from Large-Scale Egocentric Video** ✓ — arXiv:2505.11709  
  [paper](https://arxiv.org/abs/2505.11709) · [code](https://github.com/apple/ml-egodex)
- **Humanoid Policy ~ Human Policy (PH2D dataset, HAT policy)** ✓ — arXiv:2503.13441  
  [paper](https://arxiv.org/abs/2503.13441) · [page](https://human-as-robot.github.io/)
- **HumanScale: Egocentric Human Video Can Outperform Real-Robot Data for Embodied Pretraining** ✓ — arXiv:2606.20521  
  [paper](https://arxiv.org/abs/2606.20521) · [code](https://github.com/DAGroup-PKU/HumanNet/)
- **ABot-M0.5: Unified Mobility-and-Manipulation World Action Model** ✓ — arXiv:2607.00678  
  [paper](https://arxiv.org/abs/2607.00678) · [code](https://github.com/amap-cvlab/ABot-Manipulation)
- **Pushing the Limits of Cross-Embodiment Learning for Manipulation and Navigation (Appendix IX-E, Table VII)** ✓ — arXiv:2402.19432  
  [paper](https://arxiv.org/abs/2402.19432)
- **EyeRobot 2.0: Active Gaze for Precise Manipulation without Wrist Cameras** ✓ — arXiv:2610.03710  
  [paper](https://arxiv.org/abs/2610.03710)
- **TAVIS: A Benchmark for Egocentric Active Vision and Anticipatory Gaze in Imitation Learning** ✓ — arXiv:2605.07943  
  [paper](https://arxiv.org/abs/2605.07943)
- **Ego4D: Around the World in 3,000 Hours of Egocentric Video** ✓ — arXiv:2110.07058  
  [paper](https://arxiv.org/abs/2110.07058) · [page](https://ego4d-data.org)

<a id="8"></a>
## 8. Robot policies, sim-to-real, evaluation and benchmarks

- **SuperMimic: Scaling Humanoid Whole-Body Control with One Differentiable World Model (post 21/10/2026)** ✓ — arXiv:2610.28480  
  [paper](https://arxiv.org/abs/2610.28480) · [page](https://supermimic.github.io)
- **ACT: Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware** ✓ — arXiv:2304.13705  
  [paper](https://arxiv.org/abs/2304.13705) · [page](https://tonyzhaozh.github.io/aloha/)
- **Diffusion Policy: Visuomotor Policy Learning via Action Diffusion** ✓ — arXiv:2303.04137  
  [paper](https://arxiv.org/abs/2303.04137) · [page](https://diffusion-policy.cs.columbia.edu/)
- **OpenVLA: An Open-Source Vision-Language-Action Model** ✓ — arXiv:2406.09246  
  [paper](https://arxiv.org/abs/2406.09246) · [page](https://openvla.github.io/)
- **π0.5: a Vision-Language-Action Model with Open-World Generalization** ✓ — arXiv:2504.16054  
  [paper](https://arxiv.org/abs/2504.16054) · [page](https://www.pi.website/blog/pi05)
- **LocoFormer: Generalist Locomotion via Long-context Adaptation** ✓ — arXiv:2509.23745  
  [paper](https://arxiv.org/abs/2509.23745) · [page](https://generalist-locomotion.github.io/)
- **TRANSIC: Sim-to-Real Policy Transfer by Learning from Online Correction** ✓ — arXiv:2405.10315  
  [paper](https://arxiv.org/abs/2405.10315) · [page](https://transic-robot.github.io/)
- **RoboRender: Robot-Oriented Video Generation for Visual Sim-to-Real Transfer** ✓ — arXiv:2610.09254  
  [paper](https://arxiv.org/abs/2610.09254)
- **Real-to-Sim Robot Policy Evaluation with Gaussian Splatting Simulation of Soft-Body Interactions** ✓ — arXiv:2511.04665  
  [paper](https://arxiv.org/abs/2511.04665) · [page](https://real2sim-eval.github.io/)
- **RoboDojo: A Unified Sim-and-Real Benchmark for Comprehensive Evaluation of Generalist Robot Manipulation Policies** ✓ — arXiv:2607.04434  
  [paper](https://arxiv.org/abs/2607.04434) · [page](https://robodojo-benchmark.com/)
- **Open X-Embodiment: Robotic Learning Datasets and RT-X Models** ✓ — arXiv:2310.08864  
  [paper](https://arxiv.org/abs/2310.08864) · [page](https://robotics-transformer-x.github.io)
- **BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation** ✓ — arXiv:2403.09227  
  [paper](https://arxiv.org/abs/2403.09227) · [page](https://behavior.stanford.edu)
- **Emergent Dexterity via Diverse Resets and Large-Scale Reinforcement Learning** ✓ — arXiv:2603.15789  
  [paper](https://arxiv.org/abs/2603.15789)

<a id="9"></a>
## 9. Auto-labeling: segmentation, tracking, 3D instance / open-vocabulary understanding

- **LabelAny3D: Label Any Object 3D in the Wild** — arXiv:2601.01676  
  [paper](https://arxiv.org/abs/2601.01676) · [page](https://uva-computer-vision-lab.github.io/LabelAny3D/) · [code](https://github.com/UVA-Computer-Vision-Lab/LabelAny3D https://github.com/UVA-Computer-Vision-Lab/3d_annotator)
- **FlorisE/neural-labeling** — arXiv:2309.11966  
  [paper](https://arxiv.org/abs/2309.11966) · [page](https://florise.github.io/neural_labeling_web/) · [code](https://github.com/FlorisE/neural-labeling)
- **gaomingqi/Track-Anything: Track-Anything is a flexible and interactive tool for video object tracking**  
  [code](https://github.com/gaomingqi/Track-Anything)
- **hkchengrex/Tracking-Anything-with-DEVA: [ICCV 2023] Tracking Anything with Decoupled Video Segmentati** — arXiv:2309.03903  
  [paper](https://arxiv.org/abs/2309.03903) · [page](https://hkchengrex.com/Tracking-Anything-with-DEVA/ https://hkchengrex.github.io/) · [code](https://github.com/hkchengrex/Tracking-Anything-with-DEVA https://github.com/hkchengrex/C2OT)
- **jiawen-zhu/HQTrack: Tracking Anything in High Quality** — arXiv:2307.13974  
  [paper](https://arxiv.org/abs/2307.13974) · [code](https://github.com/jiawen-zhu/HQTrack https://github.com/jiawen-zhu/hqtrack)
- **facebookresearch/co-tracker: CoTracker is a model for tracking any point (pixel) on a video.**  
  [page](https://co-tracker.github.io/) · [code](https://github.com/facebookresearch/co-tracker)
- **Dense Optical Tracking: Connecting the Dots** — arXiv:2312.00786  
  [paper](https://arxiv.org/abs/2312.00786) · [page](https://16lemoing.github.io/dot/) · [code](https://github.com/16lemoing/dot)
- **AllTracker: Efficient Dense Point Tracking at High Resolution** — arXiv:2506.07310  
  [paper](https://arxiv.org/abs/2506.07310) · [page](https://alltracker.github.io https://alltracker.github.io/) · [code](https://github.com/aharley/alltracker)
- **Tracking Everything Everywhere All at Once** — arXiv:2306.05422  
  [paper](https://arxiv.org/abs/2306.05422) · [page](https://omnimotion.github.io/) · [code](https://github.com/qianqianwang68/omnimotion)
- **TAPIP3D: Tracking Any Point in Persistent 3D Geometry** — arXiv:2504.14717  
  [paper](https://arxiv.org/abs/2504.14717) · [page](https://tapip3d.github.io/) · [code](https://github.com/zbw001/TAPIP3D)
- **TrackEverything: Long Horizon Dense Tracking via De-Duplicating 3D Scene Representations** — arXiv:2609.30222  
  [paper](https://arxiv.org/abs/2609.30222) · [page](https://trackeverything.github.io/) · [code](https://github.com/ayushjain1144/trackeverything)
- **TAO-Amodal: A Benchmark for Tracking Any Object Amodally** — arXiv:2312.12433  
  [paper](https://arxiv.org/abs/2312.12433) · [page](https://tao-amodal.github.io/#TAO-Amodal https://tao-amodal.github.io) · [code](https://github.com/WesleyHsieh0806/TAO-Amodal)
- **DAM4SAM**  
  [page](https://jovanavidenovic.github.io/dam-4-sam/) · [code](https://github.com/jovanavidenovic/DAM4SAM)
- **SAM-MT: Real-Time Interactive Multi-Target Video Segmentation** — arXiv:2607.08688  
  [paper](https://arxiv.org/abs/2607.08688) · [page](https://henghuiding.com/SAM-MT/) · [code](https://github.com/FudanCVL/SAM-MT)
- **CASIA-LMC-Lab/FastSAM: Fast Segment Anything** — arXiv:2306.12156  
  [paper](https://arxiv.org/abs/2306.12156) · [code](https://github.com/CASIA-IVA-Lab/FastSAM https://github.com/casia-iva-lab/fastsam)
- **SHI-Labs/Matting-Anything: Matting Anything Model (MAM), an efficient and versatile framework for est** — arXiv:2306.05399  
  [paper](https://arxiv.org/abs/2306.05399) · [page](https://chrisjuniorli.github.io/project/Matting-Anything/) · [code](https://github.com/SHI-Labs/Matting-Anything https://github.com/shi-labs/matting-anything)
- **Recognize Anything: A Strong Image Tagging Model** — arXiv:2306.03514  
  [paper](https://arxiv.org/abs/2306.03514) · [page](https://recognize-anything.github.io https://recognize-anything.github.io/) · [code](https://github.com/xinyu1205/Recognize_Anything-Tag2Text)
- **NVlabs/ODISE: Official PyTorch implementation of ODISE: Open-Vocabulary Panoptic Segmentation with Te**  
  [code](https://github.com/NVlabs/ODISE)
- **facebookresearch/Detic: Code release for "Detecting Twenty-thousand Classes using Image-level Supervi** — arXiv:2201.02605  
  [paper](https://arxiv.org/abs/2201.02605) · [code](https://github.com/facebookresearch/Detic)
- **Mask3D 🎭** — arXiv:2210.03105  
  [paper](https://arxiv.org/abs/2210.03105) · [page](https://jonasschult.github.io/Mask3D/ https://jonasschult.github.io/) · [code](https://github.com/JonasSchult/Mask3D https://github.com/JonasSchult/dcm-net)
- **OmniSeg3D: Omniversal 3D Segmentation via Hierarchical Contrastive Learning** — arXiv:2311.11666  
  [paper](https://arxiv.org/abs/2311.11666) · [page](https://oceanying.github.io/OmniSeg3D) · [code](https://github.com/THU-luvision/OmniSeg3D https://github.com/OceanYing/OmniSeg3D-GS)
- **OpenScene: 3D Scene Understanding with Open Vocabularies** — arXiv:2211.15654  
  [paper](https://arxiv.org/abs/2211.15654)
- **aminebdj/3D-OWIS: [NeurIPS2023] 3D-OWIS is capable of detecting unknown instances in inference, and p**  
  [page](https://aminebdj.github.io/scanedit/ https://aminebdj.github.io/publications/3d_owis) · [code](https://github.com/aminebdj/3D-OWIS https://github.com/aminebdj/ScanEdit)
- **3D-VisTA** — arXiv:2308.04352  
  [paper](https://arxiv.org/abs/2308.04352) · [page](https://3d-vista.github.io https://3d-vista.github.io/) · [code](https://github.com/3d-vista/3D-VisTA)
- **evelinehong/3D-CLR-Official: [CVPR 2023] Code for "3D Concept Learning and Reasoning from Multi-View** — arXiv:2303.11327  
  [paper](https://arxiv.org/abs/2303.11327) · [code](https://github.com/evelinehong/3D-CLR-Official)
- **PartDistillation**  
  [page](https://janghyuncho.github.io/PartDistillation_website/) · [code](https://github.com/facebookresearch/PartDistillation)
- **Jingkang50/OpenPSG: Benchmarking Panoptic Scene Graph Generation (PSG), ECCV'22** — arXiv:2207.11247  
  [paper](https://arxiv.org/abs/2207.11247) · [page](https://psgdataset.org http://jingkang50.github.io/) · [code](https://github.com/Jingkang50/OpenPSG https://github.com/Jingkang50/PSG4D)
- **Maelic/SGG-Benchmark: A New Benchmark for Scene Graph Generation, targeting real-world applications**  
  [code](https://github.com/Maelic/SGG-Benchmark)
- **Accelerate Image Annotation with SAM and Grounding DINO | Python Tutorial**  
- **Holi-Spatial | Holistic Spatial Intelligence** — arXiv:2603.07660  
  [paper](https://arxiv.org/abs/2603.07660) · [page](https://visionary-laboratory.github.io/holi-spatial/) · [code](https://github.com/Visionary-Laboratory/holi-spatial https://github.com/Visionary-Laboratory/Holi-Spatial)
- **Pointcept/Pointcept: Pointcept: Perceive the world with sparse points, a codebase for point cloud per**  
  [page](https://pointcept.github.io/Utonia/ https://pointcept.github.io/Utonia/#citation) · [code](https://github.com/Pointcept/Pointcept https://github.com/Pointcept/Utonia)
- **M3: 3D-Spatial Multimodel Memory** — arXiv:2503.16413  
  [paper](https://arxiv.org/abs/2503.16413) · [page](https://m3-spatial-memory.github.io https://m3-spatial-memory.github.io/) · [code](https://github.com/MaureenZOU/m3-spatial)
- **FARM: Find Anything using Relational Spatial Memory** — arXiv:2606.15476  
  [paper](https://arxiv.org/abs/2606.15476) · [page](https://goldengait.github.io/farm/) · [code](https://github.com/GoldenGait/FARM-Project)
- **Point2Part: Unified 3D Partitioning From Point Prompts** — arXiv:2609.38180  
  [paper](https://arxiv.org/abs/2609.38180) · [page](https://henrytsui000.github.io/Point2Part/) · [code](https://github.com/henrytsui000/Point2Part)
- **SceneAligner** — arXiv:2605.22581  
  [paper](https://arxiv.org/abs/2605.22581) · [page](https://cornell-vailab.github.io/SceneAligner/ https://Cornell-VAILab.github.io/SceneAligner) · [code](https://github.com/Cornell-VAILab/SceneAligner)
- **Zero-shot Inexact CAD Model Alignment from a Single Image** — arXiv:2507.03292  
  [paper](https://arxiv.org/abs/2507.03292) · [page](https://zerocad9d.github.io/)
- **SuperDec** — arXiv:2504.00992  
  [paper](https://arxiv.org/abs/2504.00992) · [page](https://super-dec.github.io/) · [code](https://github.com/elisabettafedele/superdec)
- **CAST** — arXiv:2502.12894  
  [paper](https://arxiv.org/abs/2502.12894) · [page](https://sites.google.com/view/cast4) · [code](https://github.com/google/safevalues)
- **FirePlace** — arXiv:2503.04919  
  [paper](https://arxiv.org/abs/2503.04919) · [page](https://fireplace3d.github.io https://fireplace3d.github.io/)
- **NVlabs/BundleSDF: [CVPR 2023] BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objec** — arXiv:2303.14158  
  [paper](https://arxiv.org/abs/2303.14158) · [page](https://bundlesdf.github.io/) · [code](https://github.com/NVlabs/BundleSDF)
- **DecaYale/RNNPose: RNNPose: Recurrent 6-DoF Object Pose Refinement with Robust Correspondence Field Es**  
  [page](https://decayale.github.io/) · [code](https://github.com/decayale/rnnpose https://github.com/DecaYale/RNNPose)
- **CNJianLiu/Awesome-Object-Pose-Estimation: [IJCV 2026] Project Page for "Deep Learning-Based Object Po**  
  [page](https://link.springer.com/article/10.1007/s11263-025-02646-6) · [code](https://github.com/CNJianLiu/Awesome-Object-Pose-Estimation)
- **Jiahao-Ma/puzzles-code: Official Implementation of Puzzles: Unbounded Video-Depth Augmentation for Sc**  
  [page](https://jiahao-ma.github.io/puzzles/ https://hengyiwang.github.io/projects/spanner) · [code](https://github.com/Jiahao-Ma/puzzles-code https://github.com/HengyiWang/spann3r)
- **Recognize Detect Segment Anything - a Hugging Face Space by xinyu1205**  

<a id="10"></a>
## 10. Depth and stereo (monocular, video, metric)

- **huawei-bayerlab/marigold-v2: Marigold V2: Revisiting Diffusion Transformers for Monocular Depth Estim** — arXiv:2609.08084  
  [paper](https://arxiv.org/abs/2609.08084) · [page](https://hf.co/spaces/huawei-bayerlab/marigold-v2-web) · [code](https://github.com/huawei-bayerlab/marigold-v2)
- **isl-org/MiDaS: Code for robust monocular depth estimation described in "Ranftl et. al., Towards Robus**  
  [code](https://github.com/isl-org/MiDaS)
- **DVD: Deterministic Video Depth Estimation** — arXiv:2603.12250  
  [paper](https://arxiv.org/abs/2603.12250) · [page](https://dvd-project.github.io/) · [code](https://github.com/EnVision-Research/DVD)
- **pixel-perfect-depth** — arXiv:2510.07316  
  [paper](https://arxiv.org/abs/2510.07316) · [page](https://pixel-perfect-depth.github.io) · [code](https://github.com/gangweix/pixel-perfect-depth)
- **Stereo Any Video** — arXiv:2503.05549  
  [paper](https://arxiv.org/abs/2503.05549) · [page](https://tomtomtommi.github.io/StereoAnyVideo/) · [code](https://github.com/TomTomTommi/stereoanyvideo)
- **ZipDepth — Bringing Lightweight Zero-Shot Monocular Depth Anywhere, on Any Device** — arXiv:2607.08771  
  [paper](https://arxiv.org/abs/2607.08771) · [page](https://zipdepth.github.io) · [code](https://github.com/fabiotosi92/ZipDepth)
- **https://nvlabs.github.io/FoundationStereo/**  
  [page](https://nvlabs.github.io/FoundationStereo/) · [code](https://github.com/NVlabs/FoundationStereo)
- **facebookresearch/DistDepth: Repository for "Toward Practical Monocular Indoor Depth Estimation" (CVPR** — arXiv:2112.02306  
  [paper](https://arxiv.org/abs/2112.02306) · [page](https://distdepth.github.io/) · [code](https://github.com/facebookresearch/DistDepth)
- **facebookresearch/DVSR: DVSR ("Consistent Direct Time-of-Flight Video Depth Super-Resolution"), CVPR 2** — arXiv:2211.08658  
  [paper](https://arxiv.org/abs/2211.08658) · [code](https://github.com/facebookresearch/DVSR https://github.com/facebookresearch/dvsr)
- **Unified Video Dense Prediction from Disjoint Data** — arXiv:2607.21592  
  [paper](https://arxiv.org/abs/2607.21592) · [page](https://unid-video.github.io/) · [code](https://github.com/unid-video/unid-video.github.io)
- **Vision Banana | Google DeepMind**  
  [page](https://vision-banana.github.io/)
- **DIODE: A Dense Indoor and Outdoor DEpth Dataset** — arXiv:1908.00463  
  [paper](https://arxiv.org/abs/1908.00463) · [page](https://diode-dataset.org/) · [code](https://github.com/diode-dataset/diode-devkit)

<a id="11"></a>
## 11. Adjacent: generative 3D, world models, object/scene generation (context, lower priority)

- **One-2-3-45/One-2-3-45: [NeurIPS 2023] Official code of "One-2-3-45: Any Single Image to 3D Mesh in 45** — arXiv:2306.16928  
  [paper](https://arxiv.org/abs/2306.16928) · [page](http://one-2-3-45.com) · [code](https://github.com/One-2-3-45/One-2-3-45)
- **ashawkey/stable-dreamfusion: Text-to-3D & Image-to-3D & Mesh Exportation with NeRF + Diffusion.**  
  [code](https://github.com/ashawkey/stable-dreamfusion)
- **Make-It-3D: High-Fidelity 3D Creation from A Single Image with Diffusion Prior** — arXiv:2303.14184  
  [paper](https://arxiv.org/abs/2303.14184) · [page](https://make-it-3d.github.io/) · [code](https://github.com/junshutang/Make-It-3D)
- **MeshFormer: High-Quality Mesh Generation with 3D-Guided Reconstruction Model** — arXiv:2408.10198  
  [paper](https://arxiv.org/abs/2408.10198) · [page](https://meshformer3d.github.io/)
- **Sparc3D: Sparse Representation and Construction for High-Resolution 3D Shapes Modeling** — arXiv:2505.14521  
  [paper](https://arxiv.org/abs/2505.14521) · [page](https://lizhihao6.github.io/Sparc3D/) · [code](https://github.com/lizhihao6/Sparc3D)
- **MeshCoder: LLM-Powered Structured Mesh Code Generation from Point Clouds** — arXiv:2508.14879  
  [paper](https://arxiv.org/abs/2508.14879) · [page](https://daibingquan.github.io/MeshCoder/ https://daibingquan.github.io/MeshCoder) · [code](https://github.com/ZhaoyangLyu/MeshCoder)
- **VoxLution: Evolving Voxels for High-Fidelity 3D Scene Generation** — arXiv:2610.41501  
  [paper](https://arxiv.org/abs/2610.41501) · [page](https://daoyig.github.io/VoxLution/)
- **InSpatio-World 1.5 — Beyond the Frame, Into the World**  
  [page](https://inspatio.github.io/inspatio-world-1.5/) · [code](https://github.com/inspatio/inspatio-world-v1.5)
- **HY-WorldPlay/worldcompass at main · Tencent-Hunyuan/HY-WorldPlay**  
  [page](https://3d-models.hunyuan.tencent.com/world/) · [code](https://github.com/Tencent-Hunyuan/HY-WorldPlay)
- **Atlas: A World Model for Spatial Intelligence**  
  [page](https://www.worldlabs.ai/blog/atlas)
- **GenRecon: Bridging Generative Priors for Multi-View 3D Scene Reconstruction** — arXiv:2605.23888  
  [paper](https://arxiv.org/abs/2605.23888) · [page](https://kasothaphie.github.io/GenRecon/) · [code](https://github.com/kasothaphie/GenRecon)
- **GEN3C: 3D-Informed World-Consistent Video Generation with Precise Camera Control** — arXiv:2503.03751  
  [paper](https://arxiv.org/abs/2503.03751) · [page](https://research.nvidia.com/labs/toronto-ai/GEN3C/) · [code](https://github.com/nv-tlabs/GEN3C)
- **ReCamMaster** — arXiv:2503.11647  
  [paper](https://arxiv.org/abs/2503.11647) · [page](https://jianhongbai.github.io/ReCamMaster/) · [code](https://github.com/KwaiVGI/ReCamMaster)
- **Infinite Nature: Perpetual View Generation of Natural Scenes from a Single Image** — arXiv:2012.09855  
  [paper](https://arxiv.org/abs/2012.09855) · [page](https://infinite-nature.github.io/)
- **STORM** — arXiv:2501.00602  
  [paper](https://arxiv.org/abs/2501.00602) · [page](https://jiawei-yang.github.io/STORM/)
- **TencentARC/GAE-GeometricAutoEncoder: [arxiv'26] GAE: Learning a Geometry-Native Latent Space for 3D-C** — arXiv:2609.24981  
  [paper](https://arxiv.org/abs/2609.24981) · [page](https://jiah-cloud.github.io/GAE.github.io/) · [code](https://github.com/TencentARC/GAE-GeometricAutoEncoder)
- **Totoro97/point2mesh: Reconstruct Watertight Meshes from Point Clouds [SIGGRAPH 2020]**  
  [code](https://github.com/Totoro97/point2mesh)
- **YuQiao0303/PointDreamer: [TVCG2025]PointDreamer: Zero-shot 3D Textured Mesh Reconstruction from Color** — arXiv:2406.15811  
  [paper](https://arxiv.org/abs/2406.15811) · [code](https://github.com/YuQiao0303/PointDreamer https://github.com/yuqiao0303/pointdreamer)
- **EvaSurf: Efficient View-Aware Implicit Textured Surface Reconstruction** — arXiv:2311.09806  
  [paper](https://arxiv.org/abs/2311.09806)
- **Sat-NeRF: Learning Multi-View Satellite Photogrammetry With Transient Objects and Shadow Modeling Using RPC Cameras** — arXiv:2203.08896  
  [paper](https://arxiv.org/abs/2203.08896)
- **Scalable and Adaptive Streaming of 3D Mesh to Heterogeneous Devices - 3D Research**  
  [page](https://link.springer.com/article/10.1007/s13319-016-0108-5)
- **World-Class: NVIDIA Research Builds AI Model to Populate Virtual Worlds With 3D Objects, Characters**  
  [page](https://blogs.nvidia.com/blog/2022/09/23/3d-generative-ai-research-virtual-worlds/)

<a id="12"></a>
## 12. Tools, viewers, editors, libraries (3DGS ecosystem)

- **cnlohr/slapsplat**  
  [code](https://github.com/cnlohr/slapsplat)
- **hyperlogic/splatapult: A 3d gaussian splatting renderer in C++ and OpenGL**  
  [page](https://radiancefields.com/splatapult-3dgs-vr-and-viewer/) · [code](https://github.com/hyperlogic/splatapult)
- **keijiro/SplatVFX: 3D Gaussian Splatting with Unity VFX Graph**  
  [code](https://github.com/keijiro/SplatVFX)
- **m-schuetz/Splatshop: Edit gaussian splatting models**  
  [code](https://github.com/m-schuetz/Splatshop)
- **playcanvas/supersplat: 3D Gaussian Splat Editor**  
  [page](https://superspl.at/editor) · [code](https://github.com/playcanvas/super-splat)
- **Spark**  
  [page](https://sparkjs.dev/) · [code](https://github.com/sparkjsdev/spark)
- **3D Gaussian Splatting | Polycam**  
  [page](https://poly.cam/tools/gaussian-splatting)
- **3D Gaussians Plugin for Unreal Engine 5**  
  [page](https://neuralradiancefields.io/3d-gaussians-plugin-for-unreal-engine-5/)
- **facebookresearch/pytorch3d: PyTorch3D is FAIR's library of reusable components for deep learning with** — arXiv:2007.08501  
  [paper](https://arxiv.org/abs/2007.08501) · [page](https://pytorch3d.org/) · [code](https://github.com/facebookresearch/pytorch3d)
- **Open3D – A  Modern Library for 3D Data Processing** — arXiv:1801.09847  
  [paper](https://arxiv.org/abs/1801.09847) · [page](http://www.open3d.org/) · [code](https://github.com/isl-org/Open3D)
- **Rerun Viewer**  
  [page](https://app.rerun.io/version/0.22.1/?url=https://cvg.cit.tum.de/webshare/g/behindthescenes/anycam/davis/train-4d.rrd&url=https://cvg.cit.tum.de/webshare/g/behindthescenes/anycam/blueprint.rbl&hide_welcome_screen=true&allow_fullscreen=true) · [code](https://github.com/rerun-io/rerun)
- **Volinga unveils Gaussian Splatting Web Viewer**  
  [page](https://radiancefields.com/volinga-unveils-gaussian-splatting-web-viewer/)
- **Announcing gsplat.js - a JavaScript Gaussian Splatting library**  
- **Threejs Gaussian Splatting! (r3f + Drei) - How To Guide**  
- **Gaussian Splatting on Meta Quest 3**  
- **3D Gaussian Splatting full tutorial, crop, transform, mesh, import into UE5 & Collision**  
- **Spectacular Rec for Gaussian Splatting and NeRF reconstructions (iPhone)**  
