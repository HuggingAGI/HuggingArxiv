# RMCBench：评估大型语言模型抵御恶意代码的能力

发布时间：2024年09月23日

`LLM应用` `软件开发` `网络安全`

> RMCBench: Benchmarking Large Language Models' Resistance to Malicious Code

# 摘要

> 大型语言模型（LLM）的崛起深刻影响了软件开发的方方面面。尽管它们带来了诸多好处，但也伴随着显著风险，如生成有害内容或被恶意开发者利用来编写恶意代码。以往的研究多聚焦于 LLM 对生成偏见或冒犯性内容等违反伦理标准的抵抗能力，但对其抵抗生成恶意代码的能力却鲜有探讨。为此，我们推出了 RMCBench，这是首个包含 473 个提示的基准，专门用于评估 LLM 抵抗恶意代码生成的能力。RMCBench 设计了两种场景：一是文本到代码，LLM 根据描述生成代码；二是代码到代码，LLM 翻译或补全现有恶意代码。基于此，我们对 11 个代表性 LLM 进行了实证研究，发现它们抵抗恶意代码生成的平均拒绝率在文本到代码场景中为 40.36%，在代码到代码场景中为 11.52%。总体而言，所有 LLM 在 RMCBench 中的平均拒绝率仅为 28.71%，而 ChatGPT-4 的拒绝率更是低至 35.73%。此外，我们还深入分析了影响 LLM 抵抗恶意代码生成能力的因素，并提出了增强模型鲁棒性的建议。

> The emergence of Large Language Models (LLMs) has significantly influenced various aspects of software development activities. Despite their benefits, LLMs also pose notable risks, including the potential to generate harmful content and being abused by malicious developers to create malicious code. Several previous studies have focused on the ability of LLMs to resist the generation of harmful content that violates human ethical standards, such as biased or offensive content. However, there is no research evaluating the ability of LLMs to resist malicious code generation. To fill this gap, we propose RMCBench, the first benchmark comprising 473 prompts designed to assess the ability of LLMs to resist malicious code generation. This benchmark employs two scenarios: a text-to-code scenario, where LLMs are prompted with descriptions to generate code, and a code-to-code scenario, where LLMs translate or complete existing malicious code. Based on RMCBench, we conduct an empirical study on 11 representative LLMs to assess their ability to resist malicious code generation. Our findings indicate that current LLMs have a limited ability to resist malicious code generation with an average refusal rate of 40.36% in text-to-code scenario and 11.52% in code-to-code scenario. The average refusal rate of all LLMs in RMCBench is only 28.71%; ChatGPT-4 has a refusal rate of only 35.73%. We also analyze the factors that affect LLMs' ability to resist malicious code generation and provide implications for developers to enhance model robustness.

[Arxiv](https://arxiv.org/abs/2409.15154)