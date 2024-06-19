# 辩论优化：自适应共形预测与多样化检索在事件抽取中的应用

发布时间：2024年06月17日

`Agent

理由：这篇论文介绍了一种名为多代理辩论优化（DAO）的系统，该系统通过代理（即多个代理）之间的辩论来优化大型语言模型（LLMs）的输出。这里的核心在于使用多个代理来改进模型输出，而不涉及模型参数的调整，这与Agent分类中的概念相符，即使用代理系统来处理和优化任务。此外，论文中提到的多样性检索与生成（DRAG）和自适应共形预测（AdaCP）模块，都是为了支持代理间的辩论过程，进一步强化了这一分类。` `事件检测`

> Debate as Optimization: Adaptive Conformal Prediction and Diverse Retrieval for Event Extraction

# 摘要

> 我们设计了一种名为多代理辩论优化（DAO）的系统，旨在通过辩论不断精炼大型语言模型（LLMs）的输出，而无需调整模型参数。DAO系统中包含了两个新颖模块：多样性检索与生成（DRAG）和自适应共形预测（AdaCP）。DRAG负责检索与辩论最相关的信息，AdaCP则通过筛选低质量答案提升事件提取的准确性和可信度。实验表明，在事件检测和论点提取任务上，我们的方法在ACE05和CASIE数据集上分别将性能差距缩小了18.1%、17.8%和17.9%、15.2%，显著优于传统监督学习方法。

> We propose a multi-agent debate as optimization (DAO) system for event extraction, where the primary objective is to iteratively refine the large language models (LLMs) outputs through debating without parameter tuning. In DAO, we introduce two novel modules: the Diverse-RAG (DRAG) module and the Adaptive Conformal Prediction (AdaCP) module. DRAG systematically retrieves supporting information that best fits the debate discussion, while AdaCP enhances the accuracy and reliability of event extraction by effectively rejecting less promising answers. Experimental results demonstrate a significant reduction in the performance gap between supervised approaches and tuning-free LLM-based methods by 18.1% and 17.8% on ACE05 and 17.9% and 15.2% on CASIE for event detection and argument extraction respectively.

![辩论优化：自适应共形预测与多样化检索在事件抽取中的应用](../../../paper_images/2406.12197/x1.png)

![辩论优化：自适应共形预测与多样化检索在事件抽取中的应用](../../../paper_images/2406.12197/flanxxl_icl.png)

![辩论优化：自适应共形预测与多样化检索在事件抽取中的应用](../../../paper_images/2406.12197/flanxxl_1.png)

![辩论优化：自适应共形预测与多样化检索在事件抽取中的应用](../../../paper_images/2406.12197/flanxxl_2.png)

[Arxiv](https://arxiv.org/abs/2406.12197)