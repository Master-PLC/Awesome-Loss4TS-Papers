# Learning Objectives for Time-Series Analysis: Papers and Resources

<h3 align="center">Welcome to Loss4TS</h3>

<p align="center"><i>A curated list of learning objectives for forecasting, imputation, classification, and anomaly detection.</i></p>

## 1. Introduction

Loss4TS is a curated collection of representative learning objectives for deep time-series analysis. It organizes objectives by the task-specific challenges they address, covering time-series forecasting, imputation, classification, and anomaly detection.

The list follows the task--challenge--mechanism taxonomy in the Loss4TS survey. Some objectives appear in more than one category when they address multiple challenges.

Paper titles link to publication or preprint pages. The Code column lists a publicly available implementation when a corresponding repository could be verified.

## 2. Learning Objectives

### 2.1. Time-Series Forecasting

#### Modeling Label Autocorrelation

##### Likelihood Estimation

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| FreDF | [FreDF: learning to forecast in the frequency domain](https://openreview.net/forum?id=4A9IdSa1ul) | 2025 | ICLR | [GitHub](https://github.com/Master-PLC/FreDF) |
| Time-o1 | [Time-o1: time-series forecasting needs transformed label alignment](https://openreview.net/forum?id=RxWILaXuhb) | 2025 | NeurIPS | [GitHub](https://github.com/Master-PLC/Time-o1) |
| QDF | [Quadratic direct forecast for training multi-step time-series forecast models](https://openreview.net/forum?id=vpO8n9AqEG) | 2026 | ICLR | [GitHub](https://github.com/Master-PLC/QDF) |
| DeepAR | [DeepAR: Probabilistic forecasting with autoregressive recurrent networks](https://www.sciencedirect.com/science/article/pii/S0169207019301888) | 2020 | Int. J. Forecast. | [GitHub](https://github.com/zhykoties/TimeSeries) |
| MMKE | [Multivariate probabilistic time series forecasting with correlated errors](https://openreview.net/forum?id=cAFvxVFaii&noteId=ZL0AiqWDNn) | 2024 | NeurIPS | [GitHub](https://github.com/rottenivy/mv_pts_correlatederr) |

##### Shape Alignment

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| DTW | [Dynamic programming algorithm optimization for spoken word recognition](https://ieeexplore.ieee.org/document/1163055) | 1978 | IEEE Trans. Acoust., Speech, Signal Process. | [GitHub](https://tslearn.readthedocs.io/en/stable/gen_modules/metrics/tslearn.metrics.dtw.html) |
| Soft-DTW | [Soft-dtw: a differentiable loss function for time-series](https://proceedings.mlr.press/v70/cuturi17a.html) | 2017 | ICML | [GitHub](https://github.com/mblondel/soft-dtw) |
| DILATE | [Shape and time distortion loss for training deep time series forecasting models](https://openreview.net/forum?id=r1ld_NBxIB) | 2019 | NeurIPS | [GitHub](https://github.com/vincent-leguen/DILATE) |
| DSDTW | [Differentiable divergences between time series](https://proceedings.mlr.press/v130/blondel21a/blondel21a.pdf) | 2021 | AISTATS | [GitHub](https://github.com/google-research/soft-dtw-divergences) |
| STRIPE | [Probabilistic time series forecasting with shape and temporal diversity](https://ieeexplore.ieee.org/document/9721108) | 2020 | NeurIPS | [GitHub](https://github.com/vincent-leguen/STRIPE) |
| ShapeDTW | [shapeDTW: Shape dynamic time warping](https://www.sciencedirect.com/science/article/abs/pii/S0031320317303710) | 2018 | Pattern Recognit. | [GitHub](https://github.com/jiapingz/shapeDTW) |

##### Distribution Balancing

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| PS | [Patch-wise Structural Loss for Time Series Forecasting](https://openreview.net/pdf?id=p1KkW2kgDp) | 2025 | ICML | [GitHub](https://github.com/Dilfiraa/PS_Loss) |
| DistDF | [DistDF: time-series forecasting needs joint-distribution Wasserstein alignment](https://openreview.net/forum?id=VrdLwUmzBy) | 2026 | ICLR | [GitHub](https://github.com/Master-PLC/DistDF) |
| KMB-DF | [Deep time-series forecasting needs kernelized moment balancing](https://arxiv.org/abs/2602.00717) | 2026 | Arxiv | [GitHub](https://github.com/Master-PLC/KMB-DF) |
| AST | [Adversarial sparse transformer for time series forecasting](https://proceedings.neurips.cc/paper/2020/hash/c6b8c8d762da15fa8dbbdfb6baf9e260-Abstract.html) | 2020 | NeurIPS | [GitHub](https://github.com/hihihihiwsf/AST) |
| WRCGAN | [Generative representation learning in recurrent neural networks for causal timeseries forecasting](https://ieeexplore.ieee.org/document/10643032) | 2024 | IEEE TAI | Not available |
| SDGCN | [Transformer-Based Generative Adversarial Network for Traffic Forecasting](https://ieeexplore.ieee.org/document/11133428) | 2025 | IEEE Trans. Consum. Electron. | Not available |
| AttnWGAIN | [AttnWGAIN: Attention-Based Wasserstein Generative Adversarial Imputation Network for IoT Multivariate Time Series](https://ieeexplore.ieee.org/document/11131293) | 2025 | IEEE Trans. Consum. Electron. | [GitHub](https://github.com/wzq-come-on/AttnWGAIN) |

#### Quantifying Predictive Uncertainty

##### Quantile and Scoring Rules

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| Pinball-sMAPE | [A novel approach to multi-horizon wind power forecasting based on deep neural architecture](https://doi.org/10.1016/j.renene.2021.06.099) | 2021 | Renew. Energy | Not available |
| Arctan-Pinball | [Composite quantile regression with XGBoost using the novel arctan pinball loss](https://doi.org/10.1007/s13042-025-02671-4) | 2025 | Int. J. Mach. Learn. Cybern. | Not available |
| KDE-Pinball | [Wind Power Interval Prediction Based on Multidecomposition and Kernel Density Pinball](https://doi.org/10.1109/tii.2026.3689642) | 2026 | IEEE TII | Not available |
| MQF$^2$ | [Multivariate quantile function forecaster](https://proceedings.mlr.press/v151/kan22a/kan22a.pdf) | 2022 | AISTATS | [GitHub](https://github.com/awslabs/gluonts/tree/dev/src/gluonts/torch/model/mqf2) |
| MVG-CRPS | [Mvg-crps: A robust loss function for multivariate probabilistic forecasting](https://arxiv.org/abs/2410.09133) | 2024 | Arxiv | Not available |

##### Conformal Prediction

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| EnbPI | [Conformal prediction interval for dynamic time-series](https://proceedings.mlr.press/v139/xu21h.html) | 2021 | ICML | [GitHub](https://github.com/hamrel-cxu/EnbPI) |
| HopCPT | [Conformal prediction for time series with modern hopfield networks](https://openreview.net/forum?id=KTRwpWCMsC) | 2023 | NeurIPS | [GitHub](https://github.com/ml-jku/HopCPT) |
| ResCP | [Rescp: Reservoir conformal prediction for time series forecasting](https://openreview.net/pdf?id=WGqibe5H3W) | 2026 | ICLR | [Github](https://github.com/RobertoNeglia/reservoir-conformal-prediction) |
| NCC | [Neural conformal control for time series forecasting](https://doi.org/10.1609/aaai.v39i17.34029) | 2025 | AAAI | [GitHub](https://github.com/complex-ai-lab/ncc) |
| CPTC | [Conformal prediction for time-series forecasting with change points](https://proceedings.nips.cc/paper_files/paper/2025/hash/12271b64c483ad8f6192eb6aaa102044-Abstract-Conference.html) | 2026 | NeurIPS | [GitHub](https://github.com/Rose-STL-Lab/CPTC) |

##### Generative Modeling

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| TimeGrad | [Autoregressive denoising diffusion models for multivariate probabilistic time series forecasting](https://proceedings.mlr.press/v139/rasul21a/rasul21a.pdf) | 2021 | ICML | [GitHub](https://github.com/zalandoresearch/pytorch-ts) |
| TimeDiff | [Non-autoregressive conditional diffusion models for time series prediction](https://dl.acm.org/doi/10.5555/3618408.3619692) | 2023 | ICML | [Github](https://github.com/qc-1/timediff) |
| TMDM | [Transformer-modulated diffusion models for probabilistic multivariate time series forecasting](https://openreview.net/forum?id=qae04YACHs) | 2024 | ICLR | [GitHub](https://github.com/LiYuxin321/TMDM) |
| NsDiff | [Non-stationary Diffusion For Probabilistic Time Series Forecasting](https://openreview.net/forum?id=afpc1MFMYU&noteId=dHebxGz0sZ) | 2025 | ICML | [GitHub](https://github.com/wwy155/NsDiff) |
| TCDM | [TCDM: A Temporal Correlation-Empowered Diffusion Model for Time Series Forecasting](https://www.ijcai.org/proceedings/2025/0749.pdf) | 2025 | IJCAI | Not available |
| TSFlow | [Flow matching with gaussian process priors for probabilistic time series forecasting](https://proceedings.iclr.cc/paper_files/paper/2025/hash/ee1a1ecc92f35702b5c29dad3dc909ea-Abstract-Conference.html) | 2025 | ICLR | [GitHub](https://github.com/marcelkollovieh/TSFlow) |

#### Counteracting Non-Stationarity

##### Temporal Reweighting

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| KM-DR | [Learning theory and algorithms for forecasting non-stationary time series](https://papers.nips.cc/paper/5836-learning-theory-and-algorithms-for-forecasting-non-stationary-time-series) | 2015 | NeurIPS | Not available |
| DiffForget | [Time Series Prediction under Distribution Shift using Differentiable Forgetting](https://icml.cc/virtual/2022/20549) | 2022 | ICML Workshop | [Github](https://github.com/jase-clarkson/pods_2022_icml_ts) |
| RIDER | [Optimal Empirical Risk Minimization under Temporal Distribution Shifts](https://arxiv.org/abs/2507.13287) | 2025 | Arxiv | Not available |
| DRW-HGB | [A drift- and recency-aware boosting framework for robust forecasting under nonstationary data streams](https://doi.org/10.1016/j.mlwa.2026.100927) | 2026 | Mach. Learn. Appl. | Not available |

##### Feedback-Based Adaptation

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| TAFAS | [Battling the non-stationarity in time series forecasting via test-time adaptation](https://doi.org/10.1609/aaai.v39i17.33965) | 2025 | AAAI | [GitHub](https://github.com/kimanki/TAFAS) |
| PETSA | [Accurate Parameter-Efficient Test-Time Adaptation for Time Series Forecasting](https://icml.cc/virtual/2025/48057) | 2025 | ICML Workshop | [GitHub](https://github.com/BorealisAI/PETSA) |
| COSA | [COSA: Context-Aware Output-Space Adapter for Test-Time Adaptation in Time Series Forecasting](https://openreview.net/forum?id=L7Z5wBMPrW) | 2026 | ICLR | [GitHub](https://github.com/bigbases/COSA_ICLR2026) |
| FAC | [Towards Principled Test-Time Adaptation for Time Series Forecasting](https://openreview.net/pdf?id=bA2bMEOUFL) | 2026 | TMLR | [GitHub](https://github.com/JoshGrizzz/TSFTTA-FAC) |
| OneNet | [Onenet: Enhancing time series forecasting models under concept drift by online ensembling](https://doi.org/10.52202/075280-3066) | 2023 | NeurIPS | [GitHub](https://github.com/yfzhang114/OneNet) |
| EPOC | [EPOC: Endpoint-Preserving Online Correction With Compressed Residual State for Multi-Horizon Time Series Forecasting](https://arxiv.org/abs/2609.30929) | 2026 | Arxiv | [GitHub](https://github.com/keiotakmin/endpoint-preserving-residual-correction) |
| OMPB | [Model-Agnostic Online Certificate-Driven Calibration for Time Series Forecasting Under Distribution Shift](https://proceedings.mlr.press/v337/huang26b.html) | 2026 | Proc. Uncertain. Artif. Intell. | [GitHub](https://github.com/chenfeng-huang/OMPB-UAI-2026) |

### 2.2. Time-Series Imputation

#### Handling Complex Missing Mechanism

##### Mechanism-Aware Correction

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| IGNNK | [Inductive Graph Neural Networks for Spatiotemporal Kriging](https://doi.org/10.1609/aaai.v35i5.16575) | 2021 | AAAI | [GitHub](https://github.com/Kaimaoge/IGNNK) |
| KITS | [Kits: Inductive spatio-temporal kriging with increment training strategy](https://doi.org/10.1609/aaai.v39i12.33412) | 2025 | AAAI | [GitHub](https://github.com/Sam1224/KITS) |
| GRIN | [Filling the G_ap_s: Multivariate Time Series Imputation by Graph Neural Networks](https://openreview.net/forum?id=kOu3-S3wJ7) | 2022 | ICLR | [GitHub](https://github.com/Graph-Machine-Learning-Group/grin) |
| SPIN | [Learning to Reconstruct Missing Data from Spatiotemporal Graphs with Sparse Observations](https://papers.nips.cc/paper_files/paper/2022/hash/cf70320e93c08b39b1b29a348097a376-Abstract-Conference.html) | 2022 | NeurIPS | [GitHub](https://github.com/Graph-Machine-Learning-Group/spin) |
| PRDIM | [Missing Pattern Recognized Diffusion Imputation Model for Missing Not At Random](https://arxiv.org/abs/2605.25439) | 2026 | Arxiv | Not available |
| DMM-MNAR | [Causal View of Time Series Imputation: Some Identification Results on Missing Mechanism](https://doi.org/10.24963/ijcai.2025/532) | 2025 | IJCAI | Not available |

##### Generative Diffusion Modeling

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| SSSD | [Diffusion-based Time Series Imputation and Forecasting with Structured State Space Models](https://openreview.net/forum?id=hHiIbk7ApW) | 2023 | TMLR | [GitHub](https://github.com/AI4HealthUOL/SSSD) |
| DSDI | [Boundary-enhanced time series data imputation with long-term dependency diffusion models](https://doi.org/10.1016/j.knosys.2024.112917) | 2025 | KBS | [Github](https://github.com/xxuejiang/DSDI) |
| PriSTI | [Pristi: A conditional diffusion framework for spatiotemporal imputation](https://doi.org/10.1109/icde55515.2023.00150) | 2023 | ICDE | [GitHub](https://github.com/LMZZML/PriSTI) |
| FGTI | [Frequency-aware generative models for multivariate time series imputation](https://doi.org/10.52202/079017-1667) | 2024 | NeurIPS | [GitHub](https://github.com/FGTI2024/FGTI24) |
| CDTI | [Time-Frequency Conditioned Diffusion for Multivariate Time Series Imputation](https://doi.org/10.1109/icde65706.2026.00191) | 2026 | ICDE | [GitHub](https://github.com/Cofeesy/CDTI) |

#### Preserving Temporal Consistency

##### Adversarial Matching

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| E$^2$GAN | [E2gan: End-to-end generative adversarial network for multivariate time series imputation](https://doi.org/10.24963/ijcai.2019/429) | 2019 | IJCAI | Not available |
| SSGAN | [Generative semi-supervised learning for multivariate time series imputation](https://doi.org/10.1609/aaai.v35i10.17086) | 2021 | AAAI | Not available |
| STING | [STING: Self-attention based Time-series Imputation Networks using GAN](https://doi.org/10.1109/icdm51629.2021.00155) | 2021 | ICDM | Not available |
| NETS-ImpGAN | [Networked time-series prediction with incomplete data via generative adversarial network](https://doi.org/10.1145/3643822) | 2024 | ACM Trans. Knowl. Discov. Data | Not available |
| ACGANet | [Attentive Continuous-Time Generative Adversarial Networks for Irregular Time Series Imputation](https://doi.org/10.1109/tkde.2025.3617659) | 2025 | IEEE TKDE | Not available |

##### Optimal-Transport Balancing

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| TWI | [Temporal Wasserstein Imputation: A Versatile Method for Time Series Imputation](https://arxiv.org/abs/2411.02811) | 2024 | Arxiv | Not available |
| LSPT-D | [LSPT-D: local similarity preserved transport for direct industrial data imputation](https://doi.org/10.1109/tase.2024.3506835) | 2025 | IEEE TASE | Not available |
| SPOT-I | [SPOT-I: similarity preserved optimal transport for industrial IoT data imputation](https://doi.org/10.1109/tii.2024.3452241) | 2024 | IEEE TII | Not available |
| PSW-I | [Optimal transport for time series imputation](https://proceedings.iclr.cc/paper_files/paper/2025/hash/033394ac055e3c47bfc3c967ffcfee74-Abstract-Conference.html) | 2025 | ICLR | [GitHub](https://github.com/FMLYD/PSW-I) |
| POT-I | [Robust missing value imputation with proximal optimal transport for low-quality iiot data](https://doi.org/10.1109/tnnls.2025.3601130) | 2026 | IEEE TNNLS | Not available |

#### Optimizing Downstream Performance

##### End-to-End Task Coupling

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| BRITS | [Brits: Bidirectional recurrent imputation for time series](https://proceedings.neurips.cc/paper_files/paper/2018/hash/734e6bfcd358e25ac1db0a4241b95651-Abstract.html) | 2018 | NeurIPS | [GitHub](https://github.com/caow13/BRITS) |
| SSGAN | [Generative semi-supervised learning for multivariate time series imputation](https://doi.org/10.1609/aaai.v35i10.17086) | 2021 | AAAI | [Github](https://github.com/zjuwuyy-DL/Generative-Semi-supervised-Learning-for-Multivariate-Time-Series-Imputation) |
| V-RIN | [Uncertainty-aware variational-recurrent imputation network for clinical time series](https://doi.org/10.1109/tcyb.2021.3053599) | 2021 | IEEE TCYB | [Github](https://github.com/ku-milab/V-RIN) |
| IMAC | [Spatial imputation drives cross-domain alignment for eeg classification](https://doi.org/10.1145/3746027.3755582) | 2025 | ACM MM | Not available |
| GRU-D | [Recurrent neural networks for multivariate time series with missing values](https://doi.org/10.1038/s41598-018-24271-9) | 2018 | Scientific reports | [GitHub](https://github.com/zhiyongc/GRU-D) |

##### Masked Modeling as Pretext

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| TST | [A transformer-based framework for multivariate time series representation learning](https://doi.org/10.1145/3447548.3467401) | 2021 | KDD | [GitHub](https://github.com/gzerveas/mvts_transformer) |
| Ti-MAE | [Ti-MAE: Self-Supervised Masked Time Series Autoencoders](https://arxiv.org/abs/2301.08871) | 2023 | Arxiv | [Github](https://github.com/ImRTon/TiMAE-Lightning) |
| SimMTM | [Simmtm: A simple pre-training framework for masked time-series modeling](https://doi.org/10.52202/075280-1306) | 2023 | NeurIPS | [GitHub](https://github.com/thuml/SimMTM) |
| TimeMAE | [Timemae: Self-supervised representations of time series with decoupled masked autoencoders](https://doi.org/10.1145/3773966.3778007) | 2026 | WSDM | [GitHub](https://github.com/Mingyue-Cheng/TimeMAE) |

### 2.3. Time-Series Classification

#### Learning with Few Labels

##### Contrastive Self-Supervision

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| TS-TCC | [Time-Series Representation Learning via Temporal and Contextual Contrasting](https://doi.org/10.24963/ijcai.2021/324) | 2021 | IJCAI | [GitHub](https://github.com/emadeldeen24/TS-TCC) |
| TF-C | [Self-supervised contrastive pre-training for time series via time-frequency consistency](https://doi.org/10.52202/068431-0288) | 2022 | NeurIPS | [GitHub](https://github.com/mims-harvard/TFC-pretraining) |
| TS2Vec | [Ts2vec: Towards universal representation of time series](https://doi.org/10.1609/aaai.v36i8.20881) | 2022 | AAAI | [GitHub](https://github.com/yuezhihan/ts2vec) |
| TNC | [Unsupervised Representation Learning for Time Series with Temporal Neighborhood Coding](https://iclr.cc/virtual/2021/poster/2897) | 2021 | ICLR | [GitHub](https://github.com/sanatonek/TNC_representation_learning) |
| InfoTS | [Time series contrastive learning with information-aware augmentations](https://doi.org/10.1609/aaai.v37i4.25575) | 2023 | AAAI | [GitHub](https://github.com/chengw07/InfoTS) |

##### Few-Label Supervision

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| RankSCL | [Rank supervised contrastive learning for time series classification](https://doi.org/10.1109/icdm59182.2024.00102) | 2024 | ICDM | [Github](https://github.com/UConn-DSIS/Rank-Supervised-Contrastive-Learning-for-Time-Series-Classification) |
| TRILITE | [Enhancing time series classification with self-supervised learning](https://doi.org/10.5220/0011611300003393) | 2023 | Int. Conf. Agents Artif. Intell. | [GitHub](https://github.com/MSD-IRIMAS/TRILITE) |
| TapNet | [Tapnet: Multivariate time series classification with attentional prototypical network](https://doi.org/10.1609/aaai.v34i04.6165) | 2020 | AAAI | [Github](https://github.com/wxyhhh/tapnet) |
| COSCO | [Cosco: a sharpness-aware training framework for few-shot multivariate time series classification](https://doi.org/10.1145/3627673.3679891) | 2024 | CIKM | [GitHub](https://github.com/JRB9/COSCO) |
| IPL-SeSL | [Semi-Supervised Learning With Interpolation and Pseudo-Labeling for Few-Label Intrusion Detection](https://doi.org/10.1109/tnsm.2025.3580740) | 2025 | IEEE Trans. Netw. Service Manag. | Not available |
| TS-TFC | [Temporal-frequency co-training for time series semi-supervised learning](https://doi.org/10.1609/aaai.v37i7.26072) | 2023 | AAAI | [GitHub](https://github.com/qianlima-lab/TS-TFC) |
| TFFC | [TFFC: time-frequency fusion consistency for semi-supervised time series classification](https://doi.org/10.1007/s10489-025-06695-9) | 2025 | Appl. Intell. | Not available |

#### Learning with Noisy Labels

##### Robust Supervision

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| AGCE | [Adaptive Generalized Cross-Entropy Loss for Sound Event Classification with Noisy Labels](https://doi.org/10.1109/waspaa52581.2021.9632679) | 2021 | Workshop of IEEE Appl. Signal Process. Audio Acoust. | Not available |
| ASCE | [An adaptive symmetric loss in dynamic wide-kernel ResNet for rotating machinery fault diagnosis under noisy labels](https://doi.org/10.1109/tim.2024.3375404) | 2024 | IEEE TIM | Not available |
| RobustIncomp | [Robust classification of incomplete time series with noisy labels](https://doi.org/10.1109/cscwd61410.2024.10580639) | 2024 | Int. Conf. Computer Supported Coop. Work Design | Not available |
| NRNN | [A novel normalized recurrent neural network for fault diagnosis with noisy labels](https://doi.org/10.1007/s10845-020-01608-8) | 2021 | Journal of Intelligent Manufacturing | Not available |
| CRRCNN | [A fault diagnosis framework insensitive to noisy labels based on recurrent neural network](https://doi.org/10.1109/jsen.2020.3023748) | 2021 | IEEE Sensors J. | Not available |
| TENOR | [Learning under temporal label noise](https://proceedings.iclr.cc/paper_files/paper/2025/hash/698587c2bbe57a0a1135b92c3ac36c3c-Abstract-Conference.html) | 2025 | ICLR | [GitHub](https://github.com/sujaynagaraj/TemporalLabelNoise) |
| SREA | [Estimating the electrical power output of industrial devices with end-to-end time-series classification in the presence of label noise](https://link.springer.com/chapter/10.1007/978-3-030-86486-6_29) | 2021 | European Conf. Mach. Learn. Knowl. Discov. Data. | [GitHub](https://github.com/Castel44/SREA) |

##### Sample Selection

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| CTW | [CTW: Confident Time-Warping for Time-Series Label-Noise Learning.](https://doi.org/10.24963/ijcai.2023/450) | 2023 | IJCAI | [GitHub](https://github.com/qianlima-lab/CTW) |
| Scale-teaching | [Scale-teaching: Robust multi-scale training for time series classification with noisy labels](https://doi.org/10.52202/075280-1464) | 2023 | NeurIPS | [GitHub](https://github.com/qianlima-lab/Scale-teaching) |
| ACTLL | [Dynamical Label Augmentation and Calibration for Noisy Electronic Health Records](https://doi.org/10.1007/978-981-96-8170-9_37) | 2025 | Pacific-Asia Conf. Knowl. Discov. Data Mining | [GitHub](https://github.com/yuhao-3/ACTLL) |
| DynaClean | [DynaClean: A Multiscale Graph-Driven Noisy Label Correction Framework for Mechanical Fault Diagnosis](https://doi.org/10.1109/tim.2026.3714621) | 2026 | IEEE TIM | Not available |

#### Learning under Distribution Shift

##### Discrepancy-Based Alignment

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| AdvSKM | [Adversarial spectral kernel matching for unsupervised time series domain adaptation](https://doi.org/10.24963/ijcai.2021/378) | 2021 | IJCAI | [Github](https://github.com/jarheadjoe/Adv-spec-ker-matching) |
| DFUDA | [Deep Feature Unsupervised Domain Adaptation for Time-Series Classification](https://doi.org/10.1109/tai.2024.3491948) | 2025 | IEEE TAI | Not available |
| SASA | [Time series domain adaptation via sparse associative structure alignment](https://doi.org/10.1609/aaai.v35i8.16846) | 2021 | AAAI | [Github](https://github.com/DMIRLAB-Group/SASA) |
| RAINCOAT | [Domain adaptation for time series under feature and label shifts](https://proceedings.mlr.press/v202/he23b.html) | 2023 | ICML | [GitHub](https://github.com/mims-harvard/Raincoat) |

##### Adversarial and Contrastive Alignment

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| VRADA | [Variational recurrent adversarial deep domain adaptation](https://openreview.net/forum?id=rk9eAFcxg) | 2017 | ICLR | [Github](https://github.com/floft/vrada) |
| CoDATS | [Multi-source deep domain adaptation with weak supervision for time-series sensor data](https://doi.org/10.1145/3394486.3403228) | 2020 | KDD | [GitHub](https://github.com/floft/codats) |
| ACON | [Boosting transferability and discriminability for time series domain adaptation](https://doi.org/10.52202/079017-3187) | 2024 | NeurIPS | [GitHub](https://github.com/mingyangliu1024/ACON) |
| CLUDA | [Contrastive Learning for Unsupervised Domain Adaptation of Time Series](https://openreview.net/pdf?id=xPkJYRsQGM) | 2023 | ICLR | [GitHub](https://github.com/oezyurty/CLUDA) |
| CALDA | [CALDA: Improving Multi-Source Time Series Domain Adaptation With Contrastive Adversarial Learning](https://doi.org/10.1109/tpami.2023.3298346) | 2023 | IEEE TPAMI | [GitHub](https://github.com/floft/calda) |
| CoTMix | [Contrastive Domain Adaptation for Time-Series via Temporal Mixup](https://doi.org/10.1109/tai.2023.3293473) | 2023 | IEEE TAI | [GitHub](https://github.com/emadeldeen24/CoTMix) |

### 2.4. Time-Series Anomaly Detection

#### Detecting Anomalies with No Labels

##### Residual-Based Scoring

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| LSTM-NDT | [Detecting spacecraft anomalies using lstms and nonparametric dynamic thresholding](https://doi.org/10.1145/3219819.3219845) | 2018 | KDD | [GitHub](https://github.com/khundman/telemanom) |
| DeepAnT | [DeepAnT: A deep learning approach for unsupervised anomaly detection in time series](https://doi.org/10.1109/access.2018.2886457) | 2018 | IEEE access | [Github](https://github.com/EnsiyeTahaei/DeepAnT-Time-Series-Anomaly-Detection) |
| GDN | [Graph neural network-based anomaly detection in multivariate time series](https://doi.org/10.1609/aaai.v35i5.16523) | 2021 | AAAI | [GitHub](https://github.com/d-ailin/GDN) |
| USAD | [Usad: Unsupervised anomaly detection on multivariate time series](https://doi.org/10.1145/3394486.3403392) | 2020 | KDD | [GitHub](https://github.com/manigalati/usad) |
| TadGAN | [Tadgan: Time series anomaly detection using generative adversarial networks](https://doi.org/10.1109/bigdata50022.2020.9378139) | 2020 | IEEE BigData | [GitHub](https://github.com/sintel-dev/Orion) |
| TranAD | [TranAD: Deep Transformer Networks for Anomaly Detection in Multivariate Time Series Data](https://doi.org/10.14778/3514061.3514067) | 2022 | Proc. VLDB Endow. | [GitHub](https://github.com/imperial-qore/TranAD) |

##### Normal-Region Modeling

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| GANF | [Graph-Augmented Normalizing Flows for Anomaly Detection of Multiple Time Series](https://iclr.cc/virtual/2022/spotlight/6771) | 2022 | ICLR | [GitHub](https://github.com/EnyanDai/GANF) |
| MTGFlow | [Detecting multivariate time series anomalies with zero known label](https://doi.org/10.1609/aaai.v37i4.25623) | 2023 | AAAI | [GitHub](https://github.com/zqhang/MTGFLOW) |
| MTGFlow-C | [Label-free multivariate time series anomaly detection](https://doi.org/10.1109/tkde.2024.3349613) | 2024 | IEEE TKDE | [GitHub](https://github.com/zqhang/MTGFLOW) |
| ALDM | [Adaptive Latent Distribution Modeling for Industrial Time Series Anomaly Detection](https://doi.org/10.1109/tase.2026.3674236) | 2026 | IEEE TASE | [GitHub](https://github.com/YuLiu-61/ALDM) |
| THOC | [Timeseries anomaly detection using temporal hierarchical one-class network](https://proceedings.neurips.cc/paper/2020/hash/97e401a02082021fd24957f852e0e475-Abstract.html) | 2020 | NeurIPS | [Github](https://github.com/carrtesy/THOC-Pytorch) |
| RDSSM | [Learning robust deep state space for unsupervised anomaly detection in contaminated time-series](https://doi.org/10.1109/TKDE.2022.3171562) | 2022 | IEEE TKDE | Not available |
| COUTA | [Calibrated one-class classification for unsupervised time series anomaly detection](https://doi.org/10.1109/tkde.2024.3393996) | 2024 | IEEE TKDE | [GitHub](https://github.com/xuhongzuo/couta) |

##### Self-Supervised Discrepancy

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| NeuTraL AD | [Neural transformation learning for deep anomaly detection beyond images](https://proceedings.mlr.press/v139/qiu21a.html) | 2021 | ICML | [GitHub](https://github.com/boschresearch/NeuTraL-AD) |
| MS2D-Net | [Efficient time series anomaly detection by multiresolution self-supervised discriminative network](https://doi.org/10.1016/j.neucom.2022.03.048) | 2022 | Neural Comput. | Not available |
| Anomaly Transformer | [Anomaly Transformer: Time Series Anomaly Detection with Association Discrepancy](https://openreview.net/forum?id=LzQQ89U1qm_) | 2022 | ICLR | [GitHub](https://github.com/thuml/Anomaly-Transformer) |
| DCdetector | [Dcdetector: Dual attention contrastive representation learning for time series anomaly detection](https://doi.org/10.1145/3580305.3599295) | 2023 | KDD | [GitHub](https://github.com/DAMO-DI-ML/KDD2023-DCdetector) |
| CARLA | [CARLA: Self-supervised contrastive representation learning for time series anomaly detection](https://doi.org/10.1016/j.patcog.2024.110874) | 2025 | Pattern Recognit. | [GitHub](https://github.com/zamanzadeh/CARLA) |

#### Detecting Anomalies with Few Labels

##### Cost-Sensitive Reweighting

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| CSHN | [Class-imbalanced time series anomaly detection method based on cost-sensitive hybrid network](https://doi.org/10.1016/j.eswa.2023.122192) | 2024 | ESWA | Not available |
| CSL | [Cost-sensitive learning for anomaly detection in imbalanced ECG data using convolutional neural networks](https://doi.org/10.3390/s22114075) | 2022 | Sensors | Not available |
| VBL | [Imbalanced aircraft data anomaly detection](https://doi.org/10.1109/taes.2024.3456748) | 2025 | IEEE Trans. Aerosp. Electron. Syst. | Not available |
| IFAD | [Imbalanced flight test sensor temporal data anomaly detection](https://doi.org/10.1109/taes.2024.3471488) | 2025 | IEEE Trans. Aerosp. Electron. Syst. | [GitHub](https://github.com/zhangda1018/IFAD) |

##### Positive--Unlabeled Learning

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| NRdetector | [Noise-resilient point-wise anomaly detection in time series using weak segment labels](https://doi.org/10.1145/3690624.3709257) | 2025 | KDD | [GitHub](https://github.com/UCSC-REAL/NRdetector) |
| PU-GANomaly | [PU-GANomaly: Generative Adversarial Networks for Anomaly Detection in Positive and Unlabeled Time Series Data](https://doi.org/10.1109/tce.2026.3713045) | 2026 | IEEE Trans. Consum. Electron. | Not available |
| SatPU | [A positive-unlabeled learning approach for industrial anomaly detection based on self-adaptive training](https://doi.org/10.1016/j.neucom.2025.130488) | 2025 | Neural Comput. | [Github](https://github.com/Sakayi/SatPU) |

##### Synthetic Anomaly Supervision

| Objective | Title | Year | Venue | Code |
|-----------|-------|------|-------|------|
| NCAD | [Neural Contextual Anomaly Detection for Time Series](https://doi.org/10.24963/ijcai.2022/394) | 2022 | IJCAI | Not available |
| CutAddPaste | [Cutaddpaste: Time series anomaly detection by exploiting abnormal knowledge](https://doi.org/10.1145/3637528.3671739) | 2024 | KDD | [GitHub](https://github.com/ruiking04/CutAddPaste) |
| CoAD | [Bridging Classification and Reconstruction: Cooperative Time Series Anomaly Detection](https://doi.org/10.1145/3770855.3818108) | 2026 | KDD | [GitHub](https://github.com/richard-tang199/CoAD) |
| RedLamp | [Robust and explainable detector of time series anomaly via augmenting multiclass pseudo-anomalies](https://doi.org/10.1145/3711896.3737110) | 2025 | KDD | [GitHub](https://github.com/KoheiObata/RedLamp) |

## 3. Related Surveys

The following surveys and reviews are discussed as related work in the Loss4TS paper.

| Survey | Year | Venue | Code |
|------------|------|-------|------|
| [Loss functions in time series forecasting](https://faculty.ucr.edu/~taelee/paper/2008_IESS_Loss_Functions.pdf) | 2008 | Int. Encyclopedia Social Sci. | Not available |
| [Deep learning for time series classification: A review](https://doi.org/10.1007/s10618-019-00619-1) | 2019 | Data Mining Knowl. Disc. | Not available |
| [A comparative study of loss functions for deep neural networks in time series analysis](https://doi.org/10.1007/978-981-99-3481-2_12) | 2021 | Int. Conf. Big Data Mach. Learn. Appl. | Not available |
| [An experimental survey of missing data imputation algorithms](https://doi.org/10.1109/TKDE.2022.3186498) | 2022 | IEEE TKDE | Not available |
| [A systematic review of generative adversarial imputation network in missing data imputation](https://doi.org/10.1007/s00521-023-08840-2) | 2023 | Neural Comput. Appl. | Not available |
| [Generative adversarial networks in time series: A systematic literature review](https://doi.org/10.1145/3559540) | 2023 | ACM Comput. Surv. | Not available |
| [A comprehensive survey of regression-based loss functions for time series forecasting](https://doi.org/10.1007/978-981-97-3245-6_9) | 2024 | Int. Conf. Data Manag. Anal. Innov. | Not available |
| [A survey and benchmarking of spatial-temporal traffic data imputation models](https://arxiv.org/abs/2412.04733) | 2024 | Arxiv | Not available |
| [Time series classification: A review of algorithms and implementations](https://doi.org/10.5772/intechopen.1004810) | 2024 | Time Series Anal. Recent Adv. New Persp. Appl. | Not available |
| [A survey of deep anomaly detection in multivariate time series: Taxonomy, applications, and directions](https://doi.org/10.3390/s25010190) | 2025 | Sensors | Not available |
| [Comparative analysis of loss functions in deep learning models for water level forecasting](https://doi.org/10.1109/icaides67265.2025.11404066) | 2025 | ICAIDES | Not available |
| [Deep learning for multivariate time series anomaly detection: An evaluation of reconstruction-based methods](https://doi.org/10.1007/s10462-025-11401-9) | 2025 | Artif. Intell. Rev. | Not available |
| [Graph anomaly detection in time series: A survey](https://doi.org/10.1109/tpami.2025.3566620) | 2025 | IEEE TPAMI | Not available |
| [Task-based loss functions in computer vision: A comprehensive review](https://arxiv.org/abs/2504.04242) | 2025 | Arxiv | Not available |
| [Loss functions for time series forecasting in network security situation awareness](https://doi.org/10.1007/978-3-032-08465-1_14) | 2025 | Int. Conf. Hybrid Artif. Intell. Syst. | Not available |
| [Deep time series models: A comprehensive survey and benchmark](https://arxiv.org/abs/2407.13278) | 2026 | IEEE TPAMI | [GitHub](https://github.com/thuml/Time-Series-Library) |
| [Deep time-series forecasting in 10 years: A survey](https://doi.org/10.1109/tpami.2026.3742172) | 2026 | IEEE TPAMI | [Github](https://github.com/Master-PLC/Awesome-TSF-Papers) |
| [A survey on graph neural networks for time series: Forecasting, classification, imputation, and anomaly detection](https://doi.org/10.1109/tpami.2024.3443141) | 2024 | IEEE TPAMI | Not available |
| [Self-supervised learning for time series analysis: Taxonomy, progress, and prospects](https://doi.org/10.1109/tpami.2024.3387317) | 2024 | IEEE TPAMI | [GitHub](https://github.com/qingsongedu/Awesome-SSL4TS) |

## 4. Contributing

If you notice a missing objective, incorrect metadata, or unavailable code link, please open an issue or submit a pull request.
