# 思维链推理遭遇预先回答“攻击”挑战

发布时间：2024年05月31日

`LLM应用

这篇论文主要探讨了大型语言模型（LLM）在与思维链提示结合使用时的推理能力，特别是在预先回答情况下的稳定性和鲁棒性问题。论文通过实验分析了预先回答对模型推理能力的影响，并提出了相应的策略来增强模型的鲁棒性。这属于对LLM在特定应用场景下的性能和安全性的研究，因此归类为LLM应用。` `人工智能`

> Preemptive Answer "Attacks" on Chain-of-Thought Reasoning

# 摘要

> 当与思维链提示相结合时，大型语言模型展现出卓越的推理能力。但这种方法的稳定性仍需深入探究。本文提出了一种新情况——预先回答，即模型在推理前就给出答案，这可能无意或被恶意用户通过提示注入攻击引发。实验发现，预先回答严重削弱了模型在多种CoT方法和广泛数据集上的推理能力。为此，我们提出了两项策略，以期在一定程度上增强推理的鲁棒性。

> Large language models (LLMs) showcase impressive reasoning capabilities when coupled with Chain-of-Thought (CoT) prompting. However, the robustness of this approach warrants further investigation. In this paper, we introduce a novel scenario termed preemptive answers, where the LLM obtains an answer before engaging in reasoning. This situation can arise inadvertently or induced by malicious users by prompt injection attacks. Experiments reveal that preemptive answers significantly impair the model's reasoning capability across various CoT methods and a broad spectrum of datasets. To bolster the robustness of reasoning, we propose two measures aimed at mitigating this issue to some extent.

![思维链推理遭遇预先回答“攻击”挑战](../../../paper_images/2405.20902/x1.png)

![思维链推理遭遇预先回答“攻击”挑战](../../../paper_images/2405.20902/example.png)

![思维链推理遭遇预先回答“攻击”挑战](../../../paper_images/2405.20902/x2.png)

![思维链推理遭遇预先回答“攻击”挑战](../../../paper_images/2405.20902/x3.png)

[Arxiv](https://arxiv.org/abs/2405.20902)