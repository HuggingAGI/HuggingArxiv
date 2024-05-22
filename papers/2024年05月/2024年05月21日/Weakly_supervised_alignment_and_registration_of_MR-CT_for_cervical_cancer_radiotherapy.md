# 宫颈癌放疗中，通过弱监督方法实现MR与CT图像的对齐与注册。

发布时间：2024年05月21日

`Agent

理由：这篇论文主要介绍了一种空间对齐算法及弱监督多模态配准网络，用于解决多模态图像配准的问题，特别是在医疗领域中的应用。虽然这种方法可以被视为一种技术应用，但其核心在于开发和利用一个智能系统（Agent）来处理和解决特定问题，即通过算法和网络实现自动化的图像配准。这与Agent分类下的研究内容相符，即开发和研究能够自主执行任务的智能系统。因此，将这篇论文归类于Agent是合适的。` `放射治疗`

> Weakly supervised alignment and registration of MR-CT for cervical cancer radiotherapy

# 摘要

> 宫颈癌是女性健康的一大威胁，近距离放射治疗是其主要治疗手段。为了提升诊断与治疗的精准度，精确界定宫颈旁组织的侵犯范围至关重要。结合CT与MRI的信息特征，我们或许能更精确地勾勒出这一范围。信息融合始于图像配准，但多模态图像因深度不同，手动配准不仅易错且耗时。加之ROI大小与图像形状的变异，精确配准面临挑战。本文提出了一种空间对齐算法及弱监督多模态配准网络，有效利用了医生提供的有限标注信息，实现了多模态图像的自动对齐。通过金字塔特征与成本体积估计光流，我们的方法在多个评估指标上超越了传统方法，证明了其在多模态图像配准中的优越性。

> Cervical cancer is one of the leading causes of death in women, and brachytherapy is currently the primary treatment method. However, it is important to precisely define the extent of paracervical tissue invasion to improve cancer diagnosis and treatment options. The fusion of the information characteristics of both computed tomography (CT) and magnetic resonance imaging(MRI) modalities may be useful in achieving a precise outline of the extent of paracervical tissue invasion. Registration is the initial step in information fusion. However, when aligning multimodal images with varying depths, manual alignment is prone to large errors and is time-consuming. Furthermore, the variations in the size of the Region of Interest (ROI) and the shape of multimodal images pose a significant challenge for achieving accurate registration.In this paper, we propose a preliminary spatial alignment algorithm and a weakly supervised multimodal registration network. The spatial position alignment algorithm efficiently utilizes the limited annotation information in the two modal images provided by the doctor to automatically align multimodal images with varying depths. By utilizing aligned multimodal images for weakly supervised registration and incorporating pyramidal features and cost volume to estimate the optical flow, the results indicate that the proposed method outperforms traditional volume rendering alignment methods and registration networks in various evaluation metrics. This demonstrates the effectiveness of our model in multimodal image registration.

[Arxiv](https://arxiv.org/abs/2405.12850)