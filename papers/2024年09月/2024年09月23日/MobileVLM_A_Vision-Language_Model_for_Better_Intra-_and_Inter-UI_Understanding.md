# MobileVLM：一款专为提升 UI 内部及跨 UI 理解的视觉-语言模型

发布时间：2024年09月23日

`Agent` `移动应用` `人工智能`

> MobileVLM: A Vision-Language Model for Better Intra- and Inter-UI Understanding

# 摘要

> 近期，基于视觉语言模型（VLM）的移动AI代理备受瞩目。这些系统通常以VLM为基础，通过移动数据集进行指令微调。然而，这些VLM多在通用数据上预训练，导致移动领域特定能力不足，难以识别特定UI元素及理解细粒度信息。此外，现有微调任务仅关注与指令最相关的元素，忽视了UI页面间的关系及元素在页面转换中的作用。为此，我们提出了MobileVLM，通过两个额外预训练阶段，强化UI内部及跨UI理解。我们设计了四个基于UI的预训练任务，提升模型对细粒度元素及页面转换动作的感知能力。为弥补移动预训练数据的不足，我们自建了包含300万UI页面及真实转换动作的大型中文数据集Mobile3M，形成有向图结构。实验表明，MobileVLM在测试集及公共基准上均表现出色，超越了现有VLM。

> Recently, mobile AI agents based on VLMs have been gaining increasing attention. These works typically utilize VLM as a foundation, fine-tuning it with instruction-based mobile datasets. However, these VLMs are typically pre-trained on general-domain data, which often results in a lack of fundamental capabilities specific to the mobile domain. Therefore, they may struggle to recognize specific UI elements and understand intra-UI fine-grained information. In addition, the current fine-tuning task focuses on interacting with the most relevant element for the given instruction. These fine-tuned VLMs may still ignore the relationships between UI pages, neglect the roles of elements in page transitions and lack inter-UI understanding. To address issues, we propose a VLM called MobileVLM, which includes two additional pre-training stages to enhance both intra- and inter-UI understanding. We defined four UI-based pre-training tasks, enabling the model to better perceive fine-grained elements and capture page transition actions. To address the lack of mobile pre-training data, we built a large Chinese mobile dataset Mobile3M from scratch, which contains 3 million UI pages, and real-world transition actions, forming a directed graph structure. Experimental results show MobileVLM excels on both our test set and public mobile benchmarks, outperforming existing VLMs.

[Arxiv](https://arxiv.org/abs/2409.14818)