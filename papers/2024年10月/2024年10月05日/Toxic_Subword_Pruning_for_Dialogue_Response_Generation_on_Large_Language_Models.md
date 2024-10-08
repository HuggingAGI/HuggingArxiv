# 在大型语言模型中生成对话响应时，修剪有害子词

发布时间：2024年10月05日

`LLM应用` `人工智能` `网络安全`

> Toxic Subword Pruning for Dialogue Response Generation on Large Language Models

# 摘要

> 保护大型语言模型 (LLM) 免于生成有毒内容是一个关键研究领域。然而，现有研究多集中在通过更新模型权重来修复 LLM 的训练技术上，这种方法既昂贵又繁琐，且容易导致灾难性遗忘。为此，我们提出了一种简单而有效的算法——\textbf{Tox}ic Subword \textbf{Prun}ing (ToxPrune)，用于修剪训练后 LLM 中 BPE 包含的有毒子词。与之前认为修剪 BPE 标记对机器翻译有害的研究不同，我们发现 ToxPrune 在防止 LLM 生成有毒内容方面效果显著。此外，ToxPrune 不仅改善了有毒模型 NSFW-3B 在对话生成任务上的表现，还显著提升了 Llama-3.1-6B 的对话多样性。广泛的自动评估和人工测试表明，ToxPrune 在修复有毒 LLM 和提升非有毒 LLM 的对话生成能力方面具有潜力。\footnote{我们计划发布相关资源以支持未来研究。}

> How to defend large language models (LLMs) from generating toxic content is an important research area. Yet, most research focused on various model training techniques to remediate LLMs by updating their weights. A typical related research area is safety alignment. This however is often costly and tedious and can expose the model to even more problems such as catastrophic forgetting if the trainings are not carefully handled by experienced NLP practitioners. We thus propose a simple yet effective and novel algorithm, namely \textbf{Tox}ic Subword \textbf{Prun}ing (ToxPrune) to prune the subword contained by the toxic words from BPE in trained LLMs. In contrast to the previous work that demonstrates pruning BPE tokens as harmful to the task of machine translation, we surprisingly found its usefulness in preventing toxic content from being generated on LLMs. Fortunately, our findings suggest that ToxPrune simultaneously improves the toxic language model NSFW-3B on the task of dialogue response generation obviously. We surprisingly found that ToxPrune can even obviously improve official Llama-3.1-6B in the metric of dialogue diversity. Extensive automatic results and human evaluation indicate that ToxPrune could be helpful for both remediating toxic LLMs and improving non-toxic LLMs on the task of dialogue response generation.\footnote{We plan to release the resources to facilitate future work.}

[Arxiv](https://arxiv.org/abs/2410.04155)