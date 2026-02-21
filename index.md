---
layout: default
---
<!-- Text can be **bold**, _italic_, or ~~strikethrough~~. -->

<!-- [Link to another page](./another-page.html). -->

## Overview
A list of research papers on out-of-distribution (OOD) generalization in time series. Existing studies categorize the problem from three key perspectives: data distribution, representation learning, and OOD evaluation. For more details, please refer to our survey paper, *"Out-of-Distribution Generalization in Time Series: A Survey."*

## Data Distribution
Real-world data distributions are often dynamic rather than static and frequently subject to various distribution shifts that challenge the assumptions made during training. Two common distribution shifts are covariate shift and concept Drift.

### Covariate Shift

<!-- *  <span style="color:red;">[CVPR 2021]</span> Out-of-distribution Detection and Generation using Soft Brownian Offset Sampling and Autoencoders <a href="https://openaccess.thecvf.com/content/CVPR2021W/SAIAD/papers/Moller_Out-of-Distribution_Detection_and_Generation_Using_Soft_Brownian_Offset_Sampling_and_CVPRW_2021_paper.pdf">[Paper]</a> <a href="https://github.com/flxai/soft-brownian-offset">[Code]</a> -->
*   <span style="color:red;">[ICML 2022]</span> Time Series Prediction under Distribution Shift using Differentiable Forgetting <a href="https://sites.google.com/view/icml-2022-pods">[Paper]</a> <a href="https://github.com/jase-clarkson/pods_2022_icml_ts">[Code]</a>
*   <span style="color:red;">[ICLR 2022]</span> Reversible Instance Normalization for Accurate Time-Series Forecasting against Distribution Shift <a href="https://openreview.net/pdf?id=cGDAkQo1C0p">[Paper]</a> <a href="https://github.com/ts-kim/RevIN">[Code]</a>
*   <span style="color:red;">[SMC 2022]</span> Feature Importance Identification for Time Series Classifiers <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9945205">[Paper]</a>
*   <span style="color:red;">[ICPADS 2022]</span> Combating Distribution Shift for Accurate Time Series Forecasting via Hypernetworks <a href="https://ieeexplore.ieee.org/abstract/document/10077946">[Paper]</a><a href="https://github.com/wenyingduan/HTSF">[Code]</a>
*   <span style="color:red;">[MM 2022]</span> Domain Adaptation for Time-Series Classification to Mitigate Covariate Shift <a href="https://dl.acm.org/doi/pdf/10.1145/3503161.3548167">[Paper]</a><a href="https://www.iis.fraunhofer.de/de/ff/lv/dataanalytics/anwproj/schreibtrainer/onhw-dataset.html">[Code]</a>
*   <span style="color:red;">[FUZZ 2023]</span> An Initial Step Towards Stable Explanations for Multivariate Time Series Classifiers with LIME <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10309814">[Paper]</a>
*   <span style="color:red;">[Inf. Sci. 2023]</span> Explaining Time Series Classifiers through Meaningful Perturbation and Optimisation <a href="https://www.sciencedirect.com/science/article/pii/S0020025523009192">[Paper]</a> <a href="https://github.com/menghan1994/ETSC_through_Meainingful_Perturbation_and_Optimisation">[Code]</a>
*   <span style="color:red;">[J.Neunet 2024]</span> SEGAL Time Series Classification - Stable Explanations Using A Generative Model and An Adaptive Weighting Method for LIME <a href="https://www.sciencedirect.com/science/article/pii/S0893608024002697/pdfft?md5=3f81e6d7a6bddcb6857d94aa6ab04937&pid=1-s2.0-S0893608024002697-main.pdf">[Paper]</a>
*   <span style="color:red;">[VR 2024]</span> Generating Virtual Reality Stroke Gesture Data from Out-of-Distribution Desktop Stroke Gesture Data <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10494175">[Paper]</a> <a href="https://github.com/yuanlinping/VRStrokeOOD">[Code]</a>
*   <span style="color:red;">[AAAI 2024]</span> Generalizing across Temporal Domains with Koopman Operators <a href="https://ojs.aaai.org/index.php/AAAI/article/view/29604/31020">[Paper]</a> <a href="https://github.com/HardworkingPearl/TKNets-AAAI2024">[Code]</a>
*   <span style="color:red;">[IJCAI 2024]</span> Temporal Domain Generalization via Learning Instance-level Evolving Patterns <a href="https://www.ijcai.org/proceedings/2024/0470.pdf">[Paper]</a> <a href="https://github.com/JinYujie99/CTOT">[Code]</a>
*   <span style="color:red;">[ICML 2024]</span> Connect later: Improving fine-tuning for robustness with targeted augmentations <a href=" https://openreview.net/pdf?id=Uz4Qr40Y3C">[Paper]</a> <a href="https://github.com/helenqu/connect-later">[Code]</a>
*   <span style="color:red;">[ICML 2024]</span> TimeX++: Learning Time-Series Explanations with Information Bottleneck <a href="https://openreview.net/pdf?id=t6dBpwkbea">[Paper]</a> <a href="https://github.com/zichuan-liu/TimeXplusplus">[Code]</a>
*   <span style="color:red;">[TNNLS 2025]</span> Robust Multivariate Time Series Forecasting Against Intraseries and Interseries Transitional Shift  <a href="https://ieeexplore.ieee.org/abstract/document/11134510">[Paper]</a> 
*   <span style="color:red;">[TMLR 2025]</span> Batch Training for Streaming Time Series: A Transferable Augmentation Framework to Combat Distribution Shifts <a href="https://openreview.net/pdf?id=Ht7rlkRCHq">[Paper]</a> 
*   <span style="color:red;">[KDD 2025]</span> IN-Flow: Instance Normalization Flow for Non-stationary Time Series Forecasting <a href="https://dl.acm.org/doi/abs/10.1145/3690624.3709260">[Paper]</a> <a href="https://github.com/kamenbliznashki/normalizing_flows">[Code]</a>
*   <span style="color:red;">[ICLR 2025]</span> Minimax Optimal Two-Stage Algorithm For Moment Estimation Under Covariate Shift <a href="https://dl.acm.org/doi/abs/10.1145/3690624.3709261">[Paper]</a> 

