# LLM 总会产生幻觉，我们得学会接受这一点。

发布时间：2024年09月09日

`LLM理论` `人工智能` `计算理论`

> LLMs Will Always Hallucinate, and We Need to Live With This

# 摘要

> 随着大型语言模型在各领域的普及，审视其固有局限性变得尤为重要。本文指出，语言模型中的幻觉并非偶然错误，而是其内在特征。幻觉源于LLMs的数学和逻辑基础，无法通过架构优化、数据增强或事实核查彻底消除。我们结合计算理论和哥德尔定理，证明LLM的每个环节都存在产生幻觉的概率。因此，我们提出“结构幻觉”概念，强调其内在性，并挑战了幻觉可完全缓解的普遍观点。

> As Large Language Models become more ubiquitous across domains, it becomes important to examine their inherent limitations critically. This work argues that hallucinations in language models are not just occasional errors but an inevitable feature of these systems. We demonstrate that hallucinations stem from the fundamental mathematical and logical structure of LLMs. It is, therefore, impossible to eliminate them through architectural improvements, dataset enhancements, or fact-checking mechanisms. Our analysis draws on computational theory and Godel's First Incompleteness Theorem, which references the undecidability of problems like the Halting, Emptiness, and Acceptance Problems. We demonstrate that every stage of the LLM process-from training data compilation to fact retrieval, intent classification, and text generation-will have a non-zero probability of producing hallucinations. This work introduces the concept of Structural Hallucination as an intrinsic nature of these systems. By establishing the mathematical certainty of hallucinations, we challenge the prevailing notion that they can be fully mitigated.

[Arxiv](https://arxiv.org/abs/2409.05746)