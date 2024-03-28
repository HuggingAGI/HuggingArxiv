# LLaMoCo 是一项研究，专注于通过指令微调大规模语言模型，以提升其生成优化代码的能力。

发布时间：2024年03月02日

`LLM应用`

> LLaMoCo: Instruction Tuning of Large Language Models for Optimization Code Generation

# 摘要

> 近期研究尝试利用LLMs进行优化，或是循环询问LLMs以求得每一步解，或直白地让LLMs生成优化器，但此类方法受限于操作效率低下、对提示设计过于敏感且缺乏领域专业知识等问题。为此，我们推出了首个针对LLMs以代码到代码方式解决优化问题的指令调优框架——LLaMoCo。我们在该框架下构建了一个详尽的问题描述提示与高效优化代码组成的综合指令库，并创新性地设计了包含对比学习预热阶段的双阶段学习策略，在模型微调过程中增强了收敛性能。实验证明，经由LLaMoCo微调后的CodeGen（350M）模型在合成及真实问题集上的优化表现均超越了GPT-4 Turbo及其他竞品。微调后的模型及其使用指南可在以下网址获取：https://anonymous.4open.science/r/LLaMoCo-722A。

> Recent research explores optimization using large language models (LLMs) by either iteratively seeking next-step solutions from LLMs or directly prompting LLMs for an optimizer. However, these approaches exhibit inherent limitations, including low operational efficiency, high sensitivity to prompt design, and a lack of domain-specific knowledge. We introduce LLaMoCo, the first instruction-tuning framework designed to adapt LLMs for solving optimization problems in a code-to-code manner. Specifically, we establish a comprehensive instruction set containing well-described problem prompts and effective optimization codes. We then develop a novel two-phase learning strategy that incorporates a contrastive learning-based warm-up procedure before the instruction-tuning phase to enhance the convergence behavior during model fine-tuning. The experiment results demonstrate that a CodeGen (350M) model fine-tuned by our LLaMoCo achieves superior optimization performance compared to GPT-4 Turbo and the other competitors across both synthetic and realistic problem sets. The fine-tuned model and the usage instructions are available at https://anonymous.4open.science/r/LLaMoCo-722A.

[Arxiv](https://arxiv.org/abs/2403.01131)