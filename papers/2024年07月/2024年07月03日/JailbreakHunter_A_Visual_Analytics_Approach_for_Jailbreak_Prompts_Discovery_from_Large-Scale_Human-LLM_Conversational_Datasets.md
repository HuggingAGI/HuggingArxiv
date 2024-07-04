# JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。

发布时间：2024年07月03日

`LLM应用` `网络安全` `人工智能`

> JailbreakHunter: A Visual Analytics Approach for Jailbreak Prompts Discovery from Large-Scale Human-LLM Conversational Datasets

# 摘要

> 大型语言模型（LLM）备受瞩目，但滥用风险也引发担忧。越狱提示作为针对LLM的对抗性攻击手段，不断演化以突破安全防线。为应对这一挑战，LLM定期更新安全补丁，但恶意用户常保密成功提示以利用模型。为此，我们需深入分析大规模对话数据，以揭示那些仍能绕过防御的提示。面对数据量庞大、提示多样且藏匿于复杂对话中的挑战，我们推出了JailbreakHunter，一种可视化分析工具，用于在大规模人-LLM对话中识别越狱提示。该工具通过组级、对话级和轮次级三个层次的分析，帮助用户掌握对话分布、理解对话进展，并探索提示间的语义联系，从而发现新的越狱策略。通过案例研究和专家评估，我们验证了该工具的有效性和实用性。

> Large Language Models (LLMs) have gained significant attention but also raised concerns due to the risk of misuse. Jailbreak prompts, a popular type of adversarial attack towards LLMs, have appeared and constantly evolved to breach the safety protocols of LLMs. To address this issue, LLMs are regularly updated with safety patches based on reported jailbreak prompts. However, malicious users often keep their successful jailbreak prompts private to exploit LLMs. To uncover these private jailbreak prompts, extensive analysis of large-scale conversational datasets is necessary to identify prompts that still manage to bypass the system's defenses. This task is highly challenging due to the immense volume of conversation data, diverse characteristics of jailbreak prompts, and their presence in complex multi-turn conversations. To tackle these challenges, we introduce JailbreakHunter, a visual analytics approach for identifying jailbreak prompts in large-scale human-LLM conversational datasets. We have designed a workflow with three analysis levels: group-level, conversation-level, and turn-level. Group-level analysis enables users to grasp the distribution of conversations and identify suspicious conversations using multiple criteria, such as similarity with reported jailbreak prompts in previous research and attack success rates. Conversation-level analysis facilitates the understanding of the progress of conversations and helps discover jailbreak prompts within their conversation contexts. Turn-level analysis allows users to explore the semantic similarity and token overlap between a singleturn prompt and the reported jailbreak prompts, aiding in the identification of new jailbreak strategies. The effectiveness and usability of the system were verified through multiple case studies and expert interviews.

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x1.png)

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x2.png)

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x3.png)

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x4.png)

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x5.png)

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x6.png)

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x7.png)

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x8.png)

![JailbreakHunter：一种视觉分析方法，旨在从大规模人类与 LLM 的对话数据集中发现越狱提示。](../../../paper_images/2407.03045/x9.png)

[Arxiv](https://arxiv.org/abs/2407.03045)