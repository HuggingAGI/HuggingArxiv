# MSciNLI：为科学领域量身打造的自然语言推理多维度评测基准

发布时间：2024年04月11日

`LLM应用` `计算语言学` `科研文章`

> MSciNLI: A Diverse Benchmark for Scientific Natural Language Inference

# 摘要

> 科学自然语言推理（NLI）任务的目标是预测科研文章中两个句子的语义联系。随着名为SciNLI的新数据集的发布，这一任务应运而生，数据集源自计算语言学领域的论文。本文意在为科学NLI带来多元性，并介绍MSciNLI数据集，内含来自五个科学新领域的132,320对句子。跨领域的数据让我们得以探究科学NLI的任务迁移。通过微调预训练语言模型（PLMs）和激发大型语言模型（LLMs），我们在MSciNLI上设立了高标准。PLM和LLM的最高宏观F1分数分别达到77.21%和51.77%，表明MSciNLI对两类模型都颇具挑战。此外，领域变化对科学NLI模型的表现有所影响，反映了我们数据集内不同领域的独特性。最终，我们在一个中间任务的迁移学习框架下利用这两个科学NLI数据集，证实它们能增强科学领域后续任务的表现。相关数据集和代码已在Github公开。

> The task of scientific Natural Language Inference (NLI) involves predicting the semantic relation between two sentences extracted from research articles. This task was recently proposed along with a new dataset called SciNLI derived from papers published in the computational linguistics domain. In this paper, we aim to introduce diversity in the scientific NLI task and present MSciNLI, a dataset containing 132,320 sentence pairs extracted from five new scientific domains. The availability of multiple domains makes it possible to study domain shift for scientific NLI. We establish strong baselines on MSciNLI by fine-tuning Pre-trained Language Models (PLMs) and prompting Large Language Models (LLMs). The highest Macro F1 scores of PLM and LLM baselines are 77.21% and 51.77%, respectively, illustrating that MSciNLI is challenging for both types of models. Furthermore, we show that domain shift degrades the performance of scientific NLI models which demonstrates the diverse characteristics of different domains in our dataset. Finally, we use both scientific NLI datasets in an intermediate task transfer learning setting and show that they can improve the performance of downstream tasks in the scientific domain. We make our dataset and code available on Github.

[Arxiv](https://arxiv.org/abs/2404.08066)