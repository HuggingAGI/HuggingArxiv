# 通过拒绝功能对抗训练，实现 LLM 的稳健保护

发布时间：2024年09月30日

`LLM理论` `网络安全` `人工智能`

> Robust LLM safeguarding via refusal feature adversarial training

# 摘要

> 大型语言模型 (LLM) 容易受到引发有害响应的对抗攻击。由于越狱机制的不透明性和高计算成本，防御这些攻击仍具挑战。我们发现，对抗攻击通过消除残差流嵌入空间中的“拒绝特征”来绕过 LLM 的安全措施。基于此，我们提出了拒绝特征对抗训练 (ReFAT)，通过模拟输入级攻击的 RFA 效应，高效提升 LLM 的鲁棒性。实验表明，ReFAT 显著增强了三种流行 LLM 对多种对抗攻击的防御能力，且计算成本大幅降低。

> Large language models (LLMs) are vulnerable to adversarial attacks that can elicit harmful responses. Defending against such attacks remains challenging due to the opacity of jailbreaking mechanisms and the high computational cost of training LLMs robustly. We demonstrate that adversarial attacks share a universal mechanism for circumventing LLM safeguards that works by ablating a dimension in the residual stream embedding space called the refusal feature. We further show that the operation of refusal feature ablation (RFA) approximates the worst-case perturbation of offsetting model safety. Based on these findings, we propose Refusal Feature Adversarial Training (ReFAT), a novel algorithm that efficiently performs LLM adversarial training by simulating the effect of input-level attacks via RFA. Experiment results show that ReFAT significantly improves the robustness of three popular LLMs against a wide range of adversarial attacks, with considerably less computational overhead compared to existing adversarial training methods.

[Arxiv](https://arxiv.org/abs/2409.20089)