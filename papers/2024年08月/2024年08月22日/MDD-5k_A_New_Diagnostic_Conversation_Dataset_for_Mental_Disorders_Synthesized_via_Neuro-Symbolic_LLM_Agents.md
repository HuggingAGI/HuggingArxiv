# MDD-5k：一款由神经-符号 LLM 代理生成的心理障碍诊断对话新数据集

发布时间：2024年08月22日

`Agent` `人工智能`

> MDD-5k: A New Diagnostic Conversation Dataset for Mental Disorders Synthesized via Neuro-Symbolic LLM Agents

# 摘要

> 精神障碍的临床诊断主要依赖于医患对话。我们通过利用匿名患者案例，设计了一个神经符号多代理框架，合成诊断对话，推动 AI 心理健康护理的发展。该框架通过大型语言模型，以患者案例为输入，生成多样化的对话，涉及医生与患者代理的交互，并在符号控制下实现文本生成。我们与领先精神病医院合作，基于 1000 个真实患者案例，构建了包含 5000 个高质量对话的 MDD-5k 数据集，这是首个标记的中文精神障碍诊断数据集。人类评估显示，MDD-5k 成功模拟了人类诊断过程。数据集和代码将在 GitHub 公开。

> The clinical diagnosis of most mental disorders primarily relies on the conversations between psychiatrist and patient. The creation of such diagnostic conversation datasets is promising to boost the AI mental healthcare community. However, directly collecting the conversations in real diagnosis scenarios is near impossible due to stringent privacy and ethical considerations. To address this issue, we seek to synthesize diagnostic conversation by exploiting anonymous patient cases that are easier to access. Specifically, we design a neuro-symbolic multi-agent framework for synthesizing the diagnostic conversation of mental disorders with large language models. It takes patient case as input and is capable of generating multiple diverse conversations with one single patient case. The framework basically involves the interaction between a doctor agent and a patient agent, and achieves text generation under symbolic control via a dynamic diagnosis tree from a tool agent. By applying the proposed framework, we develop the largest Chinese mental disorders diagnosis dataset MDD-5k, which is built upon 1000 cleaned real patient cases by cooperating with a pioneering psychiatric hospital, and contains 5000 high-quality long conversations with diagnosis results as labels. To the best of our knowledge, it's also the first labelled Chinese mental disorders diagnosis dataset. Human evaluation demonstrates the proposed MDD-5k dataset successfully simulates human-like diagnostic process of mental disorders. The dataset and code will become publicly accessible in https://github.com/lemonsis/MDD-5k.

[Arxiv](https://arxiv.org/abs/2408.12142)