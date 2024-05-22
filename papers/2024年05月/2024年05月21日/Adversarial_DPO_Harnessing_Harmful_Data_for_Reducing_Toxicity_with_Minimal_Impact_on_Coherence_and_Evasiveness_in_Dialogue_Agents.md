# 对抗性DPO策略：巧妙利用有害数据，以最小化对对话代理连贯性和逃避性的影响，有效降低其毒性。

发布时间：2024年05月21日

`LLM应用

这篇论文摘要讨论了一种新型的训练算法——对抗性直接偏好优化（ADPO），用于改进大型语言模型（LLMs）在开放域对话系统中的表现，特别是在减少模型生成有害内容的能力方面。这种算法的提出是为了解决模型中毒性问题，提高用户体验。ADPO通过直接优化模型的偏好，使其更倾向于生成安全的响应，同时抑制有害内容的生成。这与LLM的应用紧密相关，因为它直接涉及到如何使用和优化LLM以改善其在实际应用中的表现，尤其是在对话系统这一特定领域。因此，这篇论文应归类于LLM应用。` `对话系统` `人工智能安全`

> Adversarial DPO: Harnessing Harmful Data for Reducing Toxicity with Minimal Impact on Coherence and Evasiveness in Dialogue Agents

# 摘要

> 开放域对话系统因高质量大型语言模型（LLMs）及多种高效训练方法的兴起而取得显著进展。但模型中的毒性问题成为一大障碍，可能损害用户体验。本研究提出了一种新型训练算法——对抗性直接偏好优化（ADPO），作为直接偏好优化（DPO）的升级版。ADPO旨在训练模型，使其更倾向于生成安全响应，同时抑制由毒性控制令牌生成的有害内容。实验表明，ADPO不仅提升了模型对有害对话的抵御力，还保持了性能稳定。与传统DPO相比，ADPO的训练过程更为稳健。这是首次尝试将有害数据直接融入生成模型的DPO算法，有效减少了对人工构建安全对话数据的依赖。

> Recent advancements in open-domain dialogue systems have been propelled by the emergence of high-quality large language models (LLMs) and various effective training methodologies. Nevertheless, the presence of toxicity within these models presents a significant challenge that can potentially diminish the user experience. In this study, we introduce an innovative training algorithm, an improvement upon direct preference optimization (DPO), called adversarial DPO (ADPO). The ADPO algorithm is designed to train models to assign higher probability distributions to preferred responses and lower distributions to unsafe responses, which are self-generated using the toxic control token. We demonstrate that ADPO enhances the model's resilience against harmful conversations while minimizing performance degradation. Furthermore, we illustrate that ADPO offers a more stable training procedure compared to the traditional DPO. To the best of our knowledge, this is the first adaptation of the DPO algorithm that directly incorporates harmful data into the generative model, thereby reducing the need to artificially create safe dialogue data.

[Arxiv](https://arxiv.org/abs/2405.12900)