### Concept Drift
*   <span style="color:red;">[ICTAI 2017]</span> Time Series Forecasting in the Presence of Concept Drift: A PSO-based Approach <a href="https://minkull.github.io/publications/OliveiraEtAlICTAI2017.pdf">[Paper]</a>
*   <span style="color:red;">[AAAI 2019]</span> Cogra: Concept-Drift-Aware Stochastic Gradient Descent for Time-Series Forecasting <a href="https://ojs.aaai.org/index.php/AAAI/article/view/4383">[Paper]</a>
*   <span style="color:red;">[TKDE 2022]</span> A Hybrid Spiking Neurons Embedded LSTM Network for Multivariate Time Series Learning Under Concept-Drift Environment <a href="https://ieeexplore.ieee.org/abstract/document/9783029">[Paper]</a>
*  <span style="color:red;">[NeurIPS 2022]</span> Dynamic Graph Neural Networks Under Spatio-Temporal Distribution Shift <a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/2857242c9e97de339ce642e75b15ff24-Paper-Conference.pdf">[Paper]</a> <a href="https://github.com/wondergo2017/DIDA">[Code]</a>
*   <span style="color:red;">[ICML 2023]</span> Domain adaptation for time series under feature and label shifts <a href="https://proceedings.mlr.press/v202/he23b.html">[Paper]</a> <a href="https://github.com/mims-harvard/Raincoat">[Code]</a>
*   <span style="color:red;">[KDD 2023]</span> Maintaining the Status Quo: Capturing Invariant Relations for OOD Spatiotemporal Learning <a href="http://home.ustc.edu.cn/~zzy0929/Home/Paper/KDD23_CauSTG.pdf">[Paper]</a> <a href="https://github.com/zzyy0929/KDD23-CauSTG">[Code]</a>
<!-- *   <span style="color:red;">[AAMAS 2024]</span> Rethinking Out-of-Distribution Detection for Reinforcement Learning: Advancing Methods for Evaluation and Detection <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p1445.pdf">[Paper]</a> <a href="https://github.com/LinasNas/DEXTER">[Code]</a> -->
*  <span style="color:red;">[TNNLS 2024]</span> Distributional Drift Adaptation With Temporal Conditional Variational Autoencoder for Multivariate Time Series Forecasting <a href="https://ieeexplore.ieee.org/abstract/document/10509830/">[Paper]</a> 
*   <span style="color:red;">[SSRN 2024]</span> Rethinking Adam for Time Series Forecasting: A Simple Heuristic to Improve Optimization under Distribution Shifts <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5570331">[Paper]</a> <a href="https://anonymous.4open.science/r/TS_Adam-B530/README.md">[Code]</a>
*  <span style="color:red;">[ICLR 2024]</span> Disentangling Time Series Representations via Contrastive Independence-of-Support on l-Variational Inference <a href="https://openreview.net/pdf?id=iI7hZSczxE">[Paper]</a> <a href="https://institut-polytechnique-de-paris.github.io/time-disentanglement-lib/">[Code]</a>
*   <span style="color:red;">[ICML 2024]</span> CATS: Enhancing Multivariate Time Series Forecasting by Constructing Auxiliary Time Series as Exogenous Variables <a href="https://proceedings.mlr.press/v235/lu24d.html">[Paper]</a> <a href="https://github.com/LJC-FVNR/CATS">[Code]</a>
*   <span style="color:red;">[TCYB 2024]</span> TS-DM: A Time Segmentation-Based Data Stream Learning Method for Concept Drift Adaptation <a href="https://ieeexplore.ieee.org/abstract/document/10633795">[Paper]</a> <a href="https://github.com/kunkun111/TS-DM">[Code]</a>
*   <span style="color:red;">[TPAMI 2024]</span> Transferable Time-Series Forecasting Under Causal Conditional Shift  <a href="https://ieeexplore.ieee.org/abstract/document/10214679">[Paper]</a> <a href="https://github.com/DMIRLAB-Group/GCA">[Code]</a>
*   <span style="color:red;">[NeurIPS 2024]</span> KAN4Drift: Are KAN Effective for Identifying and Tracking Concept Drift in Time Series?  <a href="https://openreview.net/pdf?id=QGM5BnUauL">[Paper]</a> 
*   <span style="color:red;">[KDD 2024]</span> Calibration of Time-Series Forecasting: Detecting and Adapting Context-Driven Distribution Shift  <a href="https://dl.acm.org/doi/abs/10.1145/3637528.3671926">[Paper]</a> <a href="https://github.com/HALF111/calibration_CDS">[Code]</a>
*   <span style="color:red;">[Neucom. 2025]</span> TD-IVDM: A multi-scale concept drift detection method for time series forecasting tasks  <a href="https://www.sciencedirect.com/science/article/pii/S0925231225017928">[Paper]</a> 
*   <span style="color:red;">[ArXiv 2025]</span> Continuous Evolution Pool: Taming Recurring Concept Drift in Online Time Series Forecasting  <a href="https://arxiv.org/pdf/2506.14790">[Paper]</a> <a href="https://github.com/ztxtech/cep_ts">[Code]</a>
*   <span style="color:red;">[TKDE 2025]</span> Long-Term Urban Flow Prediction Against Data Distribution Shift: A Causal Perspective  <a href="https://ieeexplore.ieee.org/abstract/document/11173987/">[Paper]</a> <a href="https://github.com/934392517/DeCau">[Code]</a>
*   <span style="color:red;">[NeurIPS 2025]</span> Learning Pattern-Specific Experts for Time Series Forecasting Under Patch-level Distribution Shift  <a href="https://arxiv.org/abs/2410.09836">[Paper]</a> <a href="https://github.com/syrGitHub/TFPS">[Code]</a>
*   <span style="color:red;">[NeurIPS 2025]</span>  OneNet: Enhancing Time Series Forecasting Models under Concept Drift by Online Ensembling <a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/dd6a47bc0aad6f34aa5e77706d90cdc4-Abstract-Conference.html">[Paper]</a> <a href="https://github.com/yfzhang114/OneNet">[Code]</a>
*   <span style="color:red;">[NeurIPS 2025]</span> How Different from the Past? Spatio-Temporal Time Series Forecasting with Self-Supervised Deviation Learning  <a href="https://arxiv.org/abs/2510.04908">[Paper]</a> <a href="https://github.com/Jimmy-7664/ST-SSDL">[Code]</a>
*   <span style="color:red;">[KDD 2025]</span> Proactive Model Adaptation Against Concept Drift for Online Time Series Forecasting  <a href="https://dl.acm.org/doi/abs/10.1145/3690624.3709210">[Paper]</a> <a href="https://github.com/SJTU-DMTai/OnlineTSF">[Code]</a>
*   <span style="color:red;">[KDD 2025]</span> MetaEformer: Unveiling and Leveraging Meta-patterns for Complex and Dynamic Systems Load Forecastin <a href="https://dl.acm.org/doi/abs/10.1145/3711896.3737047">[Paper]</a> <a href="https://github.com/EdgeBigBang/KDD25_MetaEformer">[Code]</a>


