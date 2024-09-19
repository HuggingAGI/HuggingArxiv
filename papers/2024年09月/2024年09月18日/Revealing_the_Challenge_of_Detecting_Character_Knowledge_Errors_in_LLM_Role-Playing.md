# 揭示 LLM 角色扮演中检测角色知识错误的难题

发布时间：2024年09月18日

`LLM应用` `人工智能` `游戏开发`

> Revealing the Challenge of Detecting Character Knowledge Errors in LLM Role-Playing

# 摘要

> 大型语言模型 (LLM) 的角色扮演备受瞩目，但现有研究往往忽略了 LLM 在角色扮演中检测已知和未知知识错误的能力，这影响了角色语料库的质量。本文提出了一种探测数据集，评估 LLM 对这两种错误的检测能力。结果显示，即使是先进的 LLM 也难以有效识别这些错误，尤其是在熟悉知识方面。我们尝试了多种推理策略，并提出了基于代理的自我回忆与自我怀疑 (S2RD) 方法，以提升错误检测能力。实验证明，该方法有效，但仍需持续关注。

> Large language model (LLM) role-playing has gained widespread attention, where the authentic character knowledge is crucial for constructing realistic LLM role-playing agents. However, existing works usually overlook the exploration of LLMs' ability to detect characters' known knowledge errors (KKE) and unknown knowledge errors (UKE) while playing roles, which would lead to low-quality automatic construction of character trainable corpus. In this paper, we propose a probing dataset to evaluate LLMs' ability to detect errors in KKE and UKE. The results indicate that even the latest LLMs struggle to effectively detect these two types of errors, especially when it comes to familiar knowledge. We experimented with various reasoning strategies and propose an agent-based reasoning method, Self-Recollection and Self-Doubt (S2RD), to further explore the potential for improving error detection capabilities. Experiments show that our method effectively improves the LLMs' ability to detect error character knowledge, but it remains an issue that requires ongoing attention.

[Arxiv](https://arxiv.org/abs/2409.11726)