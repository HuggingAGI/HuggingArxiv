# AutoVerus：Rust 代码的自动化证明生成工具

发布时间：2024年09月19日

`LLM应用` `软件工程` `人工智能`

> AutoVerus: Automated Proof Generation for Rust Code

# 摘要

> 生成式 AI 在软件工程中的应用已初见成效，但基于 LLM 的证明生成仍落后于代码生成。本文介绍的 AutoVerus 利用 LLM 自动生成 Rust 代码的正确性证明，专为匹配 Verus 验证工具的独特特性而设计。AutoVerus 通过模拟人类专家的证明构建过程，包括初步生成、精炼和调试，展现了高效性能。我们构建了包含 150 个复杂任务的基准套件，评估显示 AutoVerus 能自动生成 90% 以上任务的正确证明，且半数任务在 30 秒内或 3 次 LLM 调用内完成。

> Generative AI has shown its values for many software engineering tasks. Still in its infancy, large language model (LLM)-based proof generation lags behind LLM-based code generation. In this paper, we present AutoVerus. AutoVerus uses LLM to automatically generate correctness proof for Rust code. AutoVerus is designed to match the unique features of Verus, a verification tool that can prove the correctness of Rust code using proofs and specifications also written in Rust. AutoVerus consists of a network of LLM agents that are crafted and orchestrated to mimic human experts' three phases of proof construction: preliminary proof generation, proof refinement guided by generic tips, and proof debugging guided by verification errors. To thoroughly evaluate AutoVerus and help foster future research in this direction, we have built a benchmark suite of 150 non-trivial proof tasks, based on existing code-generation benchmarks and verification benchmarks. Our evaluation shows that AutoVerus can automatically generate correct proof for more than 90% of them, with more than half of them tackled in less than 30 seconds or 3 LLM calls.

[Arxiv](https://arxiv.org/abs/2409.13082)