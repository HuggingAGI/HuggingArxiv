# 无需提示的思维链推理

发布时间：2024年05月23日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在推理能力方面的内在机制，特别是通过调整解码过程来实现思维链推理，而不依赖于传统的提示技术。这种研究深入分析了LLMs的内部工作原理，特别是推理能力的激发和评估，属于对LLM理论的深入探讨。因此，将其归类为LLM理论。` `人工智能`

> Chain-of-Thought Reasoning Without Prompting

# 摘要

> 在提升大型语言模型推理能力方面，传统方法依赖于特定的提示技术，如少样本或零样本的思维链提示，这些方法虽有效但需大量人工干预。我们的研究另辟蹊径，探索了LLMs是否能在无提示的情况下进行有效推理。研究发现，通过调整解码过程，预训练的LLMs能够自发产生思维链推理路径，而非依赖传统的贪婪解码。我们采用前k个替代令牌的方法，揭示了这些路径中CoT的固有性，从而绕过了提示的复杂性，并评估了LLMs的内在推理能力。此外，解码路径中的CoT与模型答案的置信度提升相关，有效区分了CoT与非CoT路径。在多个推理基准上的实验证实，这种CoT解码方法能有效激发语言模型的推理潜能，而这些潜能以往被标准解码方法所掩盖。

> In enhancing the reasoning capabilities of large language models (LLMs), prior research primarily focuses on specific prompting techniques such as few-shot or zero-shot chain-of-thought (CoT) prompting. These methods, while effective, often involve manually intensive prompt engineering. Our study takes a novel approach by asking: Can LLMs reason effectively without prompting? Our findings reveal that, intriguingly, CoT reasoning paths can be elicited from pre-trained LLMs by simply altering the \textit{decoding} process. Rather than conventional greedy decoding, we investigate the top-$k$ alternative tokens, uncovering that CoT paths are frequently inherent in these sequences. This approach not only bypasses the confounders of prompting but also allows us to assess the LLMs' \textit{intrinsic} reasoning abilities. Moreover, we observe that the presence of a CoT in the decoding path correlates with a higher confidence in the model's decoded answer. This confidence metric effectively differentiates between CoT and non-CoT paths. Extensive empirical studies on various reasoning benchmarks show that the proposed CoT-decoding effectively elicits reasoning capabilities from language models, which were previously obscured by standard greedy decoding.

[Arxiv](https://arxiv.org/abs/2402.10200)