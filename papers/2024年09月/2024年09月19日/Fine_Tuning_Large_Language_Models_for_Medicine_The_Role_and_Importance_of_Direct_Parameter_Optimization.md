# 在医学领域微调大型语言模型时，直接参数优化的角色和重要性不容忽视。

发布时间：2024年09月19日

`LLM应用`

> Fine Tuning Large Language Models for Medicine: The Role and Importance of Direct Parameter Optimization

# 摘要

> 在医学领域，LLM 的微调应用尚未充分开发。常见的微调方法有 SFT 和 DPO，但何时使用哪种方法缺乏明确指导。我们研究了 SFT 和 DPO 在五种医学自然语言任务中的表现，发现 SFT 足以应对文本数据分类，而 DPO 则显著提升了临床推理、总结和临床分诊等复杂任务的性能。这一发现凸显了 DPO 在医学中的重要性，同时也揭示了当前软件的不足，阻碍了该技术的广泛应用。

> Large Language Model (LLM) fine tuning is underutilized in the field of medicine. Two of the most common methods of fine tuning are Supervised Fine Tuning (SFT) and Direct Parameter Optimization (DPO), but there is little guidance informing users when to use either technique. In this investigation, we compare the performance of SFT and DPO for five common natural language tasks in medicine: Classification with text data, Classification with numeric data, Clinical Reasoning, Summarization, and Clinical Triage. We find that SFT alone is sufficient for Classification with text data, whereas DPO improves performance for the more complex tasks of Clinical Reasoning, Summarization and Clinical Triage. Our results establish the role and importance of DPO fine tuning within medicine, and consequently call attention to current software gaps that prevent widespread deployment of this technique.

[Arxiv](https://arxiv.org/abs/2409.12741)