# 对话应用中，大型语言模型（LLMs）应选择微调还是RAG技术？本文将评估这两种方法的适应性。
发布时间：2024年06月10日

`RAG`
> Should We Fine-Tune or RAG? Evaluating Different Techniques to Adapt LLMs for Dialogue
>
> 本研究深入探讨了大型语言模型（LLMs）在人机对话响应生成中的局限性，并针对不同对话类型（如开放域）分析了多种适应技术的效果。我们选取了Llama-2和Mistral两种基础模型，以及开放域、知识基础、任务导向和问答四种对话场景，评估了上下文学习和微调技术在特定数据集上的表现。同时，我们探讨了在检索增强生成（RAG）和黄金知识两种情境下，引入外部知识对生成质量的影响。研究采用了统一的评估和解释标准，涵盖自动指标和人类评估协议。结果显示，最佳的LLM适应技术并非一成不变，其效果受基础模型和对话类型的双重影响。因此，为避免自动指标可能带来的误导，最佳技术的评估必须包含人类评估。
>
> https://arxiv.org/abs/2406.06399

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.06399/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.06399/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.06399/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.06399/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.06399/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.06399](https://arxiv.org/abs/2406.06399)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886