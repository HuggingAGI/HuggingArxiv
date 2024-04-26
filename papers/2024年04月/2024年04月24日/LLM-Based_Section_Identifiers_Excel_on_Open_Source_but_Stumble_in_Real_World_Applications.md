# 基于大型语言模型的章节识别器在开源项目中大放异彩，然而在现实世界的应用场景中却显得力不从心。

发布时间：2024年04月24日

`LLM应用`

> LLM-Based Section Identifiers Excel on Open Source but Stumble in Real World Applications

# 摘要

> 电子健康记录（EHR）为医疗专业人员带来了便利，但其内容日益繁杂，长度日益增加。在这些冗长的记录中寻找关键信息变得日益困难，严重影响了医患交流的质量。尽管已有多种解决方案被提出，旨在通过摘要或分节来简化这一过程，但真正有效的寥寥无几。随着自动化技术的兴起，机器学习（ML）在识别 EHR 中的关键部分方面展现出潜力。不过，大多数 ML 方法需要依赖难以获得的标记数据。与此相对，大型语言模型（LLMs）在自然语言处理（NLP）领域取得了显著成就，即便是在没有标记数据的零样本学习情况下。基于此，我们提出利用 LLMs 来识别 EHR 中的相关章节标题。我们的研究显示，GPT-4 在零样本和少样本学习环境下都能高效完成任务，并且在信息分段上超越了当前的最先进方法。此外，我们还对一个更具挑战性的现实世界数据集进行了注释，发现 GPT-4 在此数据集上的表现并不理想，这提示我们未来需要更深入的研究和更严格的评估标准。

> Electronic health records (EHR) even though a boon for healthcare practitioners, are growing convoluted and longer every day. Sifting around these lengthy EHRs is taxing and becomes a cumbersome part of physician-patient interaction. Several approaches have been proposed to help alleviate this prevalent issue either via summarization or sectioning, however, only a few approaches have truly been helpful in the past. With the rise of automated methods, machine learning (ML) has shown promise in solving the task of identifying relevant sections in EHR. However, most ML methods rely on labeled data which is difficult to get in healthcare. Large language models (LLMs) on the other hand, have performed impressive feats in natural language processing (NLP), that too in a zero-shot manner, i.e. without any labeled data. To that end, we propose using LLMs to identify relevant section headers. We find that GPT-4 can effectively solve the task on both zero and few-shot settings as well as segment dramatically better than state-of-the-art methods. Additionally, we also annotate a much harder real world dataset and find that GPT-4 struggles to perform well, alluding to further research and harder benchmarks.

![基于大型语言模型的章节识别器在开源项目中大放异彩，然而在现实世界的应用场景中却显得力不从心。](../../../paper_images/2404.16294/Handwritten_clinical_note.png)

![基于大型语言模型的章节识别器在开源项目中大放异彩，然而在现实世界的应用场景中却显得力不从心。](../../../paper_images/2404.16294/Section_Category.png)

[Arxiv](https://arxiv.org/abs/2404.16294)