# RescueADI：利用自主代理在遥感图像中实现灾难的自适应解读

发布时间：2024年10月17日

`Agent` `灾害管理`

> RescueADI: Adaptive Disaster Interpretation in Remote Sensing Images with Autonomous Agents

# 摘要

> 当前遥感图像中的灾害场景解释方法多聚焦于单一任务，如分割、检测或视觉问答。然而，这些方法在需要多感知方法和专用工具结合的任务上往往力不从心。为此，我们提出了自适应灾害解释（ADI），通过规划和执行多个相关解释任务，全面分析灾害场景。我们还推出了RescueADI数据集，包含高分辨率RSIs及规划、感知、识别三方面的注释。数据集涵盖4,044张图像、16,949个语义掩码、14,483个对象边界框和13,424个解释请求，涉及九种复杂请求类型。此外，我们提出了一种基于大型语言模型驱动的自主代理的灾害解释方法，有效处理复杂解释任务，如计数、面积计算和路径查找，无需人工干预。实验表明，我们的方法比现有VQA方法准确率高9%，优势明显。该数据集将公开，供研究使用。

> Current methods for disaster scene interpretation in remote sensing images (RSIs) mostly focus on isolated tasks such as segmentation, detection, or visual question-answering (VQA). However, current interpretation methods often fail at tasks that require the combination of multiple perception methods and specialized tools. To fill this gap, this paper introduces Adaptive Disaster Interpretation (ADI), a novel task designed to solve requests by planning and executing multiple sequentially correlative interpretation tasks to provide a comprehensive analysis of disaster scenes. To facilitate research and application in this area, we present a new dataset named RescueADI, which contains high-resolution RSIs with annotations for three connected aspects: planning, perception, and recognition. The dataset includes 4,044 RSIs, 16,949 semantic masks, 14,483 object bounding boxes, and 13,424 interpretation requests across nine challenging request types. Moreover, we propose a new disaster interpretation method employing autonomous agents driven by large language models (LLMs) for task planning and execution, proving its efficacy in handling complex disaster interpretations. The proposed agent-based method solves various complex interpretation requests such as counting, area calculation, and path-finding without human intervention, which traditional single-task approaches cannot handle effectively. Experimental results on RescueADI demonstrate the feasibility of the proposed task and show that our method achieves an accuracy 9% higher than existing VQA methods, highlighting its advantages over conventional disaster interpretation approaches. The dataset will be publicly available.

[Arxiv](https://arxiv.org/abs/2410.13384)