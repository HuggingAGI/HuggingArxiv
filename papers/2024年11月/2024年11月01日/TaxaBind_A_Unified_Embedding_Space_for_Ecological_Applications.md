# TaxaBind：生态应用的统一嵌入空间

发布时间：2024年11月01日

`LLM应用` `物种研究`

> TaxaBind: A Unified Embedding Space for Ecological Applications

# 摘要

> 我们推出了 TaxaBind，这是用于刻画任何感兴趣物种的统一嵌入空间。TaxaBind 是涵盖六种模态的多模态嵌入空间，即物种的地面图像、地理位置、卫星图像、文本、音频和环境特征，有助于解决生态问题。为学习此联合嵌入空间，我们以物种的地面图像作为绑定模态。我们提出了多模态修补技术，能将各种模态的知识有效提炼至绑定模态。我们构建了两个用于预训练的大型数据集：包含物种图像和卫星图像的 iSatNat，以及包含物种图像和音频的 iSoundNat。另外，我们引入了 TaxaBench-8k，这是一个具有六种配对模态的多元化多模态数据集，用于评估生态任务中的深度学习模型。TaxaBind 的实验显示，其在物种分类、跨模型检索和音频分类等一系列任务中具备强大的零样本和新兴能力。相关数据集和模型可在 https://github.com/mvrl/TaxaBind 获取。

> We present TaxaBind, a unified embedding space for characterizing any species of interest. TaxaBind is a multimodal embedding space across six modalities: ground-level images of species, geographic location, satellite image, text, audio, and environmental features, useful for solving ecological problems. To learn this joint embedding space, we leverage ground-level images of species as a binding modality. We propose multimodal patching, a technique for effectively distilling the knowledge from various modalities into the binding modality. We construct two large datasets for pretraining: iSatNat with species images and satellite images, and iSoundNat with species images and audio. Additionally, we introduce TaxaBench-8k, a diverse multimodal dataset with six paired modalities for evaluating deep learning models on ecological tasks. Experiments with TaxaBind demonstrate its strong zero-shot and emergent capabilities on a range of tasks including species classification, cross-model retrieval, and audio classification. The datasets and models are made available at https://github.com/mvrl/TaxaBind.

[Arxiv](https://arxiv.org/abs/2411.00683)