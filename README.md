# Loss Functions for Deep Image Retrieval

A curated list of papers introducing loss functions for content-based image retrieval (CBIR).

The losses are grouped into the four families: classification, metric learning, learning to rank and hybrid losses.

## Contents

- [Classification Losses](#classification-losses) (22)
- [Metric Learning Losses](#metric-learning-losses) (15)
- [Learning to Rank Losses](#learning-to-rank-losses) (10)
- [Hybrid Losses](#hybrid-losses) (7)

## Classification Losses

| Loss | Paper | DOI |
|---|---|---|
| Cross-Entropy | Machine Learning: A Probabilistic Perspective (K. P. Murphy, MIT Press, 2012) | - |
| Piecewise Cross-Entropy | Fine-Grained Image Retrieval via Piecewise Cross Entropy Loss | [10.1016/j.imavis.2019.10.006](https://doi.org/10.1016/j.imavis.2019.10.006) |
| LinCos-Softmax | LinCos-Softmax: Learning Angle-Discriminative Face Representations With Linearity-Enhanced Cosine Logits | [10.1109/ACCESS.2020.3002270](https://doi.org/10.1109/ACCESS.2020.3002270) |
| SphereFace | SphereFace: Deep Hypersphere Embedding for Face Recognition | [10.1109/CVPR.2017.713](https://doi.org/10.1109/CVPR.2017.713) |
| SphereFace-R | SphereFace Revived: Unifying Hyperspherical Face Recognition | [10.1109/TPAMI.2022.3159732](https://doi.org/10.1109/TPAMI.2022.3159732) |
| UniformFace | UniformFace: Learning Deep Equidistributed Representation for Face Recognition | [10.1109/CVPR.2019.00353](https://doi.org/10.1109/CVPR.2019.00353) |
| AM-Softmax | Additive Margin Softmax for Face Verification | [10.1109/LSP.2018.2822810](https://doi.org/10.1109/LSP.2018.2822810) |
| ArcFace | ArcFace: Additive Angular Margin Loss for Deep Face Recognition | [10.1109/CVPR.2019.00482](https://doi.org/10.1109/CVPR.2019.00482) |
| Sub-center ArcFace | Sub-Center ArcFace: Boosting Face Recognition by Large-Scale Noisy Web Faces | [10.1007/978-3-030-58621-8_43](https://doi.org/10.1007/978-3-030-58621-8_43) |
| CurricularFace | CurricularFace: Adaptive Curriculum Learning Loss for Deep Face Recognition | [10.1109/CVPR42600.2020.00594](https://doi.org/10.1109/CVPR42600.2020.00594) |
| KappaFace | KappaFace: Adaptive Additive Angular Margin Loss for Deep Face Recognition | [10.1109/ACCESS.2023.3338648](https://doi.org/10.1109/ACCESS.2023.3338648) |
| AwmFace | AwmFace: Adaptive Weighting Margin for Deep Face Recognition | [10.1109/IJCNN60899.2024.10651136](https://doi.org/10.1109/IJCNN60899.2024.10651136) |
| Class-Variant Margin Normalized Softmax | Class-Variant Margin Normalized Softmax Loss for Deep Face Recognition | [10.1109/TNNLS.2020.3017528](https://doi.org/10.1109/TNNLS.2020.3017528) |
| Adaptive Margin Softmax | AdaptiveFace: Adaptive Margin and Sampling for Face Recognition | [10.1109/CVPR.2019.01222](https://doi.org/10.1109/CVPR.2019.01222) |
| SFace | SFace: Sigmoid-Constrained Hypersphere Loss for Robust Face Recognition | [10.1109/TIP.2020.3048632](https://doi.org/10.1109/TIP.2020.3048632) |
| ElasticFace | ElasticFace: Elastic Margin Loss for Deep Face Recognition | [10.1109/CVPRW56347.2022.00164](https://doi.org/10.1109/CVPRW56347.2022.00164) |
| Orthogonality Loss | Orthogonality Loss: Learning Discriminative Representations for Face Recognition | [10.1109/TCSVT.2020.3021128](https://doi.org/10.1109/TCSVT.2020.3021128) |
| Fair Loss | Fair Loss: Margin-Aware Reinforcement Learning for Deep Face Recognition | [10.1109/ICCV.2019.01015](https://doi.org/10.1109/ICCV.2019.01015) |
| CosFace | CosFace: Large Margin Cosine Loss for Deep Face Recognition | [10.1109/CVPR.2018.00552](https://doi.org/10.1109/CVPR.2018.00552) |
| L-Softmax | Large-Margin Softmax Loss for Convolutional Neural Networks | - |
| L2-Softmax | L2-Constrained Softmax Loss for Discriminative Face Verification | - |
| NormFace | NormFace: L2 Hypersphere Embedding for Face Verification | [10.1145/3123266.3123359](https://doi.org/10.1145/3123266.3123359) |

## Metric Learning Losses

| Loss | Paper | DOI |
|---|---|---|
| Contrastive Loss | Dimensionality Reduction by Learning an Invariant Mapping | [10.1109/CVPR.2006.100](https://doi.org/10.1109/CVPR.2006.100) |
| Triplet Loss | FaceNet: A Unified Embedding for Face Recognition and Clustering | [10.1109/CVPR.2015.7298682](https://doi.org/10.1109/CVPR.2015.7298682) |
| Angular Loss | Deep Metric Learning with Angular Loss | [10.1109/ICCV.2017.283](https://doi.org/10.1109/ICCV.2017.283) |
| Quadruplet Loss | Beyond Triplet Loss: A Deep Quadruplet Network for Person Re-Identification | [10.1109/CVPR.2017.145](https://doi.org/10.1109/CVPR.2017.145) |
| Tuplet Margin Loss | Deep Metric Learning With Tuplet Margin Loss | [10.1109/ICCV.2019.00659](https://doi.org/10.1109/ICCV.2019.00659) |
| SupCon Loss | Supervised Contrastive Learning | - |
| Cosine Loss | Deep Learning on Small Datasets without Pre-Training using Cosine Loss | [10.1109/WACV45572.2020.9093286](https://doi.org/10.1109/WACV45572.2020.9093286) |
| CAC Loss | Class Anchor Clustering: A Loss for Distance-Based Open Set Recognition | [10.1109/WACV48630.2021.00361](https://doi.org/10.1109/WACV48630.2021.00361) |
| Group Loss++ | The Group Loss++: A Deeper Look Into Group Loss for Deep Metric Learning | [10.1109/TPAMI.2022.3163846](https://doi.org/10.1109/TPAMI.2022.3163846) |
| CAM Loss | A New Loss for Image Retrieval: Class Anchor Margin | [10.1007/978-981-97-2253-2_4](https://doi.org/10.1007/978-981-97-2253-2_4) |
| Range Loss | Range Loss for Deep Face Recognition with Long-Tailed Training Data | [10.1109/ICCV.2017.578](https://doi.org/10.1109/ICCV.2017.578) |
| Histogram Loss | Learning Deep Embeddings with Histogram Loss | - |
| Circle Loss | Circle Loss: A Unified Perspective of Pair Similarity Optimization | [10.1109/CVPR42600.2020.00643](https://doi.org/10.1109/CVPR42600.2020.00643) |
| Lifted Structure Loss | Deep Metric Learning via Lifted Structured Feature Embedding | [10.1109/CVPR.2016.434](https://doi.org/10.1109/CVPR.2016.434) |
| Multi-similarity Loss | Multi-Similarity Loss With General Pair Weighting for Deep Metric Learning | [10.1109/CVPR.2019.00516](https://doi.org/10.1109/CVPR.2019.00516) |

## Learning to Rank Losses

| Loss | Paper | DOI |
|---|---|---|
| ListWise Loss | Learning with Average Precision: Training Image Retrieval with a Listwise Loss | [10.1109/ICCV.2019.00521](https://doi.org/10.1109/ICCV.2019.00521) |
| FastAP | Deep Metric Learning to Rank | [10.1109/CVPR.2019.00196](https://doi.org/10.1109/CVPR.2019.00196) |
| RaMBO | Optimizing Rank-Based Metrics with Blackbox Differentiation | [10.1109/CVPR42600.2020.00764](https://doi.org/10.1109/CVPR42600.2020.00764) |
| Smooth-AP | Smooth-AP: Smoothing the Path Towards Large-Scale Image Retrieval | [10.1007/978-3-030-58545-7_39](https://doi.org/10.1007/978-3-030-58545-7_39) |
| AUC Loss | Area Under the ROC Curve Maximization for Metric Learning | [10.1109/CVPRW56347.2022.00318](https://doi.org/10.1109/CVPRW56347.2022.00318) |
| PNP Loss | Rethinking the Optimization of Average Precision: Only Penalizing Negative Instances before Positive Ones Is Enough | [10.1609/aaai.v36i2.20042](https://doi.org/10.1609/aaai.v36i2.20042) |
| CROLoss | CROLoss: Towards a Customizable Loss for Retrieval Models in Recommender Systems | [10.1145/3511808.3557274](https://doi.org/10.1145/3511808.3557274) |
| Recall@k Surrogate | Recall@k Surrogate Loss with Large Batches and Similarity Mixup | [10.1109/CVPR52688.2022.00735](https://doi.org/10.1109/CVPR52688.2022.00735) |
| ROADMAP | Optimization of Rank Losses for Image Retrieval | [10.1109/TPAMI.2025.3543846](https://doi.org/10.1109/TPAMI.2025.3543846) |
| NeuralLoss | NeuralLoss: A Learnable Pretrained Surrogate Loss for Learning to Rank | [10.1109/TKDE.2025.3562450](https://doi.org/10.1109/TKDE.2025.3562450) |

## Hybrid Losses

| Loss | Paper | DOI |
|---|---|---|
| Center Loss | A Discriminative Feature Learning Approach for Deep Face Recognition | [10.1007/978-3-319-46478-7_31](https://doi.org/10.1007/978-3-319-46478-7_31) |
| Center Invariant Loss | Deep Face Recognition with Center Invariant Loss | [10.1145/3126686.3126693](https://doi.org/10.1145/3126686.3126693) |
| Margin Loss | Margin Loss: Making Faces More Separable | [10.1109/LSP.2017.2789251](https://doi.org/10.1109/LSP.2017.2789251) |
| Git Loss | Git Loss for Deep Face Recognition | - |
| PEDCC Loss | A New Loss Function for CNN Classifier Based on Predefined Evenly-Distributed Class Centroids | [10.1109/ACCESS.2019.2960065](https://doi.org/10.1109/ACCESS.2019.2960065) |
| MixFace Loss | MixFace: Improving Face Verification with a Focus on Fine-Grained Conditions | [10.4218/etrij.2023-0167](https://doi.org/10.4218/etrij.2023-0167) |
| Ring Loss | Ring Loss: Convex Feature Normalization for Face Recognition | [10.1109/CVPR.2018.00534](https://doi.org/10.1109/CVPR.2018.00534) |
