# GSM-Symbolic：揭示大型语言模型在数学推理中的局限

发布时间：2024年10月07日

`LLM理论` `人工智能`

> GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models

# 摘要

> 大型语言模型 (LLM) 在数学推理方面的表现引发了广泛关注。尽管 LLM 在 GSM8K 基准上的成绩有所提升，但其真正的数学推理能力仍存疑。为此，我们进行了大规模研究，并推出了 GSM-Symbolic 基准，以更精准地评估模型。研究发现，LLM 在处理同一问题的不同变体时表现波动较大，尤其在数值变化时性能显著下降。此外，随着问题复杂度增加，模型的推理能力显著减弱。这表明当前 LLM 的推理能力仍依赖于训练数据的复制，而非真正的逻辑推理。我们的研究揭示了 LLM 在数学推理中的真实表现，为未来改进提供了方向。

> Recent advancements in Large Language Models (LLMs) have sparked interest in their formal reasoning capabilities, particularly in mathematics. The GSM8K benchmark is widely used to assess the mathematical reasoning of models on grade-school-level questions. While the performance of LLMs on GSM8K has significantly improved in recent years, it remains unclear whether their mathematical reasoning capabilities have genuinely advanced, raising questions about the reliability of the reported metrics. To address these concerns, we conduct a large-scale study on several SOTA open and closed models. To overcome the limitations of existing evaluations, we introduce GSM-Symbolic, an improved benchmark created from symbolic templates that allow for the generation of a diverse set of questions. GSM-Symbolic enables more controllable evaluations, providing key insights and more reliable metrics for measuring the reasoning capabilities of models.Our findings reveal that LLMs exhibit noticeable variance when responding to different instantiations of the same question. Specifically, the performance of all models declines when only the numerical values in the question are altered in the GSM-Symbolic benchmark. Furthermore, we investigate the fragility of mathematical reasoning in these models and show that their performance significantly deteriorates as the number of clauses in a question increases. We hypothesize that this decline is because current LLMs cannot perform genuine logical reasoning; they replicate reasoning steps from their training data. Adding a single clause that seems relevant to the question causes significant performance drops (up to 65%) across all state-of-the-art models, even though the clause doesn't contribute to the reasoning chain needed for the final answer. Overall, our work offers a more nuanced understanding of LLMs' capabilities and limitations in mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2410.05229)