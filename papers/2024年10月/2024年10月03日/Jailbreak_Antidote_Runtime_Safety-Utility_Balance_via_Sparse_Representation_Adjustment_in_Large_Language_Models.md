# 越狱防护：在大语言模型中通过稀疏表示调整，实现运行时安全与实用性的平衡

发布时间：2024年10月03日

`LLM应用` `人工智能` `网络安全`

> Jailbreak Antidote: Runtime Safety-Utility Balance via Sparse Representation Adjustment in Large Language Models

# 摘要

> 随着大型语言模型 (LLM) 在各领域的广泛应用，确保其安全性和实用性成为关键。然而，越狱攻击通过操纵 LLM 生成有害内容，对这一平衡构成挑战。现有防御措施如提示工程和安全微调，虽有效但常带来计算负担和灵活性不足。为此，我们提出 Jailbreak Antidote，一种通过微调模型内部状态稀疏子集来实时调整安全偏好的方法。该方法在不增加推理负担的前提下，灵活控制安全与实用性的平衡。实验证明，仅需调整约 5% 的内部状态即可达到显著效果。在九个不同规模的 LLM 上，对比十种攻击方法和六种防御策略，Jailbreak Antidote 展现了卓越的有效性和效率。这一创新方案不仅提升了 LLM 的安全性，还保持了其实用性，为 AI 系统的实时安全机制开辟了新路径。

> As large language models (LLMs) become integral to various applications, ensuring both their safety and utility is paramount. Jailbreak attacks, which manipulate LLMs into generating harmful content, pose significant challenges to this balance. Existing defenses, such as prompt engineering and safety fine-tuning, often introduce computational overhead, increase inference latency, and lack runtime flexibility. Moreover, overly restrictive safety measures can degrade model utility by causing refusals of benign queries. In this paper, we introduce Jailbreak Antidote, a method that enables real-time adjustment of LLM safety preferences by manipulating a sparse subset of the model's internal states during inference. By shifting the model's hidden representations along a safety direction with varying strengths, we achieve flexible control over the safety-utility balance without additional token overhead or inference delays. Our analysis reveals that safety-related information in LLMs is sparsely distributed; adjusting approximately 5% of the internal state is as effective as modifying the entire state. Extensive experiments on nine LLMs (ranging from 2 billion to 72 billion parameters), evaluated against ten jailbreak attack methods and compared with six defense strategies, validate the effectiveness and efficiency of our approach. By directly manipulating internal states during reasoning, Jailbreak Antidote offers a lightweight, scalable solution that enhances LLM safety while preserving utility, opening new possibilities for real-time safety mechanisms in widely-deployed AI systems.

[Arxiv](https://arxiv.org/abs/2410.02298)