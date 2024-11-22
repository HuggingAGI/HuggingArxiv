# GASP：用于破解 LLMs 的高效黑箱式对抗后缀生成方法

发布时间：2024年11月21日

`LLM应用` `网络安全`

> GASP: Efficient Black-Box Generation of Adversarial Suffixes for Jailbreaking LLMs

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理任务中展现出了非凡的能力，然而却易受对抗性提示（即越狱攻击）的侵扰，这些提示是精心设计用来诱导LLMs给出有害回应的。传统方法依靠手动启发式，通用性欠佳。虽说自动，但基于优化的攻击常常产生不自然的越狱提示，容易被安全过滤器察觉，或者因离散令牌优化而导致计算开销巨大。鉴于现有越狱方法的种种局限，我们推出了生成对抗后缀提示器（GASP）这一全新框架，它将人类可读的提示生成与潜在贝叶斯优化（LBO）相融合，在完全黑箱环境下优化对抗后缀的创建。GASP借助LBO，通过高效探索连续嵌入空间来打造对抗后缀，通过针对性的迭代优化过程逐步提升模型的攻击效能，同时兼顾提示的连贯性。我们的实验显示，GASP能够生成自然的越狱提示，大幅提高攻击成功率，缩短训练时间，加快推理速度，从而成为针对LLMs红队测试的高效且可扩展的解决方案。

> Large Language Models (LLMs) have shown impressive proficiency across a range of natural language processing tasks yet remain vulnerable to adversarial prompts, known as jailbreak attacks, carefully designed to elicit harmful responses from LLMs. Traditional methods rely on manual heuristics, which suffer from limited generalizability. While being automatic, optimization-based attacks often produce unnatural jailbreak prompts that are easy to detect by safety filters or require high computational overhead due to discrete token optimization. Witnessing the limitations of existing jailbreak methods, we introduce Generative Adversarial Suffix Prompter (GASP), a novel framework that combines human-readable prompt generation with Latent Bayesian Optimization (LBO) to improve adversarial suffix creation in a fully black-box setting. GASP leverages LBO to craft adversarial suffixes by efficiently exploring continuous embedding spaces, gradually optimizing the model to improve attack efficacy while balancing prompt coherence through a targeted iterative refinement procedure. Our experiments show that GASP can generate natural jailbreak prompts, significantly improving attack success rates, reducing training times, and accelerating inference speed, thus making it an efficient and scalable solution for red-teaming LLMs.

[Arxiv](https://arxiv.org/abs/2411.14133)