# deepmriprep：利用深度神经网络实现 VBM 预处理

发布时间：2024年08月20日

`LLM应用` `神经影像学`

> deepmriprep: Voxel-based Morphometry (VBM) Preprocessing via Deep Neural Networks

# 摘要

> 摘要：体素形态测量学（VBM）自2000年起在神经影像学研究中崭露头角，已应用于7000多项研究。通过磁共振成像（MRI）数据，VBM分析脑组织密度局部变化，并探讨其与生物和心理测量变量的联系。我们推出的deepmriprep，是一款基于神经网络的预处理管道，专为T1加权MR图像的VBM分析设计，利用深度神经网络完成所有必要步骤。借助图形处理单元（GPU），deepmriprep的处理速度比CAT12快37倍，后者是当前领先的VBM预处理工具箱。在组织分割和图像配准方面，deepmriprep与CAT12的准确性不相上下，这一结论基于超过100个数据集，并在VBM结果中展现出强相关性。deepmriprep的组织分割图与真实地图的一致性超过95%，其非线性配准使用监督的SYMNet，预测的变形场与CAT12相当。deepmriprep的高效处理能力使得大规模数据集的快速预处理成为可能，推动了VBM分析在大规模神经影像学研究中的应用，并有望实现实时分析。其简洁、模块化的设计便于研究人员理解、应用和进一步发展，为神经影像学研究开辟新路径。deepmriprep可作为Python包轻松安装，并在此https URL上公开提供。

> 
Abstract:Voxel-based Morphometry (VBM) has emerged as a powerful approach in neuroimaging research, utilized in over 7,000 studies since the year 2000. Using Magnetic Resonance Imaging (MRI) data, VBM assesses variations in the local density of brain tissue and examines its associations with biological and psychometric variables. Here, we present deepmriprep, a neural network-based pipeline that performs all necessary preprocessing steps for VBM analysis of T1-weighted MR images using deep neural networks. Utilizing the Graphics Processing Unit (GPU), deepmriprep is 37 times faster than CAT12, the leading VBM preprocessing toolbox. The proposed method matches CAT12 in accuracy for tissue segmentation and image registration across more than 100 datasets and shows strong correlations in VBM results. Tissue segmentation maps from deepmriprep have over 95% agreement with ground truth maps, and its non-linear registration, using supervised SYMNet, predicts smooth deformation fields comparable to CAT12. The high processing speed of deepmriprep enables rapid preprocessing of extensive datasets and thereby fosters the application of VBM analysis to large-scale neuroimaging studies and opens the door to real-time applications. Finally, deepmripreps straightforward, modular design enables researchers to easily understand, reuse, and advance the underlying methods, fostering further advancements in neuroimaging research. deepmriprep can be conveniently installed as a Python package and is publicly accessible at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2408.10656)