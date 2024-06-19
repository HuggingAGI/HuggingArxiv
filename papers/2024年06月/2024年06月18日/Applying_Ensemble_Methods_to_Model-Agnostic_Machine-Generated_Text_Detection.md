# 采用集成方法进行模型无关的机器生成文本检测

发布时间：2024年06月18日

`Agent

理由：这篇论文主要探讨了在未知大型语言模型（LLM）的情况下如何检测机器生成文本，这涉及到开发和使用特定的检测工具或代理（Agent）来分析和判断文本的来源。论文中提到的DetectGPT分类器及其集成方法，可以被视为一种检测机器生成文本的Agent。此外，论文关注的是检测方法的开发和优化，而不是LLM的理论研究或应用开发，因此不属于LLM理论或LLM应用。同时，由于内容不涉及RAG（Retrieval-Augmented Generation）的相关技术或应用，因此也不归类为RAG。` `文本检测` `机器学习`

> Applying Ensemble Methods to Model-Agnostic Machine-Generated Text Detection

# 摘要

> 本文探讨了在未知大型语言模型（LLM）的情况下如何检测机器生成文本。我们采用集成方法分析DetectGPT分类器的输出（Mitchell等人，2023年），该模型在生成与判别语言模型一致时，对机器生成文本的检测准确度极高。研究发现，通过简单汇总DetectGPT子模型的输出，AUROC可达0.73，保持了零-shot特性；而采用监督学习方法，AUROC可提升至0.94，但需依赖训练数据集。这预示着未来可能开发出一种高度准确、不依赖特定模型的机器生成文本检测器。

> In this paper, we study the problem of detecting machine-generated text when the large language model (LLM) it is possibly derived from is unknown. We do so by apply ensembling methods to the outputs from DetectGPT classifiers (Mitchell et al. 2023), a zero-shot model for machine-generated text detection which is highly accurate when the generative (or base) language model is the same as the discriminative (or scoring) language model. We find that simple summary statistics of DetectGPT sub-model outputs yield an AUROC of 0.73 (relative to 0.61) while retaining its zero-shot nature, and that supervised learning methods sharply boost the accuracy to an AUROC of 0.94 but require a training dataset. This suggests the possibility of further generalisation to create a highly-accurate, model-agnostic machine-generated text detector.

[Arxiv](https://arxiv.org/abs/2406.12570)