# CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性

发布时间：2024年06月04日

`LLM应用

这篇论文介绍了一种名为CheckEmbed的验证方法，用于验证大型语言模型（LLMs）在复杂开放式任务中的答案。该方法通过比较LLM生成的答案与真实答案的嵌入来简化验证过程，并提供了一套全面的验证流程和评估指标。这种方法特别适用于知识整合、总结和提取等任务，并在实际文档分析任务中显示出优于其他验证方案的性能。因此，这篇论文属于LLM应用类别，因为它关注的是LLM在实际应用中的验证问题和解决方案。` `文档分析` `知识验证`

> CheckEmbed: Effective Verification of LLM Solutions to Open-Ended Tasks

# 摘要

> 大型语言模型（LLMs）正革新多个领域，但验证其答案仍是一大挑战，尤其是在知识整合、总结和提取这类复杂开放式任务中。为此，我们提出了CheckEmbed：一种既准确又可扩展且操作简便的LLM验证方法。CheckEmbed的核心理念简洁而强大：通过比较LLM解决方案或与真实答案对应的答案级嵌入（如GPT Text Embedding Large模型所提供），将复杂文本答案简化为单一嵌入，从而实现直接、快速且有意义的验证。我们构建了一个全面的验证流程，实施CheckEmbed方法，并配备了评估LLM答案真实性的指标，如嵌入热图及其摘要。我们展示了如何利用这些指标来部署实用引擎，判断LLM答案是否达标。在实际文档分析任务中，包括术语提取和文档总结，CheckEmbed流程与现有基于标记、句子和事实级别的验证方案（如BERTScore或SelfCheckGPT）相比，在准确性、成本效益和运行时间性能上均有显著提升。

> Large Language Models (LLMs) are revolutionizing various domains, yet verifying their answers remains a significant challenge, especially for intricate open-ended tasks such as consolidation, summarization, and extraction of knowledge. In this work, we propose CheckEmbed: an accurate, scalable, and simple LLM verification approach. CheckEmbed is driven by a straightforward yet powerful idea: in order to compare LLM solutions to one another or to the ground-truth, compare their corresponding answer-level embeddings obtained with a model such as GPT Text Embedding Large. This reduces a complex textual answer to a single embedding, facilitating straightforward, fast, and meaningful verification. We develop a comprehensive verification pipeline implementing the CheckEmbed methodology. The CheckEmbed pipeline also comes with metrics for assessing the truthfulness of the LLM answers, such as embedding heatmaps and their summaries. We show how to use these metrics for deploying practical engines that decide whether an LLM answer is satisfactory or not. We apply the pipeline to real-world document analysis tasks, including term extraction and document summarization, showcasing significant improvements in accuracy, cost-effectiveness, and runtime performance compared to existing token-, sentence-, and fact-level schemes such as BERTScore or SelfCheckGPT.

![CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性](../../../paper_images/2406.02524/x1.png)

![CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性](../../../paper_images/2406.02524/x2.png)

![CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性](../../../paper_images/2406.02524/x11.png)

![CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性](../../../paper_images/2406.02524/x12.png)

![CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性](../../../paper_images/2406.02524/x13.png)

![CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性](../../../paper_images/2406.02524/x14.png)

![CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性](../../../paper_images/2406.02524/x15.png)

![CheckEmbed：验证大型语言模型在开放式任务中的解决方案的有效性](../../../paper_images/2406.02524/x16.png)

[Arxiv](https://arxiv.org/abs/2406.02524)