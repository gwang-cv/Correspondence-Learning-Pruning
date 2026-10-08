# Correspondence Learning/Pruning

![Correspondence-Learning-Pruning](corrprun.png)

A curated list of correspondence learning, outlier pruning, feature matching, and related geometric vision resources.

**Last literature check: 2026-10-08.** The [2026 update](#2026) screens NeurIPS (formerly NIPS), ICLR, ICML, CVPR, ICCV, AAAI, ECCV, 3DV, TPAMI, TIP, and TMM for published or officially accepted papers. Entries are selected for relevance; this is not an exhaustive survey. Earlier collections are retained, including venues outside this update's scope.

- [2026 correspondence learning and pruning](#2026)
- [2026 related applications](#2026-related-applications)
- [Search scope and verification](#search-scope-and-verification)

#### 2018
- [LFGC] Learning to Find Good Correspondences, CVPR 2018 [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1453.pdf) [[code]](https://github.com/vcg-uvic/learned-correspondence-release) 
- [DFE] Deep fundamental matrix estimation, ECCV 2018 [[code]](https://github.com/isl-org/DFE)
- [N3Net] Neural Nearest Neighbors Networks, NeurIPS 2018 [[code]](https://github.com/visinf/n3net/)
#### 2019
- [OANet] Learning Two-View Correspondences and Geometry Using Order-Aware Network ICCV 2019 [[code]](https://github.com/zjhthu/OANet)
- [NM-Net] NM-Net: Mining Reliable Neighbors for Robust Feature Correspondences, arXiv 2019 [[pdf]](https://arxiv.org/pdf/1904.00320)
- [NG-RANSAC] Neural-Guided RANSAC: Learning Where to Sample Model Hypotheses, ICCV 2019 [[pdf](https://arxiv.org/pdf/1905.04132.pdf)] [[code](https://github.com/vislearn/ngransac)] [[project](https://hci.iwr.uni-heidelberg.de/vislearn/research/neural-guided-ransac/)]
#### 2020
- [ACNe] ACNe: Attentive context normalization for robust permutation-equivariant learning, CVPR 2020[[code]](https://github.com/vcg-uvic/acne)
- [SuperGlue] SuperGlue: Learning Feature Matching with Graph Neural Networks, CVPR 2020 [[code]](https://github.com/magicleap/SuperGluePretrainedNetwork)
#### 2021
- [SGMNet] Learning to Match Features with Seeded Graph Matching Network, ICCV 2021 [[pdf](https://ieeexplore.ieee.org/document/9711340/)]
- [LMCNet] Learnable Motion Coherence for Correspondence Pruning, CVPR 2021 [[code]](https://liuyuan-pal.github.io/LMCNet/)
- [CLNet] Progressive Correspondence Pruning by Consensus Learning, ICCV 2021 [[code]](https://sailor-z.github.io/projects/CLNet)
- [T-Net] T-Net: Effective Permutation-Equivariant Network for Two-View Correspondence Learning, ICCV 2021 [[code]](https://github.com/x-gb/T-Net)
- [GLHA] Cascade Network with Guided Loss and Hybrid Attention for Finding Good Correspondences, AAAI 2021 [[code]](https://github.com/wenbingtao/GLHA)
#### 2022
- [CAT] Correspondence Attention Transformer: A Context-sensitive Network for Two-view Correspondence Learning, TMM 2022 [[code]](https://github.com/jiayi-ma/CorresAttnTransformer)
- [MS2DG-Net] MS2DG-Net: Progressive Correspondence Learning via Multiple Sparse Semantics Dynamic Graph, CVPR 2022 [[code]](https://github.com/changcaiyang/MS2DG-Net)
- [MQ-Net] Learning To Find Good Models in RANSAC, CVPR 2022 [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Barath_Learning_To_Find_Good_Models_in_RANSAC_CVPR_2022_paper.pdf) [[code]](https://github.com/danini/learning-good-models-in-ransac)
- [CSDA-Net] CSDA-Net: Seeking reliable correspondences by channel-Spatial difference augment network, PR 2022 [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0031320322000206)
- [MSA-Net] MSA-Net: Establishing Reliable Correspondences by Multiscale Attention Network, TIP 2022 [[code]](https://github.com/guobaoxiao/MSANet)
#### 2023
- [ConvMatch] ConvMatch: Rethinking Network Design for Two-View Correspondence Learning, AAAI 2023 [[code]](https://github.com/SuhZhang/ConvMatch)
- [NCMNet] Progressive Neighbor Consistency Mining for Correspondence Pruning, CVPR 2023 [[code]](https://github.com/xinliu29/NCMNet)
- [∇-RANSAC] Generalized Differentiable RANSAC, ICCV 2023 [[code]](https://github.com/weitong8591/differentiable_ransac)
- [RLSAC] RLSAC: Reinforcement Learning Enhanced Sample Consensus for End-to-End Robust Estimation, ICCV 2023 [[code]](https://github.com/IRMVLab/RLSAC)
- [U-Match] U-Match: Two-view Correspondence Learning with Hierarchy-aware Local Context Aggregation, IJCAI 2023 [[code]](https://github.com/ZizhuoLi/U-Match)
- [ANANet] Learning Second-Order Attentive Context for Efficient Correspondence Pruning, AAAI 2023 [[code]](https://github.com/DIVE128/ANANet)
- [MSA-Net] Local Consensus Enhanced Siamese Network with Reciprocal Loss for Two-view Correspondence Learning, MM 2023 
- [PGFNet] PGFNet: Preference-Guided Filtering Network for Two-View Correspondence Learning, TIP 2023 [[pdf]](https://ieeexplore.ieee.org/document/10041834/) [[code]](https://github.com/guobaoxiao/PGFNet)
- [JRA-Net] JRA-Net: Joint representation attention network for correspondence learning, PR 2023 [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0031320322006598)
#### 2024
- [MaKeGNN] Learning Feature Matching via Matchable Keypoint-Assisted Graph Neural Network, TIP 2024 [[pdf]](http://arxiv.org/abs/2307.01447)
- [DHM-Net] DHM-Net: Deep Hypergraph Modeling  for Robust Feature Matching, TIP 2024 [[code]](https://github.com/CSX777/DHM-Net)
- [ResMatch] ResMatch: Residual Attention Learning for Feature Matching, AAAI 2024 [[code]](https://github.com/ACuOoOoO/ResMatch)
- [GCT-Net] Graph Context Transformation Learning for Progressive Correspondence Pruning, AAAI 2024 [[code]](https://github.com/JunwenGuo/GCT-Net)
- [TrGa] TrGa: Reconsidering the Application of Graph Neural Networks in Two-View Correspondence Pruning, MM 2024 [[code]](https://github.com/Dailuanyuan2024/TrGa2024)
- [CorrMAE] CorrMAE: Pre-training Correspondence Transformers with Masked Autoencoder, arxiv 2024 [[pdf]](https://arxiv.org/pdf/2406.05773)
- [VSFormer] VSFormer: Visual-Spatial Fusion Transformer for Correspondence Pruning, AAAI 2024 [[code]](https://github.com/sugar-fly/VSFormer)
- [MGNet] MGNet: Learning Correspondences via Multiple Graphs, AAAI 2024 [[code]](https://github.com/DAILUANYUAN/MGNet-2024AAAI)
- [BCLNet] BCLNet: Bilateral Consensus Learning for Two-View Correspondence Pruning, AAAI 2024 [[code]](https://github.com/guobaoxiao/BCLNet)
- [MSGSA] Multi-Stage Network With Geometric Semantic Attention for Two-View Correspondence Learning, TIP 2024 [[code]](https://github.com/shuyuanlin/MSGSA)
- [SSL-Net] SSL-Net: Sparse semantic learning for identifying reliable correspondences, PR 2024 [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0031320323007367)
- [DeMatch] DeMatch: Deep Decomposition of Motion Field for Two-View Correspondence Learning, CVPR 2024 [[code]](https://github.com/SuhZhang/DeMatch)
- [CorrAdaptor] CorrAdaptor: Adaptive Local Context Learning for Correspondence Pruning, ECAI 2024 [[code]](https://github.com/TaoWangzj/CorrAdaptor)
- [NACNet] Consensus Learning with Deep Sets for Essential Matrix Estimation, NeurIPS 2024 [[code]](https://github.com/drormoran/NACNet)
#### 2025
- [MGCANet] MGCA-Net: Multi-graph contextual attention network for two-view correspondence learning, IJCAI 2025 [[code]](https://github.com/shuyuanlin/MGCANet)
- [DeMo] Deep motion field consensus with learnable kernels for two-view correspondence learning, AAAI 2025 [[code]](https://github.com/JiajunLe/DeMo)
- [MambaMatch] MambaMatch: Establishing Reliable Correspondences via Multi-Scale State Space Model, TIP 2025 [[code]](https://github.com/mxyttkx/MambaMatch)
- [GSLC] Grid-Guided Sparse Laplacian Consensus for Robust Feature Matching, TIP 2025 [[code]](https://github.com/XiaYifan1999/GSLC)
- [CSBCNet] Two-View Correspondence Pruning via Channel-Spatial Interaction and Bidirectional Consensus Interaction, MM 2025 [[code]](https://github.com/jiaowohxg/CSBCNet)
- [CorrNeXt] CorrNeXt: Making the ConvNet-Style Correspondence Pruner Stronger for Two-View Geometry,  MM 2025 [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3746027.3755350)
- [TransMatch] TransMatch: Transformer-based correspondence pruning via local and global consensus, PR 2025 [[code]](https://github.com/lyz8023lyp/TransMatch/)
- [SGNNet] Seed to Prune: A Seeded Graph Neural Network for Two-View Correspondence Learning, TNNLS 2025 [[code]](https://github.com/ZizhuoLi/SGNNet) 
- [HAT-Match] HAT-Match: Graph Transformer with Hybrid Attention for Two-View Correspondence Pruning, ECAI 2025 [[code]](https://github.com/gwang-cv/HAT-Match)
#### 2026

The following **20 papers** have a verified 2026 publication or official conference-program listing. NeurIPS entries are **accepted / scheduled**: the conference is still upcoming at the verification date, so these are not described as already published proceedings.

##### Correspondence learning, pruning, and robust estimation

- **[ISR-Net]** Correspondence Pruning by Iterative Structural Rectification, **NeurIPS 2026 (accepted / scheduled)** [[official]](https://neurips.cc/virtual/2026/poster/155477) [[OpenReview]](https://openreview.net/forum?id=5J1rwV6KnM). Rebuilds local graphs and global cluster assignments at each layer so structure and features evolve together.
- **[RANSAC Scoring]** RANSAC Scoring Done Right, **NeurIPS 2026 (accepted / scheduled)** [[official]](https://neurips.cc/virtual/2026/poster/154742) [[paper]](https://arxiv.org/abs/2606.27385) [[OpenReview]](https://openreview.net/forum?id=BK5yH67CQC). Analytically marginalizes inlier noise scale before optimizing the inlier partition, reducing dependence on manually calibrated scoring thresholds.
- **[SAE]** Boosting Correspondence Learning with Structure-Aware Estimator, **ECCV 2026** [[official / paper]](https://eccv.ecva.net/virtual/2026/poster/4879) [[code]](https://github.com/Tianyu-Yan/SAE). Uses a graph Laplacian to model inlier correlations in a differentiable geometric estimator that can replace weighted least squares.
- **[GeneralPruner]** Scalable and Generalizable Correspondence Pruning via Geometry-Consistent Pre-Training, **TPAMI 2026**, 48(8):10048–10065 [[DOI]](https://doi.org/10.1109/TPAMI.2026.3682079) [[paper]](https://arxiv.org/abs/2406.05773) [[code]](https://github.com/sugar-fly/GeneralPruner). Combines masked inlier reconstruction with a dual-stream consensus encoder to learn transferable geometric representations. This is the 2026 journal version of the earlier CorrMAE preprint listed under 2024.
- **[CorrMamba]** Selecting and Pruning: A Differentiable Causal Sequentialized State-Space Model for Two-View Correspondence Learning, **TIP 2026**, 35:816–829 [[DOI]](https://doi.org/10.1109/TIP.2026.3653189) [[abstract]](https://pubmed.ncbi.nlm.nih.gov/41543960/) [[repository]](https://github.com/ShineFox/CorrMamba). Learns differentiable causal ordering for state-space correspondence filtering. The author-linked repository is empty as of the verification date.
- **[DDFNet]** DDFNet: Dual-Neighborhoods Dynamic Fusion Network for Image Feature Matching, **TMM 2026**, 28:6407–6420 [[DOI]](https://doi.org/10.1109/TMM.2026.3668661) [[repository]](https://github.com/1211193023/DDFNet). The author-linked repository currently contains a results file only; implementation availability is not confirmed.
- **[CFM / ECFM]** Collaborative Feature Matching with Progressive Correspondence Learning, **AAAI 2026**, 40(9):7314–7322 [[official]](https://ojs.aaai.org/index.php/AAAI/article/view/37669) [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/download/37669/41631) [[code]](https://github.com/xinliu29/CFM). Jointly trains keypoint and correspondence modules with progressive feedback; ECFM adds adaptive keypoint sampling.
- **[SC-Net]** SC-Net: Robust Correspondence Learning via Spatial and Cross-Channel Context, **AAAI 2026**, 40(9):6979–6987 [[official]](https://ojs.aaai.org/index.php/AAAI/article/view/37632) [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/download/37632/41594) [[repository]](https://github.com/shuyuanlin/SCNet). Refines motion fields through spatial and channel context. The repository currently contains documentation and a license, without implementation files.
- **[MCD]** Monte Carlo Diffusion for Generalizable Learning-Based RANSAC, **AAAI 2026**, 40(12):9894–9902 [[official]](https://ojs.aaai.org/index.php/AAAI/article/view/37954) [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/download/37954/41916) [[project]](https://comedy0913.github.io/projects/MCD.html) [[repository]](https://github.com/comedy0913/MCD). Generates varied noisy correspondence distributions for training robust estimators across matchers. The repository currently contains a README only.
- **[GeoMoE]** GeoMoE: Divide-and-Conquer Motion Field Modeling with Mixture-of-Experts for Two-View Geometry, **AAAI 2026**, 40(7):5845–5853 [[official]](https://ojs.aaai.org/index.php/AAAI/article/view/37506) [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/download/37506/41468) [[code]](https://github.com/JiajunLe/GeoMoE). Decomposes heterogeneous motion fields using inlier priors and routes sub-fields to specialized experts.

##### Feature matching and correspondence generation

These methods produce or refine matches; they are useful companion work to correspondence pruners rather than interchangeable pruning baselines.

- **[WAM]** WovenAnchor Matcher: Specialized Intra- and Inter-Image Context Modeling for Feature Matching, **NeurIPS 2026 (accepted / scheduled)** [[official]](https://neurips.cc/virtual/2026/poster/155912) [[OpenReview]](https://openreview.net/forum?id=1tYCWPWHHq). Separates within-image state-space propagation from anchor-based cross-image attention for semi-dense matching.
- **[SLiM]** Scalable Feature Matching via State Space Modeling and Sparse Correlation, **CVPR 2026** [[official / paper]](https://openaccess.thecvf.com/content/CVPR2026/html/Choo_Scalable_Feature_Matching_via_State_Space_Modeling_and_Sparse_Correlation_CVPR_2026_paper.html) [[code]](https://github.com/Band-127/SLiM). Uses a Conv-Mamba backbone, norm-based feature filtering, sparse correlation, and recurrent coordinate refinement.
- **[TextFM]** TextFM: Robust Semi-dense Feature Matching with Language Guidance, **CVPR 2026** [[official / paper]](https://openaccess.thecvf.com/content/CVPR2026/html/Zheng_TextFM_Robust_Semi-dense_Feature_Matching_with_Language_Guidance_CVPR_2026_paper.html). Introduces language context and illumination priors to improve matching under domain and lighting changes.
- **[MV-RoMa]** MV-RoMa: From Pairwise Matching into Multi-View Track Reconstruction, **CVPR 2026** [[official / paper]](https://openaccess.thecvf.com/content/CVPR2026/html/Lee_MV-RoMa_From_Pairwise_Matching_into_Multi-View_Track_Reconstruction_CVPR_2026_paper.html). Jointly refines dense correspondences across co-visible views to obtain more consistent SfM tracks.
- **[UniCorrn]** UniCorrn: Unified Correspondence Transformer Across 2D and 3D, **CVPR 2026** [[official / paper]](https://openaccess.thecvf.com/content/CVPR2026/html/Goswami_UniCorrn_Unified_Correspondence_Transformer_Across_2D_and_3D_CVPR_2026_paper.html) [[code]](https://github.com/neu-vi/UniCorrn). Shares a correspondence encoder and decoder across 2D–2D, 2D–3D, and 3D–3D geometric matching.
- **[LoMa]** LoMa: Local Feature Matching Revisited, **ECCV 2026** [[official / paper]](https://eccv.ecva.net/virtual/2026/poster/4073) [[project]](https://davnords.com/loma) [[code]](https://github.com/davnords/LoMa). Scales data diversity and local matching models, and introduces the manually annotated HardMatch benchmark.
- **[RoMa v2]** RoMa v2: Harder Better Faster Denser Feature Matching, **ECCV 2026** [[official / paper]](https://eccv.ecva.net/virtual/2026/poster/3967). Revises dense matching architecture, training data and refinement, incorporating DINOv3 features for challenging image pairs.
- **[AnyMatch]** AnyMatch: Supercharging Universal Multi-Modal Image Matching with Large-Scale Single-View Images, **ECCV 2026** [[official / paper]](https://eccv.ecva.net/virtual/2026/poster/5344). Synthesizes geometrically annotated multi-view, multi-modal pairs from single images to train matchers.
- **[SemLight]** SemLight: Distilled Semantic–Geometric Fusion for Efficient Local Feature Matching, **ECCV 2026** [[official / paper]](https://eccv.ecva.net/virtual/2026/poster/5382). Distills compact semantic priors to guide appearance and geometry fusion in efficient local matching.
- **[Match-Any-Events]** Match-Any-Events: Zero-Shot Motion-Robust Feature Matching Across Wide Baselines for Event Cameras, **ECCV 2026** [[official / paper]](https://eccv.ecva.net/virtual/2026/poster/4933) [[code]](https://github.com/spikelab-jhu/Match-Any-Events). Combines motion-aware event features, sparse token selection and synthetic supervision for matching on unseen datasets.

##### Previously collected 2026 work outside this update's venue scope

- [LLHA-Net] LLHA-Net: A hierarchical attention network for two-view correspondence learning, PR 2026 [[author repositories]](https://github.com/shuyuanlin?tab=repositories). Retained from the original collection; Pattern Recognition is outside the venue scope of this update.

# Related Applications

## 2026 related applications

These **4 additional papers** connect correspondence reasoning to registration, localization, and pose estimation.

- **[Ex-Sim(3)-Reg]** Ex-Sim(3)-Reg: 2D-3D Correspondence Pruning via Extended Sim(3) Registration, **ECCV 2026** [[official / paper]](https://eccv.ecva.net/virtual/2026/poster/4129) [[paper]](https://arxiv.org/abs/2608.28096) [[code]](https://github.com/anpei96/ex-sim3-demo). Models monocular depth noise explicitly when lifting 2D–3D matches for outlier pruning. This is a geometric pruning algorithm, not a learned two-view pruner.
- **[SAG-GNN]** SAG-GNN: Semantic-Aware Guided GNN for Descriptor-Free 2D-3D Matching, **CVPR 2026** [[official / paper]](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_SAG-GNN_Semantic-Aware_Guided_GNN_for_Descriptor-Free_2D-3D_Matching_CVPR_2026_paper.html) [[code]](https://github.com/tinxu0203/SAG-GNN). Adds compact semantic guidance to descriptor-free correspondence inference for visual localization.
- **[Loc²]** Loc²: Interpretable Cross-View Localization via Depth-Lifted Local Feature Matching, **ICLR 2026** [[official / paper]](https://proceedings.iclr.cc/paper_files/paper/2026/hash/ac895e51849bfc99ae25e054fd4c2eda-Abstract-Conference.html) [[code]](https://github.com/vita-epfl/Loc2). Lifts ground–aerial matches using monocular depth and estimates pose through scale-aware Procrustes alignment, with RANSAC outlier rejection.
- **[C3PO]** C3PO: Canonicalization of 3D Pose from Partial Views With Generalizable Correspondence Features, **3DV 2026**, pp. 587–597 [[DOI]](https://doi.org/10.1109/3DV69130.2026.00062) [[author publication record]](https://cvg.vision.in.tum.de/publications?key=chi2026c3po).

## Earlier applications

- Deep Permutation Equivariant Structure From Motion, ICCV 2021 
- RESfM: Robust Deep Equivariant Structure from Motion, ICLR 2025 
- Learning to Filter Outlier Edges in Global SfM, CVPR 2025
- A2-GNN: Angle-Annular GNN for Visual Descriptor-free Camera Relocalization, 3DV 2025
- Solving the Blind Perspective-n-Point Problem End-to-End with Robust Differentiable Geometric Optimization, ECCV 2020
- Is Geometry Enough for Matching in Visual Localization?, ECCV 2022
- DGC-GNN: Leveraging Geometry and Color Cues for Visual Descriptor-Free 2D-3D Matching, CVPR 2024
- MinCD-PnP: Learning 2D-3D Correspondences with Approximate Blind PnP, ICCV 2025
- Learning Bipartite Graph Matching for Robust Visual Localization, ISMAR 2020
- DeepI2P: Image-to-Point Cloud Registration via Deep Classification, CVPR 2021
- P2-Net: Joint Description and Detection of Local Features for Pixel and Point Matching, ICCV 2021  
- 2D3D-MATR: 2D-3D Matching Transformer for Detection-Free Registration Between Images and Point Clouds, ICCV 2023
- EP2P-Loc: End-to-End 3D Point to 2D Pixel Localization for Large-Scale Visual Localization, ICCV 2023
- Learning to Produce Semi-dense Correspondences for Visual Localization, CVPR 2024
- Implicit Correspondence Learning for Image-to-Point Cloud Registration, CVPR 2025
- GraphI2P: Image-to-Point Cloud Registration with Exploring Pattern of Correspondence via Graph Learning, CVPR 2025 
- Diff2I2P: Differentiable Image-to-Point Cloud Registration with Diffusion Prior, ICCV 2025
- OnePose: One-Shot Object Pose Estimation Without CAD Models, CVPR 2022
- OnePose++: Keypoint-Free One-Shot Object Pose Estimation without CAD Models, NeurIPS 2022
- BPnP: End-to-End Learnable Geometric Vision by Backpropagating PnP Optimization, CVPR 2020
- EPro-PnP: Generalized End-to-End Probabilistic Perspective-N-Points for Monocular Object Pose Estimation, CVPR 2022

## Search scope and verification

**Cutoff:** 2026-10-08. Include a paper when its official publication year is 2026, or an official 2026 main-conference program confirms acceptance. An earlier arXiv submission year does not override the final venue year. Workshop papers, unconfirmed submissions, and arXiv-only work are not added to the curated 2026 lists.

**Topics:** two-view correspondence learning; correspondence pruning / outlier rejection; learned and geometric robust estimation; local, semi-dense and dense image feature matching; and closely related 2D–3D registration or localization. Generic model/token pruning, multimodal entity alignment, and unrelated uses of “correspondence” are excluded.

**Venue screening:** NeurIPS/NIPS, ICLR, ICML, CVPR, ICCV, AAAI, ECCV, 3DV, TPAMI, TIP, and TMM. ICML candidates found in this search addressed other correspondence tasks and were not included. ICCV's adjacent editions are [2025](https://iccv.thecvf.com/Conferences/2025) and [2027](https://iccv.thecvf.com/Conferences/2027), so there is no ICCV 2026 section. This search does not establish that no other eligible papers exist.

**Sources:** [CVF Open Access](https://openaccess.thecvf.com/CVPR2026?day=all), [ECCV accepted papers](https://eccv.ecva.net/Conferences/2026/AcceptedPapers), [NeurIPS 2026 program](https://neurips.cc/Downloads/2026), [ICLR proceedings](https://proceedings.iclr.cc/paper_files/paper/2026), [ICML 2026 program](https://icml.cc/Downloads/2026), [AAAI proceedings](https://ojs.aaai.org/index.php/AAAI), IEEE publisher DOI metadata, and author-maintained paper/code pages. DBLP and arXiv were used for discovery and cross-checking; venue attribution follows publisher or official conference records. Summaries describe the authors' proposed methods, not independently reproduced results.

**Example discovery queries** (repeat with each target venue / official-domain filter):

```text
"2026" "correspondence pruning"
"2026" "two-view correspondence"
"2026" "feature matching"
"2026" "RANSAC"
"2026" "2D-3D matching"
site:openaccess.thecvf.com/content/CVPR2026 "correspondence"
site:proceedings.iclr.cc/paper_files/paper/2026 "feature matching"
```

Official program/proceedings titles were also screened directly using `correspondence`, `RANSAC`, `feature matching`, and `image matching`, followed by abstract screening. Journal venue/year/volume/pages were cross-checked against publisher-deposited Crossref records. Title variants and earlier preprints were checked to avoid counting the same publication twice within the 2026 update.

**Resource labels:** `official` / `DOI` verifies venue attribution; `paper` / `pdf` links to a reading copy; `code` indicates that implementation files were visible in the linked author repository at the cutoff date. `repository` may be a placeholder or results-only page, as annotated above. Availability checks do not certify that the implementations run or reproduce reported results.
