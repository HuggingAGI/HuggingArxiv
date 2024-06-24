# ArgMed-Agents：借助论证方案，实现大型语言模型在临床决策推理中的可解释性讨论

发布时间：2024年06月20日

`Agent

理由：这篇论文介绍了一个名为ArgMed-Agents的框架，该框架专门设计用于通过交互让大型语言模型（LLMs）代理进行可解释的临床决策推理。这个框架的核心在于创建一个能够进行复杂推理和规划的Agent，并且能够提供决策的透明度和解释性。这与Agent的定义相符，即一个能够自主行动并作出决策的实体，特别是在复杂环境和任务中。因此，这篇论文应归类于Agent。` `临床决策`

> ArgMed-Agents: Explainable Clinical Decision Reasoning with LLM Disscusion via Argumentation Schemes

# 摘要

> 在临床推理中应用大型语言模型（LLMs）面临两大挑战：一是尽管LLMs在NLP任务中表现出色，但在复杂推理和规划上仍显不足；二是LLMs的决策方法缺乏透明度，与临床医生的思维方式大相径庭，引发用户疑虑。为此，我们开发了ArgMed-Agents框架，通过交互让LLM代理进行可解释的临床决策推理。该框架利用临床讨论论证方案进行自我迭代论证，将论证过程可视化为冲突关系图，并借助符号求解器找出支持决策的合理论证。我们建立了ArgMed-Agents的正式模型，并提出了理论保证的猜想。实验证明，ArgMed-Agents不仅提升了复杂临床决策的准确性，更通过提供决策解释增强了用户的信心。

> There are two main barriers to using large language models (LLMs) in clinical reasoning. Firstly, while LLMs exhibit significant promise in Natural Language Processing (NLP) tasks, their performance in complex reasoning and planning falls short of expectations. Secondly, LLMs use uninterpretable methods to make clinical decisions that are fundamentally different from the clinician's cognitive processes. This leads to user distrust. In this paper, we present a multi-agent framework called ArgMed-Agents, which aims to enable LLM-based agents to make explainable clinical decision reasoning through interaction. ArgMed-Agents performs self-argumentation iterations via Argumentation Scheme for Clinical Discussion (a reasoning mechanism for modeling cognitive processes in clinical reasoning), and then constructs the argumentation process as a directed graph representing conflicting relationships. Ultimately, use symbolic solver to identify a series of rational and coherent arguments to support decision. We construct a formal model of ArgMed-Agents and present conjectures for theoretical guarantees. ArgMed-Agents enables LLMs to mimic the process of clinical argumentative reasoning by generating explanations of reasoning in a self-directed manner. The setup experiments show that ArgMed-Agents not only improves accuracy in complex clinical decision reasoning problems compared to other prompt methods, but more importantly, it provides users with decision explanations that increase their confidence.

![ArgMed-Agents：借助论证方案，实现大型语言模型在临床决策推理中的可解释性讨论](../../../paper_images/2403.06294/x1.png)

![ArgMed-Agents：借助论证方案，实现大型语言模型在临床决策推理中的可解释性讨论](../../../paper_images/2403.06294/x2.png)

![ArgMed-Agents：借助论证方案，实现大型语言模型在临床决策推理中的可解释性讨论](../../../paper_images/2403.06294/x3.png)

![ArgMed-Agents：借助论证方案，实现大型语言模型在临床决策推理中的可解释性讨论](../../../paper_images/2403.06294/x4.png)

![ArgMed-Agents：借助论证方案，实现大型语言模型在临床决策推理中的可解释性讨论](../../../paper_images/2403.06294/x5.png)

[Arxiv](https://arxiv.org/abs/2403.06294)