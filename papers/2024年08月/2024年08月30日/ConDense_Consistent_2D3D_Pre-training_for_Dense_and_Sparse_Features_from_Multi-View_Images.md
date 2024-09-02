# ConDense：通过多视图图像，为密集与稀疏特征提供一致的2D/3D预训练方案。

发布时间：2024年08月30日

`LLM应用` `计算机视觉` `3D建模`

> ConDense: Consistent 2D/3D Pre-training for Dense and Sparse Features from Multi-View Images

# 摘要

> 本文推出ConDense框架，通过融合预训练2D网络与大规模多视图数据集，推动3D模型预训练的前沿。我们创新的2D-3D联合训练方案，通过端到端流程确保2D与3D特征的共嵌入与一致性，利用体积渲染技术强化特征匹配。密集像素特征的应用使我们能够：1）无缝迁移2D模型的先验知识至3D模型，构建强健的3D基础；2）提升2D特征的纯净度与一致性；3）打造一个多模态兼容的嵌入空间，让2D、3D及自然语言等数据模态能协同工作。此外，ConDense不仅擅长处理密集特征，还能精炼出稀疏但关键的特征点，如装饰性关键点，从而简化3D NeRF表示。我们的预训练模型在3D分类与分割等任务中表现卓越，大幅超越现有预训练方法。同时，它还赋能多项高效下游任务，如2D-3D图像匹配、3D场景去重及自然语言驱动的3D场景检索，且无需场景级微调。

> To advance the state of the art in the creation of 3D foundation models, this paper introduces the ConDense framework for 3D pre-training utilizing existing pre-trained 2D networks and large-scale multi-view datasets. We propose a novel 2D-3D joint training scheme to extract co-embedded 2D and 3D features in an end-to-end pipeline, where 2D-3D feature consistency is enforced through a volume rendering NeRF-like ray marching process. Using dense per pixel features we are able to 1) directly distill the learned priors from 2D models to 3D models and create useful 3D backbones, 2) extract more consistent and less noisy 2D features, 3) formulate a consistent embedding space where 2D, 3D, and other modalities of data (e.g., natural language prompts) can be jointly queried. Furthermore, besides dense features, ConDense can be trained to extract sparse features (e.g., key points), also with 2D-3D consistency -- condensing 3D NeRF representations into compact sets of decorated key points. We demonstrate that our pre-trained model provides good initialization for various 3D tasks including 3D classification and segmentation, outperforming other 3D pre-training methods by a significant margin. It also enables, by exploiting our sparse features, additional useful downstream tasks, such as matching 2D images to 3D scenes, detecting duplicate 3D scenes, and querying a repository of 3D scenes through natural language -- all quite efficiently and without any per-scene fine-tuning.

[Arxiv](https://arxiv.org/abs/2408.17027)