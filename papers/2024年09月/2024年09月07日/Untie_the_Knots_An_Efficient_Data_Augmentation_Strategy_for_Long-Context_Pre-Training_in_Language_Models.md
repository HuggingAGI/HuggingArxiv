# 解开束缚：为语言模型长上下文预训练量身定制的高效数据增强策略

发布时间：2024年09月07日

`LLM理论` `人工智能`

> Untie the Knots: An Efficient Data Augmentation Strategy for Long-Context Pre-Training in Language Models

# 摘要

> 大型语言模型 (LLM) 致力于扩展上下文窗口，以整合更多信息。然而，训练模型处理长上下文面临诸多挑战，如高质量长文本数据的稀缺、短文本任务性能下降以及注意力机制导致的训练效率降低。为此，我们提出了 Untie the Knots (UtK)，一种在继续预训练阶段使用的创新数据增强策略。UtK 通过将文档分块、打乱顺序，构建复杂的长文本结构，训练 LLM 解开这些“结”，在混乱的标记序列中精准识别相关片段。实验表明，UtK 在 128K 上下文长度下，7B 和 72B 参数模型的 RULER 准确率分别达到 75% 和 84.5%，显著超越其他长上下文策略。训练后的模型将开源，供后续研究使用。

> Large language models (LLM) have prioritized expanding the context window from which models can incorporate more information. However, training models to handle long contexts presents significant challenges. These include the scarcity of high-quality natural long-context data, the potential for performance degradation on short-context tasks, and the reduced training efficiency associated with attention mechanisms. In this paper, we introduce Untie the Knots (\textbf{UtK}), a novel data augmentation strategy employed during the continue pre-training phase, designed to efficiently enable LLMs to gain long-context capabilities without the need to modify the existing data mixture. In particular, we chunk the documents, shuffle the chunks, and create a complex and knotted structure of long texts; LLMs are then trained to untie these knots and identify relevant segments within seemingly chaotic token sequences. This approach greatly improves the model's performance by accurately attending to relevant information in long context and the training efficiency is also largely increased. We conduct extensive experiments on models with 7B and 72B parameters, trained on 20 billion tokens, demonstrating that UtK achieves 75\% and 84.5\% accurracy on RULER at 128K context length, significantly outperforming other long context strategies. The trained models will open-source for further research.

[Arxiv](https://arxiv.org/abs/2409.04774)