## Representation learning
Representation learning enhances generalization by extracting robust and generalizable features. These methods can be categorized into five groups: decoupling-based methods, invariance-based methods, ensemble-based learning, adaptive mechanism-based methods, and large time-series models.

### Decoupling-based Methods

*   <span style="color:red;">[NeurIPS 2020]</span> Feature Shift Detection: Localizing Which Features Have Shifted via Conditional Distribution Tests <a href="https://proceedings.neurips.cc/paper/2020/file/e2d52448d36918c575fa79d88647ba66-Paper.pdf">[Paper]</a> <a href="https://github.com/inouye-lab/feature-shift">[Code]</a>
*   <span style="color:red;">[ICML 2022]</span> FEDformer: Frequency Enhanced Decomposed Transformer for Long-term Series Forecasting <a href="https://proceedings.mlr.press/v162/zhou22g">[Paper]</a> <a href="https://github.com/MAZiqing/FEDformer">[Code]</a>
*  <span style="color:red;">[NeurIPS 2022]</span> Dynamic Graph Neural Networks Under Spatio-Temporal Distribution Shift <a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/2857242c9e97de339ce642e75b15ff24-Paper-Conference.pdf">[Paper]</a> <a href="https://github.com/wondergo2017/DIDA">[Code]</a>
*   <span style="color:red;">[ICRA 2022]</span> Causal-based Time Series Domain Generalization for Vehicle Intention Prediction <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9812188">[Paper]</a>
*   <span style="color:red;">[ICC 2023]</span> Out-of-distribution Internet Traffic Prediction Generalization Using Deep Sequence Model <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10279740">[Paper]</a>
<!-- *   <span style="color:red;">[IJCNN 2021]</span> Unsupervised Energy-based Out-of-distribution Detection using Stiefel-Restricted Kernel Machine <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9533706">[Paper]</a> <a href="https://github.com/taralloc/st-rkm-ood">[Code]</a> -->
<!-- *   <span style="color:red;">[ACM TCPS 2022]</span> Efficient Out-of-Distribution Detection Using Latent Space of β-VAE for Cyber-Physical Systems <a href="https://dl.acm.org/doi/pdf/10.1145/3491243">[Paper]</a> <a href="https://github.com/scope-lab-vu/Beta-VAE-OOD-Detector">[Code]</a> -->
<!-- *   <span style="color:red;">[ACM TIST 2023]</span> Out-of-distribution Detection in Time-series Domain: A Novel Seasonal Ratio Scoring Approach <a href="https://dl.acm.org/doi/pdf/10.1145/3630633">[Paper]</a> <a href="https://github.com/tahabelkhouja/SRS">[Code]</a> -->
*   <span style="color:red;">[KDD 2023]</span> Maintaining the Status Quo: Capturing Invariant Relations for OOD Spatiotemporal Learning <a href="http://home.ustc.edu.cn/~zzy0929/Home/Paper/KDD23_CauSTG.pdf">[Paper]</a> <a href="https://github.com/zzyy0929/KDD23-CauSTG">[Code]</a>
*   <span style="color:red;">[ICML 2023]</span> Neural Stochastic Differential Games for Time-series Analysis <a href="https://proceedings.mlr.press/v202/park23j/park23j.pdf">[Paper]</a> <a href="https://github.com/LGAI-AML/MaSDEs">[Code]</a>
*   <span style="color:red;">[Sci. Robot. 2023]</span> Robust Flight Navigation Out of Distribution with Liquid Neural Networks <a href="https://cap.csail.mit.edu/sites/default/files/research-pdfs/Robust%20flight%20navigation%20out%20of%20distribution%20with%20liquid%20neural%20networks.pdf">[Paper]</a> <a href="https://zenodo.org/records/7705294">[Code]</a>
*   <span style="color:red;">[KDD 2024]</span> Orthogonality Matters: Invariant Time Series Representation for Out-of-distribution Classification <a href="https://dl.acm.org/doi/pdf/10.1145/3637528.3671768">[Paper]</a> <a href="https://github.com/CGCL-codes/ITSR">[Code]</a>
*   <span style="color:red;">[TKDE 2024]</span> Disentangling Structured Components: Towards Adaptive, Interpretable and Scalable Time Series Forecasting <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10457027">[Paper]</a> <a href="https://github.com/JLDeng/SCNN">[Code]</a>
*   <span style="color:red;">[AAAI 2024]</span> MSGNet: Learning Multi-Scale Inter-Series Correlations for Multivariate Time Series Forecasting <a href="https://ojs.aaai.org/index.php/AAAI/article/view/28991/29883">[Paper]</a> <a href="https://github.com/YoZhibo/MSGNet">[Code]</a>
*   <span style="color:red;">[MM 2024]</span> Spatio-temporal Heterogeneous Federated Learning for Time Series Classification with Multi-view Orthogonal Training <a href="https://dl.acm.org/doi/abs/10.1145/3664647.3680733">[Paper]</a> 
*   <span style="color:red;">[TPAMI 2024]</span> Transferable Time-Series Forecasting Under
Causal Conditional Shift  <a href="https://ieeexplore.ieee.org/abstract/document/10214679">[Paper]</a> 
*   <span style="color:red;">[Inf. Sci. 2024]</span> A Causal Representation Learning Based Model for Time Series Prediction under External Interference  <a href="https://www.sciencedirect.com/science/article/abs/pii/S002002552400183X">[Paper]</a> <a href="https://github.com/342869125/CCR_Model_Causaual">[Code]</a>
*   <span style="color:red;">[ICML 2024]</span> CATS: Enhancing Multivariate Time Series Forecasting by Constructing Auxiliary Time Series as Exogenous Variables <a href="https://proceedings.mlr.press/v235/lu24d.html">[Paper]</a> <a href="https://github.com/LJC-FVNR/CATS">[Code]</a>
*   <span style="color:red;">[TPAMI 2024]</span> Transferable Time-Series Forecasting Under Causal Conditional Shift  <a href="https://ieeexplore.ieee.org/abstract/document/10214679">[Paper]</a> <a href="https://github.com/DMIRLAB-Group/GCA">[Code]</a>
<!-- *   <span style="color:red;">[CVPR 2021]</span> Causal Hidden Markov Model for Time Series Disease Forecasting <a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Causal_Hidden_Markov_Model_for_Time_Series_Disease_Forecasting_CVPR_2021_paper.pdf">[Paper]</a> <a href="https://github.com/LilJing/causal_hmm">[Code]</a> -->
*   <span style="color:red;">[Neucom. 2025]</span> TD-IVDM: A multi-scale concept drift detection method for time series forecasting tasks  <a href="https://www.sciencedirect.com/science/article/pii/S0925231225017928">[Paper]</a> 
*   <span style="color:red;">[KDD 2025]</span> IN-Flow: Instance Normalization Flow for Non-stationary Time Series Forecasting <a href="https://dl.acm.org/doi/abs/10.1145/3690624.3709260">[Paper]</a> <a href="https://github.com/kamenbliznashki/normalizing_flows">[Code]</a>
*   <span style="color:red;">[TKDE 2025]</span> Long-Term Urban Flow Prediction Against Data Distribution Shift: A Causal Perspective  <a href="https://ieeexplore.ieee.org/abstract/document/11173987/">[Paper]</a> <a href="https://github.com/934392517/DeCau">[Code]</a>
*   <span style="color:red;">[TNNLS 2025]</span> Robust Multivariate Time Series Forecasting Against Intraseries and Interseries Transitional Shift  <a href="https://ieeexplore.ieee.org/abstract/document/11134510">[Paper]</a> 
*   <span style="color:red;">[KDD 2025]</span> MetaEformer: Unveiling and Leveraging Meta-patterns for Complex and Dynamic Systems Load Forecastin <a href="https://dl.acm.org/doi/abs/10.1145/3711896.3737047">[Paper]</a> <a href="https://github.com/EdgeBigBang/KDD25_MetaEformer">[Code]</a>
*   <span style="color:red;">[ICLR 2025]</span> SimpleTM: A Simple Baseline for Multivariate Time Series Decoupling <a href="https://openreview.net/pdf?id=oANkBaVci5">[Paper]</a> <a href="https://github.com/vsingh-group/SimpleTM">[Code]</a>


