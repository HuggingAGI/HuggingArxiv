# UI-JEPA：通过屏幕用户活动主动感知用户意图

发布时间：2024年09月06日

`LLM应用` `软件开发` `用户体验`

> UI-JEPA: Towards Active Perception of User Intent through Onscreen User Activity

# 摘要

> 从UI操作序列中推断用户意图是全面UI理解的关键难题。尽管多模态大型语言模型（MLLMs）在此领域取得了显著进展，但其对大量参数、计算资源和高延迟的需求使其难以应用于轻量级、低延迟或高隐私要求的设备解决方案。此外，高质量数据集的匮乏也限制了轻量级模型的发展。为此，我们提出了UI-JEPA，一种通过掩码策略和自监督学习从未标记数据中提取抽象UI嵌入的新框架，并结合微调的LLM解码器进行用户意图预测。我们还推出了两个新的多模态数据集——“Intent in the Wild”（IIW）和“Intent in the Tame”（IIT），分别包含219个意图类别的1.7K个视频和10个类别的914个视频，用于少样本和零样本UI理解任务。实验表明，UI-JEPA结合JEPA风格的目标和LLM解码器，在用户意图预测上可媲美最先进的MLLMs，同时大幅减少注释和部署资源。在意图相似性评分上，UI-JEPA分别比GPT-4 Turbo和Claude 3.5 Sonnet高出10.0%和7.2%。尤其在IIW数据集上，UI-JEPA实现了50.5倍的计算成本降低和6.6倍的延迟提升。这些成果彰显了UI-JEPA在轻量级、高性能UI理解中的巨大潜力。

> Generating user intent from a sequence of user interface (UI) actions is a core challenge in comprehensive UI understanding. Recent advancements in multimodal large language models (MLLMs) have led to substantial progress in this area, but their demands for extensive model parameters, computing power, and high latency makes them impractical for scenarios requiring lightweight, on-device solutions with low latency or heightened privacy. Additionally, the lack of high-quality datasets has hindered the development of such lightweight models. To address these challenges, we propose UI-JEPA, a novel framework that employs masking strategies to learn abstract UI embeddings from unlabeled data through self-supervised learning, combined with an LLM decoder fine-tuned for user intent prediction. We also introduce two new UI-grounded multimodal datasets, "Intent in the Wild" (IIW) and "Intent in the Tame" (IIT), designed for few-shot and zero-shot UI understanding tasks. IIW consists of 1.7K videos across 219 intent categories, while IIT contains 914 videos across 10 categories. We establish the first baselines for these datasets, showing that representations learned using a JEPA-style objective, combined with an LLM decoder, can achieve user intent predictions that match the performance of state-of-the-art large MLLMs, but with significantly reduced annotation and deployment resources. Measured by intent similarity scores, UI-JEPA outperforms GPT-4 Turbo and Claude 3.5 Sonnet by 10.0% and 7.2% respectively, averaged across two datasets. Notably, UI-JEPA accomplishes the performance with a 50.5x reduction in computational cost and a 6.6x improvement in latency in the IIW dataset. These results underscore the effectiveness of UI-JEPA, highlighting its potential for lightweight, high-performance UI understanding.

[Arxiv](https://arxiv.org/abs/2409.04081)