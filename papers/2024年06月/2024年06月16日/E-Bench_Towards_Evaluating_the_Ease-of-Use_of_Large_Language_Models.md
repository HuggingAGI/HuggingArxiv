# E-Bench：探索大型语言模型易用性的评估之道

发布时间：2024年06月16日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在实际应用中对提示变化的敏感性和稳定性，以及如何通过创建E-Bench来评估和改进这些模型的易用性。研究关注的是模型在面对同义词替换、打字错误等提示变化时的表现，以及这些变化对模型性能的影响。这些问题直接关联到LLMs的实际应用场景，因此属于LLM应用分类。` `人工智能`

> E-Bench: Towards Evaluating the Ease-of-Use of Large Language Models

# 摘要

> 大型语言模型（LLMs）对提示极为敏感，微小的变化如同义词替换或打字错误都可能引发意外结果。目前，为特定需求设计最佳提示尚无理论指导，全凭人类反复试验，这成为推广生成式人工智能的一大障碍。然而，关于LLMs在实际应用中抵御提示变化的稳定性，尚缺乏系统性研究。本研究旨在评估LLMs的易用性，并创建了E-Bench，模拟人类使用中的同义词扰动（包括改述、简化、口语化）和排版扰动（如打字错误）。此外，我们还探讨了这两类扰动的结合及其对性能影响的原因。实验表明，虽然模型规模增大带来了易用性的提升，但要打造真正用户友好的模型，我们还有很长的路要走。

> Most large language models (LLMs) are sensitive to prompts, and another synonymous expression or a typo may lead to unexpected results for the model. Composing an optimal prompt for a specific demand lacks theoretical support and relies entirely on human experimentation, which poses a considerable obstacle to popularizing generative artificial intelligence. However, there is no systematic analysis of the stability of LLMs in resisting prompt perturbations in real-world scenarios. In this work, we propose to evaluate the ease-of-use of LLMs and construct E-Bench, simulating the actual situation of human use from synonymous perturbation (including paraphrasing, simplification, and colloquialism) and typographical perturbation (such as typing). On this basis, we also discuss the combination of these two types of perturbation and analyze the main reasons for performance degradation. Experimental results indicate that with the increase of model size, although the ease-of-use are significantly improved, there is still a long way to go to build a sufficiently user-friendly model.

![E-Bench：探索大型语言模型易用性的评估之道](../../../paper_images/2406.10950/x1.png)

![E-Bench：探索大型语言模型易用性的评估之道](../../../paper_images/2406.10950/x2.png)

![E-Bench：探索大型语言模型易用性的评估之道](../../../paper_images/2406.10950/x3.png)

![E-Bench：探索大型语言模型易用性的评估之道](../../../paper_images/2406.10950/x4.png)

![E-Bench：探索大型语言模型易用性的评估之道](../../../paper_images/2406.10950/x5.png)

[Arxiv](https://arxiv.org/abs/2406.10950)