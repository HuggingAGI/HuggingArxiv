# 借助思维链来强化对抗性攻击

发布时间：2024年10月29日

`LLM应用` `语言模型` `网络安全`

> Enhancing Adversarial Attacks through Chain of Thought

# 摘要

> 大型语言模型（LLMs）在众多领域展现出了非凡的性能，然而在安全性方面仍存在隐患。以往研究显示，基于梯度的对抗性攻击对于对齐的 LLMs 效果显著，思维链（CoT）提示能够通过逐步推理获取理想答案。此文提议将 CoT 提示与贪婪坐标梯度（GCG）技术相融合，以增强对齐的 LLMs 对抗攻击的稳健性。采用 CoT 触发器而非肯定目标，能够激发后端 LLMs 的推理能力，进而提升对抗性攻击的可迁移性和通用性。我们开展了一项消融研究，对我们的 CoT-GCG 方法和亚马逊网络服务自动 CoT 进行对比。结果表明，我们的方法优于基线 GCG 攻击和 CoT 提示。另外，我们运用 Llama Guard 评估潜在的有害交互，相较于将输出与拒绝短语匹配，为整个对话提供了更客观的风险评估。本文的代码可在 https://github.com/sujingbo0217/CS222W24-LLM-Attack 获取。

> Large language models (LLMs) have demonstrated impressive performance across various domains but remain susceptible to safety concerns. Prior research indicates that gradient-based adversarial attacks are particularly effective against aligned LLMs and the chain of thought (CoT) prompting can elicit desired answers through step-by-step reasoning. This paper proposes enhancing the robustness of adversarial attacks on aligned LLMs by integrating CoT prompts with the greedy coordinate gradient (GCG) technique. Using CoT triggers instead of affirmative targets stimulates the reasoning abilities of backend LLMs, thereby improving the transferability and universality of adversarial attacks. We conducted an ablation study comparing our CoT-GCG approach with Amazon Web Services auto-cot. Results revealed our approach outperformed both the baseline GCG attack and CoT prompting. Additionally, we used Llama Guard to evaluate potentially harmful interactions, providing a more objective risk assessment of entire conversations compared to matching outputs to rejection phrases. The code of this paper is available at https://github.com/sujingbo0217/CS222W24-LLM-Attack.

[Arxiv](https://arxiv.org/abs/2410.21791)