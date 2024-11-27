# 提示格式会对 LLM 性能产生影响吗？

发布时间：2024年11月15日

`LLM应用` `代码生成`

> Does Prompt Formatting Have Any Impact on LLM Performance?

# 摘要

> 摘要：在大型语言模型（LLMs）领域，提示优化对模型性能起着关键作用。尽管此前的研究已在重新表述提示上下文、运用各类提示技术（像上下文学习和思维链）以及对少量示例排序等方面有所探索，但我们对于LLM对提示模板的敏感度的理解仍很有限。所以，本文探究了不同提示模板对LLM性能的影响。我们把相同的上下文编排成多种人类可读的模板，涵盖纯文本、Markdown、JSON和YAML，并借助OpenAI的GPT模型评估了它们在自然语言推理、代码生成及翻译等任务中的作用。实验显示，在代码翻译任务中，GPT-3.5-turbo的性能会因提示模板的不同而变化多达40%，而像GPT-4这样的更大模型对这些变化的适应性更强。我们的分析凸显出，需要重新审视固定提示模板的使用，因为不同格式会显著影响模型性能。

> 
Abstract:In the realm of Large Language Models (LLMs), prompt optimization is crucial for model performance. Although previous research has explored aspects like rephrasing prompt contexts, using various prompting techniques (like in-context learning and chain-of-thought), and ordering few-shot examples, our understanding of LLM sensitivity to prompt templates remains limited. Therefore, this paper examines the impact of different prompt templates on LLM performance. We formatted the same contexts into various human-readable templates, including plain text, Markdown, JSON, and YAML, and evaluated their impact across tasks like natural language reasoning, code generation, and translation using OpenAI's GPT models. Experiments show that GPT-3.5-turbo's performance varies by up to 40\% in a code translation task depending on the prompt template, while larger models like GPT-4 are more robust to these variations. Our analysis highlights the need to reconsider the use of fixed prompt templates, as different formats can significantly affect model performance.
    

[Arxiv](https://arxiv.org/pdf/2411.10541)