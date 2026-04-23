# CVPR 2026 Oral 论文收集（含 arXiv / 代码链接）

按研究方向分类整理的 **141** 篇 CVPR 2026 Oral 论文，附 CVPR 虚拟会场、
arXiv 预印本和代码仓库直链。

[English version](./README.md)

## 统计

- 总计 Oral：**141** 篇
- 已匹配 arXiv：**102** 篇（72%）
- 已找到 GitHub：**29** 篇（20%）

> 尚未挂 arXiv 的论文可能在会议临近时放出——欢迎 PR 补充。

## 各大类数量

| # | 分类 | 数量 | arXiv | 代码 |
|---|---|---:|---:|---:|
| 1 | 3D 重建、几何、Gaussian / Radiance Field / SfM / 配准 | 45 | 33 | 7 |
| 2 | 生成模型、扩散模型、图像/视频/3D 生成与编辑 | 20 | 17 | 3 |
| 3 | 医学影像、医学 VLM、医学分割、医学重建、医学配准 | 15 | 10 | 4 |
| 4 | 分割、检测、识别、跟踪、对应关系 | 30 | 21 | 10 |
| 5 | VLM / MLLM / 多模态推理 / 安全 / Benchmark | 12 | 10 | 0 |
| 6 | 机器人、Embodied AI、导航、操控、自动驾驶、世界模型 | 8 | 6 | 2 |
| 7 | 模型压缩、训练效率、优化理论、联邦学习、任务算术 | 13 | 9 | 4 |
| 8 | 隐私、安全、水印、版权、成员推断 | 5 | 3 | 0 |
| 9 | 数据集 / Benchmark 型论文 | 11 | 10 | 2 |
| — | **去重合计** | **141** | **102** | **29** |

> 子类之间可能交叉重复收录（例如 3D 编辑同时出现在 §1 和 §2），表中按大类去重，因此总和会大于 141。

## 文件

| 路径 | 用途 |
|---|---|
| `cvpr2026_orals.json` | 结构化完整记录（标题、作者、摘要、arxiv、github、相关链接） |
| `cvpr2026_orals.csv`  | 同上的扁平表 |

## 贡献

