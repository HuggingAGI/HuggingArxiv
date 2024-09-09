# 自我和谐思维链

发布时间：2024年09月06日

`LLM应用` `人工智能`

> Self-Harmonized Chain of Thought

# 摘要

> CoT prompting 展示了大型语言模型通过中间步骤进行复杂推理的能力。主要方法有三：一是通过“让我们一步一步地思考”引导模型逐步推理；二是利用人工制作的逐步演示指导推理；三是自动生成推理步骤，但有时会导致错误，因此需要多样化演示来减少误导。然而，多样化演示在有效表示上存在挑战。为此，我们提出了 ECHO，一种自我协调的 CoT prompting 方法，能将多样化的解决方案整合成统一有效的模式，并在三个推理领域中表现出色。

> Chain-of-Thought (CoT) prompting reveals that large language models are capable of performing complex reasoning via intermediate steps. CoT prompting is primarily categorized into three approaches. The first approach utilizes straightforward prompts like ``Let's think step by step'' to generate a sequential thought process before yielding an answer. The second approach makes use of human-crafted, step-by-step demonstrations to guide the model's reasoning process. The third automates the generation of reasoned demonstrations with the 'Let's think step by step'.This approach sometimes leads to reasoning errors, highlighting the need to diversify demonstrations to mitigate its misleading effects. However, diverse demonstrations pose challenges for effective representations. In this work, we propose ECHO, a self-harmonized chain-of-thought prompting method. It consolidates diverse solution paths into a uniform and effective solution pattern.ECHO demonstrates the best overall performance across three reasoning domains.

[Arxiv](https://arxiv.org/abs/2409.04057)