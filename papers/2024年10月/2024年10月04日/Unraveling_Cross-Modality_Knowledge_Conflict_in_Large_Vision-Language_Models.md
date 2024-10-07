# 揭示大型视觉-语言模型中的跨模态知识冲突

发布时间：2024年10月04日

`LLM应用` `人工智能` `计算机视觉`

> Unraveling Cross-Modality Knowledge Conflict in Large Vision-Language Models

# 摘要

> 大型视觉-语言模型 (LVLMs) 在处理多模态输入方面表现出色，但它们容易受到视觉和语言组件间知识不一致导致的参数知识冲突。本文中，我们正式定义了 $\textbf{跨模态参数知识冲突}$ 问题，并提出了一套系统方法来检测、解释和缓解这些冲突。我们设计了一个管道，用于识别视觉和文本答案间的冲突，发现无论模型大小，近期 LVLMs 的跨模态冲突率始终居高不下。我们还研究了这些冲突如何影响推理过程，并提出了一种对比度量来区分冲突样本。基于这些发现，我们开发了一种动态对比解码方法，根据答案置信度移除置信度较低模态的不良对数。对于不提供对数的模型，我们提出了两种基于提示的策略来缓解冲突。实验结果显示，我们的方法在 ViQuAE 和 InfoSeek 数据集上显著提升了准确性，使用 LLaVA-34B 时，平均准确性提高了 2.24%。

> Large Vision-Language Models (LVLMs) have demonstrated impressive capabilities for capturing and reasoning over multimodal inputs. However, these models are prone to parametric knowledge conflicts, which arise from inconsistencies of represented knowledge between their vision and language components. In this paper, we formally define the problem of $\textbf{cross-modality parametric knowledge conflict}$ and present a systematic approach to detect, interpret, and mitigate them. We introduce a pipeline that identifies conflicts between visual and textual answers, showing a persistently high conflict rate across modalities in recent LVLMs regardless of the model size. We further investigate how these conflicts interfere with the inference process and propose a contrastive metric to discern the conflicting samples from the others. Building on these insights, we develop a novel dynamic contrastive decoding method that removes undesirable logits inferred from the less confident modality components based on answer confidence. For models that do not provide logits, we also introduce two prompt-based strategies to mitigate the conflicts. Our methods achieve promising improvements in accuracy on both the ViQuAE and InfoSeek datasets. Specifically, using LLaVA-34B, our proposed dynamic contrastive decoding improves an average accuracy of 2.24%.

[Arxiv](https://arxiv.org/abs/2410.03659)