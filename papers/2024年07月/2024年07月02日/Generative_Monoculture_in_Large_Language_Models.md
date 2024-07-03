# 大型语言模型中的生成单一文化现象

发布时间：2024年07月02日

`LLM理论` `人工智能` `出版业`

> Generative Monoculture in Large Language Models

# 摘要

> 我们提出“生成单一文化”现象，即大型语言模型在特定任务中输出多样性大幅缩减，如仅产出正面书评，即便书籍评价参差不齐。此现象虽在某些领域提升效率，如代码生成，但在需要多元观点的场合，风险倍增。随着LLM在关键领域的广泛应用，维护输出多样性变得尤为重要，以保障信息的多元性。我们通过实验揭示了这一现象的普遍性，并指出传统对策效果有限。研究还表明，问题的根源可能在于模型的对齐过程，因此，开发能促进多样性的微调方法势在必行。

> We introduce {\em generative monoculture}, a behavior observed in large language models (LLMs) characterized by a significant narrowing of model output diversity relative to available training data for a given task: for example, generating only positive book reviews for books with a mixed reception. While in some cases, generative monoculture enhances performance (e.g., LLMs more often produce efficient code), the dangers are exacerbated in others (e.g., LLMs refuse to share diverse opinions). As LLMs are increasingly used in high-impact settings such as education and web search, careful maintenance of LLM output diversity is essential to ensure a variety of facts and perspectives are preserved over time. We experimentally demonstrate the prevalence of generative monoculture through analysis of book review and code generation tasks, and find that simple countermeasures such as altering sampling or prompting strategies are insufficient to mitigate the behavior. Moreover, our results suggest that the root causes of generative monoculture are likely embedded within the LLM's alignment processes, suggesting a need for developing fine-tuning paradigms that preserve or promote diversity.

[Arxiv](https://arxiv.org/abs/2407.02209)