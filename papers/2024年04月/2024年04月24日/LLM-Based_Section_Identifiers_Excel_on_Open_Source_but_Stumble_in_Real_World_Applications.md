# 基于大型语言模型的章节识别工具在开源领域成绩斐然，却在真实应用场景中遭遇挫折。

发布时间：2024年04月24日

`LLM应用` `机器学习`

> LLM-Based Section Identifiers Excel on Open Source but Stumble in Real World Applications

# 摘要

> 电子健康档案（EHR）为医疗专业人员带来了便利，但其内容日益繁杂冗长。在这些庞大的数据中寻找有用信息变得日益艰难，影响医患交流的效率。尽管已提出多种解决方案，如摘要化和分节技术，但真正有效的寥寥无几。随着自动化技术的兴起，机器学习（ML）在识别EHR中的关键信息方面展现出潜力。不过，大多数ML技术依赖于难以获得的标记数据。与此同时，大型语言模型（LLMs）在自然语言处理（NLP）领域取得了显著成就，即便在没有标记数据的零样本学习中也能表现出色。基于此，我们提出利用LLMs来识别EHR中的相关章节标题。我们的研究显示，GPT-4不仅在零样本和少样本学习场景下能够有效完成任务，而且在数据分段上也超越了现有最先进技术。此外，我们还对一个更为复杂的现实世界数据集进行了标注，发现GPT-4在处理上存在挑战，这提示我们需要更深入的研究和更严格的评估标准。

> Electronic health records (EHR) even though a boon for healthcare practitioners, are growing convoluted and longer every day. Sifting around these lengthy EHRs is taxing and becomes a cumbersome part of physician-patient interaction. Several approaches have been proposed to help alleviate this prevalent issue either via summarization or sectioning, however, only a few approaches have truly been helpful in the past. With the rise of automated methods, machine learning (ML) has shown promise in solving the task of identifying relevant sections in EHR. However, most ML methods rely on labeled data which is difficult to get in healthcare. Large language models (LLMs) on the other hand, have performed impressive feats in natural language processing (NLP), that too in a zero-shot manner, i.e. without any labeled data. To that end, we propose using LLMs to identify relevant section headers. We find that GPT-4 can effectively solve the task on both zero and few-shot settings as well as segment dramatically better than state-of-the-art methods. Additionally, we also annotate a much harder real world dataset and find that GPT-4 struggles to perform well, alluding to further research and harder benchmarks.

![基于大型语言模型的章节识别工具在开源领域成绩斐然，却在真实应用场景中遭遇挫折。](../../../paper_images/2404.16294/Handwritten_clinical_note.png)

![基于大型语言模型的章节识别工具在开源领域成绩斐然，却在真实应用场景中遭遇挫折。](../../../paper_images/2404.16294/Section_Category.png)

[Arxiv](https://arxiv.org/abs/2404.16294)