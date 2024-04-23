# 通过信息瓶颈策略，为您的大型语言模型筑起防线。

发布时间：2024年04月22日

`LLM应用` `信息安全`

> Protecting Your LLMs with Information Bottleneck

# 摘要

> 大型语言模型（LLMs）的兴起为自然语言处理领域带来了革命性的变化，但它们也可能被利用生成有害内容。尽管人们试图让LLMs遵循道德规范，但这些模型往往脆弱，容易受到精心设计的对抗性提示的越狱攻击。为此，我们提出了信息瓶颈保护器（IBProtector），这是一种基于信息瓶颈原理的防御机制，我们调整了目标以避免简单化的解决方案。IBProtector通过一个轻量级且可训练的提取器，有选择地压缩和扰动提示，确保只保留对目标LLMs至关重要的信息，以便它们能够给出预期的回答。此外，我们还考虑了在梯度不可见的情况下的兼容性，以适应任何LLM。我们的实证评估显示，IBProtector在抵御越狱尝试方面超越了现有的防御方法，同时不会对回答质量或推理速度造成太大影响。IBProtector在多种攻击手段和目标LLMs上的有效性和适应性，突显了其作为一种新型、可移植防御措施的潜力，它能够在不改变底层模型的情况下，增强LLMs的安全性。

> The advent of large language models (LLMs) has revolutionized the field of natural language processing, yet they might be attacked to produce harmful content. Despite efforts to ethically align LLMs, these are often fragile and can be circumvented by jailbreaking attacks through optimized or manual adversarial prompts. To address this, we introduce the Information Bottleneck Protector (IBProtector), a defense mechanism grounded in the information bottleneck principle, and we modify the objective to avoid trivial solutions. The IBProtector selectively compresses and perturbs prompts, facilitated by a lightweight and trainable extractor, preserving only essential information for the target LLMs to respond with the expected answer. Moreover, we further consider a situation where the gradient is not visible to be compatible with any LLM. Our empirical evaluations show that IBProtector outperforms current defense methods in mitigating jailbreak attempts, without overly affecting response quality or inference speed. Its effectiveness and adaptability across various attack methods and target LLMs underscore the potential of IBProtector as a novel, transferable defense that bolsters the security of LLMs without requiring modifications to the underlying models.

[Arxiv](https://arxiv.org/abs/2404.13968)