### Invariant-based Methods
<!-- Invariant Risk Minimization Models: -->
*   <span style="color:red;">[ICLR 2021]</span> In-N-Out: Pre-Training and Self-Training using Auxiliary Information for Out-of-Distribution Robustness <a href="https://openreview.net/pdf?id=jznizqvr15J">[Paper]</a> <a href="https://github.com/p-lambda/in-n-out">[Code]</a>
*  <span style="color:red;">[AAAI 2021]</span> Latent independent excitation for generalizable sensor-based cross-person activity recognition <a href="https://ojs.aaai.org/index.php/AAAI/article/view/17416/17223">[Paper]</a> <a href="https://github.com/Hangwei12358/cross-person-HAR">[Code]</a>
*   <span style="color:red;">[AAAI 2021]</span> Meta-learning Framework with Applications to Zero-shot Time-series Forecasting <a href="https://ojs.aaai.org/index.php/AAAI/article/view/17115/16922">[Paper]</a> <a href="https://github.com/DFrolova/ml-sk-project">[Code]</a>
*   <span style="color:red;">[MM 2022]</span> Domain Adaptation for Time-Series Classification to Mitigate Covariate Shift <a href="https://dl.acm.org/doi/pdf/10.1145/3503161.3548167">[Paper]</a><a href="https://www.iis.fraunhofer.de/de/ff/lv/dataanalytics/anwproj/schreibtrainer/onhw-dataset.html">[Code]</a>
*   <span style="color:red;">[ICRA 2023]</span> Robust Forecasting for Robotic Control: A Game-Theoretic Approach <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10160721">[Paper]</a>
*   <span style="color:red;">[KDD 2023]</span> DoubleAdapt: A Meta-learning Approach to Incremental Learning for Stock Trend Forecasting <a href="https://dl.acm.org/doi/pdf/10.1145/3580305.3599315">[Paper]</a> <a href="https://github.com/SJTU-DMTai/DoubleAdapt">[Code]</a>
*   <span style="color:red;">[KDD 2023]</span> TSMixer: Lightweight MLP-Mixer Model for Multivariate Time Series Forecasting <a href="https://dl.acm.org/doi/pdf/10.1145/3580305.3599533">[Paper]</a> <a href="https://huggingface.co/docs/transformers/model_doc/patchtsmixer">[Code]</a>
*   <span style="color:red;">[NeurIPS 2023]</span> Evolving Standardization for Continual Domain Generalization over Temporal Drift <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/459a911eb49cd2e0192055ee156d04e5-Paper-Conference.pdf">[Paper]</a> <a href="https://github.com/BIT-DA/EvoS">[Code]</a>
*   <span style="color:red;">[ICDM 2023]</span> Boosting Urban Prediction via Addressing Spatial-Temporal Distribution Shift  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10415754">[Paper]</a>
*   <span style="color:red;">[ICLR 2023]</span> Out-of-distribution Representation Learning for Time Series Classification <a href="https://openreview.net/pdf?id=gUZWOE42l6Q">[Paper]</a> <a href="https://github.com/lrx0014/DiversifyAnalysis">[Code]</a>
*   <span style="color:red;">[ICML 2023]</span> Domain adaptation for time series under feature and label shifts <a href="https://proceedings.mlr.press/v202/he23b.html">[Paper]</a> <a href="https://github.com/mims-harvard/Raincoat">[Code]</a>
*   <span style="color:red;">[AAAI 2023]</span> Dish-TS: A General Paradigm for Alleviating Distribution Shift in Time Series Forecasting <a href="https://ojs.aaai.org/index.php/AAAI/article/view/25914">[Paper]</a> <a href="https://github. com/weifantt/Dish-TS">[Code]</a>
*   <span style="color:red;">[WWW 2024]</span> Towards Invariant Time Series Forecasting in Smart Cities <a href="https://dl.acm.org/doi/proceedings/10.1145/3589335?tocHeading=heading10">[Paper]</a> <a href="https://www.youtube.com/watch?v=7GSY1nYn5g8">[Video]</a>
*   <span style="color:red;">[ICML 2024]</span> Time-Series Forecasting for Out-of-Distribution Generalization Using Invariant Learning <a href="https://openreview.net/pdf?id=SMUXPVKUBg">[Paper]</a> <a href="https://github.com/AdityaLab/FOIL">[Code]</a>
*   <span style="color:red;">[ACM TKDD 2024]</span>Domain Generalization in Time Series Forecasting <a href="https://dl.acm.org/doi/full/10.1145/3643035">[Paper]</a> <a href="https://github.com/songgaojundeng/cedar-dg">[Code]</a>
*   <span style="color:red;">[ICLR 2025]</span> Out-of-distribution Generalization for Total Variation based Invariant Risk Minimization <a href="https://openreview.net/pdf?id=c4wEKJOjY3">[Paper]</a> <a href="https://github.com/laizhr/OOD-TV-IRM">[Code]</a>
*  <span style="color:red;">[TNNLS 2024]</span> Distributional Drift Adaptation With Temporal Conditional Variational Autoencoder for Multivariate Time Series Forecasting <a href="https://ieeexplore.ieee.org/abstract/document/10509830/">[Paper]</a> 
*   <span style="color:red;">[VR 2024]</span> Generating Virtual Reality Stroke Gesture Data from Out-of-Distribution Desktop Stroke Gesture Data <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10494175">[Paper]</a> <a href="https://github.com/yuanlinping/VRStrokeOOD">[Code]</a>
*   <span style="color:red;">[AAAI 2024]</span> Generalizing across Temporal Domains with Koopman Operators <a href="https://ojs.aaai.org/index.php/AAAI/article/view/29604/31020">[Paper]</a> <a href="https://github.com/HardworkingPearl/TKNets-AAAI2024">[Code]</a>
*   <span style="color:red;">[ICML 2024]</span> Connect later: Improving fine-tuning for robustness with targeted augmentations <a href="https://openreview.net/pdf?id=Uz4Qr40Y3C">[Paper]</a> <a href="https://github.com/helenqu/connect-later">[Code]</a>
*   <span style="color:red;">[NeurIPS 2024]</span> Continuous Temporal Domain Generalization <a href="https://openreview.net/pdf?id=G24fOpC3JE">[Paper]</a> <a href="https://github.com/Zekun-Cai/Koodos">[Code]</a>
*   <span style="color:red;">[TPAMI 2024]</span> Diversify: A General Framework for Time Series Out-of-Distribution Detection and Generalization <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10402053">[Paper]</a> <a href="https://microsoft.github.io/robustlearn/diversify">[Code]</a>
*   <span style="color:red;">[DAC 2024]</span> SMORE: Similarity-based Hyperdimensional Domain Adaptation for Multi-Sensor Time Series Classification <a href="https://dl.acm.org/doi/pdf/10.1145/3649329.3658477">[Paper]</a> <a href="https://bpb-us-e2.wpmucdn.com/sites.uci.edu/dist/9/5133/files/2024/07/DAC_2024.pdf">[PPT]</a>
*   <span style="color:red;">[NeurIPS 2025]</span> Learning Pattern-Specific Experts for Time Series Forecasting Under Patch-level Distribution Shift  <a href="https://arxiv.org/abs/2410.09836">[Paper]</a> <a href="https://github.com/syrGitHub/TFPS">[Code]</a>
*   <span style="color:red;">[NeurIPS 2025]</span> Learning Without Augmenting: Unsupervised Time Series Representation Learning via Frame Projections<a href="https://openreview.net/pdf?id=LwPjJHVWSn">[Paper]</a> <a href="https://github.com/eth-siplab/Learning-with-FrameProjections">[Code]</a>
*   <span style="color:red;">[ICML 2025]</span> Time Series Representations with Hard-Coded Invariances <a href="https://openreview.net/forum?id=SaKPKyjDp6">[Paper]</a> <a href="https://github.com/sissykosm/TS-InvConv">[Code]</a>
<!-- Domain-Invariance Methods: -->

