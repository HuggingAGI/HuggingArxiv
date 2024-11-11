# 迈向使用 LMM 代理进行低资源有害模因检测

发布时间：2024年11月08日

`Agent` `社交媒体` `多模态检测`

> Towards Low-Resource Harmful Meme Detection with LMM Agents

# 摘要

> 在社交媒体时代，网络梗图的大量涌现需要对有害的梗图进行有效识别。由于梗图的动态性质，现有的数据驱动模型在只有少数有标签示例可用的低资源场景中可能会遇到困难。在本文中，我们提出了一个用于低资源有害梗图检测的代理驱动框架，使用少量带注释的样本进行外向和内向分析。受大型多模态模型（LMMs）在多模态推理方面强大能力的启发，我们首先检索带有注释的相关梗图，以利用标签信息作为 LMM 代理的辅助信号。然后，我们在 LMM 代理中引发知识修订行为，以得出对梗图有害性的普遍见解。通过结合这些策略，我们的方法能够对复杂和隐含的有害指示模式进行辩证推理。在三个梗图数据集上进行的大量实验表明，我们提出的方法在低资源有害梗图检测任务上的性能优于最先进的方法。

> The proliferation of Internet memes in the age of social media necessitates effective identification of harmful ones. Due to the dynamic nature of memes, existing data-driven models may struggle in low-resource scenarios where only a few labeled examples are available. In this paper, we propose an agency-driven framework for low-resource harmful meme detection, employing both outward and inward analysis with few-shot annotated samples. Inspired by the powerful capacity of Large Multimodal Models (LMMs) on multimodal reasoning, we first retrieve relative memes with annotations to leverage label information as auxiliary signals for the LMM agent. Then, we elicit knowledge-revising behavior within the LMM agent to derive well-generalized insights into meme harmfulness. By combining these strategies, our approach enables dialectical reasoning over intricate and implicit harm-indicative patterns. Extensive experiments conducted on three meme datasets demonstrate that our proposed approach achieves superior performance than state-of-the-art methods on the low-resource harmful meme detection task.

[Arxiv](https://arxiv.org/abs/2411.05383)