# FoRAG：优化事实性的检索增强生成技术，专为网络增强的长篇问答设计
发布时间：2024年06月19日

`RAG`
> FoRAG: Factuality-optimized Retrieval Augmented Generation for Web-enhanced Long-form Question Answering
>
> Retrieval Augmented Generation (RAG) 因其利用搜索引擎提升长篇问答（LFQA）质量的能力而在 QA 任务中广受欢迎。尽管有多种开源方法和网络增强的商业系统如 Bing Chat 出现，但生成长篇答案的事实性和逻辑清晰度两大难题仍未解决。本文通过系统研究网络增强的 LFQA 中的答案生成来应对这些挑战。我们首先提出了一种提纲增强的生成器，确保多方面答案生成逻辑清晰，并为此建立了两个数据集。接着，我们开发了一种基于双重细粒度 RLHF 框架的事实性优化方法，该框架在不同粒度级别上进行自动评估和奖励建模。我们的方法不仅包含了传统的细粒度 RLHF 方法，还通过广泛实验证明了其优越性，尤其是在英语和中文基准测试中。特别地，应用我们的方法于 Llama2-7B-chat 后，得到的 FoRAG-L-7B 模型在连贯性、有用性和事实性三个指标上超越了 WebGPT-175B，且参数数量仅为后者的 1/24。我们的数据集和模型已公开，以促进研究的可复现性：https://huggingface.co/forag。
>
> https://arxiv.org/abs/2406.13779

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13779/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13779/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.13779](https://arxiv.org/abs/2406.13779)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2