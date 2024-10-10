# 无需训练，借助注意力提示实现开放式对象检测与分割

发布时间：2024年10月08日

`LLM应用` `计算机视觉` `人工智能`

> Training-Free Open-Ended Object Detection and Segmentation via Attention as Prompts

# 摘要

> 现有的感知模型虽通过大量标注数据学习取得了成功，但在开放世界场景中仍显不足。为解决此问题，研究人员提出了开放集感知任务，以检测或分割训练集中未见过的对象。然而，这些模型在推理时需预定义对象类别，这在现实世界中难以实现。最近，研究人员提出了更实际的开放式对象检测问题，即在不使用任何对象类别的情况下发现新对象。本文中，我们提出了VL-SAM，一个无需训练的框架，结合视觉语言模型和分割一切模型，以解决开放式对象检测和分割任务。我们通过注意力图作为提示，将这两个模型连接起来，无需额外训练。具体来说，我们设计了注意力图生成模块，通过头部聚合和正则化注意力流，生成高质量的注意力图。然后，我们通过提示生成模块从注意力图中采样正负点，并发送给SAM以分割对象。实验结果表明，我们的方法在对象检测任务上超越了现有方法，并能提供额外的实例分割掩码。此外，VL-SAM在实际应用中表现出色，并展示了良好的模型泛化能力，可结合多种VLM和SAM。

> Existing perception models achieve great success by learning from large amounts of labeled data, but they still struggle with open-world scenarios. To alleviate this issue, researchers introduce open-set perception tasks to detect or segment unseen objects in the training set. However, these models require predefined object categories as inputs during inference, which are not available in real-world scenarios. Recently, researchers pose a new and more practical problem, \textit{i.e.}, open-ended object detection, which discovers unseen objects without any object categories as inputs. In this paper, we present VL-SAM, a training-free framework that combines the generalized object recognition model (\textit{i.e.,} Vision-Language Model) with the generalized object localization model (\textit{i.e.,} Segment-Anything Model), to address the open-ended object detection and segmentation task. Without additional training, we connect these two generalized models with attention maps as the prompts. Specifically, we design an attention map generation module by employing head aggregation and a regularized attention flow to aggregate and propagate attention maps across all heads and layers in VLM, yielding high-quality attention maps. Then, we iteratively sample positive and negative points from the attention maps with a prompt generation module and send the sampled points to SAM to segment corresponding objects. Experimental results on the long-tail instance segmentation dataset (LVIS) show that our method surpasses the previous open-ended method on the object detection task and can provide additional instance segmentation masks. Besides, VL-SAM achieves favorable performance on the corner case object detection dataset (CODA), demonstrating the effectiveness of VL-SAM in real-world applications. Moreover, VL-SAM exhibits good model generalization that can incorporate various VLMs and SAMs.

[Arxiv](https://arxiv.org/abs/2410.05963)