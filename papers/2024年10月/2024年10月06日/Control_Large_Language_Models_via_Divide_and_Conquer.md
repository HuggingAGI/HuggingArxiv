# 驾驭大型语言模型：分而治之的策略

发布时间：2024年10月06日

`LLM应用` `文本生成` `人工智能`

> Control Large Language Models via Divide and Conquer

# 摘要

> 本文探讨了基于提示控制的大型语言模型 (LLM) 的可控生成，特别关注词汇约束生成 (LCG)。我们系统评估了 LLM 在满足词汇约束方面的表现，以及其在实际应用中的效果。研究发现，LLM 在一致满足词汇约束方面存在显著挑战，主要问题包括位置偏差、对解码参数的低响应性以及处理复杂约束的困难。为此，我们提出了一种分治生成策略，显著提升了 LLM 在 LCG 任务中的表现，成功率提高了 90% 以上。这一策略不仅适用于不同类型的 LLM，还为更高级和个性化的文本生成应用开辟了新路径。

> This paper investigates controllable generation for large language models (LLMs) with prompt-based control, focusing on Lexically Constrained Generation (LCG). We systematically evaluate the performance of LLMs on satisfying lexical constraints with prompt-based control, as well as their efficacy in downstream applications. We conclude that LLMs face significant challenges in consistently satisfying lexical constraints with prompt-based control. We identified three key limitations of LLMs for LCG, including (1) position bias, where LLMs tend to satisfy constraints that appear in specific positions within the input; (2) low responsiveness to decoding parameters, which render minimal impact on control of LLMs; and (3) struggle with handling the inherent complexity of certain constraints (e.g., compound words). To address these issues, we introduce a Divide and Conquer Generation strategy, effective for both white-box and black-box LLMs, to enhance LLMs performance in LCG tasks, which demonstrates over 90% improvement on success rate in the most challenging LCG task. Our analysis provides valuable insights into the performance of LLMs in LCG with prompt-based control, and our proposed strategy offers a pathway to more sophisticated and customized text generation applications.

[Arxiv](https://arxiv.org/abs/2410.04628)