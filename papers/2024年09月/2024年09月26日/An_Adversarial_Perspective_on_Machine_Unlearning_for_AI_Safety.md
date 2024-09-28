# 从对抗视角探讨机器遗忘在 AI 安全中的应用

发布时间：2024年09月26日

`LLM理论` `网络安全` `人工智能安全`

> An Adversarial Perspective on Machine Unlearning for AI Safety

# 摘要

> 大型语言模型虽经微调以拒绝危险知识提问，但其保护措施常被绕过。遗忘方法旨在彻底移除危险能力，使其无法被对手利用。本研究从对抗视角探讨遗忘与传统安全后训练的根本差异。我们发现，先前被认为对遗忘无效的越狱方法，若谨慎应用，仍可成功。此外，我们开发了多种自适应方法，恢复了大多数被认为已遗忘的能力。例如，通过在10个不相关示例上微调或在激活空间中移除特定方向，可恢复使用RMU编辑的模型的大多数危险能力。这些发现挑战了当前遗忘方法的鲁棒性，并对其在安全训练上的优势提出质疑。

> Large language models are finetuned to refuse questions about hazardous knowledge, but these protections can often be bypassed. Unlearning methods aim at completely removing hazardous capabilities from models and make them inaccessible to adversaries. This work challenges the fundamental differences between unlearning and traditional safety post-training from an adversarial perspective. We demonstrate that existing jailbreak methods, previously reported as ineffective against unlearning, can be successful when applied carefully. Furthermore, we develop a variety of adaptive methods that recover most supposedly unlearned capabilities. For instance, we show that finetuning on 10 unrelated examples or removing specific directions in the activation space can recover most hazardous capabilities for models edited with RMU, a state-of-the-art unlearning method. Our findings challenge the robustness of current unlearning approaches and question their advantages over safety training.

[Arxiv](https://arxiv.org/abs/2409.18025)