<!-- *   <span style="color:red;">[Struct. 2024]</span> Enhancing Time Series Data Classification for Structural Damage Detection through Out-of-Distribution Representation Learning <a href="https://www.sciencedirect.com/science/article/abs/pii/S2352012424009184">[Paper]</a> -->

<!-- ### Ensemble-based Learning -->
<!-- *   <span style="color:red;">[SAIS 2022]</span> Out-of-distribution in Human Activity Recognition <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833052">[Paper]</a> -->
<!-- *   <span style="color:red;">[RESS 2022]</span> Out-of-Distribution Detection-Assisted Trustworthy Machinery Fault Diagnosis Approach with Uncertainty-Aware Deep Ensembles <a href="https://www.sciencedirect.com/science/article/abs/pii/S0951832022002836">[Paper]</a> -->
<!-- *   <span style="color:red;">[ArXiv 2025]</span> Continuous Evolution Pool: Taming Recurring Concept Drift in Online Time Series Forecasting  <a href="https://arxiv.org/pdf/2506.14790">[Paper]</a> <a href="https://github.com/ztxtech/cep_ts">[Code]</a> -->
<!-- *   <span style="color:red;">[AIC 2023]</span> Classifying Falls Using Out-of-Distribution Detection in Human Activity Recognition <a href="https://content.iospress.com/download/ai-communications/aic220205?id=ai-communications%2Faic220205">[Paper]</a> -->
<!-- *   <span style="color:red;">[AAMAS 2024]</span> Rethinking Out-of-Distribution Detection for Reinforcement Learning: Advancing Methods for Evaluation and Detection <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p1445.pdf">[Paper]</a> <a href="https://github.com/LinasNas/DEXTER">[Code]</a> -->

