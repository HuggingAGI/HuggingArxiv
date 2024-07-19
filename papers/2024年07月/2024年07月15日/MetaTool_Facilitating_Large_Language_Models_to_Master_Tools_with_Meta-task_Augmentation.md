# MetaTool：借助元任务增强，助力大型语言模型精通工具使用

发布时间：2024年07月15日

`Agent` `人工智能` `软件开发`

> MetaTool: Facilitating Large Language Models to Master Tools with Meta-task Augmentation

# 摘要

> 在现实场景中，AI 代理需要掌握复杂工具，这依赖于大型语言模型 (LLM) 的运用。核心难题是理解工具的使用和功能。传统方法如少量演示或专家轨迹微调虽有效，但对复杂工具和任务，仅依赖上下文演示可能不足。此外，基于训练的方法因数据集构建成本高和泛化能力有限而受限。为此，我们提出了一种新的工具学习方法 MetaTool，适用于任何可重复使用的工具集。该方法通过自监督数据增强技术，让 LLM 全面理解工具，提升任务完成能力。我们设计了一系列元任务，通过预测工具执行的掩蔽因素，自动生成高质量的工具理解 QA 数据。将这些数据融入指令调优过程，MetaTool 模型在工具导向任务上表现卓越，与 GPT-4/GPT-3.5 媲美。

> Utilizing complex tools with Large Language Models (LLMs) is a critical component for grounding AI agents in various real-world scenarios. The core challenge of manipulating tools lies in understanding their usage and functionality. The prevailing approach involves few-shot prompting with demonstrations or fine-tuning on expert trajectories. However, for complex tools and tasks, mere in-context demonstrations may fail to cover sufficient knowledge. Training-based methods are also constrained by the high cost of dataset construction and limited generalizability. In this paper, we introduce a new tool learning methodology (MetaTool) that is generalizable for mastering any reusable toolset. Our approach includes a self-supervised data augmentation technique that enables LLMs to gain a comprehensive understanding of various tools, thereby improving their ability to complete tasks effectively. We develop a series of meta-tasks that involve predicting masked factors of tool execution. These self-supervised tasks enable the automatic generation of high-quality QA data concerning tool comprehension. By incorporating meta-task data into the instruction tuning process, the proposed MetaTool model achieves significant superiority to open-source models and is comparable to GPT-4/GPT-3.5 on multiple tool-oriented tasks.

![MetaTool：借助元任务增强，助力大型语言模型精通工具使用](../../../paper_images/2407.12871/Figure_1.jpg)

![MetaTool：借助元任务增强，助力大型语言模型精通工具使用](../../../paper_images/2407.12871/Figure_2.jpg)

![MetaTool：借助元任务增强，助力大型语言模型精通工具使用](../../../paper_images/2407.12871/Figure_3.png)

![MetaTool：借助元任务增强，助力大型语言模型精通工具使用](../../../paper_images/2407.12871/Figure_4.png)

[Arxiv](https://arxiv.org/abs/2407.12871)