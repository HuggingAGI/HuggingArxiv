# 探究大型语言模型多代理在ICD编码中的应用

发布时间：2024年04月01日

`Agent

这篇论文提出了一种创新的多代理ICD编码方法，该方法模拟了真实编码流程中的复杂互动，包括患者、医生、编码员、审查员和调整员五个代理，每个代理都基于大型语言模型（LLM）。这种方法在ICD编码任务中表现出色，特别是在处理常见和罕见代码时，其性能优于零样本思维链提示和自我一致性方法。此外，该方法在编码准确性、罕见代码准确性和可解释性方面与需要预训练或微调的顶尖ICD编码方法相当。因此，这篇论文应归类为Agent，因为它主要关注的是通过多个代理来改进ICD编码任务的执行。` `编码系统`

> Exploring LLM Multi-Agents for ICD Coding

# 摘要

> 大型语言模型（LLMs）在多个领域展现出卓越能力，如无需特定领域训练即可从临床文本中提取信息。但在ICD编码任务中，LLMs因ICD代码的高维偏斜特性，常虚构关键信息，导致高召回低精确的结果。现有方法未能考虑患者、医生和编码员等人类代理间的复杂互动，且缺乏透明度和可靠性。本文提出一种创新的多代理ICD编码方法，模拟真实编码流程，包含患者、医生、编码员、审查员和调整员五个代理，各司其职，均基于LLM模型。在MIMIC-III数据集上的测试表明，该框架在常见与罕见代码上的表现均优于零样本思维链提示和自我一致性方法。消融研究证实了各代理角色的有效性。此外，我们的方法在编码准确性、罕见代码准确性和可解释性方面，与需要预训练或微调的顶尖ICD编码方法不相上下。

> Large Language Models (LLMs) have demonstrated impressive and diverse abilities that can benefit various domains, such as zero and few-shot information extraction from clinical text without domain-specific training. However, for the ICD coding task, they often hallucinate key details and produce high recall but low precision results due to the high-dimensional and skewed distribution of the ICD codes. Existing LLM-based methods fail to account for the complex and dynamic interactions among the human agents involved in coding, such as patients, physicians, and coders, and they lack interpretability and reliability. In this paper, we present a novel multi-agent method for ICD coding, which mimics the real-world coding process with five agents: a patient agent, a physician agent, a coder agent, a reviewer agent, and an adjuster agent. Each agent has a specific function and uses a LLM-based model to perform it. We evaluate our method on the MIMIC-III dataset and show that our proposed multi-agent coding framework substantially improves performance on both common and rare codes compared to Zero-shot Chain of Thought (CoT) prompting and self-consistency with CoT. The ablation study confirms the proposed agent roles' efficacy. Our method also matches the state-of-the-art ICD coding methods that require pre-training or fine-tuning, in terms of coding accuracy, rare code accuracy, and explainability.

[Arxiv](https://arxiv.org/abs/2406.15363)