### Adaptive Mechanism-based Methods
*   <span style="color:red;">[ICTAI 2017]</span> Time Series Forecasting in the Presence of Concept Drift: A PSO-based Approach <a href="https://minkull.github.io/publications/OliveiraEtAlICTAI2017.pdf">[Paper]</a>
*   <span style="color:red;">[AAAI 2019]</span> Cogra: Concept-Drift-Aware Stochastic Gradient Descent for Time-Series Forecasting <a href="https://ojs.aaai.org/index.php/AAAI/article/view/4383">[Paper]</a>
*   <span style="color:red;">[TKDE 2022]</span> A Hybrid Spiking Neurons Embedded LSTM Network for Multivariate Time Series Learning Under Concept-Drift Environment <a href="https://ieeexplore.ieee.org/abstract/document/9783029">[Paper]</a>
*   <span style="color:red;">[ICML 2022]</span> Time Series Prediction under Distribution Shift using Differentiable Forgetting <a href="https://sites.google.com/view/icml-2022-pods">[Paper]</a> <a href="https://github.com/jase-clarkson/pods_2022_icml_ts">[Code]</a>
*   <span style="color:red;">[ICPADS 2022]</span> Combating Distribution Shift for Accurate Time Series Forecasting via Hypernetworks <a href="https://ieeexplore.ieee.org/abstract/document/10077946">[Paper]</a><a href="https://github.com/wenyingduan/HTSF">[Code]</a>
*   <span style="color:red;">[TCYB 2024]</span> TS-DM: A Time Segmentation-Based Data Stream Learning Method for Concept Drift Adaptation <a href="https://ieeexplore.ieee.org/abstract/document/10633795">[Paper]</a> <a href="https://github.com/kunkun111/TS-DM">[Code]</a>
*   <span style="color:red;">[SSRN 2024]</span> Rethinking Adam for Time Series Forecasting: A Simple Heuristic to Improve Optimization under Distribution Shifts <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5570331">[Paper]</a> <a href="https://anonymous.4open.science/r/TS_Adam-B530/README.md">[Code]</a>
*   <span style="color:red;">[NeurIPS 2024]</span> KAN4Drift: Are KAN Effective for Identifying and Tracking Concept Drift in Time Series?  <a href="https://openreview.net/pdf?id=QGM5BnUauL">[Paper]</a> 
*   <span style="color:red;">[KDD 2024]</span> Calibration of Time-Series Forecasting: Detecting and Adapting Context-Driven Distribution Shift  <a href="https://dl.acm.org/doi/abs/10.1145/3637528.3671926">[Paper]</a> <a href="https://github.com/HALF111/calibration_CDS">[Code]</a>
*   <span style="color:red;">[JMLR 2024]</span>  Conformal Inference for Online Prediction with Arbitrary Distribution Shifts  <a href="http://www.jmlr.org/papers/v25/22-1218.html">[Paper]</a> <a href="https://github.com/isgibbs/DtACI">[Code]</a>
*   <span style="color:red;">[ArXiv 2025]</span> Continuous Evolution Pool: Taming Recurring Concept Drift in Online Time Series Forecasting  <a href="https://arxiv.org/pdf/2506.14790">[Paper]</a> <a href="https://github.com/ztxtech/cep_ts">[Code]</a>
*   <span style="color:red;">[TMLR 2025]</span> Batch Training for Streaming Time Series: A Transferable Augmentation Framework to Combat Distribution Shifts <a href="https://openreview.net/pdf?id=Ht7rlkRCHq">[Paper]</a> 
*   <span style="color:red;">[NeurIPS 2025]</span> How Different from the Past? Spatio-Temporal Time Series Forecasting with Self-Supervised Deviation Learning  <a href="https://arxiv.org/abs/2510.04908">[Paper]</a> <a href="https://github.com/Jimmy-7664/ST-SSDL">[Code]</a>
*   <span style="color:red;">[NeurIPS 2025]</span>  OneNet: Enhancing Time Series Forecasting Models under Concept Drift by Online Ensembling <a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/dd6a47bc0aad6f34aa5e77706d90cdc4-Abstract-Conference.html">[Paper]</a> <a href="https://github.com/yfzhang114/OneNet">[Code]</a>
*   <span style="color:red;">[KDD 2025]</span> Proactive Model Adaptation Against Concept Drift for Online Time Series Forecasting  <a href="https://dl.acm.org/doi/abs/10.1145/3690624.3709210">[Paper]</a> <a href="https://github.com/SJTU-DMTai/OnlineTSF">[Code]</a>

### Large Time-Series Models

