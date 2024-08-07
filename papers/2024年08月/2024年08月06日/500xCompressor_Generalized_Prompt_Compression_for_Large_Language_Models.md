# 500xCompressor：专为大型语言模型设计的通用提示压缩工具

发布时间：2024年08月06日

`LLM应用` `问答系统`

> 500xCompressor: Generalized Prompt Compression for Large Language Models

# 摘要

> 提示压缩技术对于提升推理效率、节约成本及优化用户体验至关重要。然而，现有方法常受限于低压缩比及评估中的潜在数据泄露问题。为此，我们研发了500xCompressor，一种能将庞大自然语言上下文精简至单一特殊标记的创新方法。该技术仅增加约0.3%的参数，却能实现6至480倍的惊人压缩比。它不仅适用于各类文本压缩与问答，还能直接与原始大型语言模型（LLM）协同工作，无需额外微调。经过在Arxiv语料库预训练及ArxivQA数据集微调后，500xCompressor在全新及经典问答数据集上展现了优异性能，LLM能力保留率高达62.26-72.89%。研究进一步揭示，并非所有压缩标记均等效利用，且在高压缩比情境下，K V值在信息保留方面显著优于嵌入技术。自然语言提示的高度压缩潜力，尤其是针对精细复杂信息，为未来应用及新一代LLM语言开发打开了无限可能。

> Prompt compression is crucial for enhancing inference speed, reducing costs, and improving user experience. However, current methods face challenges such as low compression ratios and potential data leakage during evaluation. To address these issues, we propose 500xCompressor, a method that compresses extensive natural language contexts into a minimum of one single special token. The 500xCompressor introduces approximately 0.3% additional parameters and achieves compression ratios ranging from 6x to 480x. It is designed to compress any text, answer various types of questions, and could be utilized by the original large language model (LLM) without requiring fine-tuning. Initially, 500xCompressor was pretrained on the Arxiv Corpus, followed by fine-tuning on the ArxivQA dataset, and subsequently evaluated on strictly unseen and classical question answering (QA) datasets. The results demonstrate that the LLM retained 62.26-72.89% of its capabilities compared to using non-compressed prompts. This study also shows that not all the compressed tokens are equally utilized and that K V values have significant advantages over embeddings in preserving information at high compression ratios. The highly compressive nature of natural language prompts, even for fine-grained complex information, suggests promising potential for future applications and further research into developing a new LLM language.

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/cover_figure_2.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/0-1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/reg-1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/reg-2.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/qa-1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/qa-2.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/reg-qa-legend.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/reg-rouge-1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/reg-rouge-2.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/reg-rouge-3.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/qa-f1-1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/qa-f1-2.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/qa-f1-3.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/ablation-legend.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/pretrain-loss-1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/pretrain-loss-2.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/pretrain-loss-3.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/finetune-loss-1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/finetune-loss-2.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/finetune-loss-3.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/loss-legend.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/squad-f1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/re-f1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/hotpotqa-f1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/race-f1.png)

![500xCompressor：专为大型语言模型设计的通用提示压缩工具](../../../paper_images/2408.03094/reg-qa-legend.png)

[Arxiv](https://arxiv.org/abs/2408.03094)