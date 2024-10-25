# 使用前沿开源大型语言模型进行知识蒸馏：泛化能力和合成数据的作用

发布时间：2024年10月24日

`LLM应用` `知识蒸馏`

> Knowledge Distillation Using Frontier Open-source LLMs: Generalizability and the Role of Synthetic Data

# 摘要

> 领先的开源大型语言模型（LLM），如 Llama-3.1-Instruct-405B，在生成文本、回答问题和解决各种自然语言理解任务方面非常有能力。然而，与较小的 LLM 相比，它们会产生更高的推理成本和延迟。知识蒸馏提供了一种方法，可以使用这些大型、有能力的教师模型的输出，来训练较小的学生模型，这些学生模型可以以更低的成本和延迟进行推理，同时保持相当的准确性。我们研究了使用 Llama-3.1-405B-Instruct 教师模型和较小的 Llama-3.1-8B-Instruct 及 Llama-3.1-70B-Instruct 学生模型进行蒸馏的效果。这项工作的贡献包括：（a）我们评估了上述 Llama-3.1 师生对在不同任务和数据集上的蒸馏泛化能力（b）我们表明，在蒸馏过程中使用合成数据显著提高了 8B 和 70B 模型的准确性，并且当与推理链一起使用时，在某些数据集上甚至与 405B 模型的零样本准确性相当或超过（c）我们通过经验表明，仅使用标准微调（无需定制任何损失函数），蒸馏使 8B 和 70B 模型能够内化 405B 的推理能力。这使得学生模型的推理具有成本和延迟效率。（d）我们展示了蒸馏评估中的陷阱，并提出了特定任务的评估，包括人工和 LLM 评分，以及基于真实情况的传统准确性基准。这种有条理的研究揭示了合成数据质量在知识蒸馏中的根本重要性，以及在评估蒸馏效果时结合多种特定任务的准确性和质量评估方法的重要性。

> Leading open-source large language models (LLMs) such as Llama-3.1-Instruct-405B are extremely capable at generating text, answering questions, and solving a variety of natural language understanding tasks. However, they incur higher inference cost and latency compared to smaller LLMs. Knowledge distillation provides a way to use outputs from these large, capable teacher models to train smaller student models which can be used for inference at lower cost and latency, while retaining comparable accuracy. We investigate the efficacy of distillation using the Llama-3.1-405B-Instruct teacher and the smaller Llama-3.1-8B-Instruct and Llama-3.1-70B-Instruct student models. Contributions of this work include (a) We evaluate the generalizability of distillation with the above Llama-3.1 teacher-student pairs across different tasks and datasets (b) We show that using synthetic data during distillation significantly improves the accuracy of 8B and 70B models, and when used with reasoning chains, even matches or surpasses the zero-shot accuracy of 405B model on some datasets (c) We empirically show that distillation enables 8B and 70B models to internalize 405B's reasoning ability by using only standard fine-tuning (without customizing any loss function). This allows cost and latency-efficient student model inference. (d) We show pitfalls in evaluation of distillation, and present task-specific evaluation, including both human and LLM-grading, and ground-truth based traditional accuracy benchmarks. This methodical study brings out the fundamental importance of synthetic data quality in knowledge distillation, and of combining multiple, task-specific ways of accuracy and quality evaluation in assessing the effectiveness of distillation.

[Arxiv](https://arxiv.org/abs/2410.18588)