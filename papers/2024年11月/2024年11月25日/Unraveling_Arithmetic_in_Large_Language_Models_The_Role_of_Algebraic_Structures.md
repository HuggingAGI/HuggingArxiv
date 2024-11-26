# 探索大型语言模型中的算术：代数结构所起的作用

发布时间：2024年11月25日

`LLM理论`

> Unraveling Arithmetic in Large Language Models: The Role of Algebraic Structures

# 摘要

> 大型语言模型（LLMs）展现出了非凡的数学能力，这主要得益于思维链（CoT）提示，它能将复杂推理拆解为一步步的解法。此方法成效显著，GSM8K 和 MATH 等基准测试成绩就是明证。不过，LLMs 在 CoT 单步中进行算术运算的能力所基于的机制仍未被充分理解。现有研究在争论 LLMs 是对数值进行编码还是依靠符号推理，还有一些在探究算术任务中的注意力和多层处理。在本研究中，我们认为 LLMs 是通过捕捉代数结构（比如交换性和恒等性）来学习算术的。由于这些结构能通过输入 - 输出关系被观测到，所以能推广到未曾见过的数据。我们通过实验证明，LLMs 能够利用自定义的算术问题数据集学习代数结构。我们的发现表明，借助代数结构能够提升 LLMs 的算术能力，为改进其算术表现提供了思路。

> Large language models (LLMs) have demonstrated remarkable mathematical capabilities, largely driven by chain-of-thought (CoT) prompting, which decomposes complex reasoning into step-by-step solutions. This approach has enabled significant advancements, as evidenced by performance on benchmarks like GSM8K and MATH. However, the mechanisms underlying LLMs' ability to perform arithmetic in a single step of CoT remain poorly understood. Existing studies debate whether LLMs encode numerical values or rely on symbolic reasoning, while others explore attention and multi-layered processing in arithmetic tasks. In this work, we propose that LLMs learn arithmetic by capturing algebraic structures, such as \emph{Commutativity} and \emph{Identity} properties. Since these structures are observable through input-output relationships, they can generalize to unseen data. We empirically demonstrate that LLMs can learn algebraic structures using a custom dataset of arithmetic problems. Our findings indicate that leveraging algebraic structures can enhance the LLMs' arithmetic capabilities, offering insights into improving their arithmetic performance.

[Arxiv](https://arxiv.org/abs/2411.16260)