发现缺失的 arxiv / github 链接？欢迎提出[issue](https://github.com/ooonesevennn/CVPR_2026_Oral_Papers/issues)。

---


## 1. 3D 重建、几何、Gaussian / Radiance Field / SfM / 配准


### 1.1 3D 重建、Gaussian Splatting、NeRF、动态场景

- **40261** [GLINT: Modeling Scene-Scale Transparency via Gaussian Radiance Transport](https://cvpr.thecvf.com/virtual/2026/oral/40261) — *Youngju Na et al.* · [arxiv](https://arxiv.org/abs/2603.26181)
- **40277** [Energy-GS: Image Energy-guided Pose Alignment Gaussian Splatting with redesigned pose gradient flow](https://cvpr.thecvf.com/virtual/2026/oral/40277) — *Yu Gao et al.*
- **40279** [SmokeSVD: Smoke Reconstruction from A Single View via Progressive Novel View Synthesis and Refinement with Diffusion Models](https://cvpr.thecvf.com/virtual/2026/oral/40279) — *Chen Li et al.* · [arxiv](https://arxiv.org/abs/2507.12156)
- **40287** [GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials](https://cvpr.thecvf.com/virtual/2026/oral/40287) — *Bei Huang et al.* · [arxiv](https://arxiv.org/abs/2601.09265)
- **40289** [Proxy-GS: Unified Occlusion Priors for Training and Inference in Structured 3D Gaussian Splatting](https://cvpr.thecvf.com/virtual/2026/oral/40289) — *Yuanyuan Gao et al.* · [arxiv](https://arxiv.org/abs/2509.24421)
- **40291** [Z-Order Transformer for Feed-Forward Gaussian Splatting](https://cvpr.thecvf.com/virtual/2026/oral/40291) — *Can Wang et al.*
- **40312** [RetimeGS: Continuous-Time Reconstruction of 4D Gaussian Splatting](https://cvpr.thecvf.com/virtual/2026/oral/40312) — *Xuezhen Wang et al.* · [arxiv](https://arxiv.org/abs/2603.13783)
- **40313** [PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://cvpr.thecvf.com/virtual/2026/oral/40313) — *Jiale Wu et al.* · [arxiv](https://arxiv.org/abs/2603.14001)
- **40333** [MeshSplatting: Differentiable Rendering with Opaque Meshes](https://cvpr.thecvf.com/virtual/2026/oral/40333) — *Jan Held et al.* · [arxiv](https://arxiv.org/abs/2512.06818)
- **40345** [Efficiently Reconstructing Dynamic Scenes one D4RT at a Time](https://cvpr.thecvf.com/virtual/2026/oral/40345) — *Chuhan Zhang et al.* · [arxiv](https://arxiv.org/abs/2512.08924)
- **40355** [Selfi: Self Improving Reconstruction Engine via 3D Geometric Feature Alignment](https://cvpr.thecvf.com/virtual/2026/oral/40355) — *Youming Deng et al.* · [arxiv](https://arxiv.org/abs/2512.08930)
- **40358** [4D Primitive-Mâché: Glueing Primitives for Persistent 4D Scene Reconstruction](https://cvpr.thecvf.com/virtual/2026/oral/40358) — *Kirill Mazur et al.*
- **40372** [Evidential Neural Radiance Fields](https://cvpr.thecvf.com/virtual/2026/oral/40372) — *Ruxiao Duan et al.* · [arxiv](https://arxiv.org/abs/2602.23574) [code](https://github.com/KerryDRX/EvidentialNeRF)
- **40381** [VGGT-$\Omega$](https://cvpr.thecvf.com/virtual/2026/oral/40381) — *Jianyuan Wang et al.*
- **40395** [Chorus: Multi-Teacher Pretraining for Holistic 3D Gaussian Scene Encoding](https://cvpr.thecvf.com/virtual/2026/oral/40395) — *Yue Li et al.* · [arxiv](https://arxiv.org/abs/2512.17817)

### 1.2 反射、透明、材质、光照、逆渲染

- **40274** [PPISP: Physically-Plausible Compensation and Control of Photometric Variations in Radiance Field Reconstruction](https://cvpr.thecvf.com/virtual/2026/oral/40274) — *Isaac Deutsch et al.* · [arxiv](https://arxiv.org/abs/2601.18336) [code](https://github.com/nv-tlabs/ppisp)
- **40290** [POLAR: A Portrait OLAT Dataset and Generative Framework for Illumination-Aware Face Modeling](https://cvpr.thecvf.com/virtual/2026/oral/40290) — *Zhuo Chen et al.* · [arxiv](https://arxiv.org/abs/2512.13192)
- **40310** [3DReflecNet: A Large-Scale Dataset for 3D Reconstruction of Reflective, Transparent, and Low-Texture Objects](https://cvpr.thecvf.com/virtual/2026/oral/40310) — *Zhicheng Liang et al.*
- **40314** [Dual Band Video Thermography: Separating Time-Varying Reflection and Emission Near Ambient Conditions](https://cvpr.thecvf.com/virtual/2026/oral/40314) — *Sriram Narayanan et al.*
- **40328** [OLATverse: A Large-scale Real-world Object Dataset with Precise Lighting Control](https://cvpr.thecvf.com/virtual/2026/oral/40328) — *Xilong Zhou et al.* · [arxiv](https://arxiv.org/abs/2511.02483)
- **40356** [Towards Photorealistic and Efficient Bokeh Rendering via Diffusion Framework](https://cvpr.thecvf.com/virtual/2026/oral/40356) — *Linxiao Shi et al.*
- **40359** [SeeGroup: Multi-Layer Depth Estimation of Transparent Surfaces via Self-Determined Grouping](https://cvpr.thecvf.com/virtual/2026/oral/40359) — *Hongyu Wen et al.*
- **40390** [Relightable Holoported Characters: Capturing and Relighting Dynamic Human Performance from Sparse Views](https://cvpr.thecvf.com/virtual/2026/oral/40390) — *Kunwar Maheep Singh et al.* · [arxiv](https://arxiv.org/abs/2512.00255)
- **40393** [UnReflectAnything: RGB-Only Highlight Removal by Rendering Synthetic Specular Supervision](https://cvpr.thecvf.com/virtual/2026/oral/40393) — *Alberto Rota et al.* · [arxiv](https://arxiv.org/abs/2512.09583)

### 1.3 多视图几何、SfM、相机、位姿图

- **40264** [QuadSync: Quadrifocal Tensor Synchronization via Tucker Decomposition](https://cvpr.thecvf.com/virtual/2026/oral/40264) — *Daniel Miao et al.* · [arxiv](https://arxiv.org/abs/2602.22639) [code](http://github.com/dmiao153/QuadSync)
- **40265** [Breaking the Scalability Limit of Multi-Projector Calibration with Embedded Cameras](https://cvpr.thecvf.com/virtual/2026/oral/40265) — *Takumi Kawano et al.*
- **40268** [PoseGAM: Robust Unseen Object Pose Estimation via Geometry-Aware Multi-View Reasoning](https://cvpr.thecvf.com/virtual/2026/oral/40268) — *Jianqi Chen et al.* · [arxiv](https://arxiv.org/abs/2512.10840)
- **40275** [From Pairs to Sequences: Track-Aware Policy Gradients for Keypoint Detection](https://cvpr.thecvf.com/virtual/2026/oral/40275) — *yepeng liu et al.* · [arxiv](https://arxiv.org/abs/2602.20630)
- **40302** [Global-Aware Edge Prioritization for Pose Graph Initialization](https://cvpr.thecvf.com/virtual/2026/oral/40302) — *Tong Wei et al.* · [arxiv](https://arxiv.org/abs/2602.21963) [code](https://github.com/weitong8591/global_edge_prior)
- **40320** [TESO: Online Tracking of Essential Matrix by Stochastic Optimization](https://cvpr.thecvf.com/virtual/2026/oral/40320) — *Jaroslav Moravec et al.* · [arxiv](https://arxiv.org/abs/2604.19420)
- **40341** [Linear Fundamental Matrix Estimation from 7 or 5 Points](https://cvpr.thecvf.com/virtual/2026/oral/40341) — *Taci Ata Kucukpinar et al.*

### 1.4 3D 表示、形状分解、形状建模

- **40259** [Learning Convex Decomposition via Feature Fields](https://cvpr.thecvf.com/virtual/2026/oral/40259) — *Yuezhi Yang et al.* · [arxiv](https://arxiv.org/abs/2603.09285)
- **40276** [Learning Eigenstructures of Unstructured Data Manifolds](https://cvpr.thecvf.com/virtual/2026/oral/40276) — *Roy Velich et al.* · [arxiv](https://arxiv.org/abs/2512.01103)
- **40283** [Native and Compact Structured Latents for 3D Generation](https://cvpr.thecvf.com/virtual/2026/oral/40283) — *Jianfeng XIANG et al.* · [arxiv](https://arxiv.org/abs/2512.14692)
- **40293** [Residual Primitive Fitting of 3D Shapes with SuperFrusta](https://cvpr.thecvf.com/virtual/2026/oral/40293) — *Aditya Ganeshan et al.* · [arxiv](https://arxiv.org/abs/2512.09201)
- **40323** [FILTR: Extracting Topological Features from Pretrained 3D Models](https://cvpr.thecvf.com/virtual/2026/oral/40323) — *Louis Martinez et al.*
- **40325** [FAITHFUL CONTOURING: NEAR-LOSSLESS 3D VOXEL REPRESENTATION FREE FROM ISO-SURFACE](https://cvpr.thecvf.com/virtual/2026/oral/40325) — *Yihao Luo et al.* · [arxiv](https://arxiv.org/abs/2511.04029)
- **40370** [SAM 3D: 3Dfy Anything in Images](https://cvpr.thecvf.com/virtual/2026/oral/40370) — *Xingyu Chen et al.* · [arxiv](https://arxiv.org/abs/2511.16624)
- **40380** [AnchorFlow: Training-Free 3D Editing via Latent Anchor-Aligned Flows](https://cvpr.thecvf.com/virtual/2026/oral/40380) — *Zhenglin Zhou et al.* · [arxiv](https://arxiv.org/abs/2511.22357) [code](https://github.com/ZhenglinZhou/AnchorFlow)

### 1.5 Occupancy / Scene Completion / Active Mapping / 空间建模

- **40286** [SparseWorld-TC: Trajectory-Conditioned Sparse Occupancy World Model](https://cvpr.thecvf.com/virtual/2026/oral/40286) — *Jiayuan Du et al.* · [arxiv](https://arxiv.org/abs/2511.22039)
- **40308** [OccuFly: A 3D Vision Benchmark for Semantic Scene Completion from the Aerial Perspective](https://cvpr.thecvf.com/virtual/2026/oral/40308) — *Markus Gross et al.* · [arxiv](https://arxiv.org/abs/2512.20770) [code](https://github.com/markus-42/occufly)
- **40324** [Monocular Open Vocabulary Occupancy Prediction for Indoor Scenes](https://cvpr.thecvf.com/virtual/2026/oral/40324) — *Changqing Zhou et al.* · [arxiv](https://arxiv.org/abs/2602.22667) [code](https://github.com/JuIvyy/LegoOcc)
- **40384** [MAGICIAN: Efficient Long-Term Planning with Imagined Gaussians for Active Mapping](https://cvpr.thecvf.com/virtual/2026/oral/40384) — *Shiyao Li et al.* · [arxiv](https://arxiv.org/abs/2603.22650)

### 1.6 多视图/点云配准

- **40330** [FUSER: Feed-Forward Multiview 3D Registration Transformer and SE(3)$^N$ Diffusion Refinement](https://cvpr.thecvf.com/virtual/2026/oral/40330) — *Haobo Jiang et al.* · [arxiv](https://arxiv.org/abs/2512.09373)
- **40391** [ComPose: A Unified Completion-Pose Framework for Robust Category-Level Object Pose Estimation](https://cvpr.thecvf.com/virtual/2026/oral/40391) — *Huan Ren et al.*

## 2. 生成模型、扩散模型、图像/视频/3D 生成与编辑


### 2.1 图像生成与编辑

- **40271** [A Style is Worth One Code: Unlocking Code-to-Style Image Generation with Discrete Style Space](https://cvpr.thecvf.com/virtual/2026/oral/40271) — *Huijie Liu et al.* · [arxiv](https://arxiv.org/abs/2511.10555) [code](https://github.com/Kwai-Kolors/CoTyle)
- **40301** [SliderEdit: Continuous Image Editing with Fine-Grained Instruction Control](https://cvpr.thecvf.com/virtual/2026/oral/40301) — *Arman Zarei et al.* · [arxiv](https://arxiv.org/abs/2511.09715)
- **40304** [PixelDiT: Pixel Diffusion Transformers for Image Generation](https://cvpr.thecvf.com/virtual/2026/oral/40304) — *Yongsheng Yu et al.* · [arxiv](https://arxiv.org/abs/2511.20645) [code](https://github.com/NVlabs/PixelDiT)
- **40306** [Guiding a Diffusion Model by Swapping Its Tokens](https://cvpr.thecvf.com/virtual/2026/oral/40306) — *Weijia Zhang et al.* · [arxiv](https://arxiv.org/abs/2604.08048)
- **40319** [Breaking Semantic Boundaries: Distribution-Guided Semantic Exploration for Creative Generation](https://cvpr.thecvf.com/virtual/2026/oral/40319) — *Fu Feng et al.*
- **40352** [ChordEdit: One-Step Low-Energy Transport for Image Editing](https://cvpr.thecvf.com/virtual/2026/oral/40352) — *Liangsi Lu et al.* · [arxiv](https://arxiv.org/abs/2602.19083)
- **40353** [SeaCache: Spectral-Evolution-Aware Cache for Accelerating Diffusion Models](https://cvpr.thecvf.com/virtual/2026/oral/40353) — *Jiwoo Chung et al.* · [arxiv](https://arxiv.org/abs/2602.18993)
- **40360** [SenCache: Accelerating Diffusion Model Inference via Sensitivity-Aware Caching](https://cvpr.thecvf.com/virtual/2026/oral/40360) — *Yasaman Haghighi et al.* · [arxiv](https://arxiv.org/abs/2602.24208)

### 2.2 视频生成、视频理解相关生成

- **40256** [ProPhy: Progressive Physical Alignment for Dynamic World Simulation](https://cvpr.thecvf.com/virtual/2026/oral/40256) — *Zijun Wang et al.* · [arxiv](https://arxiv.org/abs/2512.05564)
- **40300** [Thinking with Drafts: Speculative Temporal Reasoning for Efficient Long-Video Understanding](https://cvpr.thecvf.com/virtual/2026/oral/40300) — *Pengfei Hu et al.* · [arxiv](https://arxiv.org/abs/2512.00805)
- **40338** [Texvent: Asynchronous Event Data Simulation via Text Prompt](https://cvpr.thecvf.com/virtual/2026/oral/40338) — *Ruofei Wang et al.*
- **40357** [TEAR: Temporal-aware Automated Red-teaming for Text-to-Video Models](https://cvpr.thecvf.com/virtual/2026/oral/40357) — *Jiaming He et al.* · [arxiv](https://arxiv.org/abs/2511.21145)
- **40364** [PAVAS: Physics-Aware Video-to-Audio Synthesis](https://cvpr.thecvf.com/virtual/2026/oral/40364) — *Oh Hyun-Bin et al.* · [arxiv](https://arxiv.org/abs/2512.08282)

### 2.3 3D 生成与编辑

- **40283** [Native and Compact Structured Latents for 3D Generation](https://cvpr.thecvf.com/virtual/2026/oral/40283) — *Jianfeng XIANG et al.* · [arxiv](https://arxiv.org/abs/2512.14692)
- **40344** [SPARK: Sim-ready Part-level Articulated Reconstruction with VLM Knowledge](https://cvpr.thecvf.com/virtual/2026/oral/40344) — *Yumeng He et al.* · [arxiv](https://arxiv.org/abs/2512.01629)
- **40368** [3D-LATTE: Latent Space 3D Editing from Textual Instructions](https://cvpr.thecvf.com/virtual/2026/oral/40368) — *Maria Parelli et al.* · [arxiv](https://arxiv.org/abs/2509.00269)
- **40380** [AnchorFlow: Training-Free 3D Editing via Latent Anchor-Aligned Flows](https://cvpr.thecvf.com/virtual/2026/oral/40380) — *Zhenglin Zhou et al.* · [arxiv](https://arxiv.org/abs/2511.22357) [code](https://github.com/ZhenglinZhou/AnchorFlow)

### 2.4 多模态生成 / tokenizer / interleaved generation

- **40278** [Molmo2: Open Weights and Data for Vision-Language Models with Video Understanding and Grounding](https://cvpr.thecvf.com/virtual/2026/oral/40278) — *Christopher Clark et al.* · [arxiv](https://arxiv.org/abs/2601.10611)
- **40282** [AToken: A Unified Tokenizer for Vision](https://cvpr.thecvf.com/virtual/2026/oral/40282) — *Jiasen Lu et al.* · [arxiv](https://arxiv.org/abs/2509.14476)
- **40336** [Weaver: Decoupled Training for Interleaved Multi-modal Generation](https://cvpr.thecvf.com/virtual/2026/oral/40336) — *Jinbo Xing et al.*

## 3. 医学影像、医学 VLM、医学分割、医学重建、医学配准


### 3.1 医学分割

- **40258** [SegMoTE: Token-Level Mixture of Experts for Medical Image Segmentation](https://cvpr.thecvf.com/virtual/2026/oral/40258) — *Yujie Lu et al.* · [arxiv](https://arxiv.org/abs/2602.19213)
- **40281** [DK-DDIL: Adaptive Knowledge Retention for Dynamic Domain-Incremental Learning in Medical Imaging](https://cvpr.thecvf.com/virtual/2026/oral/40281) — *Yuxi Ma et al.*
- **40317** [Dual-level Adapter Boosting Prompt-free Curvilinear Structure Segmentation](https://cvpr.thecvf.com/virtual/2026/oral/40317) — *Kai Zhu et al.*
- **40334** [R$^2$-Seg: Training-Free OOD Medical Tumor Segmentation via Anatomical Reasoning and Statistical Rejection](https://cvpr.thecvf.com/virtual/2026/oral/40334) — *Shuaike Shen et al.* · [arxiv](https://arxiv.org/abs/2511.12691) [code](https://github.com/Eurekashen/R2Seg)
- **40347** [MDCS-MoAME: Multi-directional Composite Scanning with Mixture of Attention and Mamba Experts for Cancer Survival Prediction](https://cvpr.thecvf.com/virtual/2026/oral/40347) — *Linjie Qu et al.*
- **40369** [Medic-AD: : Towards Medical Vision-Language Model's Clinical Intelligence](https://cvpr.thecvf.com/virtual/2026/oral/40369) — *Woohyeon Park et al.*
- **40373** [CURE: Curriculum-guided Multi-task Training for Reliable Anatomy Grounded Report Generation](https://cvpr.thecvf.com/virtual/2026/oral/40373) — *Pablo Messina et al.* · [arxiv](https://arxiv.org/abs/2601.15408) [code](https://github.com/PabloMessina/CURE)

### 3.2 医学重建 / inverse problem / 成像

- **40257** [Neural Field-Based 3D Surface Reconstruction of Microstructures from Multi-Detector Signals in Scanning Electron Microscopy](https://cvpr.thecvf.com/virtual/2026/oral/40257) — *Shuo Chen et al.* · [arxiv](https://arxiv.org/abs/2508.04728) [code](https://github.com/zju3dv/NFH-SEM)
- **40269** [Efficient unrolled networks for large-scale 3D inverse problems](https://cvpr.thecvf.com/virtual/2026/oral/40269) — *Romain Vo et al.* · [arxiv](https://arxiv.org/abs/2601.02141)
- **40298** [Differentiable Vector Quantization for Rate-Distortion Optimization of Generative Image Compression](https://cvpr.thecvf.com/virtual/2026/oral/40298) — *SHIYIN JIANG et al.* · [arxiv](https://arxiv.org/abs/2604.10546) [code](https://github.com/CVL-UESTC/RDVQ)
- **40307** [Hearing the Room Through the Shape of the Drum: Modal-Guided Sound Recovery from Multi-Point Surface Vibrations](https://cvpr.thecvf.com/virtual/2026/oral/40307) — *Shai Bagon et al.*
- **40309** [Spectrum from Defocus: Fast Spectral Imaging with Chromatic Focal Stack](https://cvpr.thecvf.com/virtual/2026/oral/40309) — *M. Kerem Aydin et al.* · [arxiv](https://arxiv.org/abs/2503.20184)
- **40361** [MetaSpectra+: A Compact Broadband Metasurface Camera for Snapshot Hyperspectral+ Imaging](https://cvpr.thecvf.com/virtual/2026/oral/40361) — *Yuxuan Liu et al.* · [arxiv](https://arxiv.org/abs/2603.09116)

### 3.3 医学 VLM / uncertainty / 可靠性

- **40270** [LATA: Laplacian-Assisted Transductive Adaptation for Conformal Uncertainty in Medical VLMs](https://cvpr.thecvf.com/virtual/2026/oral/40270) — *Behzad Bozorgtabar et al.* · [arxiv](https://arxiv.org/abs/2602.17535)
- **40369** [Medic-AD: : Towards Medical Vision-Language Model's Clinical Intelligence](https://cvpr.thecvf.com/virtual/2026/oral/40369) — *Woohyeon Park et al.*
- **40373** [CURE: Curriculum-guided Multi-task Training for Reliable Anatomy Grounded Report Generation](https://cvpr.thecvf.com/virtual/2026/oral/40373) — *Pablo Messina et al.* · [arxiv](https://arxiv.org/abs/2601.15408) [code](https://github.com/PabloMessina/CURE)

### 3.4 医学配准

- **40376** [Learning Diffeomorphism for Medical Image Registration with Time-Embedded Architectures Using Semigroup Regularization](https://cvpr.thecvf.com/virtual/2026/oral/40376) — *Mohammadjavad Matinkia et al.* · [arxiv](https://arxiv.org/abs/2405.18684)

## 4. 分割、检测、识别、跟踪、对应关系


### 4.1 图像/视频分割

- **40263** [INSID3: Training-Free In-Context Segmentation with DINOv3](https://cvpr.thecvf.com/virtual/2026/oral/40263) — *Claudia Cuttano et al.* · [arxiv](https://arxiv.org/abs/2603.28480) [code](https://github.com/visinf/INSID3)
- **40267** [S$^2$AM3D: Scale-controllable Part Segmentation of 3D Point Clouds](https://cvpr.thecvf.com/virtual/2026/oral/40267) — *Han Su et al.*
- **40296** [VGGT-Segmentor: Geometry-Enhanced Cross-View Segmentation](https://cvpr.thecvf.com/virtual/2026/oral/40296) — *Yulu Gao et al.* · [arxiv](https://arxiv.org/abs/2604.13596)
- **40297** [RobotSeg: A Model and Dataset for Segmenting Robots in Image and Video](https://cvpr.thecvf.com/virtual/2026/oral/40297) — *Haiyang Mei et al.* · [arxiv](https://arxiv.org/abs/2511.22950) [code](https://github.com/showlab/RobotSeg)
- **40321** [PR-MaGIC: Prompt Refinement Via Mask Decoder Gradient Flow For In-Context Segmentation](https://cvpr.thecvf.com/virtual/2026/oral/40321) — *Minjae Lee et al.* · [arxiv](https://arxiv.org/abs/2604.12113)
- **40362** [CoSMo3D: Open-World Promptable 3D Semantic Segmentation through LLM-Guided Canonical Spatial Modeling](https://cvpr.thecvf.com/virtual/2026/oral/40362) — *Li Jin et al.* · [arxiv](https://arxiv.org/abs/2603.01205)
- **40374** [Differentiable Laplacian Matrix Guided Superpixel Segmentation](https://cvpr.thecvf.com/virtual/2026/oral/40374) — *Jeremy Juybari et al.*

### 4.2 检测 / OOD / 长尾 / 类别发现

- **40266** [Learning Latent Concepts for Detecting Out-of-Distribution Objects](https://cvpr.thecvf.com/virtual/2026/oral/40266) — *Ting Peng et al.*
- **40292** [ANTS: Adaptive Negative Textual Space Shaping for OOD Detection via Test-Time MLLM Understanding and Reasoning](https://cvpr.thecvf.com/virtual/2026/oral/40292) — *Wenjie Zhu et al.* · [arxiv](https://arxiv.org/abs/2509.03951) [code](https://github.com/ZhuWenjie98/ANTS)
- **40316** [Learning Like Humans: Analogical Concept Learning for Generalized Category Discovery](https://cvpr.thecvf.com/virtual/2026/oral/40316) — *Jizhou Han et al.* · [arxiv](https://arxiv.org/abs/2603.19918) [code](https://github.com/zhou-9527/AnaLogical-GCD)
- **40340** [Confusion-Aware Spectral Regularizer for Long-Tailed Recognition](https://cvpr.thecvf.com/virtual/2026/oral/40340) — *Ziquan Zhu et al.* · [arxiv](https://arxiv.org/abs/2603.16732)

### 4.3 语义对应、关键点、光流、视频跟踪、表征

- **40275** [From Pairs to Sequences: Track-Aware Policy Gradients for Keypoint Detection](https://cvpr.thecvf.com/virtual/2026/oral/40275) — *yepeng liu et al.* · [arxiv](https://arxiv.org/abs/2602.20630)
- **40295** [Customized Fusion: A Closed-Loop Dynamic Network for Adaptive Multi-Task-Aware Infrared-Visible Image Fusion](https://cvpr.thecvf.com/virtual/2026/oral/40295) — *Zengyi Yang et al.* · [arxiv](https://arxiv.org/abs/2604.08924) [code](https://github.com/YR0211/CLDyN)
- **40305** [MARCO: Navigating the Unseen Space of Semantic Correspondence](https://cvpr.thecvf.com/virtual/2026/oral/40305) — *Claudia Cuttano et al.* · [arxiv](https://arxiv.org/abs/2604.18267) [code](https://github.com/visinf/MARCO)
- **40322** [The SA-FARI Dataset: Segment Anything in Footage of Animals for Recognition and Identification](https://cvpr.thecvf.com/virtual/2026/oral/40322) — *Dante Wasmuht et al.* · [arxiv](https://arxiv.org/abs/2511.15622)
- **40348** [Optical Flow Matching: Reframing Optical Flow as Continuous Transport Dynamics](https://cvpr.thecvf.com/virtual/2026/oral/40348) — *Ao Luo et al.*
- **40366** [Featurising Pixels from Dynamic 3D Scenes with Linear In-Context Learners](https://cvpr.thecvf.com/virtual/2026/oral/40366) — *Nikita Araslanov et al.*
- **40367** [Streaming Diffusion Model for Fast Infrared and Visible Video Fusion](https://cvpr.thecvf.com/virtual/2026/oral/40367) — *Jinyuan Liu et al.*
- **40392** [SEATrack: Simple, Efficient, and Adaptive Multimodal Tracker](https://cvpr.thecvf.com/virtual/2026/oral/40392) — *Junbin Su et al.* · [arxiv](https://arxiv.org/abs/2604.12502) [code](https://github.com/AutoLab-SAI-SJTU/SEATrack)
- **40394** [SDTrack: A Baseline for Event-based Tracking via Spiking Neural Networks](https://cvpr.thecvf.com/virtual/2026/oral/40394) — *Yimeng Shan et al.* · [arxiv](https://arxiv.org/abs/2503.08703)
- **40396** [U$^{2}$Flow: Uncertainty-Aware Unsupervised Optical Flow Estimation](https://cvpr.thecvf.com/virtual/2026/oral/40396) — *Xunpei Sun et al.* · [arxiv](https://arxiv.org/abs/2604.10056) [code](https://github.com/sunzunyi/U2FLOW)

### 4.4 特殊识别 / 人体运动 / 舞蹈 / 手语

- **40280** [ImmerIris: A Large-Scale Dataset and Benchmark for Off-Axis and Unconstrained Iris Recognition in Immersive Applications](https://cvpr.thecvf.com/virtual/2026/oral/40280) — *Yuxi Mi et al.* · [arxiv](https://arxiv.org/abs/2510.10113)
- **40311** [SAM 3D Body: Robust Full-Body Human Mesh Recovery](https://cvpr.thecvf.com/virtual/2026/oral/40311) — *Xitong Yang et al.* · [arxiv](https://arxiv.org/abs/2602.15989) [code](https://github.com/facebookresearch/sam-3d-body)
- **40331** [Plant Taxonomy Meets Plant Counting: A Fine-Grained, Taxonomic Dataset for Counting Hundreds of Plant Species](https://cvpr.thecvf.com/virtual/2026/oral/40331) — *Jinyu Xu et al.* · [arxiv](https://arxiv.org/abs/2603.21229) [code](https://github.com/tiny-smart/TPC-268)
- **40349** [Fine-grained Image Aesthetic Assessment: Learning Discriminative Scores from Relative Ranks](https://cvpr.thecvf.com/virtual/2026/oral/40349) — *Zhichao Yang et al.* · [arxiv](https://arxiv.org/abs/2603.03907)
- **40350** [MAMMA: Markerless Accurate Multi-person Motion Acquisition](https://cvpr.thecvf.com/virtual/2026/oral/40350) — *Hanz Cuevas Velasquez et al.*
- **40351** [Natural Human Motion Recovery by Aligning High-Order Temporal Dynamics from Monocular Videos](https://cvpr.thecvf.com/virtual/2026/oral/40351) — *Dingkun Wei et al.*
- **40354** [SoccerMaster: A Vision Foundation Model for Soccer Understanding](https://cvpr.thecvf.com/virtual/2026/oral/40354) — *Haolin Yang et al.* · [arxiv](https://arxiv.org/abs/2512.11016)
- **40375** [BoostSLT: Boosting Sign Language Translation via a Plug-and-Play Diffusion-Based Semantic Enhancer](https://cvpr.thecvf.com/virtual/2026/oral/40375) — *Changzhou Han et al.*
- **40388** [OpenDance: Multimodal Controllable 3D Dance Generation with Large-scale Internet Data](https://cvpr.thecvf.com/virtual/2026/oral/40388) — *Jinlu Zhang et al.* · [arxiv](https://arxiv.org/abs/2506.07565)

## 5. VLM / MLLM / 多模态推理 / 安全 / Benchmark


### 5.1 多模态推理与能力分析

- **40284** [VS-Bench: Evaluating VLMs for Strategic Abilities in Multi-Agent Environments](https://cvpr.thecvf.com/virtual/2026/oral/40284) — *Zelai Xu et al.* · [arxiv](https://arxiv.org/abs/2506.02387)
- **40303** [GeoViS: Geospatially Rewarded Visual Search for Remote Sensing Visual Grounding](https://cvpr.thecvf.com/virtual/2026/oral/40303) — *Peirong Zhang et al.* · [arxiv](https://arxiv.org/abs/2512.02715)
- **40318** [FINER: MLLMs Hallucinate under Fine-grained Negative Queries](https://cvpr.thecvf.com/virtual/2026/oral/40318) — *Rui Xiao et al.* · [arxiv](https://arxiv.org/abs/2603.17662)
- **40335** [PAI-Bench: A Comprehensive Benchmark For Physical AI](https://cvpr.thecvf.com/virtual/2026/oral/40335) — *Fengzhe Zhou et al.* · [arxiv](https://arxiv.org/abs/2512.01989)
- **40378** [Understanding Task Transfer in Vision-Language Models](https://cvpr.thecvf.com/virtual/2026/oral/40378) — *Bhuvan Sachdeva et al.*
- **40382** [InfiniBench: Infinite Benchmarking for Visual Spatial Reasoning with Customizable Scene Complexity](https://cvpr.thecvf.com/virtual/2026/oral/40382) — *Haoming Wang et al.* · [arxiv](https://arxiv.org/abs/2511.18200)
- **40386** [CodeV: Code with Images for Faithful Visual Reasoning via Tool-Aware Policy Optimization](https://cvpr.thecvf.com/virtual/2026/oral/40386) — *Xinhai Hou et al.* · [arxiv](https://arxiv.org/abs/2511.19661)

### 5.2 MLLM / VLM 安全与攻击防御

- **40299** [Adversarial Style Optimization: Enhancing VLM Jailbreaks by GRPO-based Stylistic Triggers Optimization](https://cvpr.thecvf.com/virtual/2026/oral/40299) — *Bingjun Luo et al.*
- **40357** [TEAR: Temporal-aware Automated Red-teaming for Text-to-Video Models](https://cvpr.thecvf.com/virtual/2026/oral/40357) — *Jiaming He et al.* · [arxiv](https://arxiv.org/abs/2511.21145)
- **40371** [ARGUS: Defending Against Multimodal Indirect Prompt Injection via Steering Instruction-Following Behavior](https://cvpr.thecvf.com/virtual/2026/oral/40371) — *Weikai Lu et al.* · [arxiv](https://arxiv.org/abs/2512.05745)

### 5.3 视频/视觉语言模型能力

- **40278** [Molmo2: Open Weights and Data for Vision-Language Models with Video Understanding and Grounding](https://cvpr.thecvf.com/virtual/2026/oral/40278) — *Christopher Clark et al.* · [arxiv](https://arxiv.org/abs/2601.10611)
- **40326** [PAS: A Training-Free Stabilizer for Temporal Encoding in Video LLMs](https://cvpr.thecvf.com/virtual/2026/oral/40326) — *Bowen Sun et al.* · [arxiv](https://arxiv.org/abs/2511.10979)

## 6. 机器人、Embodied AI、导航、操控、自动驾驶、世界模型


### 6.1 Embodied / Navigation / Manipulation

- **40327** [Memory-Augmented Scene Understanding and Exploration for Open-World Aerial Object-Goal Navigation](https://cvpr.thecvf.com/virtual/2026/oral/40327) — *Jiacong Zhou et al.*
- **40337** [SocialNav: Training Human-Inspired Foundation Model for Socially-Aware Embodied Navigation](https://cvpr.thecvf.com/virtual/2026/oral/40337) — *Ziyi Chen et al.* · [arxiv](https://arxiv.org/abs/2511.21135)
- **40363** [AT-VLA: Adaptive Tactile Injection for Enhanced Feedback Reaction in Vision-Language-Action Models](https://cvpr.thecvf.com/virtual/2026/oral/40363) — *Xiaoqi Li et al.*
- **40389** [Structural Action Transformer for 3D Dexterous Manipulation](https://cvpr.thecvf.com/virtual/2026/oral/40389) — *Xiaohan Lei et al.* · [arxiv](https://arxiv.org/abs/2603.03960)

### 6.2 自动驾驶 / 世界模型 / 场景挖掘

- **40329** [WorldLens: Full-Spectrum Evaluations of Driving World Models in Real World](https://cvpr.thecvf.com/virtual/2026/oral/40329) — *Alan Liang et al.* · [arxiv](https://arxiv.org/abs/2512.10958)
- **40346** [RefAV: Towards Planning Centric Scenario Mining](https://cvpr.thecvf.com/virtual/2026/oral/40346) — *Cainan Davidson et al.* · [arxiv](https://arxiv.org/abs/2505.20981) [code](https://github.com/CainanD/RefAV)
- **40379** [Learning to Drive via Real-World Simulation at Scale](https://cvpr.thecvf.com/virtual/2026/oral/40379) — *Haochen Tian et al.* · [arxiv](https://arxiv.org/abs/2511.23369) [code](https://github.com/OpenDriveLab/SimScale)

### 6.3 游戏智能体

- **40365** [NitroGen: An Open Foundation Model for Generalist Gaming Agents](https://cvpr.thecvf.com/virtual/2026/oral/40365) — *Loïc Magne et al.* · [arxiv](https://arxiv.org/abs/2601.02427)

## 7. 模型压缩、训练效率、优化理论、联邦学习、任务算术


### 7.1 压缩 / 加速 / edge

- **40260** [Mapping Networks](https://cvpr.thecvf.com/virtual/2026/oral/40260) — *Lord Sen et al.*
- **40262** [NuWa: Deriving Lightweight Class-Specific Vision Transformers for Edge Devices](https://cvpr.thecvf.com/virtual/2026/oral/40262) — *Ziteng Wei et al.*
- **40385** [Does YOLO Really Need to See Every Training Image in Every Epoch?](https://cvpr.thecvf.com/virtual/2026/oral/40385) — *Xingxing Xie et al.* · [arxiv](https://arxiv.org/abs/2603.17684)

### 7.2 推理与结构效率

- **40326** [PAS: A Training-Free Stabilizer for Temporal Encoding in Video LLMs](https://cvpr.thecvf.com/virtual/2026/oral/40326) — *Bowen Sun et al.* · [arxiv](https://arxiv.org/abs/2511.10979)
- **40332** [ViT$^3$: Unlocking Test-Time Training in Vision](https://cvpr.thecvf.com/virtual/2026/oral/40332) — *Dongchen Han et al.* · [arxiv](https://arxiv.org/abs/2512.01643) [code](http://github.com/LeapLabTHU/ViTTT)
- **40353** [SeaCache: Spectral-Evolution-Aware Cache for Accelerating Diffusion Models](https://cvpr.thecvf.com/virtual/2026/oral/40353) — *Jiwoo Chung et al.* · [arxiv](https://arxiv.org/abs/2602.18993)
- **40360** [SenCache: Accelerating Diffusion Model Inference via Sensitivity-Aware Caching](https://cvpr.thecvf.com/virtual/2026/oral/40360) — *Yasaman Haghighi et al.* · [arxiv](https://arxiv.org/abs/2602.24208)

### 7.3 优化 / 联邦 / 聚类 / 理论

- **40272** [FedAdamom: Adaptive Momentum for Improved Generalization in Federatedd Optimization](https://cvpr.thecvf.com/virtual/2026/oral/40272) — *Wenjie Hou et al.*
- **40273** [Advancing Image Classification with Discrete Diffusion Classification Modeling](https://cvpr.thecvf.com/virtual/2026/oral/40273) — *Omer Belhasin et al.* · [arxiv](https://arxiv.org/abs/2511.20263) [code](https://github.com/omerb01/didicm)
- **40288** [Scalable Multi-View Subspace Clustering with Tensorized Anchor Guidance](https://cvpr.thecvf.com/virtual/2026/oral/40288) — *Miao Jia et al.*
- **40387** [Understanding and Enforcing Weight Disentanglement in Task Arithmetic](https://cvpr.thecvf.com/virtual/2026/oral/40387) — *Shangge Liu et al.* · [arxiv](https://arxiv.org/abs/2604.17078) [code](https://github.com/RL-MIND/OrthoReg)

### 7.4 数据蒸馏 / 数据质量

- **40285** [Rethinking Dataset Distillation: Hard Truths about Soft Labels](https://cvpr.thecvf.com/virtual/2026/oral/40285) — *Priyam Dey et al.* · [arxiv](https://arxiv.org/abs/2604.18811)
- **40377** [Data Leakage Detection and De-duplication in Large Scale Geospatial Image Datasets](https://cvpr.thecvf.com/virtual/2026/oral/40377) — *Yeshwanth Kumar Adimoolam et al.* · [arxiv](https://arxiv.org/abs/2304.02296) [code](https://github.com/yeshwanth95/Hash_and_search)

## 8. 隐私、安全、水印、版权、成员推断

- **40294** [Erasing Invisible Watermarks via Novel View Synthesis](https://cvpr.thecvf.com/virtual/2026/oral/40294) — *Fahad Shamshad et al.* · [arxiv](https://arxiv.org/abs/2601.08832)
- **40315** [Black-box Membership Inference Attacks on the Pre-training Data of Image-generation Models](https://cvpr.thecvf.com/virtual/2026/oral/40315) — *Tao Qi et al.*
- **40339** [Revisiting Geometric Obfuscation with Dual Convergent Lines for Privacy-Preserving Image Queries in Visual Localization](https://cvpr.thecvf.com/virtual/2026/oral/40339) — *Jeonggon Kim et al.*
- **40342** [NOWA: Null-space Optical Watermark for Invisible Capture Fingerprinting and Tamper Localization](https://cvpr.thecvf.com/virtual/2026/oral/40342) — *Edwin Vargas et al.* · [arxiv](https://arxiv.org/abs/2512.22501)
- **40383** [LDP-Slicing: Local Differential Privacy for Images via Randomized Bit-Plane Slicing](https://cvpr.thecvf.com/virtual/2026/oral/40383) — *Yuanming Cao et al.* · [arxiv](https://arxiv.org/abs/2603.03711)


## 9. 数据集 / Benchmark 型论文

- **40280** [ImmerIris: A Large-Scale Dataset and Benchmark for Off-Axis and Unconstrained Iris Recognition in Immersive Applications](https://cvpr.thecvf.com/virtual/2026/oral/40280) — *Yuxi Mi et al.* · [arxiv](https://arxiv.org/abs/2510.10113)
- **40308** [OccuFly: A 3D Vision Benchmark for Semantic Scene Completion from the Aerial Perspective](https://cvpr.thecvf.com/virtual/2026/oral/40308) — *Markus Gross et al.* · [arxiv](https://arxiv.org/abs/2512.20770) [code](https://github.com/markus-42/occufly)
- **40310** [3DReflecNet: A Large-Scale Dataset for 3D Reconstruction of Reflective, Transparent, and Low-Texture Objects](https://cvpr.thecvf.com/virtual/2026/oral/40310) — *Zhicheng Liang et al.*
- **40322** [The SA-FARI Dataset: Segment Anything in Footage of Animals for Recognition and Identification](https://cvpr.thecvf.com/virtual/2026/oral/40322) — *Dante Wasmuht et al.* · [arxiv](https://arxiv.org/abs/2511.15622)
- **40328** [OLATverse: A Large-scale Real-world Object Dataset with Precise Lighting Control](https://cvpr.thecvf.com/virtual/2026/oral/40328) — *Xilong Zhou et al.* · [arxiv](https://arxiv.org/abs/2511.02483)
- **40329** [WorldLens: Full-Spectrum Evaluations of Driving World Models in Real World](https://cvpr.thecvf.com/virtual/2026/oral/40329) — *Alan Liang et al.* · [arxiv](https://arxiv.org/abs/2512.10958)
- **40331** [Plant Taxonomy Meets Plant Counting: A Fine-Grained, Taxonomic Dataset for Counting Hundreds of Plant Species](https://cvpr.thecvf.com/virtual/2026/oral/40331) — *Jinyu Xu et al.* · [arxiv](https://arxiv.org/abs/2603.21229) [code](https://github.com/tiny-smart/TPC-268)
- **40335** [PAI-Bench: A Comprehensive Benchmark For Physical AI](https://cvpr.thecvf.com/virtual/2026/oral/40335) — *Fengzhe Zhou et al.* · [arxiv](https://arxiv.org/abs/2512.01989)
- **40343** [CineBrain: A Large-Scale Multi-Modal Brain Dataset During Naturalistic Audiovisual Narrative Processing](https://cvpr.thecvf.com/virtual/2026/oral/40343) — *Jianxiong Gao et al.* · [arxiv](https://arxiv.org/abs/2503.06940)
- **40354** [SoccerMaster: A Vision Foundation Model for Soccer Understanding](https://cvpr.thecvf.com/virtual/2026/oral/40354) — *Haolin Yang et al.* · [arxiv](https://arxiv.org/abs/2512.11016)
- **40382** [InfiniBench: Infinite Benchmarking for Visual Spatial Reasoning with Customizable Scene Complexity](https://cvpr.thecvf.com/virtual/2026/oral/40382) — *Haoming Wang et al.* · [arxiv](https://arxiv.org/abs/2511.18200)


