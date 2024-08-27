# TF-Attack：针对大型语言模型的可迁移与快速对抗攻击

发布时间：2024年08月25日

`LLM应用` `网络安全` `人工智能`

> TF-Attack: Transferable and Fast Adversarial Attacks on Large Language Models

# 摘要

> 随着 LLM 技术的飞速发展，针对这些模型的对抗攻击也日益受到关注。我们发现，现有的攻击方法在转移性和效率上存在明显不足，尤其是在 LLM 应用中。本文深入剖析了传统攻击方法的局限，指出重要性得分分布的差异和顺序攻击带来的时间开销是两大瓶颈。为此，我们提出了 TF-Attack 方案，通过外部 LLM 作为监督者，并引入重要性级别概念，实现了并行攻击，大幅提升了攻击的转移性和速度。实验结果表明，TF-Attack 在多个基准测试中表现卓越，速度提升高达 20 倍，显著优于现有方法。

> With the great advancements in large language models (LLMs), adversarial attacks against LLMs have recently attracted increasing attention. We found that pre-existing adversarial attack methodologies exhibit limited transferability and are notably inefficient, particularly when applied to LLMs. In this paper, we analyze the core mechanisms of previous predominant adversarial attack methods, revealing that 1) the distributions of importance score differ markedly among victim models, restricting the transferability; 2) the sequential attack processes induces substantial time overheads. Based on the above two insights, we introduce a new scheme, named TF-Attack, for Transferable and Fast adversarial attacks on LLMs. TF-Attack employs an external LLM as a third-party overseer rather than the victim model to identify critical units within sentences. Moreover, TF-Attack introduces the concept of Importance Level, which allows for parallel substitutions of attacks. We conduct extensive experiments on 6 widely adopted benchmarks, evaluating the proposed method through both automatic and human metrics. Results show that our method consistently surpasses previous methods in transferability and delivers significant speed improvements, up to 20 times faster than earlier attack strategies.

[Arxiv](https://arxiv.org/abs/2408.13985)