# 视觉融合攻击：提升神经机器翻译中对抗性文本的激进性与隐秘性

发布时间：2024年09月08日

`LLM应用` `网络安全` `人工智能`

> Vision-fused Attack: Advancing Aggressive and Stealthy Adversarial Text against Neural Machine Translation

# 摘要

> 尽管 NMT 模型在日常生活中表现出色，但它们易受对抗性攻击。这些攻击虽有害，却有助于理解和提升 NMT 模型，因此备受研究关注。然而，现有研究在攻击能力和人类感知方面存在不足，仅关注语言层面。本文提出视觉融合攻击 (VFA) 框架，旨在生成更具侵略性和隐蔽性的对抗性文本。通过视觉合并解决方案空间增强策略，我们扩大了语义空间，提升了攻击能力。同时，感知保留的对抗性文本选择策略确保了文本的不可感知性，使其更具欺骗性。实验证明，VFA 在 ASR 和 SSIM 上分别提升了 81% 和 14%，显著优于现有方法。

> While neural machine translation (NMT) models achieve success in our daily lives, they show vulnerability to adversarial attacks. Despite being harmful, these attacks also offer benefits for interpreting and enhancing NMT models, thus drawing increased research attention. However, existing studies on adversarial attacks are insufficient in both attacking ability and human imperceptibility due to their sole focus on the scope of language. This paper proposes a novel vision-fused attack (VFA) framework to acquire powerful adversarial text, i.e., more aggressive and stealthy. Regarding the attacking ability, we design the vision-merged solution space enhancement strategy to enlarge the limited semantic solution space, which enables us to search for adversarial candidates with higher attacking ability. For human imperceptibility, we propose the perception-retained adversarial text selection strategy to align the human text-reading mechanism. Thus, the finally selected adversarial text could be more deceptive. Extensive experiments on various models, including large language models (LLMs) like LLaMA and GPT-3.5, strongly support that VFA outperforms the comparisons by large margins (up to 81%/14% improvements on ASR/SSIM).

[Arxiv](https://arxiv.org/abs/2409.05021)