# 通过中间语言评估代码生成

发布时间：2024年07月07日

`LLM应用` `软件开发` `人工智能`

> Assessing Code Generation with Intermediate Languages

# 摘要

> 本研究通过思维链等中间步骤方法，探讨了多种中间语言（如编程语言、自然语言及伪代码）对大型语言模型在代码生成任务中性能的影响。实验涉及 CodeLlama、GPT 和 Mistral 系列的多款模型及新发布的小型模型。结果显示，自然语言作为中间表示在各目标语言中表现最佳，但未发现适用于所有模型和语言的通用有效中间语言。此外，中间解决方案的正确性与最终生成结果的关联较弱，暗示性能提升更多来自思维链效应而非特定语言的传递。特别地，GPT 系列模型在无明确自我修正指令下多次提示，可显著提升性能。

> Intermediate step methodologies like chain of thoughts (COT) have demonstrated effectiveness in enhancing the performance of Large Language Models (LLMs) on code generation. This study explores the utilization of intermediate languages, including various programming languages, natural language solutions, and pseudo-code, and systematically evaluates their impact on the performance of LLMs in code generation tasks. Our experiments encompass eleven models across the CodeLlama, GPT, and Mistral families, as well as newly released smaller models. Our findings reveal that intermediate languages generally exhibit greater efficacy in larger models that have not yet achieved state-of-the-art performance. Natural language consistently emerges as the most effective intermediate representation across all target languages. However, we observe no universally effective intermediate formal language across different models and target languages. Furthermore, we uncover a weak correlation between the correctness of intermediate solutions and final generation, suggesting that improvements may stem from the chain-of-thought effect rather than language-specific transfer. Interestingly, we discover that for GPT family models, prompting multiple times without explicit self-correction instructions yields performance gains across the studied languages.

[Arxiv](https://arxiv.org/abs/2407.05411)