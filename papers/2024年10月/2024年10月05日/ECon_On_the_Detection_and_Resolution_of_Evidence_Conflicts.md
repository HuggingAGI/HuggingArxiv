# ECon：探讨证据冲突的检测与解决之道

发布时间：2024年10月05日

`LLM应用` `决策系统` `信息管理`

> ECon: On the Detection and Resolution of Evidence Conflicts

# 摘要

> 随着大型语言模型（LLM）的崛起，决策系统中的信息质量受到显著影响，AI 生成内容泛滥，错误信息检测和管理“证据间冲突”成为难题。本研究提出了一种生成多样化、验证过的证据冲突的方法，模拟现实中的错误信息场景。我们评估了包括自然语言推理（NLI）、事实一致性（FC）和 LLM 在内的冲突检测方法（RQ1），并分析了 LLM 的冲突解决行为（RQ2）。研究发现：(1) NLI 和 LLM 在检测答案冲突时精度高，但弱模型召回率低；(2) FC 模型难以处理词汇相似的冲突，而 NLI 和 LLM 表现较好；(3) 如 GPT-4 等强模型在处理细微冲突时表现稳健。在冲突解决方面，LLM 常无充分理由地偏向某一证据，并在有先验信念时依赖内部知识。

> The rise of large language models (LLMs) has significantly influenced the quality of information in decision-making systems, leading to the prevalence of AI-generated content and challenges in detecting misinformation and managing conflicting information, or "inter-evidence conflicts." This study introduces a method for generating diverse, validated evidence conflicts to simulate real-world misinformation scenarios. We evaluate conflict detection methods, including Natural Language Inference (NLI) models, factual consistency (FC) models, and LLMs, on these conflicts (RQ1) and analyze LLMs' conflict resolution behaviors (RQ2). Our key findings include: (1) NLI and LLM models exhibit high precision in detecting answer conflicts, though weaker models suffer from low recall; (2) FC models struggle with lexically similar answer conflicts, while NLI and LLM models handle these better; and (3) stronger models like GPT-4 show robust performance, especially with nuanced conflicts. For conflict resolution, LLMs often favor one piece of conflicting evidence without justification and rely on internal knowledge if they have prior beliefs.

[Arxiv](https://arxiv.org/abs/2410.04068)