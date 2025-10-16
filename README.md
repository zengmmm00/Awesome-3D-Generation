+ # Awesome-3D-Generation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
  
  A curated list of recent diffusion models for 3D generation.
  
  ## Table of Contents <!-- omit in toc -->
  
  - [Websites](#toolboxes-and-foundation-models)
  - [Implicit Shape](#implicit-shape)
  - [3DGS](#3DGS)
  - [Mesh](#Mesh)
  
  ## Websites
  
  - [Hunyuan3D](https://3d.hunyuan.tencent.com/)
  
  + [Tripo AI](https://www.tripo3d.ai/)
  
  ## Implicit Shape
  
  |                           Preview                            | Title                                                        |           Publication           |                            Links                             |
  | :----------------------------------------------------------: | :----------------------------------------------------------- | :-----------------------------: | :----------------------------------------------------------: |
  | <img src="assets/img/TripoSF.jpg" width="300"> | SparseFlex: High-Resolution and Arbitrary-Topology 3D Shape Modeling (TripoSF) |           arXiv 2025            | [Paper](https://arxiv.org/pdf/2503.21732) <br> [Code](https://github.com/VAST-AI-Research/TripoSF) |
  | <img src="assets/img/Ultra3D.jpg" width="300"> | Ultra3D: Efficient and High-Fidelity 3D Generation with Part Attention |           arXiv 2025            |        [Paper](https://arxiv.org/pdf/2507.17745.pdf)         |
  | <img src="assets/img/Sparc3D.jpg" width="300"> | Sparc3D: Sparse Representation and Construction for High-Resolution 3D Shapes Modeling |           arXiv 2025            |          [Paper](https://arxiv.org/pdf/2505.14521)           |
  | <img src="assets/img/HierOctFusion.jpg" width="300"> | HierOctFusion: Multi-scale Octree-based 3D Shape Generation via Part-Whole-Hierarchy Message Passing |           arXiv 2024            |          [Paper](https://arxiv.org/pdf/2508.11106)           |
  | <img src="assets/img/TRELLIS.jpg" width="300"> | TRELLIS: Structured 3D Latents for Scalable and Versatile 3D Generation |            CVPR 2025            | [Paper](https://arxiv.org/pdf/2412.01506) <br> [Code](https://github.com/microsoft/TRELLIS) |
  | <img src="assets/img/OctFusion.jpg" width="300"> | OctFusion: Octree-based Diffusion Models for 3D Shape Generation |            SGP 2025             | [Paper](https://arxiv.org/pdf/2408.14732) <br> [Code](https://github.com/octree-nn/octfusion) |
  | <img src="assets/img/LaGeM.jpg" width="300"> | LaGeM: A Large Geometry Model for 3D Representation Learning and Diffusion |            ICLR 2025            | [Paper](https://arxiv.org/abs/2410.01295) <br> [Code](https://github.com/1zb/LaGeM) <br> [Project](https://1zb.github.io/LaGeM/) |
  | <img src="assets/img/XCube.jpg" width="300"> | XCube: Large-Scale 3D Generative Modeling using Sparse Voxel Hierarchies |            CVPR 2024            | [Paper](https://arxiv.org/pdf/2312.03806) <br> [Code](https://github.com/nv-tlabs/XCube) |
  | <img src="assets/img/SplatSDF.jpg" width="300"> | SplatSDF: Boosting Neural Implicit SDF via Gaussian Splatting Fusion |           arXiv 2024            |          [Paper](https://arxiv.org/pdf/2411.15468)           |
  | <img src="assets/img/MeshFormer.jpg" width="300"> | MeshFormer: High-Quality Mesh Generation with 3D-Guided Reconstruction Model |           arXiv 2024            |          [Paper](https://arxiv.org/pdf/2408.10198)           |
  | <img src="assets/img/Mosaic-SDF.jpg" width="300"> | Mosaic-SDF for 3D Generative Models                          |           arXiv 2024            |          [Paper](https://arxiv.org/pdf/2312.09222)           |
  | <img src="assets/img/CraftsMan.jpg" width="300"> | CraftsMan: High-fidelity Mesh Generation with 3D Native Generation and Interactive Geometry Refiner |           arXiv 2024            | [Paper](https://arxiv.org/pdf/2405.14979) <br> [Code](https://github.com/wyysf-98/CraftsMan3D) |
  | <img src="assets/img/GSDF.jpg" width="300"> | GSDF: 3DGS Meets SDF for Improved Neural Rendering and Reconstruction |          NeurIPS 2024           |          [Paper](https://arxiv.org/pdf/2403.16964)           |
  | <img src="assets/img/GEM3D.jpg" width="300"> | GEM3D: GEnerative Medial Abstractions for 3D Shape Synthesis |          SIGGRAPH 2024          | [Paper](https://arxiv.org/abs/2402.16994) <br> [Code](https://github.com/lodurality/GEM3D_paper_code) <br> [Project](https://lodurality.github.io/GEM3D/) |
  | <img src="assets/img/SurroundSDF.jpg" width="300"> | SurroundSDF: Implicit 3D Scene Understanding Based on Signed Distance Field |            CVPR 2024            | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_SurroundSDF_Implicit_3D_Scene_Understanding_Based_on_Signed_Distance_Field_CVPR_2024_paper.pdf) |
  | <img src="assets/img/HSDF.jpg" width="300"> | HSDF: Hybrid Sign and Distance Field for Neural Representation of Surfaces With Arbitrary Topologies |            IEEE 2024            |   [Paper](https://ieeexplore.ieee.org/document/10636762/)    |
  | <img src="assets/img/3DShape2VecSet.jpg" width="300"> | 3DShape2VecSet: A 3D Shape Representation for Neural Fields and Generative Diffusion Models |          ACM TOG 2023           | [Paper](https://arxiv.org/pdf/2301.11445) <br> [Code](https://github.com/1zb/3DShape2VecSet) |
  | <img src="assets/img/LocallyAttentionalSDF.jpg" width="300"> | Locally Attentional SDF Diffusion for Controllable 3D Shape Generation |          ACM TOG 2023           |          [Paper](https://arxiv.org/pdf/2305.04461)           |
  | <img src="assets/img/DiffusionSDF.jpg" width="300"> | Diffusion-SDF: Conditional Generative Modeling of Signed Distance Functions |            ICCV 2023            | [Paper](https://light.princeton.edu/publication/diffusion-sdf/) <br> [Project](https://light.princeton.edu/publication/diffusion-sdf/) |
  | <img src="assets/img/CSG-Neural-SDF.jpg" width="300"> | Constructive Solid Geometry on Neural Signed Distance Fields |     ACM SIGGRAPH Asia 2023      | [Paper](https://dl.acm.org/doi/fullHtml/10.1145/3610548.3618170) <br> [Project](https://zoemarschner.com/research/csg_on_neural_sdfs.html) |
  | <img src="assets/img/SDFusion.jpg" width="300"> | SDFusion: Multimodal 3D Shape Completion, Reconstruction, and Generation |            CVPR 2023            | [Paper](https://yccyenchicheng.github.io/SDFusion/) <br> [Code](https://github.com/yccyenchicheng/SDFusion) |
  | <img src="assets/img/SDF-Diffusion.jpg" width="300"> | SDF-Diffusion: Text-to-Shape via Voxelized Diffusion         |            CVPR 2023            |          [Paper](https://arxiv.org/pdf/2212.03293)           |
  | <img src="assets/img/MeshDiffusion.jpg" width="300"> | MeshDiffusion: Score-based Generative 3D Mesh Modeling       |            ICLR 2023            | [Paper](https://arxiv.org/pdf/2303.08133) <br> [Code](https://github.com/lzzcd001/MeshDiffusion) |
  | <img src="assets/img/SDF-StyleGAN.jpg" width="300"> | SDF-StyleGAN: Implicit SDF-Based StyleGAN for 3D Shape Generation |            SGP 2022             | [Paper](https://arxiv.org/pdf/2206.12055) <br> [Code](https://github.com/Zhengxinyang/SDF-StyleGAN) |
  | <img src="assets/img/neural_wavelet.jpg" width="300"> | Neural Wavelet-domain Diffusion for 3D Shape Generation, Inversion, and Manipulation | SIGGRAPH Asia 2022 <br> ACM TOG | [Paper](https://arxiv.org/abs/2302.00190) <br> [Code](https://github.com/edward1997104/Wavelet-Generation) |
  | <img src="assets/img/AutoSDF.jpg" width="300"> | AutoSDF: Shape Priors for 3D Completion, Reconstruction and Generation |            CVPR 2022            |          [Paper](https://arxiv.org/pdf/2203.09516)           |
  | <img src="assets/img/3DILG.jpg" width="300"> | 3DILG: Irregular Latent Grids for 3D Generative Modeling     |          NeurIPS 2022           | [Paper](https://arxiv.org/abs/2205.13914) <br> [Code](https://github.com/1zb/3DILG) <br> [Project](https://1zb.github.io/3DILG/) |
  | <img src="assets/img/NeuS.jpg" width="300"> | NeuS: Learning Neural Implicit Surfaces by Volume Rendering for Multi-view Reconstruction |          NeurIPS 2021           | [Paper](https://arxiv.org/pdf/2106.10689) <br> [Code](https://github.com/Totoro97/NeuS) |
  | <img src="assets/img/SIREN.jpg" width="300"> | SIREN: Implicit Neural Representations with Periodic Activation Functions |          NeurIPS 2020           | [Paper](https://arxiv.org/pdf/2006.09661) <br> [Code](https://github.com/vsitzmann/siren) |
  | <img src="assets/img/DeepSDF.jpg" width="300"> | DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation |            CVPR 2019            | [Paper](https://arxiv.org/pdf/1901.05103) <br> [Code](https://github.com/facebookresearch/DeepSDF) |
  | <img src="assets/img/NDF.jpg" width="300"> | Neural Unsigned Distance Fields for Implicit Function Learning |          NeurIPS 2020           |          [Paper](https://arxiv.org/pdf/2010.13938)           |
  | <img src="assets/img/ConvOccNets.jpg" width="300"> | Convolutional Occupancy Networks                             |            ECCV 2020            | [Paper](https://arxiv.org/pdf/2003.04618) <br> [Code](https://github.com/autonomousvision/convolutional_occupancy_networks) |
  | <img src="assets/img/IM-Net.jpg" width="300"> | IM-Net: Learning Implicit Fields for Generative Shape Modeling |            CVPR 2019            | [Paper](https://arxiv.org/abs/1812.02822) <br> [Code](https://github.com/czq142857/implicit-decoder) |
  
  ## 3DGS
  
  |                           Preview                            | Title                                                        |          Publication           |                            Links                             |
  | :----------------------------------------------------------: | :----------------------------------------------------------- | :----------------------------: | :----------------------------------------------------------: |
  | <img src="assets/img/VRSplat.jpg" width="300"> | VRSplat: Fast and Robust Gaussian Splatting for Virtual Reality |           arXiv 2025           |          [Paper](https://arxiv.org/pdf/2505.10144)           |
  | <img src="assets/img/GaussianSDF.jpg" width="300"> | Gaussian Splatting with Discretized SDF for Relightable Assets |           arXiv 2025           |          [Paper](https://arxiv.org/pdf/2507.15629)           |
  | <img src="assets/img/GaussianCompression.jpg" width="300"> | Enhancing 3D Gaussian Splatting Compression via Spatial Condition-based Prediction |           arXiv 2025           |          [Paper](https://arxiv.org/pdf/2503.23337)           |
  | <img src="assets/img/GSurvey2024.jpg" width="300"> | 3D Gaussian Splatting as a New Era: A Survey                 |         IEEE TVCG 2024         |   [Paper](https://ieeexplore.ieee.org/document/10521791/)    |
  | <img src="assets/img/WildGaussians.jpg" width="300"> | WildGaussians: 3D Gaussian Splatting In the Wild             |          NeurIPS 2024          |    [Paper](https://neurips.cc/virtual/2024/poster/95434)     |
  | <img src="assets/img/SpecGaussian.jpg" width="300"> | Spec-Gaussian: Anisotropic View-Dependent Appearance for 3D Gaussian Splatting |          NeurIPS 2024          |      [Paper](https://nips.cc/virtual/2024/poster/93509)      |
  | <img src="assets/img/ODGS.jpg" width="300"> | ODGS: 3D Scene Reconstruction from Omnidirectional Images with 3D Gaussian Splattings |          NeurIPS 2024          | [Paper](https://arxiv.org/pdf/2410.20686) <br> [Code](https://github.com/esw0116/ODGS) |
  | <img src="assets/img/DOGS.jpg" width="300"> | DOGS: Distributed-Oriented Gaussian Splatting for Large-Scale 3D Reconstruction |          NeurIPS 2024          | [Paper](https://arxiv.org/pdf/2405.13943) <br> [Code](https://github.com/AIBluefisher/DOGS) |
  | <img src="assets/img/FreeSplat.jpg" width="300"> | FreeSplat: Generalizable 3D Gaussian Splatting for Free-View Synthesis |          NeurIPS 2024          | [Paper](https://arxiv.org/pdf/2405.17958) <br> [Code](https://github.com/wangys16/FreeSplat) |
  | <img src="assets/img/MCMCGS.jpg" width="300"> | 3D Gaussian Splatting as Markov Chain Monte Carlo            |    NeurIPS 2024 (Spotlight)    |          [Paper](https://arxiv.org/pdf/2404.09591)           |
  | <img src="assets/img/3iGS.jpg" width="300"> | 3iGS: Factorised Tensorial Illumination for 3D Gaussian Splatting |           ECCV 2024            |   [Paper](https://eccv.ecva.net/virtual/2024/poster/2035)    |
  | <img src="assets/img/HeadStudio.jpg" width="300"> | HeadStudio: Text to Animatable Head Avatars with 3D Gaussian Splatting |           ECCV 2024            | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-73411-3_9) |
  | <img src="assets/img/GaussianGrouping.jpg" width="300"> | Gaussian Grouping: Segment and Edit Anything in 3D Scenes    |           ECCV 2024            | [Paper](https://arxiv.org/pdf/2312.00732) <br> [Code](https://github.com/lkeab/gaussian-grouping) |
  | <img src="assets/img/2DGS.jpg" width="300"> | 2D Gaussian Splatting for Geometrically Accurate Radiance Fields |         SIGGRAPH 2024          | [Paper](https://arxiv.org/pdf/2403.17888.pdf) <br> [Code](https://github.com/hbb1/2d-gaussian-splatting) |
  | <img src="assets/img/RecentAdvances.jpg" width="300"> | Recent Advances in 3D Gaussian Splatting                     |           arXiv 2024           |          [Paper](https://arxiv.org/pdf/2403.11134)           |
  | <img src="assets/img/COLMAPFREE.jpg" width="300"> | COLMAP-Free 3D Gaussian Splatting                            |           CVPR 2024            | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Fu_COLMAP-Free_3D_Gaussian_Splatting_CVPR_2024_paper.pdf) |
  | <img src="assets/img/GaussianSLAM.jpg" width="300"> | Gaussian Splatting SLAM                                      |     CVPR 2024 (Best Demo)      | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Matsuki_Gaussian_Splatting_SLAM_CVPR_2024_paper.html) |
  | <img src="assets/img/MipSplatting.jpg" width="300"> | Mip-Splatting: Alias-free 3D Gaussian Splatting              | CVPR 2024 (Best Student Paper) | [Paper](https://arxiv.org/pdf/2311.16493) <br> [Code](https://niujinshuchong.github.io/mip-splatting/) |
  | <img src="assets/img/DreamGaussian.jpg" width="300"> | DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation |        ICLR 2024 (Oral)        | [Paper](https://arxiv.org/pdf/2309.16653.pdf) <br> [Code](https://github.com/dreamgaussian/dreamgaussian) |
  | <img src="assets/img/3DGS.jpg" width="300"> | 3D Gaussian Splatting for Real-Time Radiance Field Rendering |         SIGGRAPH 2023          | [Paper](https://arxiv.org/pdf/2308.04079.pdf) <br> [Code](https://github.com/graphdeco-inria/gaussian-splatting) |
  | <img src="assets/img/ASurvey.jpg" width="300"> | A Survey on 3D Gaussian Splatting                            |           arXiv 2024           |          [Paper](https://arxiv.org/pdf/2401.03890)           |
  | <img src="assets/img/SuGaR.jpg" width="300"> | SuGaR: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction and High-Quality Mesh Rendering |           CVPR 2024            | [Paper](https://github.com/Anttwo/SuGaR) <br> [Code](https://github.com/Anttwo/SuGaR) |
  
  ## Mesh
  
  |                           Preview                            | Title                                                        |    Publication     |                            Links                             |
  | :----------------------------------------------------------: | :----------------------------------------------------------- | :----------------: | :----------------------------------------------------------: |
  | <img src="assets/img/VertexRegen.jpg" width="300"> | VertexRegen: Mesh Generation with Continuous Level of Detail |     arXiv 2025     | [Paper](https://arxiv.org/pdf/2508.09062) <br> [Project](https://vertexregen.github.io/) |
  | <img src="assets/img/FastMesh.jpg" width="300"> | FastMesh: Efficient Artistic Mesh Generation via Component Decoupling |     arXiv 2025     |          [Paper](https://arxiv.org/pdf/2508.19188)           |
  | <img src="assets/img/LLaMAMesh.jpg" width="300"> | LLaMA-Mesh: Unifying 3D Mesh Generation with Language Models |     arXiv 2024     | [Paper](https://arxiv.org/pdf/2411.09595) <br> [Code](https://github.com/nv-tlabs/LLaMA-Mesh) <br> [Demo](https://huggingface.co/spaces/Zhengyi/LLaMA-Mesh) |
  | <img src="assets/img/FreeMesh.jpg" width="300"> | FreeMesh: Boosting Mesh Generation with Coordinates Merging  |     ICML 2025      |          [Paper](https://arxiv.org/pdf/2505.13573)           |
  | <img src="assets/img/MeshRFT.jpg" width="300"> | Mesh-RFT: Enhancing Mesh Generation via Fine-grained Reinforcement Fine-Tuning |     arXiv 2025     |          [Paper](https://arxiv.org/pdf/2505.16761)           |
  | <img src="assets/img/ScalingMesh.jpg" width="300"> | Scaling mesh generation via compressive tokenization         |     CVPR 2025      | [Paper](https://arxiv.org/pdf/2411.07025) <br> [Project](https://whaohan.github.io/bpt/) <br> [Code](https://github.com/tencent-hunyuan/bpt) |
  | <img src="assets/img/iFlame.jpg" width="300"> | iFlame: Interleaving Full and Linear Attention for Efficient Mesh Generation |     arXiv 2025     | [Paper](https://arxiv.org/pdf/2503.16653) <br> [Code](https://github.com/hanxiaowang00/iFlame) |
  | <img src="assets/img/MeshSilksong.jpg" width="300"> | Mesh Silksong: Auto-Regressive Mesh Generation as Weaving Silk |     arXiv 2025     |          [Paper](https://arxiv.org/pdf/2507.02477)           |
  | <img src="assets/img/MeshPad.jpg" width="300"> | MeshPad: Interactive Sketch-Conditioned Artist-Designed Mesh Generation and Editing |     arXiv 2025     | [Paper](https://arxiv.org/pdf/2503.01425) <br> [Project](https://derkleineli.github.io/meshpad/) |
  | <img src="assets/img/DeepMesh.jpg" width="300"> | DeepMesh: Auto-Regressive Artist-mesh Creation with Reinforcement Learning |     ICCV 2025      | [Paper](https://arxiv.org/pdf/2503.15265) <br> [Project](https://zhaorw02.github.io/DeepMesh/) <br> [Code](https://github.com/zhaorw02/DeepMesh) |
  | <img src="assets/img/EdgeRunner.jpg" width="300"> | EdgeRunner: Auto-regressive Auto-encoder for Artistic Mesh Generation |     ICLR 2025      | [Paper](https://arxiv.org/pdf/2409.18114) <br> [Code](https://github.com/NVlabs/EdgeRunner) |
  | <img src="assets/img/MeshArt.jpg" width="300"> | MeshArt: Generating Articulated Meshes with Structure-guided Transformers |     CVPR 2025      | [Paper](https://arxiv.org/pdf/2412.11596) <br> [Code](https://github.com/DaoyiG/MeshArt) |
  | <img src="assets/img/TreeMeshGPT.jpg" width="300"> | TreeMeshGPT: Topology-Aware Mesh Generation with Tree-Structured Graph Priors |     CVPR 2025      |          [Paper](https://arxiv.org/pdf/2503.11629)           |
  | <img src="assets/img/Meshtron.jpg" width="300"> | Meshtron: High-Fidelity, Artist-Like 3D Mesh Generation at Scale |     arXiv 2024     | [Paper](https://arxiv.org/pdf/2412.09548) <br> [Project](https://meshtron.github.io/) |
  | <img src="assets/img/MeshAnythingV2.jpg" width="300"> | MeshAnything V2: Artist-Created Mesh Generation With Adjacent Mesh Tokenization |     ICCV 2025      | [Paper](https://arxiv.org/pdf/2408.02555) <br> [Project](https://buaacyw.github.io/meshanything-v2/) <br> [Code](https://github.com/buaacyw/MeshAnything) |
  | <img src="assets/img/MeshXL.jpg" width="300"> | MeshXL: Neural Coordinate Field for Generative 3D Foundation Models |    NeurIPS 2024    | [Paper](https://arxiv.org/pdf/2405.20853) <br> [Code](https://github.com/OpenMeshLab/MeshXL) |
  | <img src="assets/img/SpaceMesh.jpg" width="300"> | SpaceMesh: A Continuous Representation for Learning Manifold Surface Meshes | SIGGRAPH Asia 2024 | [Paper](https://arxiv.org/pdf/2409.20562) <br> [Project](https://research.nvidia.com/labs/toronto-ai/space-mesh/) |
  | <img src="assets/img/PivotMesh.jpg" width="300"> | PivotMesh: Generic 3D Mesh Generation via Pivot Vertices Guidance |     ICLR 2025      | [Paper](https://arxiv.org/pdf/2405.16890) <br> [Project](https://whaohan.github.io/pivotmesh/) <br> [Code](https://github.com/whaohan/pivotmesh) |
  | <img src="assets/img/MeshAnything.jpg" width="300"> | MeshAnything: Artist-Created Mesh Generation with Autoregressive Transformers |     ICLR 2025      | [Paper](https://arxiv.org/pdf/2406.10163) <br> [Project](https://buaacyw.github.io/mesh-anything/) <br> [Code](https://github.com/buaacyw/MeshAnything) |
  | <img src="assets/img/MeshGPT.jpg" width="300"> | MeshGPT: Generating Triangle Meshes with Decoder-Only Transformers |     CVPR 2024      | [Paper](https://arxiv.org/pdf/2311.15475) <br> [Code](https://github.com/lucidrains/meshgpt-pytorch) |
  | <img src="assets/img/PolyDiff.jpg" width="300"> | PolyDiff: Generating 3D Polygonal Meshes with Diffusion Models |     arXiv 2023     |          [Paper](https://arxiv.org/pdf/2312.11417)           |
  | <img src="assets/img/PolyGen.jpg" width="300"> | PolyGen: An Autoregressive Generative Model of 3D Meshes     |     ICML 2020      | [Paper](https://arxiv.org/pdf/2002.10880) <br> [Code](https://github.com/google-deepmind/deepmind-research/tree/master/polygen) |
  
  
  ---
