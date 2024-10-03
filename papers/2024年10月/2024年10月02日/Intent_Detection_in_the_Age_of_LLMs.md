# 在 LLM 时代，意图检测的新篇章

发布时间：2024年10月02日

`LLM应用` `对话系统` `人工智能`

> Intent Detection in the Age of LLMs

# 摘要

> 意图检测是任务导向对话系统的核心，它帮助系统在每次对话中准确识别用户意图。传统方法依赖于需要大量训练数据的监督模型，且在处理未知意图时表现不佳。生成式大型语言模型（LLM）凭借其丰富的知识库，为解决这一难题提供了新思路。我们通过自适应上下文学习和思维链提示，优化了 7 个顶尖 LLM 的意图检测能力，并与对比微调的句子变换器模型进行了性能对比，展示了预测质量与延迟之间的平衡。我们设计了一种混合系统，通过不确定性路由策略结合两种方法，并引入负数据增强，实现了在延迟降低 50% 的情况下，准确率接近原生 LLM 的 98%。此外，我们通过实验发现，LLM 的 OOS 检测能力受意图标签范围和标签空间大小的显著影响。我们还提出了一种两步法，利用 LLM 内部表示，显著提升了 OOS 检测的准确率和 F1 分数，特别适用于 Mistral-7B 模型。

> Intent detection is a critical component of task-oriented dialogue systems (TODS) which enables the identification of suitable actions to address user utterances at each dialog turn. Traditional approaches relied on computationally efficient supervised sentence transformer encoder models, which require substantial training data and struggle with out-of-scope (OOS) detection. The emergence of generative large language models (LLMs) with intrinsic world knowledge presents new opportunities to address these challenges. In this work, we adapt 7 SOTA LLMs using adaptive in-context learning and chain-of-thought prompting for intent detection, and compare their performance with contrastively fine-tuned sentence transformer (SetFit) models to highlight prediction quality and latency tradeoff. We propose a hybrid system using uncertainty based routing strategy to combine the two approaches that along with negative data augmentation results in achieving the best of both worlds ( i.e. within 2% of native LLM accuracy with 50% less latency). To better understand LLM OOS detection capabilities, we perform controlled experiments revealing that this capability is significantly influenced by the scope of intent labels and the size of the label space. We also introduce a two-step approach utilizing internal LLM representations, demonstrating empirical gains in OOS detection accuracy and F1-score by >5% for the Mistral-7B model.

[Arxiv](https://arxiv.org/abs/2410.01627)