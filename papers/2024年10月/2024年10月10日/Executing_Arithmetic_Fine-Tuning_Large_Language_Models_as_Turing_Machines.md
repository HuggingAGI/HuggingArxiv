# 微调大型语言模型，使其具备图灵机的算术执行能力。

发布时间：2024年10月10日

`LLM理论` `人工智能`

> Executing Arithmetic: Fine-Tuning Large Language Models as Turing Machines

# 摘要

> 尽管 LLM 在 NLP 和推理任务中表现出色，但在基础算术领域仍显不足。LLM 往往依赖记忆而非理解计算逻辑，限制了其解决新问题的能力。为此，我们设计了 CAEF 框架，通过模拟图灵机让 LLM 逐步学习计算，真正掌握计算逻辑。CAEF 不仅高效，还能组合学习到的操作符，简化复杂运算的学习。实验表明，CAEF 在 LLaMA 3.1-8B 模型上对七种常见数学运算的准确率接近 100%，甚至在处理 100 位操作数的计算时，也优于 GPT-4o。

> Large Language Models (LLMs) have demonstrated remarkable capabilities across a wide range of natural language processing and reasoning tasks. However, their performance in the foundational domain of arithmetic remains unsatisfactory. When dealing with arithmetic tasks, LLMs often memorize specific examples rather than learning the underlying computational logic, limiting their ability to generalize to new problems. In this paper, we propose a Composable Arithmetic Execution Framework (CAEF) that enables LLMs to learn to execute step-by-step computations by emulating Turing Machines, thereby gaining a genuine understanding of computational logic. Moreover, the proposed framework is highly scalable, allowing composing learned operators to significantly reduce the difficulty of learning complex operators. In our evaluation, CAEF achieves nearly 100% accuracy across seven common mathematical operations on the LLaMA 3.1-8B model, effectively supporting computations involving operands with up to 100 digits, a level where GPT-4o falls short noticeably in some settings.

[Arxiv](https://arxiv.org/abs/2410.07896)