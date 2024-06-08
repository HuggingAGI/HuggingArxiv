# 大型语言模型在多项选择题中的应用：一项基于虚构医疗数据的案例研究

发布时间：2024年06月04日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在医疗领域的应用，特别是在通过多项选择题（MCQs）进行评估时的表现。论文通过设计一个虚构的医学基准，使用非真实的腺体Glianorex来测试LLMs的知识和应试技巧。研究结果表明，现有的MCQ基准可能不足以准确评估LLMs的临床推理能力，而是更多地展示了其模式识别能力。因此，论文强调了需要更精准的评估方法来更好地理解LLMs在医疗领域的潜力。这与LLM应用分类相符，因为它关注的是LLMs在特定领域（医疗）的应用和评估方法。`

> Multiple Choice Questions and Large Languages Models: A Case Study with Fictional Medical Data

# 摘要

> ChatGPT等大型语言模型（LLMs）在医疗领域的潜力巨大，常通过类似USMLE的多项选择题（MCQs）进行评估。尽管MCQs在医学教育中普遍，但在评估LLMs时，其局限性可能被放大。为此，我们设计了一个虚构的医学基准，专注于一个名为Glianorex的非真实腺体，以此来区分LLM的知识与应试技巧。我们利用GPT-4编写了关于Glianorex的英法双语教科书，并配套了双语MCQs。通过这些题目，我们在零样本环境下测试了多种LLMs，平均得分约67%，英语略优于法语。尽管英语中微调的医学模型有所提升，法语中则不然。所有模型的高分表明，传统MCQ基准可能无法准确评估LLMs的临床推理能力，而是突显了其模式识别能力。这提示我们需要更精准的评估方法来揭示LLMs在医疗领域的真正潜能。

> Large Language Models (LLMs) like ChatGPT demonstrate significant potential in the medical field, often evaluated using multiple-choice questions (MCQs) similar to those found on the USMLE. Despite their prevalence in medical education, MCQs have limitations that might be exacerbated when assessing LLMs. To evaluate the effectiveness of MCQs in assessing the performance of LLMs, we developed a fictional medical benchmark focused on a non-existent gland, the Glianorex. This approach allowed us to isolate the knowledge of the LLM from its test-taking abilities. We used GPT-4 to generate a comprehensive textbook on the Glianorex in both English and French and developed corresponding multiple-choice questions in both languages. We evaluated various open-source, proprietary, and domain-specific LLMs using these questions in a zero-shot setting. The models achieved average scores around 67%, with minor performance differences between larger and smaller models. Performance was slightly higher in English than in French. Fine-tuned medical models showed some improvement over their base versions in English but not in French. The uniformly high performance across models suggests that traditional MCQ-based benchmarks may not accurately measure LLMs' clinical knowledge and reasoning abilities, instead highlighting their pattern recognition skills. This study underscores the need for more robust evaluation methods to better assess the true capabilities of LLMs in medical contexts.

![大型语言模型在多项选择题中的应用：一项基于虚构医疗数据的案例研究](../../../paper_images/2406.02394/accuracy_plot.png)

![大型语言模型在多项选择题中的应用：一项基于虚构医疗数据的案例研究](../../../paper_images/2406.02394/distribution_plot.png)

[Arxiv](https://arxiv.org/abs/2406.02394)