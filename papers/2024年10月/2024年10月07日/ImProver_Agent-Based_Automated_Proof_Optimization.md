# ImProver：一种基于代理的自动证明优化工具

发布时间：2024年10月07日

`Agent` `人工智能`

> ImProver: Agent-Based Automated Proof Optimization

# 摘要

> 大型语言模型 (LLM) 已被用于在 Lean 等证明助手中生成数学定理的正式证明。然而，我们通常希望根据其下游用途优化正式证明的各种标准。例如，我们可能希望证明符合某种风格，或者可读、简洁或模块化结构。为此，我们研究了一个新的自动证明优化问题：重写证明，使其正确并针对任意标准（如长度或可读性）进行优化。作为自动证明优化的第一种方法，我们提出了 ImProver，这是一个大型语言模型代理，它重写证明以在 Lean 中优化任意用户定义的指标。我们发现，天真地将 LLM 应用于证明优化是不够的，我们将各种改进纳入 ImProver，例如在新的 Chain-of-States 技术中使用符号化 Lean 上下文，以及错误纠正和检索。我们在重写真实世界的本科、竞赛和研究级数学定理时测试了 ImProver，发现 ImProver 能够重写证明，使其显著更短、更模块化且更易读。

> Large language models (LLMs) have been used to generate formal proofs of mathematical theorems in proofs assistants such as Lean. However, we often want to optimize a formal proof with respect to various criteria, depending on its downstream use. For example, we may want a proof to adhere to a certain style, or to be readable, concise, or modularly structured. Having suitably optimized proofs is also important for learning tasks, especially since human-written proofs may not optimal for that purpose. To this end, we study a new problem of automated proof optimization: rewriting a proof so that it is correct and optimizes for an arbitrary criterion, such as length or readability. As a first method for automated proof optimization, we present ImProver, a large-language-model agent that rewrites proofs to optimize arbitrary user-defined metrics in Lean. We find that naively applying LLMs to proof optimization falls short, and we incorporate various improvements into ImProver, such as the use of symbolic Lean context in a novel Chain-of-States technique, as well as error-correction and retrieval. We test ImProver on rewriting real-world undergraduate, competition, and research-level mathematics theorems, finding that ImProver is capable of rewriting proofs so that they are substantially shorter, more modular, and more readable.

[Arxiv](https://arxiv.org/abs/2410.04753)