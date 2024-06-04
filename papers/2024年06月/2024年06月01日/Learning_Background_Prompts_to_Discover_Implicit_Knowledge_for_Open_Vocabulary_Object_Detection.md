# 探索背景提示，解锁开放词汇对象检测中的隐含知识宝库

发布时间：2024年06月01日

`Agent

理由：这篇论文主要介绍了一种新型的开放词汇对象检测（OVD）框架，名为LBP，它通过学习背景提示来挖掘并利用隐式背景知识，以提升检测器在基础与新型类别上的表现。这个框架涉及的模块和方法主要是为了增强检测器作为Agent的能力，即在复杂环境中识别和处理不同类别对象的能力。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论。` `计算机视觉` `对象检测`

> Learning Background Prompts to Discover Implicit Knowledge for Open Vocabulary Object Detection

# 摘要

> 开放词汇对象检测（OVD）旨在开发一种能够识别基础与新型类别对象的顶尖检测器。近期研究通过知识蒸馏，将大规模预训练视觉-语言模型的深刻知识迁移至对象检测任务，显著提升了检测器识别未知类别的能力。但这些方法在背景解释和模型过拟合上遇到难题，导致关键背景知识流失，检测器性能受限。为此，我们提出了一种名为LBP的新型OVD框架，通过学习背景提示来挖掘并利用隐式背景知识，从而提升检测器在基础与新型类别上的表现。我们设计了三个模块：背景类别特定提示、背景对象发现和推理概率校正，以增强检测器发现、表示和利用背景提案中隐式对象知识的能力。在OV-COCO和OV-LVIS两个基准数据集上的评估显示，我们的方法在处理OVD任务上超越了现有最先进技术。

> Open vocabulary object detection (OVD) aims at seeking an optimal object detector capable of recognizing objects from both base and novel categories. Recent advances leverage knowledge distillation to transfer insightful knowledge from pre-trained large-scale vision-language models to the task of object detection, significantly generalizing the powerful capabilities of the detector to identify more unknown object categories. However, these methods face significant challenges in background interpretation and model overfitting and thus often result in the loss of crucial background knowledge, giving rise to sub-optimal inference performance of the detector. To mitigate these issues, we present a novel OVD framework termed LBP to propose learning background prompts to harness explored implicit background knowledge, thus enhancing the detection performance w.r.t. base and novel categories. Specifically, we devise three modules: Background Category-specific Prompt, Background Object Discovery, and Inference Probability Rectification, to empower the detector to discover, represent, and leverage implicit object knowledge explored from background proposals. Evaluation on two benchmark datasets, OV-COCO and OV-LVIS, demonstrates the superiority of our proposed method over existing state-of-the-art approaches in handling the OVD tasks.

![探索背景提示，解锁开放词汇对象检测中的隐含知识宝库](../../../paper_images/2406.00510/x1.png)

![探索背景提示，解锁开放词汇对象检测中的隐含知识宝库](../../../paper_images/2406.00510/x2.png)

![探索背景提示，解锁开放词汇对象检测中的隐含知识宝库](../../../paper_images/2406.00510/x3.png)

![探索背景提示，解锁开放词汇对象检测中的隐含知识宝库](../../../paper_images/2406.00510/x4.png)

![探索背景提示，解锁开放词汇对象检测中的隐含知识宝库](../../../paper_images/2406.00510/x5.png)

![探索背景提示，解锁开放词汇对象检测中的隐含知识宝库](../../../paper_images/2406.00510/x6.png)

[Arxiv](https://arxiv.org/abs/2406.00510)