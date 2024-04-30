# 一种简洁高效的集成策略，用于辨识 AI 创作的文本

发布时间：2023年11月07日

`LLM应用` `文本生成` `内容识别`

> A Simple yet Efficient Ensemble Approach for AI-generated Text Detection

# 摘要

> 近期的大型语言模型（LLMs）在模仿多种风格和类型的人类写作方面展现出了卓越的文本生成能力。然而，这种能力也容易被滥用，比如制造假新闻、垃圾邮件的编写，以及在学术作业中的不恰当使用。因此，开发能够辨别人工生成文本与人类创作文本的自动化工具显得尤为重要。本文提出了一种简洁高效的解决方案，即通过整合多个子LLMs的预测结果。相较于之前基于困惑度或多模型集成的方法，我们的精简集成方法仅用两个子LLMs就实现了相当的性能。在四个文本生成分类的基准数据集上的实验表明，与先前最先进方法相比，我们的性能提升了0.5%至100%。我们还探讨了不同LLMs的训练数据对模型性能的影响，并发现使用Falcon、LLaMA2、MPT等开放语言模型生成的数据替代商业限制的GPT数据是一个可行的方案。此外，为了验证零样本泛化能力，我们在英语论文数据集上进行了测试，结果表明我们的集成方法能够有效处理新数据。

> Recent Large Language Models (LLMs) have demonstrated remarkable capabilities in generating text that closely resembles human writing across wide range of styles and genres. However, such capabilities are prone to potential abuse, such as fake news generation, spam email creation, and misuse in academic assignments. Hence, it is essential to build automated approaches capable of distinguishing between artificially generated text and human-authored text. In this paper, we propose a simple yet efficient solution to this problem by ensembling predictions from multiple constituent LLMs. Compared to previous state-of-the-art approaches, which are perplexity-based or uses ensembles with a number of LLMs, our condensed ensembling approach uses only two constituent LLMs to achieve comparable performance. Experiments conducted on four benchmark datasets for generative text classification show performance improvements in the range of 0.5 to 100\% compared to previous state-of-the-art approaches. We also study the influence that the training data from individual LLMs have on model performance. We found that substituting commercially-restrictive Generative Pre-trained Transformer (GPT) data with data generated from other open language models such as Falcon, Large Language Model Meta AI (LLaMA2), and Mosaic Pretrained Transformers (MPT) is a feasible alternative when developing generative text detectors. Furthermore, to demonstrate zero-shot generalization, we experimented with an English essays dataset, and results suggest that our ensembling approach can handle new data effectively.

[Arxiv](https://arxiv.org/abs/2311.03084)