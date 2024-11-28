# 针对自动驾驶中视觉语言模型的视觉对抗攻击

发布时间：2024年11月27日

`LLM应用` `自动驾驶` `视觉语言模型`

> Visual Adversarial Attack on Vision-Language Models for Autonomous Driving

# 摘要

> 视觉语言模型（VLMs）凭借增强推理能力，极大地推动了自动驾驶（AD）的进步。但这些模型在对抗性攻击面前仍十分脆弱。现有的研究多聚焦于一般性的 VLM 攻击，而针对 AD 这一安全关键场景定制的攻击开发却被严重忽视。本文中，我们率先着手设计针对 AD 中 VLMs 的对抗性攻击，揭示了此类攻击在这一关键领域所构成的重大风险。我们明确了针对 AD VLMs 进行有效对抗性攻击的两大独特挑战：文本指令的多变性以及视觉场景的时间序列特性。为此，我们提出了 ADvLM，这是首个专为 AD 中的 VLMs 打造的视觉对抗攻击框架。我们的框架引入了语义不变诱导，它借助大型语言模型，并在语义熵的引导下，创建出语义内容一致的多样化文本指令提示库。在此基础上，我们推出了场景关联增强，即通过注意力机制在驾驶场景中选取关键帧和视角，以优化能在整个场景通用的对抗性扰动。在多个基准上针对若干 AD VLMs 开展的大量实验表明，ADvLM 达到了顶尖的攻击效果。而且，现实世界中的攻击研究进一步证实了其在实际应用中的适用性和潜力。

> Vision-language models (VLMs) have significantly advanced autonomous driving (AD) by enhancing reasoning capabilities. However, these models remain highly vulnerable to adversarial attacks. While existing research has primarily focused on general VLM attacks, the development of attacks tailored to the safety-critical AD context has been largely overlooked. In this paper, we take the first step toward designing adversarial attacks specifically targeting VLMs in AD, exposing the substantial risks these attacks pose within this critical domain. We identify two unique challenges for effective adversarial attacks on AD VLMs: the variability of textual instructions and the time-series nature of visual scenarios. To this end, we propose ADvLM, the first visual adversarial attack framework specifically designed for VLMs in AD. Our framework introduces Semantic-Invariant Induction, which uses a large language model to create a diverse prompt library of textual instructions with consistent semantic content, guided by semantic entropy. Building on this, we introduce Scenario-Associated Enhancement, an approach where attention mechanisms select key frames and perspectives within driving scenarios to optimize adversarial perturbations that generalize across the entire scenario. Extensive experiments on several AD VLMs over multiple benchmarks show that ADvLM achieves state-of-the-art attack effectiveness. Moreover, real-world attack studies further validate its applicability and potential in practice.

[Arxiv](https://arxiv.org/abs/2411.18275)