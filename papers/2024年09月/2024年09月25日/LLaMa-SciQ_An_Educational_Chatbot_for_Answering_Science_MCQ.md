# LLaMa-SciQ：专为解答科学选择题而生的教育聊天机器人

发布时间：2024年09月25日

`LLM应用` `STEM`

> LLaMa-SciQ: An Educational Chatbot for Answering Science MCQ

# 摘要

> 大型语言模型 (LLM) 在处理数学推理任务时往往表现不佳，尤其是多项选择题 (MCQs)。为此，我们推出了 LLaMa-SciQ，一个专为大学生设计的教育聊天机器人，帮助他们解决和理解 STEM 领域的 MCQs。我们首先对模型进行微调，使其更符合人类偏好。经过对比，我们选择了评估准确性更高的 LLaMa-8B 作为基础模型。为了进一步提升准确性，我们引入了检索增强生成 (RAG) 技术，并通过量化压缩模型，缩短推理时间，使学生更易使用。在数学推理测试中，LLaMa-SciQ 在 GSM8k 数据集上准确率达到 74.5%，在 MATH 数据集上为 30%。尽管 RAG 未能提升性能，甚至有所下降，可能是检索器或模型对上下文不熟悉所致，但量化后的模型仅损失 5% 的性能，显著提高了效率。

> Large Language Models (LLMs) often struggle with tasks requiring mathematical reasoning, particularly multiple-choice questions (MCQs). To address this issue, we developed LLaMa-SciQ, an educational chatbot designed to assist college students in solving and understanding MCQs in STEM fields. We begin by fine-tuning and aligning the models to human preferences. After comparing the performance of Mistral-7B and LLaMa-8B, we selected the latter as the base model due to its higher evaluation accuracy. To further enhance accuracy, we implement Retrieval-Augmented Generation (RAG) and apply quantization to compress the model, reducing inference time and increasing accessibility for students. For mathematical reasoning, LLaMa-SciQ achieved 74.5% accuracy on the GSM8k dataset and 30% on the MATH dataset. However, RAG does not improve performance and even reduces it, likely due to retriever issues or the model's unfamiliarity with context. Despite this, the quantized model shows only a 5% loss in performance, demonstrating significant efficiency improvements.

[Arxiv](https://arxiv.org/abs/2409.16779)