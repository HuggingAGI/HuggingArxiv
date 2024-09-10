# 探索与解答：表格问答中的推理之道

发布时间：2024年09月08日

`LLM应用` `数据分析`

> Seek and Solve Reasoning for Table Question Answering

# 摘要

> 基于表格的问答 (TQA) 任务因其复杂的表格结构和问题逻辑，即使对大型语言模型 (LLM) 也颇具挑战。本文通过利用 LLM 的推理能力，提出了一种 Seek-and-Solve 流程，指导模型先寻找相关信息再回答问题。这一流程在推理层面集成，并形成连贯的 Seek-and-Solve CoT (SS-CoT)。此外，我们还设计了一种紧凑的单阶段 TQA 解决提示。实验显示，在上下文学习中，使用 SS-CoT 路径的样本作为演示，能有效提升 LLM 解决复杂 TQA 任务的能力，增强性能和可靠性。这凸显了在复杂 TQA 任务中，正确激发 LLM 推理能力的重要性。

> Table-based Question Answering (TQA) involves answering questions based on tabular data. The complexity of table structures and question logic makes this task difficult even for Large Language Models (LLMs). This paper improves TQA performance by leveraging LLMs' reasoning capabilities. Inspired by how humans solve TQA tasks, we propose a Seek-and-Solve pipeline that instructs the LLM to first seek relevant information and then answer questions. The two stages are integrated at the reasoning level, and their Chain of Thought (CoT) paths are integrated into a coherent Seek-and-Solve CoT (SS-CoT). Furthermore, we present a compact single-stage TQA-solving prompt distilled from the pipeline. Experiments demonstrate that under In-Context Learning settings, using samples with SS-CoT paths as demonstrations, the TQA-solving prompt can effectively guide the LLM to solve complex TQA tasks, resulting in improved performance and reliability. Our results highlight the importance of properly eliciting LLMs' reasoning capabilities in solving complex TQA tasks.

[Arxiv](https://arxiv.org/abs/2409.05286)