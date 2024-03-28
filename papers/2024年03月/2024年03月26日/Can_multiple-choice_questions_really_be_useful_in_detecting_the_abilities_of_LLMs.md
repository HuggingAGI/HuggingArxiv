# 多项选择题是否真的有助于评估大型语言模型的能力？

发布时间：2024年03月26日

`LLM应用` `问答系统` `语言模型评估`

> Can multiple-choice questions really be useful in detecting the abilities of LLMs?

# 摘要

> 多项选择题（MCQs）在评估大型语言模型（LLMs）时广受欢迎，因其简便高效。但人们质疑MCQs是否真能准确衡量LLMs在知识密集型任务中的长篇幅生成能力。我们通过在中英文两个问答数据集上对九个LLM进行评估，深入探讨了MCQs的适用性。研究发现，LLMs对双语MCQs的答案顺序颇为敏感，尤其偏好首位答案。我们进一步比较了MCQs和长篇幅生成问题（LFGQs）的直接输出、标记逻辑和嵌入，揭示了两者在相同问题上答案的相关性较低。我们还提出了两种评估LLM输出一致性和信心的方法，这些方法也适用于其他QA评估标准。值得注意的是，我们的研究对“高一致性等同于高准确性”这一观点提出了质疑。此外，我们发现MCQs在预期校准误差方面不如LFGQs可靠。MCQs与LFGQs之间的不匹配不仅体现在评估表现上，还体现在嵌入空间的差异上。相关代码和模型可在 https://github.com/Meetyou-AI-Lab/Can-MC-Evaluate-LLMs 获取。

> Multiple-choice questions (MCQs) are widely used in the evaluation of large language models (LLMs) due to their simplicity and efficiency. However, there are concerns about whether MCQs can truly measure LLM's capabilities, particularly in knowledge-intensive scenarios where long-form generation (LFG) answers are required. The misalignment between the task and the evaluation method demands a thoughtful analysis of MCQ's efficacy, which we undertake in this paper by evaluating nine LLMs on four question-answering (QA) datasets in two languages: Chinese and English. We identify a significant issue: LLMs exhibit an order sensitivity in bilingual MCQs, favoring answers located at specific positions, i.e., the first position. We further quantify the gap between MCQs and long-form generation questions (LFGQs) by comparing their direct outputs, token logits, and embeddings. Our results reveal a relatively low correlation between answers from MCQs and LFGQs for identical questions. Additionally, we propose two methods to quantify the consistency and confidence of LLMs' output, which can be generalized to other QA evaluation benchmarks. Notably, our analysis challenges the idea that the higher the consistency, the greater the accuracy. We also find MCQs to be less reliable than LFGQs in terms of expected calibration error. Finally, the misalignment between MCQs and LFGQs is not only reflected in the evaluation performance but also in the embedding space. Our code and models can be accessed at https://github.com/Meetyou-AI-Lab/Can-MC-Evaluate-LLMs.

[Arxiv](https://arxiv.org/abs/2403.17752)