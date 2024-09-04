# 针对 In-Context Learning 的成员推理攻击研究

发布时间：2024年09月02日

`LLM应用` `网络安全` `隐私保护`

> Membership Inference Attacks Against In-Context Learning

# 摘要

> 将 LLM 适应特定任务时，计算效率成为关注焦点，推动了对 ICL 等高效方法的研究。然而，ICL 在现实条件下的隐私攻击风险尚未充分探讨。本研究首次针对 ICL 提出成员推理攻击，仅依赖生成文本，无需相关概率。我们设计了四种适应不同限制条件的攻击策略，并在四个主流 LLM 上进行了详尽实验。实验表明，我们的攻击在多数情况下能精准识别成员身份，如对 LLaMA 的准确率高达 95%，风险远超基于概率的传统攻击。我们还创新了一种混合攻击，整合各策略优势，准确率同样超过 95%。同时，我们探索了三种防御策略，发现多维度防御结合能大幅降低隐私泄露风险，强化隐私保护。

> Adapting Large Language Models (LLMs) to specific tasks introduces concerns about computational efficiency, prompting an exploration of efficient methods such as In-Context Learning (ICL). However, the vulnerability of ICL to privacy attacks under realistic assumptions remains largely unexplored. In this work, we present the first membership inference attack tailored for ICL, relying solely on generated texts without their associated probabilities. We propose four attack strategies tailored to various constrained scenarios and conduct extensive experiments on four popular large language models. Empirical results show that our attacks can accurately determine membership status in most cases, e.g., 95\% accuracy advantage against LLaMA, indicating that the associated risks are much higher than those shown by existing probability-based attacks. Additionally, we propose a hybrid attack that synthesizes the strengths of the aforementioned strategies, achieving an accuracy advantage of over 95\% in most cases. Furthermore, we investigate three potential defenses targeting data, instruction, and output. Results demonstrate combining defenses from orthogonal dimensions significantly reduces privacy leakage and offers enhanced privacy assurances.

[Arxiv](https://arxiv.org/abs/2409.01380)