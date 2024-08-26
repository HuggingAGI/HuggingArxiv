# 多模态对比上下文学习

发布时间：2024年08月23日

`LLM理论` `人工智能` `多模态学习`

> Multimodal Contrastive In-Context Learning

# 摘要

> 随着大型语言模型 (LLM) 的广泛应用，无梯度上下文学习 (ICL) 的重要性日益凸显。然而，揭示其内部机制仍充满挑战。本文提出了一种创新的多模态对比 ICL 框架，旨在深化我们对 LLM 中 ICL 的理解。首先，我们通过对比学习方法，在实际应用中解读 ICL，将关键值表示的差异作为 ICL 的核心区分点。接着，我们构建了一个分析框架，以纠正多模态输入在实际数据集中的格式偏差。我们验证了 ICL 在基线性能不佳时的有效性，即便面对未见过的数据格式。最后，我们引入了一种即时 ICL 方法（基于文本锚定的 ICL），在检测仇恨表情包等资源受限任务中表现出色。大量实验表明，我们的方法在多种复杂和资源受限场景下显著提升了 ICL 性能，并揭示了 LLM 中 ICL 的运作机制。这些发现对于构建更具解释性、高效且稳健的多模态 AI 系统至关重要，尤其是在面对挑战性任务和资源受限环境时。

> The rapid growth of Large Language Models (LLMs) usage has highlighted the importance of gradient-free in-context learning (ICL). However, interpreting their inner workings remains challenging. This paper introduces a novel multimodal contrastive in-context learning framework to enhance our understanding of ICL in LLMs. First, we present a contrastive learning-based interpretation of ICL in real-world settings, marking the distance of the key-value representation as the differentiator in ICL. Second, we develop an analytical framework to address biases in multimodal input formatting for real-world datasets. We demonstrate the effectiveness of ICL examples where baseline performance is poor, even when they are represented in unseen formats. Lastly, we propose an on-the-fly approach for ICL (Anchored-by-Text ICL) that demonstrates effectiveness in detecting hateful memes, a task where typical ICL struggles due to resource limitations. Extensive experiments on multimodal datasets reveal that our approach significantly improves ICL performance across various scenarios, such as challenging tasks and resource-constrained environments. Moreover, it provides valuable insights into the mechanisms of in-context learning in LLMs. Our findings have important implications for developing more interpretable, efficient, and robust multimodal AI systems, especially in challenging tasks and resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2408.12959)