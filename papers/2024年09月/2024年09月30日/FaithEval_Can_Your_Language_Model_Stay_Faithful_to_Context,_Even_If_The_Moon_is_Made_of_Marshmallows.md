# FaithEval：面对“月亮是棉花糖做的”这种说法，你的语言模型能否坚守上下文的忠实性？

发布时间：2024年09月30日

`LLM应用` `人工智能`

> FaithEval: Can Your Language Model Stay Faithful to Context, Even If "The Moon is Made of Marshmallows"

# 摘要

> 在 LLM 和 RAG 系统中，确保对上下文的忠实性至关重要，因为错误信息会损害用户信任。尽管基准测试有所进步，但模型生成与上下文不符的响应（忠实性幻觉）仍是一大难题。为此，我们推出了 FaithEval，一个专为评估 LLM 在三种复杂任务中上下文忠实性的全面基准：不可回答、不一致和反事实上下文。FaithEval 包含 4.9K 个高质量问题，通过四阶段严格验证框架确保准确性。研究发现，即使是顶尖模型也难以完全忠实于上下文，且模型规模并非决定忠实性的唯一因素。项目详情请访问：\url{https://github.com/SalesforceAIResearch/FaithEval}。

> Ensuring faithfulness to context in large language models (LLMs) and retrieval-augmented generation (RAG) systems is crucial for reliable deployment in real-world applications, as incorrect or unsupported information can erode user trust. Despite advancements on standard benchmarks, faithfulness hallucination-where models generate responses misaligned with the provided context-remains a significant challenge. In this work, we introduce FaithEval, a novel and comprehensive benchmark tailored to evaluate the faithfulness of LLMs in contextual scenarios across three diverse tasks: unanswerable, inconsistent, and counterfactual contexts. These tasks simulate real-world challenges where retrieval mechanisms may surface incomplete, contradictory, or fabricated information. FaithEval comprises 4.9K high-quality problems in total, validated through a rigorous four-stage context construction and validation framework, employing both LLM-based auto-evaluation and human validation. Our extensive study across a wide range of open-source and proprietary models reveals that even state-of-the-art models often struggle to remain faithful to the given context, and that larger models do not necessarily exhibit improved faithfulness.Project is available at: \url{https://github.com/SalesforceAIResearch/FaithEval}.

[Arxiv](https://arxiv.org/abs/2410.03727)