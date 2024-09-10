# CauseJudger：借助 LLM 进行溯因逻辑推理，精准识别原因

发布时间：2024年09月09日

`LLM应用` `人工智能` `逻辑推理`

> CauseJudger: Identifying the Cause with LLMs for Abductive Logical Reasoning

# 摘要

> 大型语言模型 (LLM) 在解决常识、算术和演绎等多样推理任务中表现出色。然而，面对逆向思维和无关前提的挑战，溯因逻辑推理中原因真实性的判定仍是一个未解之谜。借鉴假设验证法和人类思维中无关信息的识别，我们推出了名为 CauseJudger (CJ) 的新框架，通过正向思维和信息筛选来验证原因的真实性。我们还创建了包含 200,000 个任务的 CauseLogics 数据集，用于溯因逻辑推理。实验表明，CJ 不仅在整体和消融实验中表现优异，而且在案例研究中也展现了其高效性，仅需两次 LLM 调用。使用 gpt-3.5 时，CJ 的正确性提升了 41%，而 gpt-4 则使其在所有数据集上的准确率突破 90%。

> Large language models (LLMs) have been utilized in solving diverse reasoning tasks, encompassing common sense, arithmetic and deduction tasks. However, with difficulties of reversing thinking patterns and irrelevant premises, how to determine the authenticity of the cause in abductive logical reasoning remains underexplored. Inspired by hypothesis and verification method and identification of irrelevant information in human thinking process, we propose a new framework for LLMs abductive logical reasoning called CauseJudger (CJ), which identifies the authenticity of possible cause by transforming thinking from reverse to forward and removing irrelevant information. In addition, we construct an abductive logical reasoning dataset for decision task called CauseLogics, which contains 200,000 tasks of varying reasoning lengths. Our experiments show the efficiency of CJ with overall experiments and ablation experiments as well as case studies on our dataset and reconstructed public dataset. Notably, CJ's implementation is efficient, requiring only two calls to LLM. Its impact is profound: when using gpt-3.5, CJ achieves a maximum correctness improvement of 41% compared to Zero-Shot-CoT. Moreover, with gpt-4, CJ attains an accuracy exceeding 90% across all datasets.

[Arxiv](https://arxiv.org/abs/2409.05559)