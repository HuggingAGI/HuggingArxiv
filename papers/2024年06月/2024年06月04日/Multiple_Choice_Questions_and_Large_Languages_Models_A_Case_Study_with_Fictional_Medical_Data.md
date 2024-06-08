# 大型语言模型在多项选择题中的应用：虚构医疗数据案例探析

发布时间：2024年06月04日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在医疗领域的应用，特别是在评估这些模型时使用传统多项选择题（MCQs）的局限性。通过创建一个虚构的腺体Glianorex，并基于此开发了一个新的医学基准，研究者旨在更准确地评估LLMs的知识而非仅仅是应试技巧。论文通过实验评估了多种LLMs的表现，并讨论了这些结果对未来评估工具设计的启示。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在特定领域（医疗）的实际应用和评估方法。`

> Multiple Choice Questions and Large Languages Models: A Case Study with Fictional Medical Data

# 摘要

> ChatGPT等大型语言模型（LLMs）在医疗领域的潜力巨大，常通过类似USMLE的多项选择题（MCQs）进行评估。尽管MCQs在医学教育中广泛使用，但在评估LLMs时，其局限性可能被放大。为此，我们创造了一个虚构的腺体——Glianorex，并以此为基础开发了一个医学基准，旨在单独评估LLM的知识而非应试技巧。我们利用GPT-4编写了关于Glianorex的教科书，涵盖英法双语，并设计了相应的多选题。在零样本测试中，我们评估了多种LLMs，平均得分约67%，英语略优于法语，而微调后的医学模型在英语上有所提升，法语则不然。这些结果表明，传统MCQ基准可能无法准确反映LLMs的临床推理能力，更多揭示了其模式识别能力。这提示我们需要更精确的评估工具来真正衡量LLMs在医疗领域的潜力。

> Large Language Models (LLMs) like ChatGPT demonstrate significant potential in the medical field, often evaluated using multiple-choice questions (MCQs) similar to those found on the USMLE. Despite their prevalence in medical education, MCQs have limitations that might be exacerbated when assessing LLMs. To evaluate the effectiveness of MCQs in assessing the performance of LLMs, we developed a fictional medical benchmark focused on a non-existent gland, the Glianorex. This approach allowed us to isolate the knowledge of the LLM from its test-taking abilities. We used GPT-4 to generate a comprehensive textbook on the Glianorex in both English and French and developed corresponding multiple-choice questions in both languages. We evaluated various open-source, proprietary, and domain-specific LLMs using these questions in a zero-shot setting. The models achieved average scores around 67%, with minor performance differences between larger and smaller models. Performance was slightly higher in English than in French. Fine-tuned medical models showed some improvement over their base versions in English but not in French. The uniformly high performance across models suggests that traditional MCQ-based benchmarks may not accurately measure LLMs' clinical knowledge and reasoning abilities, instead highlighting their pattern recognition skills. This study underscores the need for more robust evaluation methods to better assess the true capabilities of LLMs in medical contexts.

![大型语言模型在多项选择题中的应用：虚构医疗数据案例探析](../../../paper_images/2406.02394/accuracy_plot.png)

![大型语言模型在多项选择题中的应用：虚构医疗数据案例探析](../../../paper_images/2406.02394/distribution_plot.png)

[Arxiv](https://arxiv.org/abs/2406.02394)