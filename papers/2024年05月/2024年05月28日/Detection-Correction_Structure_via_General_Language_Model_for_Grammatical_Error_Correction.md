# 利用通用语言模型构建的语法错误检测与修正框架

发布时间：2024年05月28日

`LLM应用

这篇论文摘要描述了一个基于大型语言模型（LLMs）的新结构DeCoGLM，用于语法错误修正（GEC）任务。该结构整合了检测和修正两个环节，通过特定的技术实现了模型内的多任务学习，并在英语和中文GEC数据集上展示了优异的性能。这表明论文主要关注的是LLMs在实际应用中的具体实现和效果，因此应归类为LLM应用。`

> Detection-Correction Structure via General Language Model for Grammatical Error Correction

# 摘要

> 语法错误修正（GEC）任务旨在通过最小化编辑来修正文本，其核心包括检测与修正两个环节。以往研究多侧重于直接修正，鲜有将两者融合于单一模型的尝试。大型语言模型（LLMs）对检测-修正范式的研究亦显不足。本文提出的DeCoGLM结构，基于通用语言模型（GLM），巧妙地将检测与修正环节整合。检测阶段采用容错模板，修正阶段则运用自回归掩码填充技术，精准定位并修正错误。通过精心设计输入令牌与注意力掩码，DeCoGLM实现了模型内的多任务学习。实验证明，DeCoGLM在英语与中文GEC数据集上均展现出与顶尖模型相媲美的性能，揭示了LLMs中检测-修正结构的有效性，为GEC领域开辟了新的研究方向。

> Grammatical error correction (GEC) is a task dedicated to rectifying texts with minimal edits, which can be decoupled into two components: detection and correction. However, previous works have predominantly focused on direct correction, with no prior efforts to integrate both into a single model. Moreover, the exploration of the detection-correction paradigm by large language models (LLMs) remains underdeveloped. This paper introduces an integrated detection-correction structure, named DeCoGLM, based on the General Language Model (GLM). The detection phase employs a fault-tolerant detection template, while the correction phase leverages autoregressive mask infilling for localized error correction. Through the strategic organization of input tokens and modification of attention masks, we facilitate multi-task learning within a single model. Our model demonstrates competitive performance against the state-of-the-art models on English and Chinese GEC datasets. Further experiments present the effectiveness of the detection-correction structure in LLMs, suggesting a promising direction for GEC.

![利用通用语言模型构建的语法错误检测与修正框架](../../../paper_images/2405.17804/x1.png)

![利用通用语言模型构建的语法错误检测与修正框架](../../../paper_images/2405.17804/x2.png)

![利用通用语言模型构建的语法错误检测与修正框架](../../../paper_images/2405.17804/x3.png)

![利用通用语言模型构建的语法错误检测与修正框架](../../../paper_images/2405.17804/x4.png)

![利用通用语言模型构建的语法错误检测与修正框架](../../../paper_images/2405.17804/loss-observation.png)

[Arxiv](https://arxiv.org/abs/2405.17804)