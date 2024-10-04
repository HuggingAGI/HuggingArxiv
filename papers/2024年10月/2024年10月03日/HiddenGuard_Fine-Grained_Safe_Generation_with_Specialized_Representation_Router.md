# HiddenGuard：细粒度安全生成与专用表示路由器

发布时间：2024年10月03日

`LLM应用` `人工智能` `网络安全`

> HiddenGuard: Fine-Grained Safe Generation with Specialized Representation Router

# 摘要

> 随着大型语言模型 (LLM) 的日益强大，确保其安全并与人类价值观一致仍是一大挑战。理想情况下，LLM 应提供有价值的信息，同时避免泄露有害或敏感内容。然而，当前的对齐方法过于依赖拒绝策略，如完全拒绝有害提示或粗略过滤，这导致要么过度谨慎，要么无法识别细微的有害信息。例如，LLM 可能因担忧误用而拒绝提供基本的药物信息。此外，这些方法难以应对混合内容，且无法灵活适应上下文的敏感性，导致对良性内容的过度审查。为解决这些问题，我们推出了 HiddenGuard，一个细粒度安全生成的新框架。HiddenGuard 结合了 Prism，通过实时、令牌级检测和修订有害内容，实现更精细、上下文感知的调节。这使得模型既能生成有价值的信息，又能有选择地处理敏感内容，而非简单拒绝。我们还提供了一个包含细粒度注释的综合数据集。实验显示，HiddenGuard 在检测和修订有害内容方面表现优异，F1 分数超过 90%，同时保持了响应的效用和信息量。

> As Large Language Models (LLMs) grow increasingly powerful, ensuring their safety and alignment with human values remains a critical challenge. Ideally, LLMs should provide informative responses while avoiding the disclosure of harmful or sensitive information. However, current alignment approaches, which rely heavily on refusal strategies, such as training models to completely reject harmful prompts or applying coarse filters are limited by their binary nature. These methods either fully deny access to information or grant it without sufficient nuance, leading to overly cautious responses or failures to detect subtle harmful content. For example, LLMs may refuse to provide basic, public information about medication due to misuse concerns. Moreover, these refusal-based methods struggle to handle mixed-content scenarios and lack the ability to adapt to context-dependent sensitivities, which can result in over-censorship of benign content. To overcome these challenges, we introduce HiddenGuard, a novel framework for fine-grained, safe generation in LLMs. HiddenGuard incorporates Prism (rePresentation Router for In-Stream Moderation), which operates alongside the LLM to enable real-time, token-level detection and redaction of harmful content by leveraging intermediate hidden states. This fine-grained approach allows for more nuanced, context-aware moderation, enabling the model to generate informative responses while selectively redacting or replacing sensitive information, rather than outright refusal. We also contribute a comprehensive dataset with token-level fine-grained annotations of potentially harmful information across diverse contexts. Our experiments demonstrate that HiddenGuard achieves over 90% in F1 score for detecting and redacting harmful content while preserving the overall utility and informativeness of the model's responses.

[Arxiv](https://arxiv.org/abs/2410.02684)