*   <span style="color:red;">[NeurIPS 2023]</span> ForecastPFN: Synthetically-Trained Zero-Shot Forecasting <a href="https://openreview.net/pdf?id=tScBQRNgjk">[Paper]</a> <a href="https://github.com/abacusai/ForecastPFN">[Code]</a>
*   <span style="color:red;">[EACL 2023]</span> Transfer Knowledge from Natural Language to Electrocardiography: Can We Detect Cardiovascular Disease Through Language Models? <a href="https://aclanthology.org/2023.findings-eacl.33.pdf">[Paper]</a> <a href="https://github.com/Jielin-Qiu/Transfer_Knowledge_from_Language_to_ECG">[Code]</a>
*   <span style="color:red;">[NeurIPS 2024]</span> Tiny Time Mixers (TTMs): Fast Pre-trained Models for Enhanced Zero/Few-shot Forecasting of Multivariate Time Series <a href="https://openreview.net/pdf?id=3O5YCEWETq">[Paper]</a> <a href="https://huggingface.co/ibm-granite/granite-timeseries-ttm-r1">[Code]</a>
*   <span style="color:red;">[NeurIPS 2023]</span> JoLT: Jointly Learned Representations of Language and Time-Series <a href="https://openreview.net/pdf?id=UVF1AMBj9u">[Paper]</a>
*   <span style="color:red;">[NeurIPS 2023]</span> One Fits All: Power General Time Series Analysis by Pretrained LM <a href="https://openreview.net/pdf?id=gMS6FVZvmF">[Paper]</a> <a href="https://github.com/DAMO-DI-ML/NeurIPS2023-One-Fits-All">[Code]</a>
*   <span style="color:red;">[R0-FoMo 2023]</span> Lag-Llama: Towards Foundation Models for Time Series Forecasting <a href="https://openreview.net/pdf?id=jYluzCLFDM">[Paper]</a> <a href="https://github.com/time-series-foundation-models/lag-llama">[Code]</a>
*   <span style="color:red;">[NeurIPS 2023]</span> Large Language Models Are Zero-Shot Time Series Forecasters <a href="https://openreview.net/pdf?id=md68e8iZK1">[Paper]</a> <a href="https://github.com/ngruver/llmtime">[Code]</a>
*   <span style="color:red;">[ArXiv 2023]</span> Pushing the Limits of Pre-training for Time Series Forecasting in the CloudOps Domain <a href="https://arxiv.org/abs/2310.05063">[Paper]</a> <a href="https://github.com/SalesforceAIResearch/pretrain-time-series-cloudops">[Code]</a>
*   <span style="color:red;">[ArXiv 2023]</span> TimeGPT-1 <a href="https://arxiv.org/abs/2310.03589">[Paper]</a> <a href="https://github.com/Nixtla/nixtla">[Code]</a>
*   <span style="color:red;">[ICASSP 2024]</span> ETP: Learning Transferable ECG Representations via ECG-Text Pre-Training <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10446742">[Paper]</a>
*   <span style="color:red;">[AAAI 2024]</span> JoLT: Jointly Learned Representations of Language and Time-Series for Clinical Time-Series Interpretation (Student Abstract) <a href="https://ojs.aaai.org/index.php/AAAI/article/view/30423/32496">[Paper]</a>
*   <span style="color:red;">[ICLR 2024]</span> Time-LLM: Time Series Forecasting by Reprogramming Large Language Models <a href="https://openreview.net/pdf?id=Unb5CVPtae">[Paper]</a> <a href="https://github.com/KimMeen/Time-LLM">[Code]</a>
*   <span style="color:red;">[ICML 2024]</span> Unified Rraining of Universal Time Series Forecasting Transformers <a href="https://dl.acm.org/doi/10.5555/3692070.3694248">[Paper]</a> <a href="https://github.com/SalesforceAIResearch/uni2ts">[Code]</a>  
*   <span style="color:red;">[CIKM 2024]</span> General Time Transformer: an Encoder-only Foundation Model for Zero-Shot Multivariate Time Series Forecasting <a href="https://dl.acm.org/doi/pdf/10.1145/3627673.3679931">[Paper]</a> <a href="https://github.com/cfeng783/GTT">[Code]</a>
*   <span style="color:red;">[NeurIPS 2024]</span> Align and Fine-Tune: Enhancing LLMs for Time-Series Forecasting <a href="https://openreview.net/pdf?id=AaRCmJieG4">[Paper]</a>
*   <span style="color:red;">[NeurIPS 2024]</span> Tri-Level Navigator: LLM-Empowered Tri-Level Learning for Time Series OOD Generalization <a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/c78d9d035215039ab46e48c281e6a63d-Abstract-Conference.html">[Paper]</a>
*   <span style="color:red;">[ICML 2024]</span> MOMENT: A Family of Open Time-series Foundation Models <a href="file:///Users/xinwu/Downloads/goswami24a.pdf">[Paper]</a> <a href="https://github.com/moment-timeseries-foundation-model/moment">[Code]</a>
*   <span style="color:red;">[ICML 2024]</span> Timer: Generative Pre-trained Transformers Are Large Time Series Models <a href="https://dl.acm.org/doi/10.5555/3692070.3693383">[Paper]</a> <a href="https://github.com/thuml/Large-Time-Series-Model">[Code]</a>
*   <span style="color:red;">[ICML 2024]</span> A Decoder-only Foundation Model for Time-series Forecasting <a href="https://raw.githubusercontent.com/mlresearch/v235/main/assets/das24c/das24c.pdf">[Paper]</a> <a href="https://github.com/google-research/timesfm?tab=readme-ov-file">[Code]</a>
*   <span style="color:red;">[TMLR 2024]</span> Chronos: Learning the Language of Time Series <a href="https://openreview.net/pdf?id=gerNCVqqtR">[Paper]</a> <a href="https://github.com/amazon-science/chronos-forecasting">[Code]</a>
*   <span style="color:red;">[ICLR 2025]</span> Towards Neural Scaling Laws for Time Series Foundation Models <a href="https://openreview.net/pdf?id=uCqxDfLYrB">[Paper]</a> <a href="https://github.com/Qingrenn/TSFM-ScalingLaws">[Code]</a>
*   <span style="color:red;">[AAAI 2025]</span> ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data <a href="https://arxiv.org/abs/2412.11376">[Paper]</a> <a href="https://github.com/forestsking/chattime">[Code]</a>
*   <span style="color:red;">[AAAI 2025]</span> CALF: Aligning LLMs for Time Series Forecasting via Cross-modal Fine-Tuning <a href="https://arxiv.org/abs/2403.07300">[Paper]</a> <a href="https://github.com/Hank0626/CALF">[Code]</a>
*   <span style="color:red;">[CIKM 2025]</span> TableTime: Reformulating Time Series Classification as Training-Free Table Understanding with Large Language Models <a href="https://arxiv.org/abs/2411.15737">[Paper]</a> <a href="https://github.com/realwangjiahao/tabletime">[Code]</a>
*   <span style="color:red;">[TKDE 2025]</span> TimeRAF: Retrieval-Augmented Foundation Model for Zero-Shot Time Series Forecasting <a href="https://ieeexplore.ieee.org/abstract/document/11031238">[Paper]</a>


