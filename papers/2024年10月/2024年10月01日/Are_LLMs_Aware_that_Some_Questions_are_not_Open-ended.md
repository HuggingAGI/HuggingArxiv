# 大型语言模型是否能识别出某些问题并非开放性问题？

发布时间：2024年10月01日

`LLM理论` `人工智能`

> Are LLMs Aware that Some Questions are not Open-ended?

# 摘要

> 大型语言模型 (LLM) 在回答各类问题时表现出色，但面对不同类型的问题时，LLM 是否能意识到某些问题答案有限，需要更确定性地回答，而有些则不需要，这一问题值得探讨。我们称之为 LLM 的问题意识。LLM 缺乏问题意识会导致两种现象：(1) 对非开放性问题回答过于随意，或 (2) 对开放性问题回答过于乏味。本文首先评估了 LLM 的问题意识，发现其在某些领域（如事实知识）缺乏意识，导致生成过程中出现幻觉。为此，我们提出了问题意识温度采样 (QuATS) 方法，通过自适应调整输出分布，增强 LLM 的问题意识。QuATS 的自动调整不仅消除了手动调优的需求，还在各类基准测试中持续提升模型性能。

> Large Language Models (LLMs) have shown the impressive capability of answering questions in a wide range of scenarios. However, when LLMs face different types of questions, it is worth exploring whether LLMs are aware that some questions have limited answers and need to respond more deterministically but some do not. We refer to this as question awareness of LLMs. The lack of question awareness in LLMs leads to two phenomena that LLMs are: (1) too casual to answer non-open-ended questions or (2) too boring to answer open-ended questions. In this paper, we first evaluate the question awareness in LLMs. The experimental results show that LLMs have the issues of lacking awareness of questions in certain domains, e.g. factual knowledge, resulting in hallucinations during the generation. To mitigate these, we propose a method called Question Awareness Temperature Sampling (QuATS). This method enhances the question awareness of LLMs by adaptively adjusting the output distributions based on question features. The automatic adjustment in QuATS eliminates the need for manual temperature tuning in text generation and consistently improves model performance in various benchmarks.

[Arxiv](https://arxiv.org/abs/2410.00423)