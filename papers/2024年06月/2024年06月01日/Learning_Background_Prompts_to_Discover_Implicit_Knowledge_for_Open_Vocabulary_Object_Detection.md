# 探索背景提示，揭示开放词汇对象检测中的隐含知识

发布时间：2024年06月01日

`Agent

理由：这篇论文介绍了一个名为LBP的新框架，该框架通过学习背景提示来利用隐式背景知识，以提升对象检测器识别基础与新颖类别的能力。这个框架包含特定的模块，用于挖掘并利用背景提案中的隐式对象知识。这种方法涉及到开发和利用智能体（Agent）来执行特定的任务，即对象检测，并且该智能体能够从环境中学习并改进其性能。因此，这篇论文更符合Agent分类，因为它描述了一个能够自主学习和执行任务的系统。` `计算机视觉` `对象检测`

> Learning Background Prompts to Discover Implicit Knowledge for Open Vocabulary Object Detection

# 摘要

> 开放词汇对象检测（OVD）追求的是一种能够识别基础与新颖类别的顶尖对象检测器。近期，通过知识蒸馏，将大规模预训练的视觉-语言模型的深刻知识迁移至对象检测任务，极大地增强了检测器识别未知类别的能力。但这些方法在背景解释和模型过拟合上遭遇难题，导致关键背景知识流失，检测器性能受限。为此，我们推出了名为LBP的新框架，通过学习背景提示，巧妙利用隐式背景知识，显著提升了对基础与新颖类别的检测能力。该框架包含三个创新模块：背景类别特定提示、背景对象发现及推理概率校正，旨在挖掘并利用背景提案中的隐式对象知识。在OV-COCO与OV-LVIS两大基准数据集上的评估显示，我们的方法在处理OVD任务上超越了现有技术水平。

> Open vocabulary object detection (OVD) aims at seeking an optimal object detector capable of recognizing objects from both base and novel categories. Recent advances leverage knowledge distillation to transfer insightful knowledge from pre-trained large-scale vision-language models to the task of object detection, significantly generalizing the powerful capabilities of the detector to identify more unknown object categories. However, these methods face significant challenges in background interpretation and model overfitting and thus often result in the loss of crucial background knowledge, giving rise to sub-optimal inference performance of the detector. To mitigate these issues, we present a novel OVD framework termed LBP to propose learning background prompts to harness explored implicit background knowledge, thus enhancing the detection performance w.r.t. base and novel categories. Specifically, we devise three modules: Background Category-specific Prompt, Background Object Discovery, and Inference Probability Rectification, to empower the detector to discover, represent, and leverage implicit object knowledge explored from background proposals. Evaluation on two benchmark datasets, OV-COCO and OV-LVIS, demonstrates the superiority of our proposed method over existing state-of-the-art approaches in handling the OVD tasks.

![探索背景提示，揭示开放词汇对象检测中的隐含知识](../../../paper_images/2406.00510/x1.png)

![探索背景提示，揭示开放词汇对象检测中的隐含知识](../../../paper_images/2406.00510/x2.png)

![探索背景提示，揭示开放词汇对象检测中的隐含知识](../../../paper_images/2406.00510/x3.png)

![探索背景提示，揭示开放词汇对象检测中的隐含知识](../../../paper_images/2406.00510/x4.png)

![探索背景提示，揭示开放词汇对象检测中的隐含知识](../../../paper_images/2406.00510/x5.png)

![探索背景提示，揭示开放词汇对象检测中的隐含知识](../../../paper_images/2406.00510/x6.png)

[Arxiv](https://arxiv.org/abs/2406.00510)