## Time Series Datasets 📊

📌 General Time Series
- 💾 [UEA Classification](https://www.timeseriesclassification.com/index.php) – A rich set of time series datasets for classification tasks.
- 📊 [UCR Archive](https://www.cs.ucr.edu/~eamonn/time_series_data_2018) – Benchmark datasets for time series research.

💰 Economy & Finance
- 📈 [PPA Dataset](https://github.com/LilJing/causal_hmm) – Causal inference data for Power Purchase Agreements.
- 💹 [Exchange Rate](https://github.com/laiguokun/multivariate-time-series-data/tree/master/electricity) – Historical exchange rates for financial forecasting.

🚗 Transportation
- 🛣 [SIP Traffic](https://data.cic-tp.com/h5/sample-data/china/export-data/company/suzhou-industrial-park) – Traffic data from Suzhou Industrial Park.
- 🚌 [METR-LA](https://www.kaggle.com/datasets/annnnguyen/metr-la-dataset) – Los Angeles traffic sensor data.
- ✈️ [Flight Data](https://opensky-network.org) – Aircraft trajectory & air traffic. data.
- 🚦 [Traffic Flow](https://github.com/laiguokun/multivariate-time-series-data) – Multi-city traffic congestion datasets.

⚡ Energy & Environment
- 🔋 [Electricity Load](https://github.com/laiguokun/multivariate-time-series-data/tree/master/electricity) – Power consumption data for energy forecasting.
- ☀️ [Solar Energy](https://github.com/laiguokun/multivariate-time-series-data) – Solar power generation datasets.
- 🌦 [Weather & ETT](https://drive.google.com/drive/folders/1ZOYpTUa82_jCcxIdTmyr0LXQfvaM9vIy) – Meteorological time series for climate analysis.

🌫 Air Quality
- 🌍 [KnowAir PM2.5](https://github.com/shuowang-ai/PM2.5-GNN) – Air pollution dataset focusing on PM2.5 levels.

🏥 Health & Medicine
- 🦾 [EMG](https://archive.ics.uci.edu/dataset/481/emg+data+for+gestures) - Electromyography dataset records muscle activity.


⌚️ Human Activity Recognition
- 🏃🏻‍♀️ [UCIHAR](https://drive.google.com/drive/folders/1JjEZaVDYHaV7z4hz-fWgoJ9PToR9SOtZ) - Smartphone-based human activity recognition dataset.
- 🩼 [UniMiB-SHAR](htthttps://drive.google.com/drive/folders/1JjEZaVDYHaV7z4hz-fWgoJ9PToR9SOtZ) - Smartphone-based human activity recognition and fall detection dataset.
- 📱 [Opportunity](https://drive.google.com/drive/folders/1JjEZaVDYHaV7z4hz-fWgoJ9PToR9SOtZ) - Multiple wearable and environmental sensors for human activity recognition dataset.

🛠 More Datasets
- 📚 [Multivariate Time Series](https://github.com/laiguokun/multivariate-time-series-data) – Traffic, electricity, solar, and financial datasets.


## Other Related Papers

*   <span style="color:red;">[ArXiv 2021]</span> Towards Out-of-Distribution Generalization: A Survey <a href="https://arxiv.org/pdf/2108.13624">[Paper]</a>
*   <span style="color:red;">[ArXiv 2022]</span> Out-of-Distribution Generalization on Graphs: A Survey <a href="https://arxiv.org/pdf/2202.07987">[Paper]</a>
<!-- *   <span style="color:red;">[TPAMI 2022]</span> Domain Generalization: A Survey <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9847099">[Paper]</a> -->
*   <span style="color:red;">[EMNLP 2023]</span> Out-of-Distribution Generalization in Natural Language Processing: Past, Present, and Future <a href="https://aclanthology.org/2023.emnlp-main.276.pdf">[Paper]</a>
<!-- *   <span style="color:red;">[TKDE 2023]</span> Generalizing to Unseen Domains: A Survey on Domain Generalization <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9782500">[Paper]</a> -->
<!-- *   <span style="color:red;">[ACM Comput. Surv. 2023]</span> Generative Adversarial Networks in Time Series: A Systematic Literature Review <a href="https://dl.acm.org/doi/pdf/10.1145/3559540">[Paper]</a> -->
*   <span style="color:red;">[TPAMI 2024]</span> Self-Supervised Learning for Time Series Analysis: Taxonomy, Progress, and Prospects <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10496248">[Paper]</a>
*   <span style="color:red;">[TPAMI 2024]</span> A Survey on Graph Neural Networks for Time Series: Forecasting, Classification, Imputation, and Anomaly Detection <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10636792">[Paper]</a>
*   <span style="color:red;">[TKDE 2024]</span> A Survey on Time-Series Pre-Trained
models <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10706809">[Paper]</a>
*   <span style="color:red;">[TMLR 2024]</span> WOODS: Benchmarks for Out-of-Distribution Generalization in Time Series <a href="https://openreview.net/pdf?id=mvftzofTYQ">[Paper]</a>
<!-- *   <span style="color:red;">[IJCV 2024]</span> Generalized Out-of-Distribution Detection: A Survey <a href="https://link.springer.com/article/10.1007/s11263-024-02117-4">[Paper]</a> -->


#### Acknowledgement

Last updated on February 17, 2026. (For problems, contact xinwu5386@gmail.com. To add papers, please pull request at <a href="https://github.com/tsood-generalization/tsood-generalization.github.io">our repo</a>)

<div style="width: 200px; height: 150px; margin: 0 auto;">
<!-- Map Widget -->
<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=q6eVgeaBn-p2jkFoYf-6vSskb8SxHJqWuia9GW0Q_AE&cl=ffffff&w=a"></script> -->
<!-- Globe Widget -->
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=q6eVgeaBn-p2jkFoYf-6vSskb8SxHJqWuia9GW0Q_AE"></script>
</div>

